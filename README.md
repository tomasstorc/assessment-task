# Assessment task

## Overview

In this task you will create following resources:

- Resource group
- Network with two subnets
- Virtual Machine
- Log Analytics Workspace
- Key vault

In the end you should be able connect to virtual machine and access key vault which will be accessible only via private ip address.In the key vault you will create secret. Last task is to setup monitoring for virtual machine.

## General guidelines

- Naming of the resources is up to you, but should be meaningful.
- Use North Europe as location for the resources.
- Costs should be minimalized
- It is good practise to use tags.

## Task 1 - Create resource group (RG)

- All needed info is described in General guidelines

## Task 2 - Create virtual network (VNET)

- Place VNET into created RG.
- Use 10.0.0.0/25 as an address space.
- Create two subnets in VNET, first should have 11 assigneable IP addresses and second 25 assigneable addresses.

## Task 3 - Create virtual machine (VM)

- Create VM with Windows server operating system.
- Choose best SKU for server that needs 2 vCores and 4GB of RAM.
- VM should have access to VNET and should be accessible from the internet as well.
- No redundancy is required.

## Task 4 - Create Log Analytics Worksace (LAW)

- Place LAW into created RG.

## Task 5 - Configure VM insights

- For created VM enable VM insights so it is possible to check all VM performance metrics
- Collect metrics into previosly created LAW.

## Task 6 - Create Key vault (KV)

- KV should be accessible only from VNET, no internet connection should be allowd.
- Use RBAC access for data plane.
- Assign yourself enough rights to be able to create secret in key vault, use least privilege model.

## Task 7 - Create secret

- Login into created VM and go to Azure portal.
- Open created KV and create a new secret.
