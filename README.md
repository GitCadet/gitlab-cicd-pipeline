# Simple GitLab CICD Pipeline
This repository showcases a basic CI/CD pipeline I built using GitLab. 
I practiced configuring and automating workflows with GitLab CI/CD through the creation and management of a .gitlab-ci.yml file. The pipeline automates two main stages: building and deploying the application.

## Key Features
**Build Stage:** Installs dependencies and caches node_modules to speed up subsequent builds.                                 
**Deploy Stage:** Installs dependencies again and starts the application.

![image_alt](https://github.com/GitCadet/my-gitlab-cicd-pipeline/blob/main/gitlab-cicd_pip.png?raw=true)

## Troubleshooting
Some issues I came across include: 
- Missing Dependencies: I ensured node_modules and package-lock.json were correctly cached.
- Deployment Failures: I reviewed logs for environment or configuration issues, eventually resolving the problem.

![image_alt](https://github.com/GitCadet/my-gitlab-cicd-pipeline/blob/main/gitlab%20cicd.png?raw=true)

**This project highlights my experience in working with GitLab CI/CD pipelines and showcases how I used GitLab to automate stages of the development process.**

