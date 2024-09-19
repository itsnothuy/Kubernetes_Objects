# Practice Lab: Introduction to Kubernetes Objects

## Overview

This practice lab provides a hands-on introduction to key Kubernetes objects and concepts. You will learn how to create and manage services, deploy StatefulSets and DaemonSets, and use essential `kubectl` commands. By the end of this lab, you will have gained practical experience with managing Kubernetes workloads and objects in a real-world scenario.

## Objectives

Upon completion of this lab, you will be able to:

- Create a Kubernetes Service
- Execute various `kubectl` commands for managing Kubernetes resources
- Deploy a **StatefulSet** to manage stateful applications
- Implement a **DaemonSet** to run a pod on every node in a Kubernetes cluster

## Prerequisites

- Basic understanding of Kubernetes concepts and objects
- Access to a Kubernetes cluster (via the CognitiveClass lab environment)
- Installed `kubectl` command-line tool

## Instructions

1. **Accessing the Lab Environment**:  
   Log into the lab environment provided by CognitiveClass.ai. Ensure that you complete the entire lab in a single session to avoid lab timeout issues, as your environment may go into offline mode if idle for too long.

2. **Creating a Kubernetes Service**:  
   Learn how to create and expose a Kubernetes service to allow other components to communicate with your application.

3. **Executing `kubectl` Commands**:  
   Familiarize yourself with key `kubectl` commands to interact with Kubernetes objects. You will run commands to:
   - Create resources
   - Check the status of running pods, services, and deployments
   - View logs and events

4. **Deploying a StatefulSet**:  
   Deploy a StatefulSet for managing stateful applications. StatefulSets ensure that each pod has a unique and stable identity across restarts.

5. **Implementing a DaemonSet**:  
   Set up a DaemonSet to ensure that a specific pod runs on all nodes in your Kubernetes cluster.

## Important Notes

- **Single-session completion**: To avoid any disruptions during the lab process, it is crucial to complete the lab in a single session. The lab environment may go into offline mode if left idle, which could lead to errors.
- **Issue resolution**: If you encounter errors or issues while working in the lab, log out of the lab environment, clear your system’s cache and cookies, and then log back in to continue.

## Conclusion

By completing this lab, you will have hands-on experience with core Kubernetes concepts such as StatefulSets, DaemonSets, and services. These are fundamental for managing real-world Kubernetes clusters and workloads efficiently.

