loudBees Multibranch Pipeline Templates

This repository contains centrally governed multibranch pipeline templates for CloudBees CI using the Pipeline Template Catalog (PTC) feature.

These templates allow teams to create standardized, secure, and reusable Multibranch Pipelines without requiring Jenkinsfiles in application repositories.

🎯 Purpose

Centralize CI pipeline definitions

Enforce enterprise CI standards

Eliminate Jenkinsfile duplication

Enable secure, parameterized multibranch pipelines

Support governance and RBAC in CloudBees

🏗 Repository Structure
cloudbees-multibranch-templates/
├── catalogs.yaml
├── templates/
│   ├── springboot-gradle-git-multibranch.yaml
│   ├── maven-git-multibranch.yaml
│   └── docker-build-multibranch.yaml
└── README.md
