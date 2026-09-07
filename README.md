# CRUUZ

### Full-Stack Mobility Platform

CRUUZ is a mobility technology platform under active development, connecting rider and driver experiences with backend services, real-time workflows, payments, safety tooling, business mobility, operations, and internal workplace systems.

**Status:** Active Development  
**Website:** https://www.cruuz.org

> This public repository is a portfolio and product-documentation repository. The full application source is not currently published here.

---

## Project Overview

CRUUZ is being developed as a multi-application mobility ecosystem rather than a single ride-booking application.

Current engineering work spans:

- Rider and driver application experiences
- Booking and trip lifecycle workflows
- Driver matching and dispatch concepts
- Real-time application events
- Authentication, authorization, and RBAC
- Wallet, payment, earnings, and incentive workflows
- Safety and operational tooling
- Business mobility accounts
- Employee and People/HR workflows
- Backend APIs and database-driven services
- AI-assisted mobility and workplace concepts

Some components are implemented and testable, while others remain under active development or are planned architecture. This README intentionally distinguishes those states rather than presenting the platform as production-complete.

---

## System Architecture

```text
CRUUZ
|
|-- Rider Application
|-- Driver Application
|-- Backend / API Services
|-- Real-Time Services
|-- Authentication & Access Control
|-- Wallet & Payment Workflows
|-- Safety & Trust Workflows
|-- Operations Tooling
|-- Business Mobility
`-- Employee / People Workspace
```

### Rider Experience

Development areas include account and profile functionality, ride booking, trip lifecycle, driver information, real-time trip updates, payment-related workflows, wallet functionality, promotions, and safety features.

### Driver Experience

Development areas include driver account functionality, availability, ride requests, active-trip management, earnings, incentives, performance information, safety workflows, and real-time connectivity.

### Backend & API Services

Backend engineering includes REST APIs, authentication, authorization, role-based access control, database operations, trip workflows, payment-related logic, real-time events, and operational services.

### Operations Tooling

Operational areas include dispatch, finance, safety, growth, compliance, driver operations, rider operations, and business-account workflows.

---

## Real-Time Functionality

Socket.IO is used where applicable for event-driven communication between applications and backend services.

Examples include:

- Trip-state updates
- Driver and rider events
- Dispatch-related communication
- Operational events
- Application connectivity updates

---

## Intelligent Driver Recommendation

CRUUZ is exploring an intelligent booking model that can go beyond simple nearest-driver assignment. The concept evaluates relevant operational and service factors to recommend suitable available drivers while preserving rider choice where supported.

This component remains experimental and under active development.

---

## Payments, Wallet & Earnings

Financial workflows being developed include rider payments, driver earnings, wallet functionality, promotions, incentives, driver bonuses, cancellation-related logic, and operational finance processes.

These workflows continue to evolve with the rest of the platform and should not be interpreted as a production payment service from this public repository alone.

---

## Business Mobility

CRUUZ is also being designed for organizational mobility. Developing and planned capabilities include company accounts, employee management, scheduled rides, airport transfers, department billing, cost centres, ride policies, business travel management, and monthly invoicing workflows.

---

## Employee & People Operations

The CRUUZ web application also contains workplace and People/HR interfaces. Current UI work demonstrated during development includes:

- Employee dashboard
- Leave self-service and leave management
- Training progress
- Performance and appraisal workflows
- People / HR workspace
- Recruitment and employee records navigation
- Documents
- Role-aware workplace navigation
- AI-assistant concepts

These modules are part of the broader operating platform and remain under development.

---

## Security & Access Control

Security-related engineering areas include:

- Authentication
- Authorization
- Role-Based Access Control (RBAC)
- API security principles
- Operational access controls
- Identity and access-management concepts
- Security-aware application development

---

## Technology Stack

| Layer | Technologies |
| --- | --- |
| Web | TypeScript, React, Next.js |
| Mobile | React Native, Expo |
| Backend | Node.js, Express.js, REST APIs |
| Real-time | Socket.IO |
| Data | PostgreSQL, Prisma |
| Engineering | Git, GitHub, API integration, debugging, testing |

---

## Engineering Areas Demonstrated

CRUUZ is being used to build practical experience across full-stack development, backend APIs, frontend and mobile application development, relational databases, authentication and authorization, RBAC, real-time systems, event-driven workflows, payment-related application logic, operational tooling, debugging, testing, and systems design.

---

## Product Preview

A curated screenshot showcase is being prepared from the working CRUUZ interfaces. Public screenshots will use sanitized demonstration data and will avoid exposing personal, payroll, appraisal, authentication, or other sensitive information.

Selected showcase areas:

1. Employee Dashboard
2. People / HR Workspace
3. Leave Management
4. Performance & Appraisals overview

Screenshots will be stored under `docs/screenshots/` and referenced here with descriptive alt text once the sanitized assets are ready.

---

## Development Status

**Active Development**

CRUUZ is an evolving engineering project. The public repository currently documents the system and its development progress; it is not a claim that every described capability is production-ready.

The project continues through implementation, integration, testing, debugging, and architectural refinement.

---

## Engineering Contribution

**Max Collins Botchway**  
Software Engineer / Full-Stack Developer

Work on CRUUZ spans frontend interfaces, backend services, database-driven workflows, authentication and authorization, real-time functionality, mobile development, operational workflows, debugging, testing, and application integration.

Core technologies:

`TypeScript` · `React` · `Next.js` · `React Native` · `Node.js` · `Express.js` · `PostgreSQL` · `Prisma` · `REST APIs` · `Socket.IO`

LinkedIn: https://www.linkedin.com/in/maxcb  
GitHub: https://github.com/maxbotchway
