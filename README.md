# 🚀 Enterprise Jenkins CI Pipeline – Slack Notification Integration on AWS

[![Jenkins](https://img.shields.io/badge/Jenkins-CI-blue)](https://www.jenkins.io/)
[![AWS](https://img.shields.io/badge/AWS-EC2-orange)](https://aws.amazon.com/ec2/)
[![SonarQube](https://img.shields.io/badge/SonarQube-Code%20Quality-brightgreen)](https://www.sonarsource.com/products/sonarqube/)
[![Nexus Repository](https://img.shields.io/badge/Nexus-Artifact%20Repository-blue)](https://www.sonatype.com/products/repository-oss)
[![Slack](https://img.shields.io/badge/Slack-Build%20Notifications-4A154B)](https://slack.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📖 Project Overview

This project demonstrates the integration of *Slack notifications* into an enterprise Jenkins Continuous Integration (CI) pipeline hosted on Amazon Web Services (AWS). The implementation enables Jenkins to automatically send real-time build notifications to a Slack channel whenever a pipeline execution completes successfully or fails.

The integration extends an existing enterprise CI pipeline for the VProfile Java application, providing immediate visibility into build outcomes without requiring team members to continuously monitor the Jenkins dashboard.

The solution uses the *Jenkins Slack Notification Plugin, a **custom Slack App with Bot User OAuth authentication, and **secure credential management* within Jenkins. Notifications include the build status, job name, build number, and a direct link to the Jenkins build
