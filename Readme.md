# KnoxAutoPolicy

KnoxAutoPolicy is a policy recommendation system that suggests network and system policies based on the collected network and system logs respectively from the various container network interfaces (CNI) such as Cilium, Bastion, and Calico and container-aware runtime security enforcement system (CRSE) such as KubeArmor.

# Deployment Guide

- Deploy KubeArmor in your Kubernetes environment

   KnoxAutoPolicy currently supports self-managed Kubernetes and Google Kubernetes Engine \(GKE\). Amazon Elastic Kubernetes Service \(EKS\) and Azure Kubernetes Service \(AKS\) not tested. (it will be tested later)
   
   
   * Deploy KnoxAutoPolicy in your Kubernetes

     ```sh
       $ cd deployments/k8s
       $ kubectl apply -f .
     ```
