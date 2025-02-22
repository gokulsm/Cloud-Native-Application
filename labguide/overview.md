# Cloud Native Applications

## Abstract and learning objectives

This hands-on lab will guide the student through deploying a web application and API microservice to a Kubernetes platform hosted on Azure Kubernetes Services (AKS). In addition, the lab will instruct the student on configuring the behaviour of these services through dynamic service discovery, service scale-out, and high availability in the context of AKS-hosted services. By demonstrating crucial Kubernetes concepts, the student will gain experience with the Kubernetes deployment and service resource types. The student will create them manually through the Azure Portal and manipulate their configurations to scale the associated microservice instances up and down and manage their CPU and memory resource allocations with the Kubernetes cluster.

At the conclusion of this lab, you have a solid understanding of how to build and deploy containerized applications to Azure Kubernetes Service and perform common tasks and procedures.


## Overview

Contoso Traders (ContosoTraders) provides online retail website services tailored to the electronics community. They are refactoring their application to run as a Docker application. They want to implement a proof of concept that will help them get familiar with the development process, lifecycle of deployment, and critical aspects of the hosting environment. They will be deploying their applications to Azure Kubernetes Service and want to learn how to deploy containers in a dynamically load-balanced manner, discover containers, and scale them on demand.

In this hands-on lab, you will assist with completing this POC with a subset of the application codebase. You will use a pre-created build agent based on Linux and an Azure Kubernetes Service cluster for running deployed applications. You will be helping them to complete the Docker setup for their application, test locally, push to an image repository, deploy to the cluster, test load-balancing and scale and use Azure Monitor and view the insights.

## Solution Architecture

Below is a diagram of the solution architecture you will build in this lab. Please study this carefully to understand the whole of the solution as you are working on the various components.

The proposed containers deployed to the cluster are illustrated below with Cosmos DB as a managed service.

  ![Selecting Add to create a deployment.](media/newoverview.png "Selecing + Add to create a deployment")
