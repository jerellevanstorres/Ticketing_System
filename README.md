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
2. **Instance Setup:**
   - Follow the setup wizard to configure your instance and log in.

### Create a New Project

1. **Create Project:**
   - Go to "Projects" > "Create project."
   - Choose the "Service Management" template.
   - Name your project (e.g., "Help Desk").

## Configuration

### Set Up Request Types

1. **Add Request Types:**
   - Go to "Project settings" > "Request types."
   - Add request types like "IT Support," "Password Reset," and "Software Installation."
   - Map fields like Summary, Description, and Priority to these request types.

### Create Simple Workflow

1. **Define Workflow:**
   - Go to "Project settings" > "Workflows."
   - Use the default workflow or create a simple one with statuses like:
     - **Open:** Initial state when a ticket is created.
     - **In Progress:** When a technician is working on the ticket.
     - **Resolved:** When the issue is resolved.
     - **Closed:** When the ticket is confirmed resolved and closed.
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

## Tasks

### Create Sample Tickets

1. **Common IT Issues:**
   - Create sample tickets for common issues:
     - **Password Reset:** Create a ticket requesting a password reset.
     - **Software Installation:** Create a ticket requesting software installation.
     - **Hardware Issue:** Create a ticket reporting a hardware issue.
   - Ensure each ticket follows the predefined workflows.

### Automate Ticket Assignment

1. **Set Up Automation:**
   - Go to "Project settings" > "Automation."
   - Create a rule to automatically assign tickets to specific technicians based on request type or priority.

### Set Up Notifications

1. **Configure Notifications:**
   - Go to "Project settings" > "Notifications."
   - Configure email or in-app notifications to alert users of ticket updates and resolutions.

### Generate Basic Reports and Dashboards

1. **Create Simple Reports:**
   - Go to "Reports" in the project.
   - Create reports to track metrics like response times, resolution times, and ticket volumes.

2. **Set Up Dashboards:**
   - Go to "Dashboards" > "Create dashboard."
   - Add gadgets to visualize key metrics and service performance.



