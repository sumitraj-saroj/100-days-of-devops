# 🔧 Introduction to DevOps – Summary

## 1. Traditional Software Development Process

- **Development**:
  - Developers build features and fix bugs using languages like Java, Python, JavaScript.
  - Teams are often structured around applications or features.

- **Testing**:
  - Ensures new features work without breaking existing ones.
  - Uses manual and automated testing (automation preferred for large systems).

- **Release**:
  - Application is built, packaged, and deployed to production.
  - Traditionally managed by the **Operations** team with a focus on stability and uptime.

---

## 2. Traditional Development vs Operations

### Different Goals:
- **DEV**: Rapid development and release of new features.
- **OPS**: Stability, uptime, and performance of production systems.

### Different Skillsets:
- **DEV**: Programming, testing, version control, database handling.
- **OPS**: Linux, scripting, automation, infrastructure monitoring.

### Key Challenges:
- Siloed teams → poor communication and unclear handoffs.
- Conflicting goals (speed vs stability).
- Manual processes → slow releases, more errors.
- Tedious checklists for deployment and testing.

---

## 3. DevOps: The Solution

- **Purpose**: Remove inefficiencies and automate the release process.
- **Definition**:
  - Simplest: Intersection of DEV and OPS.
  - Better: A system for **continuous delivery** that is **fast** and **error-free**.

### Evolution:
- Began as a cultural shift toward collaboration.
- Now includes specific practices, tools, and a defined role: **DevOps Engineer**.

---

## 4. DevOps Engineer Role

- Acts as a **bridge** between DEV and OPS teams.
- Builds **automated pipelines** for smooth deployments.
- Requires knowledge from both sides + DevOps-specific tools.
- Focus: Automation, monitoring, reliability, and speed of software delivery.

---

## 5. Core DevOps Tasks & Tools

### 🛠 Key Concepts:
- Commit Code
- Package Management
- Source Code Management
- CI/CD (Continuous Integration & Delivery)
- Infrastructure as Code (IaC)
- Container Orchestration
- Cloud Platforms
- Continuous Monitoring

### 📦 Common Tools:
- **SCM**: Git
- **CI/CD**: Jenkins, GitLab
- **Containers**: Docker
- **IaC**: Terraform, Ansible
- **Orchestration**: Kubernetes
- **Cloud**: AWS, Azure, Google Cloud
- **Monitoring**: Prometheus

---

## 6. Methodologies That Impact DevOps

### 🚧 Waterfall:
- Sequential, long-term cycles.
- Testing & deployment occur late → high rework and slow feedback.
- Prone to failure and delays.

### 🌀 Agile:
- Iterative, fast, and flexible.
- Early and frequent testing and deployment.
- Immediate feedback improves quality and speed.
- Backbone of **CI/CD** practices.
- Implementations: **Scrum**, **Kanban**

---
