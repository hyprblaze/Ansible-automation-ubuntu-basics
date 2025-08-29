<h1 align="center">📘 Ansible Automation on Ubuntu – Basics for Beginners </h1>


<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg"></a>
  <a href="https://www.ansible.com/"><img src="https://img.shields.io/badge/Ansible-Automation-blue?logo=ansible&logoColor=white"></a>
  <a href="https://ubuntu.com/"><img src="https://img.shields.io/badge/Ubuntu-Server-orange?logo=ubuntu&logoColor=white"></a>
  <a href="https://github.com/hyprblaze"><img src="https://img.shields.io/badge/Made%20by-HYPRBLAZE-purple?logo=github"></a>
</p>

---

## 📖 Description  
This repository is a **beginner-friendly guide to Ansible automation on Ubuntu servers**.  
It covers:  
- Installing Ansible on Ubuntu  
- Setting up password-less SSH  
- Writing and running your first playbooks  

The repo includes **three simple playbooks** for practice:  
1. Create a file (`hello.txt`) with “Hello World” in the target node’s home directory  
2. Retrieve Ubuntu version and kernel information  
3. Retrieve RAM and CPU information  

Designed for newcomers, this repo helps you **take your first steps into IT automation with Ansible**.  

---

## 🔑 Topics / Tags  
`Ansible` · `Automation` · `Ubuntu` · `Servers` · `DevOps` · `Beginner` · `Playbooks` · `Linux` · `System Administration`  

---
---
# Introduction to Ansible
---
## What is Ansible?  
Ansible is an **open-source configuration management and orchestration tool**.  
It simplifies automation by enabling users to **manage systems, deploy applications, and execute tasks remotely**.  

### Key Aspects of Ansible  
- **Configuration Management** → Centrally manage and automate the configuration of services, packages, system settings, and more.  
- **Orchestration** → Automate and orchestrate the deployment of complex applications across multiple systems.  
- **Declarative Syntax** → Playbooks are written in simple YAML, making them easy to understand and write.  
- **Agentless** → No agent installation required on target machines; Ansible uses **SSH** for communication.  

---

## Why Automate Ubuntu Server Tasks?  
Automation provides several advantages when managing Ubuntu servers:  

- **Consistency** → Ensures every task is executed the same way, reducing human error.  
- **Speed** → Automates tasks that would otherwise take hours if done manually.  
- **Repeatability** → Run the same tasks multiple times without missing steps.  
- **Scalability** → Easily add new servers or update configurations across multiple systems.  
- **Time Savings** → Frees up time for strategic work while handling repetitive tasks automatically.  

---

## Course Objectives  
This course is designed to **introduce you to Ansible** and how it can automate tasks on Ubuntu servers.  
By the end of the course, you will be able to:  

1. **Set up an Ansible Control Node on Ubuntu Server**  
   - Configure one Ubuntu server as the **control node**, which will manage and execute automation tasks on other servers (**target nodes**).  

2. **Configure Password-less SSH to Multiple Ubuntu Target Nodes**  
   - Enable secure, password-less communication between the control node and target servers.  

3. **Write and Run Playbooks to Collect System Information**  
   - Automate tasks like gathering **OS details, kernel version, CPU, and RAM info** from remote servers.  

---

## Ansible Automation Rough Diagram  
 

In this setup:  
- **1 Ubuntu server** acts as the **Ansible Control Node**  
- **3 Ubuntu servers** act as the **Target Nodes**  
- The control node connects to and automates the target nodes via **SSH**.  
