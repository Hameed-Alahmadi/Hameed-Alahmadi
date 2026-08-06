<h1 align="center">Hi, I'm Hameed</h1>

<p align="center">
  DevOps learner · Building projects and writing the courses I wish I'd had
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdulhameed-alahmadi/"><img src="https://img.shields.io/badge/LinkedIn-2b3137?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:a.a.alahmadi94@gmail.com"><img src="https://img.shields.io/badge/Email-2b3137?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## About

I came to DevOps from web development, and stayed because the problems are the
interesting kind: how software actually gets built, shipped, and kept running.

I learn by building the whole chain end to end, then writing down what I learned
— including the parts that broke. Everything below is work I've done myself on my
own machines and my own cloud account.

|  |  |
| --- | --- |
| **Currently** | Building DevOps projects and documenting them as courses |
| **Daily driver** | Arch Linux (Hyprland) · Neovim · Git · Docker · AWS |
| **Learning** | Terraform · Ansible · Kubernetes |
| **Also into** | Systems programming (C++) · game development |

---

## Projects

### [Leaderboard Platform](https://github.com/Hameed-Alahmadi/leaderboard-platform)

A small Flask/PostgreSQL API used as the vehicle for a complete, production-style
delivery pipeline — **the application is deliberately simple; the platform around
it is the work.**

`git push` → GitHub Actions (lint, test, Trivy scan) → image published to GHCR →
**Argo CD** reconciles a Kubernetes cluster from Git. No manual `kubectl apply`.

Built and running: horizontal pod autoscaling, zero-downtime rolling deploys,
a PostgreSQL StatefulSet with persistent storage, Sealed Secrets, RBAC and
NetworkPolicies, non-root containers, Prometheus/Grafana dashboards with
SLO-based alerts, and an etcd backup drill.

`Docker` `Kubernetes` `Helm` `Argo CD` `GitHub Actions` `Prometheus` `Grafana` `Python`

### AWS Cost Guardian — *in progress*

A serverless tool that scans an AWS account for wasted resources, prices them,
and reports the total. Lambda on an EventBridge schedule, all infrastructure in
Terraform, deployed from GitHub Actions via OIDC — no stored AWS credentials.
The scanner is read-only by design; deletion lives in a separate function behind
an IAM tag condition.

`AWS Lambda` `Terraform` `DynamoDB` `CloudWatch` `boto3` `pytest + moto`

---

## Courses

Written as I learn — detailed, beginner-friendly, and concept-first rather than
a list of commands.

| Course | What it covers | Status |
| --- | --- | --- |
| [**DevOps Foundations**](https://github.com/Hameed-Alahmadi/devops-foundations) | A concept-first guide to DevOps for people starting from zero | `Published` |
| [**Docker Course**](https://github.com/Hameed-Alahmadi/docker-course) | Containers, images, Compose, and real project workflows | `Published` |
| **Linux Course** | The command line, filesystem, processes, permissions, services | `In progress` |
| **Kubernetes Course** | Orchestration, from core objects to real deployments | `Planned` |
| **Terraform (AWS) Course** | Infrastructure as code on AWS, from zero to real infrastructure | `Planned` |
| **Ansible Course** | Configuration management, from playbooks to roles | `Planned` |

<sub>Links go live as each course is published. I use AI to keep formatting
consistent and to refine the English — the material and the work behind it are
my own.</sub>

---

## Tech

![Linux](https://img.shields.io/badge/Linux-2b3137?style=flat-square&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2b3137?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-2b3137?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-2b3137?style=flat-square&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-2b3137?style=flat-square&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-2b3137?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-2b3137?style=flat-square&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-2b3137?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2b3137?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-2b3137?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-2b3137?style=flat-square&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-2b3137?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-2b3137?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-2b3137?style=flat-square&logo=git&logoColor=white)

---

<p align="center"><sub>Learning in public, one project at a time.</sub></p>
