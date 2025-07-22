# 🐳 Minikube & kubectl Setup on WSL (Ubuntu)

This guide helps you set up a **local Kubernetes cluster using Minikube** and `kubectl` inside **Windows Subsystem for Linux (WSL2)** running Ubuntu.

## ✅ What This Covers

- Installing `kubectl` CLI
- Installing `Minikube`
- Setting up Docker as the driver
- Troubleshooting `.kube/config` issues
- Running Kubernetes inside WSL2

## 📄 Setup Guide

See the full step-by-step instructions here:  
📘 **[Minikube & kubectl Installation Guide (WSL)](./Minikube in WSL)**



## 🚀 Quick Start

```bash
minikube start --driver=docker
kubectl get nodes
