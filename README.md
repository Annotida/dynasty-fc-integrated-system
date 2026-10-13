# Dynasty FC Integrated System

A web-based football club management system designed to bring club information, administrative operations, and digital services together in one platform.

**Project status:** Under development

## Overview

Dynasty FC Integrated System is a software development project focused on supporting the digital operations of a football club.

The project combines a Python Flask backend with a web frontend to provide a foundation for managing club information and administrative activities.

The goal is to improve the organisation of club information and provide a central platform for players, staff, administrators, and other stakeholders.

## Features and Project Modules

The project includes pages and modules for the following areas:

- **Club website:** Homepage, club information, teams, gallery, news, and contact pages.
- **Player management:** Interfaces for player-related information.
- **Staff management:** Pages for staff administration.
- **Finance:** Interfaces for financial information and reporting.
- **Inventory:** Pages for managing inventory-related information.
- **Documents and contracts:** Interfaces for document and contract management.
- **Training:** A section for training-related information.
- **User access:** Login, registration, and access-denied pages.
- **Reports and audit:** Pages intended to support reporting and administrative oversight.
- **Donations:** Interfaces for donations and getting involved with the club.

These modules describe the areas represented in the project. Their operational status depends on the current backend, database configuration, and implementation.

## Technology Stack

### Backend
- Python
- Flask
- MySQL integration
- REST-style web routes, where implemented

### Frontend
- HTML
- CSS
- JavaScript

### Development Tools
- Visual Studio Code
- Git
- GitHub

## Project Structure

```text
Dynasty_Integrated_System/
├── backend/
│   ├── app.py
│   ├── database/
│   ├── security.py
│   └── email_template.py
├── frontend/
│   ├── css/
│   ├── images/
│   ├── js/
│   └── templates/
├── requirements.txt
├── runtime.txt
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

Install the following software:

- Python compatible with the project dependencies
- pip
- MySQL Server
- Git

### 1. Clone the repository

```bash
git clone https://github.com/Mankwanyana/dynasty-fc.git
cd dynasty-fc
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

On Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Configure environment variables

Create a local `.env` file containing the environment variables required by the application.

Configure the database connection using the variable names expected by the backend.

Do not commit database passwords, API keys, email credentials, or other secrets.

### 5. Configure the database

Install and start MySQL Server.

Create the database specified in your local configuration and ensure the configured database user has the required permissions.

The exact database setup depends on the application's current schema and configuration.

### 6. Start the application

From the project root, run:

```bash
python backend/app.py
```

If the application starts successfully, open the local address displayed in the terminal.

**Note:** Database configuration may be required before the application can start. The setup instructions should be updated as the project is tested in a clean environment.

## Security Considerations

- Keep real environment variables and credentials out of version control.
- Use `.env.example` for placeholder configuration values.
- Do not publish real user information or database exports.
- Review authentication, authorisation, and input validation before deploying the application publicly.
- Use HTTPS and secure production configuration when deploying.

## Current Status and Future Improvements

The project is under development.

Potential areas for continued development include:

- Completing and testing database integration.
- Verifying the functionality of each module.
- Improving error handling and application logging.
- Adding automated tests.
- Improving deployment and configuration documentation.
- Reviewing accessibility and responsive design.
- Documenting security controls and authentication behaviour.

## Purpose

This project demonstrates practical work in web development, backend programming, database integration, and the organisation of a multi-module application.

It is presented as a software development portfolio project.