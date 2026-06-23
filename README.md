# Git Jenkins Integration

A practice repository for learning how to integrate **Git/GitHub with Jenkins** to set up a basic Continuous Integration (CI) workflow.

## 📌 About

This repository documents hands-on practice with connecting a GitHub repository to a Jenkins pipeline — covering webhook setup, job configuration, and triggering automated builds on code changes. The goal was to understand the fundamentals of CI/CD before applying them to larger automation projects (see the [BStack Demo Capstone Project](https://github.com/MiruthyanJayanS/Bstack-demo-Automation-Testing-Capstone-Project), which builds on this).

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Version Control | Git / GitHub |
| CI/CD Tool | Jenkins |

## 🎯 Topics Covered

- Setting up a Jenkins job linked to a GitHub repository
- Configuring GitHub webhooks to trigger Jenkins builds automatically
- Writing and understanding a basic `Jenkinsfile` / pipeline configuration
- Triggering builds on push events and viewing build status

## 📂 Project Structure

```
gitjenkinsintegration/
├── Jenkinsfile        # Pipeline configuration for the Jenkins job
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- A Jenkins instance (local or hosted)
- A GitHub account/repository
- Git installed locally

### Setup
```bash
git clone https://github.com/MiruthyanJayanS/gitjenkinsintegration.git
cd gitjenkinsintegration
```

### Setting Up the Integration
1. Create a new Jenkins job (Pipeline or Freestyle) and point it to this repository
2. In the GitHub repository settings, add a Webhook pointing to your Jenkins server's GitHub webhook endpoint
3. Configure the Jenkins job to use the `Jenkinsfile` from this repo (if using a Pipeline job)
4. Push a commit to trigger the build automatically and verify it runs in Jenkins

## 🎯 Learning Outcomes

- Understood the basics of CI/CD and why it matters in a development workflow
- Learned how Jenkins jobs are triggered via GitHub webhooks
- Got hands-on experience writing a simple Jenkins pipeline configuration

## 📄 License

This repository is for personal learning and reference purposes.
