# ERPWatcher — Application Availability Monitoring

**Full-Stack Web Application | React · Node.js · Express · PostgreSQL**

[English](README.md) | [Français](README.fr.md)

## Overview

ERPWatcher is a full-stack web application designed to monitor application interruptions, calculate availability rates, and provide insights into the reliability of ERP systems.

The application centralizes application management, interruption tracking, and availability monitoring through an interactive dashboard.

This personal project demonstrates my experience in full-stack development, REST API design, database management, JWT authentication, and data visualization.

## Key Features

### Authentication and Security
- User authentication using JSON Web Tokens (JWT)
- Protected application features

### Application Management
- Add and update monitored applications
- Activate or deactivate applications
- Manage application information through a centralized interface

### Interruption Management
- Create, update, and delete interruption types
- Prevent deletion of interruption types already associated with recorded interruptions
- Record and track application downtime
- View interruption history

### Availability Dashboard
- Calculate application availability rates based on recorded interruptions
- Display overall system availability
- Visualize key performance indicators (KPIs)
- Support monitoring and operational reporting

### Responsive User Interface
- Responsive layout for desktop, tablet, and mobile devices
- React-based navigation and interactive components

## Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React 18, React Router DOM, Axios, CSS |
| Backend | Node.js, Express.js |
| Database | PostgreSQL, node-postgres (pg) |
| Authentication | JSON Web Tokens (JWT) |
| API | RESTful API |

## Application Architecture

ERPWatcher follows a client-server architecture with a clear separation between frontend, backend, and database responsibilities.

**Frontend — React**

Provides the user interface for managing applications, recording interruptions, and viewing availability metrics.

**Backend — Node.js / Express**

Exposes REST API endpoints, handles authentication, processes application and interruption data, and implements business logic.

**Database — PostgreSQL**

Stores application information, interruption types, downtime records, and related data.

### Data Flow

`React Frontend → REST API (Express) → PostgreSQL`

The backend processes requests, retrieves or updates database records, and returns responses to the React interface.

## Screenshots

### Availability Dashboard

![ERPWatcher Dashboard](screenshots/dashboard.png)

### Application Management

![Application Management](screenshots/applications.png)

### Interruption Tracking

![Interruption Tracking](screenshots/interruptions.png)



## Technical Highlights

- Developed a full-stack application connecting React, Express, and PostgreSQL.
- Implemented JWT-based authentication to protect application functionality.
- Designed REST APIs for application and interruption management.
- Implemented business rules to prevent deletion of interruption types referenced by existing records.
- Developed availability calculations based on recorded downtime.
- Built responsive interfaces for monitoring and managing application data.

## Project Status

**Personal full-stack project**

The application demonstrates practical full-stack development skills through a complete application-monitoring workflow.

## Source Code

The complete source code is maintained in a private GitHub repository.

This public showcase presents the application's features, technical architecture, and user interface without exposing the implementation.

## Author

**Carmela Urbano — Full-Stack Developer**

- Portfolio: https://www.curbano.fr
- GitHub: https://github.com/carmela0505
