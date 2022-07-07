Provisioning an IBM Cloud virtual server for VPC

Use IBM Cloud Provider plug-in to provision a VPC, and set up networking for your VPC, and provision a virtual server for VPC in your IBM Cloud account. A VPC allows you to create your own space in IBM Cloud so that you can run an isolated environment in the public cloud with custom network policies.

Objectives

In this tutorial, you will learn to provisions:

    1 VPC where you provision your VPC virtual server instance
    1 security group and a rule for this security group to allow SSH connection to your virtual server instance
    1 subnet to enable networking in your VPC
    1 VPC virtual server instance
    1 floating IP address that you use to access your VPC virtual server instance over the public network

Audience

This tutorial is intended for system administrators who want to learn how to provision an IBM Cloud virtual server for a VPC by using IBM Cloud Provider.
Prerequisites

    Install the latest Terraform on IBM Cloud and the latest IBM Cloud Provider plug-in for Terraform on IBM Cloud.
    Retrieve your IBM Cloud credentials, upload an SSH key, and configure the IBM Cloud Provider plug-in.