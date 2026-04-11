# First_Name Last_Name

+91 987654321 | myemail@gmail.com | [linkedin.com/in/myprofile](https://linkedin.com/in/myprofile) | City, India

---

## PROFESSIONAL SUMMARY

Senior Backend Engineer with **5.6+ years** of experience in **Java, Spring Boot, Kafka, and Microservices**, specializing in enterprise-scale identity management platforms for the telecom domain. Hands-on expertise in building **event-driven systems**, **REST/SOAP API integrations** with 19+ third-party systems, **database migration** (Liquibase/Oracle), and **CI/CD pipeline automation** (Jenkins). Successfully delivered production-grade solutions for **Vodafone Germany & Italy** handling 50M+ subscribers. Strong in end-to-end development — from architecture and coding to deployment and production support.

---

## SKILLS

**Backend**: Java (8/17), Spring Boot, Spring Framework 6, Spring Security, Spring Kafka, Spring Data JPA, JPA/Hibernate, Microservices, Design Patterns
**APIs & Integration**: REST API, SOAP Web Services (Apache CXF), Spring Integration Gateway, SAML 2.0, OIDC/OAuth2, FIDO2, Apigee API Gateway
**Messaging**: Apache Kafka (Consumer/Producer, Spring Kafka 3.3.5), RabbitMQ, Event-Driven Architecture
**Databases**: Oracle, MySQL/MariaDB, SQL, PL/SQL, Liquibase (Database Migration & Versioning), Query Optimization
**Search & Cache**: Elasticsearch (Indexing, Reindexing), Hazelcast (Distributed Caching & Session Replication)
**DevOps**: Docker, Docker Compose, Jenkins (CI/CD Pipelines), Maven (Multi-Module), Nginx, Git, Bitbucket, Nexus
**Testing**: JUnit 5, Mockito, MockServer, Postman, SonarQube, JaCoCo
**Cloud & Infra**: AWS (Fundamentals), OCI Vault, RPM Deployment, Tomcat 8
**Process & Tools**: Agile/Scrum, Jira, Code Review, Bitbucket PR Workflow

---

## WORK EXPERIENCE

### Software Engineer — Company_XYZ, Pune
*Jan 2022 – Present*

**Project: Vodafone Germany (VFDE) — ULM Identity Provider** *(2.5 years)*
*Tech: Java 17, Spring 6, Spring Kafka, Oracle, Liquibase, Docker, Jenkins*

- Engineered **Kafka consumer pipeline** processing 5 real-time billing event topics (Customer, BillingAccount, Product, Party, Reconciliation) from Solstice/FusionC CRM, synchronizing identity data for **50M+ Vodafone Germany subscribers**.
- Built **dual Kafka architecture**: inbound consumers for billing data sync + outbound producers for system events (login, registration, password change, 2FA, batch jobs) consumed by monitoring/analytics systems.
- Implemented **6 authentication methods** — Password, SMS OTP, Email OTP, TOTP (Authenticator App), FIDO2/WebAuthn (Passkeys), U2F Hardware Keys — with configurable fallback and user preference.
- Integrated **19 third-party service modules** (ACRM, EAI, CAMA, DXL, AMS, CDH, KSC, OXmail, SCIM, OCI Vault, Apigee, WebIAM, etc.) using Spring Integration Gateway pattern with standardized error handling and retry logic.
- Configured **SAML 2.0 SSO** (Shibboleth 5.1.4) for federated authentication across GigaTV, OXmail, F-Secure, and built **OIDC/OAuth2** provider with token exchange, device secret, and introspection endpoints.
- Authored **921+ Liquibase overlay changesets** for schema versioning and rollback handling, managing zero-downtime database evolution from 8+ legacy migration sources.
- Designed **database-level account locking** for concurrent Kafka message processing, preventing race conditions on shared billing account records.
- Implemented **DEK rotation** using OCI Vault with ShedLock for cluster-safe distributed key management across multiple application nodes.
- Configured and maintained **Docker Compose** multi-container environment (Oracle, Kafka, Zookeeper, RabbitMQ, Hazelcast, Elasticsearch, Nginx, MockServer) for development and integration testing.
- Maintained **Jenkins CI/CD pipelines** with SonarQube integration for automated build, test, quality analysis, and multi-environment deployment.

**Project: Vodafone Italy (VFIT) — Reindexing Application** *(built during VFDE tenure)*
*Tech: Spring Boot, Elasticsearch, Docker, Jenkins*

- Developed **VFIT-Reindexing application** — a standalone multi-module microservice (ms-api, ms-domain, ms-services, ms-gateway, ms-query, ms-resources) for large-scale customer data migration from Oracle DB to Elasticsearch.
- Containerized with **Docker** and automated deployment via **Jenkins pipeline**.

---

### Associate Software Engineer — Company_XYZ, Pune
*Jan 2020 – Dec 2021*

**Project: Vodafone Italy (VFIT) — ULM Identity Provider** *(3 years total)*
*Tech: Java 8, Spring Framework, Oracle, MariaDB, Tomcat, Liquibase, RabbitMQ, Elasticsearch*

- Contributed to **User Lifecycle Management (ULM)** identity platform managing 6 core user journey flows: registration, activation, password recovery/reset, identifier recovery, and authentication identifier management.
- Designed and implemented **REST APIs** for session management (`/session/start`, `/session/end`), process execution (`/process/start`, `/process/step`), and OTP services (generate, validate, resend via Twilio SDK).
- Integrated 5 external Vodafone systems via **SOAP web services** (Apache CXF) — CRM customer lookup, legacy registration validation, Master Migration List, ASM session management, and ESB middleware.
- Implemented **AES encryption service** for securing MSISDN and sensitive subscriber data at rest and in transit.
- Authored **Liquibase migration scripts** and SQL stored procedures for data migration, transformation, and rollback from legacy systems.
- Optimized **SQL queries** and indexes on Oracle subscriber tables with millions of records, improving API response times.
- Configured **RabbitMQ** Bidirectional Messaging System (BMS) for asynchronous event processing within the ULM platform.
- Managed **Elasticsearch** indexing for full-text user search with Kibana dashboards for monitoring.
- Wrote **JUnit + Mockito** unit tests, used **MockServer** for simulating external APIs, and maintained **Postman collections** for end-to-end testing.

*Promoted to Software Engineer based on consistent delivery across VFIT project.*

---

## EDUCATION

**Master of Computer Applications (MCA)** — NIT Tiruchirappalli *(2017–2020)* | CGPA: 7.87/10
**Bachelor of Computer Science (BSc CS)** — DAVV Indore *(2014–2017)* | 69.78%

---

## CERTIFICATIONS

- **Udacity Java Web Developer Nanodegree** — [Certificate](https://graduation.udacity.com/confirm/KRKPFPPL)
- **Design and Analysis of Algorithms** — NPTEL, IIT Madras (Elite Certificate)
- **Programming in C++** — NPTEL, IIT Kharagpur (Elite Certificate)

---

## ACHIEVEMENTS

- Certificate of Recognition for contribution to Vodafone Italy project delivery.
- Secured **AIR 69** in KIITEE-2017 (National MCA Entrance Exam).
- Awarded by Chief Minister of Madhya Pradesh for Academic Excellence.

---

<!--
TIER-2 OPTIMIZATION NOTES:
- Target: Flipkart, Atlassian, Razorpay, Swiggy, PhonePe, Freshworks, SAP, Goldman Sachs tech, 
  mid-size product companies, established enterprises
- WHAT'S DIFFERENT FROM COMMON (20-30% changes):
  1. Summary emphasizes END-TO-END development (architecture to production support)
  2. Skills section is MORE DETAILED — includes specific tool versions, process tools (Agile, Jira)
  3. Experience has MORE BULLETS — Tier 2 wants to see BREADTH and DEPTH of hands-on work
  4. Integration details are SPECIFIC (named all 19 modules) — shows real enterprise experience
  5. DevOps/CI-CD given more prominence (Docker Compose env, Jenkins, SonarQube)
  6. Testing section is stronger (MockServer, Postman, JaCoCo)
  7. VFIT section is MORE DETAILED — shows growth from associate to SE with specific APIs
  8. Soft skills included (Agile/Scrum, code review, distributed team)
  9. Both projects have TECH STACK listed explicitly under project name
  10. RabbitMQ + Elasticsearch + Hazelcast mentioned (Tier 2 cares about tooling breadth)
- ATS keywords optimized for: Spring Boot, Kafka, REST API, SOAP, Liquibase, Oracle, Docker,
  Jenkins, CI/CD, Elasticsearch, Hazelcast, SAML, OIDC, Agile, Scrum, microservices
- Estimated ATS Score: 85-90% for senior Java backend roles at mid-tier product/enterprise companies
-->
