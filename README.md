# Git Jenkins Integration

A simple Java practice repository, created while exploring **Git and Jenkins integration workflows**.

## 📌 About

This repository currently contains a basic Java program (`Sample.java` / `Sample.class`) used as a placeholder/test file while setting up and experimenting with connecting this repository to a Jenkins CI pipeline. The Java file itself is intentionally simple — the main learning focus of this repo was the **Git ↔ Jenkins integration process** (e.g. linking a GitHub repo to a Jenkins job, triggering builds on changes), rather than the Java code itself.

> 📌 Note: This repo currently holds minimal sample code (`Sample.java`). It primarily served as a working test bed for Jenkins/Git integration practice rather than a fully built-out application.

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Java |
| Version Control | Git / GitHub |
| CI Tool (practiced with) | Jenkins |

## 📂 Project Structure

```
gitjenkinsintegration/
├── Sample.java     # Simple Java source file
├── Sample.class    # Compiled Java class file
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Java JDK 8+

### Setup
```bash
git clone https://github.com/MiruthyanJayanS/gitjenkinsintegration.git
cd gitjenkinsintegration
```

### Running
```bash
java Sample
```
> If `Sample.class` is outdated, recompile first:
> ```bash
> javac Sample.java
> java Sample
> ```

## 🎯 Learning Outcomes

- Practiced setting up a basic Git repository for use with Jenkins
- Explored how a Jenkins job can be configured to track and build from a GitHub repository
- Used a minimal Java file as a low-stakes test case while learning the integration setup

## 📄 License

This repository is for personal learning and reference purposes.
