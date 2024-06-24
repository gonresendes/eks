# EKS Deployment with Nginx Proxy and Let's Encrypt Certificates

This repository contains the necessary configuration and scripts to deploy applications on an Amazon EKS cluster with an Nginx reverse proxy and Let's Encrypt SSL certificates.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
  - [Clone the Repository](#clone-the-repository)
  - [Configure Nginx](#configure-nginx)
  - [Create Secrets](#create-secrets)
- [Deploy](#deploy)
- [Accessing the Applications](#accessing-the-applications)


## Overview

This project sets up a Kubernetes environment on Amazon EKS, deploying multiple applications behind an Nginx proxy, secured with SSL certificates issued by Let's Encrypt.

## Prerequisites

Before you begin, ensure you have the following installed:

- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [AWS CLI](https://aws.amazon.com/cli/)

- An EKS cluster

## Setup

### Clone the Repository

Clone this repository to your local machine:

```sh
git clone https://github.com/gonresendes/eks.git
cd eks
