# CRUUZ

### Full-Stack Mobility Platform

CRUUZ is a mobility technology platform under active development, connecting distinct rider and driver applications with backend services, real-time workflows, payments, safety tooling, business mobility, and a separate employee-facing workplace console.

**Status:** Active Development  
**Website:** https://www.cruuz.org

> This public repository is a portfolio and product-documentation repository. The full application source is not currently published here.

---

## Project Overview

CRUUZ is being developed as a multi-application mobility ecosystem rather than a single ride-booking application.

Current engineering work spans:

- Rider application
- Driver application
- Booking and trip lifecycle workflows
- Driver matching and dispatch concepts
- Real-time application events
- Authentication, authorization, and RBAC
- Wallet, payment, earnings, and incentive workflows
- Safety and operational tooling
- Business mobility accounts
- CRUUZ Employee Console / Employee Portal
- Backend APIs and database-driven services
- AI-assisted mobility and workplace concepts

Some components are implemented and testable, while others remain under active development or are planned architecture. This README intentionally distinguishes those states rather than presenting the platform as production-complete.

---

## Product Surfaces

```text
CRUUZ
|
|-- Rider App
|-- Driver App
|-- Backend / API Services
|-- Real-Time Services
|-- Authentication & Access Control
|-- Wallet & Payment Workflows
|-- Safety & Trust Workflows
|-- Business Mobility
`-- Employee Console / Employee Portal
```

### Rider App

The rider-facing application covers the customer mobility experience, including account and profile functionality, ride booking, trip lifecycle, driver information, real-time trip updates, payment-related workflows, wallet functionality, promotions, and safety features.

### Driver App

The driver-facing application is a separate operational experience covering driver account functionality, availability, ride requests, active-trip management, earnings, incentives, performance information, safety workflows, and real-time connectivity.

### Backend & API Services

Backend engineering includes REST APIs, authentication, authorization, role-based access control, database operations, trip workflows, payment-related logic, real-time events, and operational services.

### CRUUZ Employee Console

The CRUUZ Employee Console is the employee-facing digital workplace. It is distinct from the Nexaro Ops Enterprise Command System, which is a separate Nexaro project.

Employee Console development includes:

- Employee dashboard
- Profile and workspace navigation
- Tasks and calendar
- Notifications
- Documents
- Leave self-service
- Payroll interfaces
- Training
- Performance and appraisal workflows
- People / HR workspace
- Role-aware navigation
- AI Copilot / assistant concepts

---

## Real-Time Functionality

Socket.IO is used where applicable for event-driven communication between applications and backend services.

Examples include trip-state updates, driver and rider events, dispatch-related communication, operational events, and application connectivity updates.

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

## Security & Access Control

Security-related engineering areas include authentication, authorization, Role-Based Access Control (RBAC), API security principles, operational access controls, identity and access-management concepts, and security-aware application development.

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

CRUUZ is being used to build practical experience across full-stack development, backend APIs, frontend and mobile application development, relational databases, authentication and authorization, RBAC, real-time systems, event-driven workflows, payment-related application logic, workplace tooling, debugging, testing, and systems design.

---

## Product Previews

CRUUZ is presented as three distinct application experiences:

1. **Rider App** — customer ride-booking and trip experience.
2. **Driver App** — driver operations, trip management, earnings, and connectivity.
3. **Employee Console** — employee workplace, leave, payroll, training, performance, documents, and People/HR workflows.

Selected public-safe application previews will be added as the portfolio documentation evolves.

---

## Development Status

**Active Development**

CRUUZ is an evolving engineering project. The public repository currently documents the system and its development progress; it is not a claim that every described capability is production-ready.

The project continues through implementation, integration, testing, debugging, and architectural refinement.

---

## Engineering Contribution

**Max Collins Botchway**  
Software Engineer / Full-Stack Developer

Work on CRUUZ spans frontend interfaces, backend services, database-driven workflows, authentication and authorization, real-time functionality, mobile development, workplace interfaces, debugging, testing, and application integration.

Core technologies:

`TypeScript` · `React` · `Next.js` · `React Native` · `Node.js` · `Express.js` · `PostgreSQL` · `Prisma` · `REST APIs` · `Socket.IO`

LinkedIn: https://www.linkedin.com/in/maxcb  
GitHub: https://github.com/maxbotchway
