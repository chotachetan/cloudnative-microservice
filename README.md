# Cloud Native Microservice
The objective of this project is to run a Cloud Native Microservices Application on a Kubernetes Cluster.


## Table of Contents
* [Introduction](#introduction)
* [Application Overview](#application-overview)
* [Project repositories](#project-repositories)
* [Deploy the Application](#deploy-the-application)
  + [Download required CLIs](#download-required-clis)
  + [Get application source code (optional)](#get-application-source-code-optional)
  + [Create a Kubernetes Cluster](#create-a-kubernetes-cluster)
  + [Deploy to Kubernetes Cluster](#deploy-to-kubernetes-cluster)
* [Validate the Application](#validate-the-application)
  + [Minikube](#minikube)
  + [Login](#login)
  + [Troubleshooting Deployments](#troubleshooting-deployments)
* [Delete the Application](#delete-the-application)
* [Optional Deployments](#optional-deployments)
  + [Deploy to Google Container Engine](#deploy-gcp-to-google-container-engine)
    - [Access and Validate the Application](#access-and-validate-the-application)
* [DevOps automation, Resiliency and Cloud Management and Monitoring](#devops-automation-resiliency-and-cloud-management-and-monitoring)
  + [DevOps](#devops)
  + [Cloud Management and monitoring](#cloud-management-and-monitoring)
  + [Making Microservices Resilient](#making-microservices-resilient)
  + [Secure The Application](#secure-the-application)

## Introduction
This project provides a reference implementation for running a Cloud Native Mobile and Web Application using a Microservices architecture on a Kubernetes cluster.  
