# IT Service Management (ITSM) and Ticketing System Lab

This repository contains a comprehensive guide for setting up and managing an IT Service Management (ITSM) system using Jira Service Management. The lab simulates a help desk environment and demonstrates the ability to manage IT service requests and incidents efficiently.

## Table of Contents

1. [Lab Overview](#lab-overview)
2. [Setup](#setup)
   - [Sign Up for Jira Service Management](#sign-up-for-jira-service-management)
   - [Create a New Project](#create-a-new-project)
3. [Configuration](#configuration)
   - [Set Up Request Types](#set-up-request-types)
   - [Create Simple Workflow](#create-simple-workflow)
   - [Set Up SLAs (Service Level Agreements)](#set-up-slas-service-level-agreements)
4. [Tasks](#tasks)
   - [Create Sample Tickets](#create-sample-tickets)
   - [Automate Ticket Assignment](#automate-ticket-assignment)
   - [Set Up Notifications](#set-up-notifications)
   - [Generate Basic Reports and Dashboards](#generate-basic-reports-and-dashboards)

## Lab Overview

This lab demonstrates the following:
- Setting up a ticketing system using Jira Service Management.
- Creating and managing IT service requests and incidents.
- Implementing basic workflows and SLAs.
- Automating ticket assignments and notifications.
- Generating basic reports and dashboards to track key metrics.

## Setup

### Sign Up for Jira Service Management

1. **Sign Up:**
   - Visit the [Jira Service Management site](https://www.atlassian.com/software/jira/service-management) and sign up for a free trial or personal instance.
![Jira Home](https://github.com/user-attachments/assets/dd1b95f2-1f10-4d86-92cc-9052f259d7f9)
2. **Instance Setup:**
   - Follow the setup wizard to configure your instance and log in.

### Create a New Project

1. **Create Project:**
   - Go to "Projects" > "Create project."
   - Choose the "Service Management" template.
   ![create project](https://github.com/user-attachments/assets/5772a866-18c5-4ebb-82aa-91ac1b9b90d5)
   - Name your project (e.g., "Help Desk").

## Configuration

### Set Up Request Types

1. **Add Request Types:**
   - Go to "Project settings" > "Request types."
   - Add request types like "IT Support," "Password Reset," and "Software Installation."
   ![Jira Request Types](https://github.com/user-attachments/assets/3fd9dfdd-584a-4145-8948-cdceca9473a9)
   - Map fields like Summary, Description, and Priority to these request types.

### Create Simple Workflow

1. **Define Workflow:**
   - Go to "Project settings" > "Workflows."
   ![Jira Workflow](https://github.com/user-attachments/assets/d59a6a22-915a-4334-a7dd-56f0277157d9)
   - Use the default workflow or create a simple one with statuses like:
     - **Open:** Initial state when a ticket is created.
     - **In Progress:** When a technician is working on the ticket.
     - **Resolved:** When the issue is resolved.
     - **Closed:** When the ticket is confirmed resolved and closed.
   ![Jira incident management workflow](https://github.com/user-attachments/assets/4bd3b799-b7b0-4139-b7cf-257c7fd40bea)
   - Define transitions between these statuses:
     - Open -> In Progress
     - In Progress -> Resolved
     - Resolved -> Closed

### Set Up SLAs (Service Level Agreements)

1. **Create SLA Rules:**
   - Go to "Project settings" > "SLAs."
   - Create simple SLA rules:
     - **Time to First Response:** Start when a ticket is created, stop when it moves to "In Progress," goal: 30 minutes.
     - **Time to Resolution:** Start when a ticket is created, stop when it moves to "Resolved," goal: 4 hours.
     ![Jra SLA](https://github.com/user-attachments/assets/4055cd35-9293-469a-bbd5-44e9998ceb04)

## Tasks

### Create Sample Tickets

1. **Common IT Issues:**
   - Create sample tickets for common issues:
   ![Jira create tickets](https://github.com/user-attachments/assets/a40f1d02-c855-4279-9162-37b758fb3488)
     - **Password Reset:** Create a ticket requesting a password reset.
     - **Software Installation:** Create a ticket requesting software installation.
     - **Hardware Issue:** Create a ticket reporting a hardware issue.
   - Ensure each ticket follows the predefined workflows.
   ![Jira resolved ticket](https://github.com/user-attachments/assets/c4425eab-65f2-4ce0-b744-7321c51c3216)

### Automate Ticket Assignment

1. **Set Up Automation:**
   - Go to "Project settings" > "Automation."
   - Create a rule to automatically assign tickets to specific technicians based on request type or priority.
   ![jira tier 4](https://github.com/user-attachments/assets/e43263cc-5afe-443f-b39c-2aa3f5ebf706)

### Set Up Notifications

1. **Configure Notifications:**
   - Go to "Project settings" > "Notifications."
   - Configure email or in-app notifications to alert users of ticket updates and resolutions.
   ![jira notification](https://github.com/user-attachments/assets/f3bbb8e4-554b-4457-96ea-168c4ee78cbe)

### Generate Basic Reports and Dashboards

1. **Create Simple Reports:**
   - Go to "Reports" in the project.
   - Create reports to track metrics like response times, resolution times, and ticket volumes.
   ![reports service requests](https://github.com/user-attachments/assets/2e664bed-2c47-42cb-9a93-343181a2887d)

2. **Set Up Dashboards:**
   - Go to "Dashboards" > "Create dashboard."
   - Add gadgets to visualize key metrics and service performance.
   ![Jira Dashboard](https://github.com/user-attachments/assets/5a5efb90-82f4-481b-a210-8ab80c7903c6)




