# 🚀 Enterprise Jenkins CI Pipeline – Slack Notification Integration on AWS

[![Jenkins](https://img.shields.io/badge/Jenkins-CI-blue)](https://www.jenkins.io/)
[![AWS](https://img.shields.io/badge/AWS-EC2-orange)](https://aws.amazon.com/ec2/)
[![SonarQube](https://img.shields.io/badge/SonarQube-Code%20Quality-brightgreen)](https://www.sonarsource.com/products/sonarqube/)
[![Nexus Repository](https://img.shields.io/badge/Nexus-Artifact%20Repository-blue)](https://www.sonatype.com/products/repository-oss)
[![Slack](https://img.shields.io/badge/Slack-Build%20Notifications-4A154B)](https://slack.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

📖 Project Overview

This project demonstrates the integration of Slack notifications into an enterprise Jenkins Continuous Integration (CI) pipeline hosted on Amazon Web Services (AWS). The primary objective was to automate real-time build notifications, enabling development and DevOps teams to receive immediate feedback whenever a pipeline execution completes successfully or fails.

The implementation extends an existing CI pipeline for the VProfile Java application by integrating Jenkins with Slack through the Jenkins Slack Notification Plugin and a custom Slack App using Bot User OAuth authentication. Upon completion of each pipeline execution, Jenkins automatically sends a notification to a designated Slack channel containing the build status, job name, build number, and a direct link to the build for quick investigation.

The notification process is fully integrated into the CI workflow, which includes source code checkout from GitHub, application build with Apache Maven, unit testing, Checkstyle analysis, SonarQube code quality analysis, Quality Gate validation, artifact publication to Nexus Repository Manager, and automated Slack notifications.

This project demonstrates practical experience in integrating collaboration platforms with CI pipelines to improve team communication, build visibility, and operational efficiency while following enterprise DevOps best practices.
