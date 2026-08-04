<p align="center">
  <img src="./file.png" width="100%" />
</p>

<h1 align="center">Hi, I'm Himani 👋</h1>

<p align="center">
  <b>DevSecOps • Cloud Security • Software Engineering</b>
</p>

<p align="center">
  Building secure and automated software delivery systems while learning
  DevSecOps, cloud security and software engineering.
</p>

<p align="center">
  <a href="https://github.com/himanidhawan-cloud">
    <img src="https://img.shields.io/badge/GitHub-himanidhawan--cloud-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
</p>

---

## 🚀 Currently Working On

### 🔐 SecureDeploy

**SecureDeploy** is my major DevSecOps project focused on integrating
security into the software delivery lifecycle.

The goal is to create a system where a Pull Request can be automatically
analysed for security issues before it reaches deployment.

### 🔄 Planned Workflow

```text
                    GitHub Pull Request
                            │
                            ▼
                     GitHub Webhook
                            │
                            ▼
                         Jenkins
                            │
                ┌───────────┴───────────┐
                ▼                       ▼
            SonarQube                  OSV
          Code Analysis        Dependency Scanning
                │                       │
                └───────────┬───────────┘
                            ▼
                     Security Engine
                            │
                            ▼
                  Security Scorecard
                            │
                            ▼
                      Security Gate
                            │
                     ┌──────┴──────┐
                     │             │
                   FAIL           PASS
                     │             │
                     ▼             ▼
                  Report      Deployment Request
                                   │
                                   ▼
                              Admin Approval
                                   │
                                   ▼
                              Docker Build
                                   │
                                   ▼
                               AWS Deploy
