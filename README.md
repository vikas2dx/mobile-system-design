# Mobile System Design

A collection of mobile system design case studies focused on building
scalable, reliable, performant, and offline-capable mobile applications.

The goal is to understand system design from both perspectives:

- Mobile application architecture
- Backend and distributed-system architecture

---

## Case Studies

| #   | System                                          | Key Concepts                                 | Status        |
| --- | ----------------------------------------------- | -------------------------------------------- | ------------- |
| 01  | [Expense Sharing](./01-expense-sharing)         | Offline-first, sync, conflicts, transactions | 🚧 In Progress |
| 02  | [Food Delivery](./02-food-delivery)             | Location, orders, real-time updates          | ⏳ Planned     |
| 03  | [Instagram Feed](./03-instagram-feed)           | Feed, pagination, caching, scalability       | ⏳ Planned     |
| 04  | [Chat Application](./04-chat-application)       | WebSockets, messaging, offline sync          | ⏳ Planned     |
| 05  | [Notification System](./05-notification-system) | Push notifications, queues, retries          | ⏳ Planned     |
| 06  | [Video Streaming](./06-video-streaming)         | CDN, adaptive streaming, caching             | ⏳ Planned     |
| 07  | [Payment App](./07-payment-app)                 | Security, idempotency, transactions          | ⏳ Planned     |

---

## Design Framework

Each case study follows a consistent system-design framework.

### 1. Requirements

- Problem Statement
- Functional Requirements
- Non-Functional Requirements
- Assumptions & Constraints

### 2. Architecture

- High-Level Architecture
- Mobile Architecture
- Backend Architecture
- Data Flow

### 3. API & Data

- API Design
- Data Model
- Database
- Pagination

### 4. Mobile Engineering

- Local Storage
- Caching
- Offline Strategy
- Synchronization
- Conflict Resolution
- Error Handling
- Retry Strategy

### 5. Scalability & Reliability

- Scalability
- Failure Scenarios
- Fault Tolerance
- Performance

### 6. Security & Observability

- Authentication
- Authorization
- Data Protection
- Logging
- Metrics
- Monitoring
- Alerting

### 7. Design Decisions

- Trade-offs
- Alternatives Considered
- Bottlenecks
- Future Improvements

### 8. Interview Deep Dive

- Common Interview Questions
- Architecture Discussion
- Scaling Questions
- Failure Scenarios
- Mobile-Specific Questions

---

## Goals

- Practice mobile system design for senior-level interviews
- Prepare for SDE-2, SDE-3, and Mobile Lead interviews
- Understand mobile and backend architecture together
- Develop strong offline-first architecture skills
- Understand synchronization and conflict resolution
- Practice scalability and distributed-system concepts
- Document architectural trade-offs
- Build reusable system-design knowledge

---

## Focus Areas

### Mobile

- Flutter
- Android
- Local persistence
- Offline-first architecture
- Caching
- Synchronization
- Background processing
- Network reliability
- Performance

### Backend

- REST APIs
- Databases
- Caching
- Message queues
- Distributed systems
- Scalability
- Consistency
- Idempotency
- Fault tolerance

### System Design

- High-level architecture
- Data modeling
- API design
- Scalability
- Reliability
- Security
- Observability
- Trade-offs

---

## Learning Approach

Each system is designed from requirements to implementation-level
architecture.

```text
Requirements
     ↓
Architecture
     ↓
API Design
     ↓
Data Model
     ↓
Mobile Architecture
     ↓
Offline Strategy
     ↓
Synchronization
     ↓
Scalability
     ↓
Failure Scenarios
     ↓
Trade-offs
     ↓
Interview Discussion