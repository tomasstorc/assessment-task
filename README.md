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

- Naming of all the resources is up to you, but should be meaningful.
- Use Nort Europe as location for the resources.

## Task 1 - Create resource group (RG)

## Task 2 - Create virtual network (VNET)

- Place VNET into created RG.
- Use 10.0.0.0/25 as an address space.
- Create two subnets in VNET, first should have 11 assigneable IP addresses and second 25 assigneable addresses.

## Task 3 - Create virtual machine (VM)
