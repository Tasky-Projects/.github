# 👋 Welcome to **Tasky-Projects**

🌟 **Demo Enterprise Project Public**  
Built by **Rob Mann**

---

## ✅ **Overview**
The **Demo Enterprise Project** is an integrated enterprise solution showcasing modern architecture, robust workflows, and seamless platform integration.  
It combines **.NET technologies**, **cloud hosting**, and **collaboration tools** to deliver a scalable and maintainable system.

---

## 📋 **Detailed Sections**

### 🖥️ **Technology Stack**
- ⚙️ **.NET**, **Entity Framework (EF)**, **Dependency Injection (DI)**
- 🖌️ **Blazor** for UI
- 🗄️ **SQL** for data management
- ✅ **Testing frameworks**
- 💻 **C#** as the primary language

### 🔗 **Version Control & CI/CD**
- 🔄 **GitHub Actions** for automated CI/CD pipelines
- 📂 Repository hosted in project space

### 📚 **Documentation**
- 🏗️ **Confluence** structure for team collaboration
- 🤖 **Automation** and **templates** for streamlined documentation
- 🔗 Integration with **Jira** for traceability

### 📈 **Project Management**
- 🔄 **Jira** workflow configuration
- 🔗 Integration with **Confluence** and **Git**

### ☁️ **Cloud Hosting**
- **Azure** for deployment and hosting *(details to be defined)*

---

## 🔗 **Links**
- **Jira**: [Tasky Jira Board](https://common-pensions-project.atlassian.net/jira/software/projects/TASKY/boards/101)  
- **GitHub**: [Tasky GitHub Org](https://github.com/Tasky-Projects)  
- **Confluence**: [Tasky Confluence Space](https://common-pensions-project.atlassian.net/wiki/spaces/TASKY/overview)  

---

## ✅ **CI/CD Status**
*(Add badges here for build, test, deploy)*

---

## 📦 **Repositories by Product**

### 🔹 **Tasky Core**
Note this wil only work from within the Tasky-Projects GitHub organization.

| 📂 **Repository** | 📝 **Description** | ✅ **Status** |
|--------------------|----------------------|---------------|
| `Tasky.WebApp` | 🌐 WebApp with login functionality | ![Build]( https://img.shields.io/github/actions/workflow/status/Tasky-Projects/Tasky.WebApi/build.yml?branch=main) |
| `Tasky.Application` | 🛠 Service interfaces & business logic | ![BuildStatus](https://img.shields.io/github/actions/workflow/status/Tasky-Projects/Tasky.Application/publish-nuget.yml?branch=main) |
| `Tasky.Domain.Data` | 🗄 Data interface for Tasky domain | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Infrastructure.Repositories` | 📦 Data repositories for querying logic | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Domain.Calculations` | ➗ Domain-specific calculations | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Calculations` | 🔢 Reusable math library | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Infrastructure.Core` | 🏗 Entity Framework database setup | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Shared.Library` | 🔄 Shared configuration for CI/CD | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.WebApi` | 🔌 Backend API for Tasky | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Dtos` | 📦 Data Transfer Objects | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Common` | ⚙️ Common constants & shared objects | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `Tasky.Data.Persistence.Migrator` | 🔄 Database migration project | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |

### 🔹 **Common Pensions Project (CPP)**
| 📂 **Repository** | 📝 **Description** | ✅ **Status** |
|--------------------|----------------------|---------------|
| `cpp-docs` | 📚 Documentation repository | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `cpp-specifications` | 📜 OpenAPI specifications | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `cpp-sdks` | 🔧 Generated SDKs for multiple languages | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `cpp-reference` | 🏗 Reference implementation | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `cpp-testing` | ✅ Testing for CPP | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |
| `cpp-api` | 🧩 Production-grade RESTful API | ![Build](https://img.shields.io/badge/build-passing-brightgreen) |

---

## 🖼 Architecture Diagram
![Architecture Diagram](architecture_diagram.png)
