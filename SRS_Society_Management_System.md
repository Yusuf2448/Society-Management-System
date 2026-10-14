# Software Requirements Specification (SRS)
## Society Management System (SocietySRS)
Version: 1.0 (Baseline)
Date: 2026-10-14
Status: Approved Baseline

### 1. Introduction and Purpose
This SRS defines requirements for a Society Management System used to maintain resident records, maintenance billing, visitor access, complaints, and society notices.

### 2. Scope and Target Users
The system coordinates community operations for housing societies and gated communities.
Target user roles:
- Management Committee / Society Administrator
- Residents (Owners and Tenants)
- Security Gate Staff
- Society Accountant

### 3. Functional Requirements
- FR-01: Flat and Resident Directory Management
- FR-02: Society Maintenance Billing and Payment Tracking
- FR-03: Security Gate Visitor and Vehicle Log
- FR-04: Clubhouse and Community Facility Booking
- FR-05: Maintenance Helpdesk and Resident Ticketing
- FR-06: Digital Notice Board and Announcements
- FR-07: The system shall allow authenticated users to highlight selected text in SocietySRS/help content and retain those highlights for later review.

### 4. Non-Functional Requirements
- NFR-01 Performance: The system shall support up to 200 concurrent authenticated society residents under normal operating conditions; 95% of standard resident and maintenance queries shall respond within 2 seconds.
- NFR-02 Security: Role-based access control (RBAC) and encrypted resident credential storage.
- NFR-03 Availability: 99.5% operational availability for portal services.

### 5. Assumptions and Constraints
Maintenance assessments are derived from validated flat configurations, billings, and authorized adjustments. Alternative features are evaluated on separate SCM branches and do not change the approved baseline unless merged.
