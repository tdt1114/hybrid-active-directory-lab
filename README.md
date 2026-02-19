# Hybrid Active Directory Lab (Azure)

## Overview

This project documents the deployment of a hybrid Active Directory environment in Microsoft Azure and the operational tasks performed within it. The goal of the lab is to understand how identity, authentication, authorization, and administrative delegation function inside a domain environment.

This environment will serve as the foundation for future identity monitoring and detection exercises.

---

## Attribution
This lab was originally inspired by an Active Directory deployment guide by
[Jake Hulberg](https://www.jakehulberg.dev/).
I followed the core infrastructure setup and will continue to extended the environment with additional administrative and operational tasks to better understand real-world usage.

All implementation steps, documentation, troubleshooting, and validation in this repository reflect my own execution and learning process.

---

## Environment Architecture

* Windows Server 2022 Domain Controller
* Windows 10 Enterprise domain workstation
* Azure Virtual Network with segmented subnets
* Organizational Units structured by department

---

## Identity Administration Tasks Performed

* Domain join and authentication validation
* PowerShell-based user provisioning
* Security group assignment
* Remote Desktop authorization configuration
* Helpdesk password reset delegation
* Domain password policy configuration
* Logon script deployment via SYSVOL

---

## Key Concepts Practiced

* Authentication vs Authorization
* Role-based access control
* Delegated administration
* Policy enforcement
* Centralized identity management

---

## Validation

Screenshots and verification steps are included in the `/Validation` directory demonstrating successful authentication, policy application, and permission enforcement.

---

## Next Phase

This lab will be expanded into a security-focused environment to simulate identity-based attack scenarios and detection engineering workflows.
