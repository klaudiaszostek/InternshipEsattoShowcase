# InternshipEsattoShowcase
This repository summarizes my learning experience during the internship at Esatto Poland (2025). Due to NDA restrictions, the original source code cannot be shared. This repo documents the architecture, technologies, workflows, and testing setup.

## 🧭 Overview

- **Company:** Esatto Poland  
- **Project:** Internal HR System (Next.js + .NET + Azure)  
- **Duration:** 2 months  
- **My role:** Fullstack Intern
- **Team:** 3 interns + mentors
- **Goal:** To design and implement an internal expense and budget management system for Esatto employees (budget, approvals, notifications).

---

## 🧩 Tech Stack

| Area | Technology |
|------|-------------|
| Frontend | React, Next.js (App Router), TypeScript, TailwindCSS, DaisyUI |
| Backend | .NET 9.0, Entity Framework Core, REST API |
| Database | Microsoft SQL Server (EF Core migrations) |
| CI/CD | Azure DevOps Pipelines |
| Deployment | Azure App Service, Docker |
| Tests | Jest, React Testing Library, xUnit, FluentAssertions, NSubstitute |
| Notifications | SendGrid API |
| Version Control | Git + feature branching strategy |

---


## ⚙️ Key Areas in Our Team

### 🧠 Frontend (Next.js)
- Implemented app router structure using **Next.js**
- Configured **Jest** and **React Testing Library**
- Integrated **TailwindCSS + DaisyUI** for UI theming
- Added standalone mode for Azure deployment (`output: "standalone"`)
- Wrote and maintained unit tests with `jest-junit` reports for CI

### ⚡ Backend (.NET)
- Created and maintained REST API endpoints for expense and budget management  
- Worked with **Entity Framework Core** for migrations and SQL Server setup  
- Used **Dependency Injection** and DTO patterns for clean architecture  
- Wrote backend tests with **xUnit**, **FluentAssertions**, and **NSubstitute**

### ☁️ Azure & DevOps
- Built and deployed both frontend and backend via **Azure Pipelines**
- Configured **pipeline tasks** for build, test, and deploy steps
- Connected pipelines with Azure SQL Database and Blob Storage
- Added environment variables via pipeline YAML configuration

### 🧰 Git Workflow
- Worked in feature branches (`feature/12345_feature_name`)
- Regular merges with `main` using pull requests and code review

---


# 🧠 Lessons Learned
- How to structure fullstack projects with Next.js + .NET
- CI/CD automation with Azure
- Writing maintainable tests for both frontend and backend
- Debugging deployment issues and handling pipelines
- Collaborating efficiently in a small dev team




> ⚠️ This repository contains personal notes related to my internship at Esatto.
> It does not include or expose any proprietary code or confidential information belonging to Esatto.
