# Project II - VProfile Project Setup [LOCAL]
# I.) Project Setup
* About the Project
The VProfile project is focused on building a multi-tier web application stack that runs seamlessly on your laptop or desktop. It serves as a foundational step, laying the groundwork for upcoming projects. The goal is to simplify the process of setting up and managing local development environments, ensuring a smoother and more efficient workflow.

* Scenario: Working on a Project
This project brings together several key services to create a functional runtime environment:

- Database Services: MySQL and PostgreSQL handle data storage and management.
- Web Services: Apache and Nginx manage web traffic and deliver content effectively.
- Application Services: Tomcat and GlassFish support the application layer.
A comprehensive RunBook and setup guide will assist with the installation, configuration, and troubleshooting of these services.

# The Challenges
 * 1 Making direct changes on real servers is risky and uncomfortable.
 * 2 Setting up a local environment can be complex and frustrating.
 * 3 Routine tasks take too long to complete.
 * 4 The setup process is inconsistent and hard to replicate.

# The Solution
To address these challenges, this project adopts a fully automated and repeatable local setup aligned with Infrastructure as Code (IaC) principles. This allows for seamless experimentation and research directly on your local machine.

# Tools Utilized
* Hypervisor: Oracle VM VirtualBox – For creating and managing virtual environments.
* Automation: Vagrant – Simplifies the setup and management of development environments.
* CLI: Git Bash – Preferred for command-line operations.
* IDE: Sublime Text or Visual Studio – Chosen based on project requirements.

# Objectives
* Automate virtual machine setup processes locally to optimize workflows.
* Establish a strong foundation for future projects and initiatives.
* Enable real-world experimentation and innovation through locally-hosted projects.

# The Architecture of Project Services
Automation Setup Overview

Core Components: Vagrant, VirtualBox, Git Bash, Scripts, Commands

# II.) Flow of Execution
 1 Begin by setting up the tools mentioned in the Prerequisite Video.

Clone the source code repository.

Navigate to the Vagrant directory (cd into it).

Spin up the virtual machines using Vagrant.

Validate that the VMs are functioning correctly.

Configure and set up the following services:

MySQL
Memcached
RabbitMQ
Tomcat (Apache)
Nginx
Build and deploy the application.

Open your browser to verify that everything works as expected.



# VProfile-Project-Setup-LOCAL-
# Prerequisites
* JDK 17
* Maven 3
* MySQL 8
# Technologies
* Spring MVC
* Spring Security
* Spring Data JPA
* Maven
* JSP
* Tomcat
* MySQL
* Memcached
* Rabbitmq
* ElasticSearch

# Database
Here, we used Mysql DB sql dump file:

* /src/main/resources/db_backup.sql
* db_backup.sql file is a mysql dump file. We have to import this dump to mysql db server

