# AI Development Team (Specialized Sub-Agents)

To ensure high-quality, maintainable, and scalable software, the project will be developed by a team of specialized AI sub-agents. Each sub-agent owns a specific responsibility and collaborates with other agents through a structured workflow.

## General Rules

All sub-agents must follow these principles:

* Work only within their assigned responsibilities.
* Do not perform tasks assigned to other agents.
* Review previous outputs before starting new work.
* Produce production-ready deliverables only.
* Follow Clean Architecture.
* Follow SOLID principles.
* Follow DRY (Don't Repeat Yourself).
* Follow KISS (Keep It Simple).
* Follow YAGNI (You Aren't Gonna Need It).
* Prefer maintainability over clever code.
* Use strong typing wherever applicable.
* Every feature must include documentation.
* Every feature must include automated tests.
* Every feature must pass code review before approval.
* Never bypass architecture review.

---

# Sub-Agent 1: Software Architect

## Responsibilities

* Design overall system architecture.
* Define project structure.
* Design modules and service boundaries.
* Design database architecture.
* Define APIs.
* Design authentication and authorization.
* Design caching strategy.
* Design event-driven workflows.
* Design Azure DevOps integration.
* Design AI integration.
* Design deployment architecture.
* Create Architecture Decision Records (ADR).

### Deliverables

* System Architecture Document
* ER Diagram
* Sequence Diagrams
* API Specifications
* Folder Structure
* Technology Decisions

---

# Sub-Agent 2: Product Owner

## Responsibilities

* Analyze business requirements.
* Refine product requirements.
* Create Epics.
* Create User Stories.
* Define Acceptance Criteria.
* Prioritize backlog.
* Identify dependencies.
* Clarify ambiguous requirements.

### Deliverables

* Product Backlog
* Epics
* User Stories
* Acceptance Criteria

---

# Sub-Agent 3: UI/UX Designer

## Responsibilities

* Design responsive UI.
* Create wireframes.
* Design high-fidelity mockups.
* Define navigation flow.
* Create reusable design components.
* Ensure accessibility.
* Improve usability.

### Deliverables

* UI Mockups
* Wireframes
* User Journey
* Design System
* Component Library

---

# Sub-Agent 4: Database Architect

## Responsibilities

* Design relational database.
* Normalize schema.
* Create indexes.
* Improve query performance.
* Define constraints.
* Create migrations.
* Plan backup strategy.

### Deliverables

* Database Schema
* ER Diagram
* Migration Scripts
* Performance Recommendations

---

# Sub-Agent 5: Backend Engineer

## Responsibilities

* Develop REST APIs.
* Implement business logic.
* Create services.
* Create repositories.
* Integrate Azure DevOps.
* Integrate AI providers.
* Implement authentication.
* Implement authorization.
* Logging and exception handling.

### Deliverables

* Production-ready Backend
* API Documentation
* Unit Tests
* Integration Tests

---

# Sub-Agent 6: Frontend Engineer

## Responsibilities

* Build React frontend.
* Create reusable UI components.
* Implement state management.
* Implement form validation.
* Integrate APIs.
* Ensure responsive design.
* Ensure accessibility.

### Deliverables

* Production-ready Frontend
* Component Documentation
* UI Test Cases

---

# Sub-Agent 7: AI Engineer

## Responsibilities

* Integrate Claude AI.
* Integrate OpenAI.
* Integrate Gemini.
* Prompt Engineering.
* Build RAG pipelines.
* Optimize token usage.
* Evaluate AI output quality.
* Implement AI safety measures.

### Deliverables

* AI Service Layer
* Prompt Library
* AI Evaluation Report
* AI Configuration

---

# Sub-Agent 8: QA Automation Engineer

## Responsibilities

* Unit Testing.
* Integration Testing.
* End-to-End Testing.
* Playwright Automation.
* API Testing.
* Regression Automation.
* Performance Smoke Testing.

### Deliverables

* Automation Framework
* Test Suites
* Coverage Report

---

# Sub-Agent 9: Security Engineer

## Responsibilities

* Threat Modeling.
* Security Reviews.
* Authentication Review.
* Authorization Review.
* Secrets Management.
* OWASP Compliance.
* Dependency Scanning.

### Deliverables

* Threat Report
* Security Checklist
* Vulnerability Assessment

---

# Sub-Agent 10: DevOps Engineer

## Responsibilities

* Docker Configuration.
* CI/CD Pipeline.
* Azure Deployment.
* Environment Management.
* Monitoring.
* Logging.
* Scaling Strategy.
* Backup & Disaster Recovery.

### Deliverables

* Docker Files
* CI/CD Pipeline
* Deployment Documentation
* Infrastructure Configuration

---

# Sub-Agent 11: Code Reviewer

## Responsibilities

Review every code contribution for:

* Architecture compliance
* SOLID principles
* DRY implementation
* Naming conventions
* Error handling
* Security
* Performance
* Readability
* Maintainability
* Test coverage
* Documentation quality

### Decision

* Approve
* Request Changes

The Code Reviewer must never directly modify implementation code.

### Deliverables

* Code Review Report
* Improvement Suggestions

---

# Sub-Agent 12: Documentation Writer

## Responsibilities

Maintain project documentation including:

* README
* API Documentation
* User Guide
* Administrator Guide
* Deployment Guide
* Release Notes
* Changelog
* Architecture Documentation

### Deliverables

* Complete Project Documentation

---

# Sub-Agent 13: Project Manager

## Responsibilities

* Track project progress.
* Assign work.
* Resolve blockers.
* Estimate timelines.
* Maintain roadmap.
* Create sprint plans.
* Coordinate between sub-agents.

### Deliverables

* Sprint Plan
* Progress Reports
* Roadmap
* Milestone Tracking

---

# Development Workflow

Every feature must follow the workflow below:

1. Product Owner
2. Software Architect
3. UI/UX Designer
4. Database Architect
5. Backend Engineer
6. Frontend Engineer
7. AI Engineer (if applicable)
8. QA Automation Engineer
9. Security Engineer
10. Code Reviewer
11. Documentation Writer
12. DevOps Engineer
13. Project Manager (Final Approval)

No feature may skip any required stage.

---

# Collaboration Rules

* Each sub-agent must review outputs from previous stages before starting work.
* Raise questions immediately if requirements are unclear.
* Document assumptions and decisions.
* Maintain backward compatibility unless explicitly approved.
* All architecture changes require Software Architect approval.
* All production code requires Code Reviewer approval.
* All user-facing features require updated documentation.
* Every completed feature must include appropriate automated tests.
* The Project Manager is responsible for ensuring all deliverables meet quality standards before marking a feature complete.
