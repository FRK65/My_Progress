# First_Name Last_Name

+91 987654321 | myemail@gmail.com | [linkedin.com/in/myprofile](https://linkedin.com/in/myprofile) | [github.com/myprofile](https://github.com/myprofile) | City, India

---

## PROFESSIONAL SUMMARY

Backend Engineer with **5.6+ years** of experience designing and building **distributed, high-scale identity management systems** serving **50M+ users**. Deep expertise in **event-driven architecture (Kafka)**, **multi-protocol authentication (SAML, OIDC, FIDO2/WebAuthn)**, **concurrent systems**, and **large-scale data pipelines**. Experienced in integrating 19+ distributed service modules and designing database-level concurrency controls for real-time event processing. Strong foundation in **data structures, algorithms, and system design** (NIT Trichy, AIR 69 in national entrance exam).

---

## SKILLS

**Languages & Core**: Java 17, Multithreading, Concurrency, Design Patterns (Factory, Strategy, Builder, Observer), SOLID, OOP
**Frameworks**: Spring Boot, Spring Framework 6, Spring Security, Spring Kafka 3.3.5, Spring Data JPA, Spring Integration
**Distributed Systems**: Apache Kafka (Consumer Groups, Partitions, Event Sourcing), RabbitMQ, Hazelcast (Distributed Cache/Sessions), Event-Driven Architecture
**Identity & Security**: SAML 2.0 (Shibboleth 5.1.4), OIDC/OAuth2, FIDO2/WebAuthn (Passkeys), TOTP, AES Encryption, DEK Rotation (OCI Vault)
**APIs**: REST API Design, SOAP (Apache CXF), API Gateway (Apigee), SCIM Protocol
**Databases**: Oracle, MySQL, SQL Optimization, Indexing (B-tree, Composite), Liquibase (5,000+ Migration Scripts)
**Search**: Elasticsearch (Indexing, Bulk Operations, Reindexing Pipelines)
**DevOps**: Docker, Jenkins CI/CD, Maven (Multi-Module), Nginx, Git
**Testing**: JUnit 5, Mockito, MockServer, Integration Testing, Postman
**Cloud**: AWS Fundamentals, OCI Vault (Key Management)

---

## WORK EXPERIENCE

### Software Engineer — Company_XYZ, Pune
*Jan 2022 – Present*

**Vodafone Germany — Identity Provider Platform (50M+ Users, Java 17, Kafka, OIDC/FIDO2)**

- Architected and maintained a **large-scale identity platform** handling 27 distinct user lifecycle process flows (registration, multi-factor authentication, contract management, account delegation) for 50M+ Vodafone Germany subscribers.
- Designed **dual-purpose Kafka architecture**: 5 Solstice/FusionC consumer topics for real-time billing data synchronization (Customer, BillingAccount, Product, Party, Reconciliation) and system event producers for audit/analytics consumers.
- Implemented **database-level account locking** (`SolsticeProcessingAccountLockDao`) using Oracle row-level locks to prevent race conditions when concurrent Kafka messages arrive for the same billing account — ensuring data consistency without distributed locks.
- Built **6 authentication method support** in a single platform: Password, SMS OTP, Email OTP, TOTP (Authenticator App), FIDO2/WebAuthn (Passkeys), U2F — with fallback hierarchy and user choice.
- Designed and implemented **OIDC provider** with token issuance, token exchange, device secret flow, and introspection endpoints; configured **SAML 2.0 IdP** (Shibboleth 5.1.4) for federated SSO across service providers.
- Engineered **DEK (Data Encryption Key) rotation** system using OCI Vault with ShedLock for cluster-safe distributed key rotation across multiple Tomcat instances.
- Built integration layer connecting **19 third-party modules** (REST + SOAP + Kafka) using Spring Integration Gateway pattern with standardized error handling, retry, and timeout management.
- Implemented **runtime Kafka toggle controls** via database settings — enabling/disabling consumers and producers without redeployment, supporting zero-downtime operational changes.

**Vodafone Italy — Reindexing Microservice (Elasticsearch, Multi-Module Architecture)**

- Architected **multi-module microservice** (ms-api, ms-domain, ms-services, ms-gateway, ms-query, ms-resources, ms-exe) for bulk data migration from Oracle DB to Elasticsearch with batch processing and error recovery.
- Designed **Elasticsearch bulk indexing pipeline** processing millions of customer records with configurable batch size, retry logic, and validation.

---

### Associate Software Engineer — Company_XYZ, Pune
*Jan 2020 – Dec 2021*

**Vodafone Italy — ULM Identity Provider (Java 8, Spring, Oracle, SAML)**

- Contributed to identity platform managing user registration, activation, password recovery, and SAML-based SSO for Vodafone Italy subscribers.
- Integrated 5 external systems via **SOAP web services** (Apache CXF) — CRM lookup, legacy registration validation, migration list, session management, and ESB middleware.
- Authored **Liquibase migration scripts** and SQL stored procedures for large-scale data migration from legacy billing systems with validation and rollback capabilities.
- Optimized SQL queries on subscriber tables with millions of records, improving query performance through index analysis (EXPLAIN ANALYZE) and query rewriting.

*Promoted to Software Engineer based on delivery excellence and technical growth.*

---

## EDUCATION

**Master of Computer Applications (MCA)** — NIT Tiruchirappalli *(2017–2020)* | CGPA: 7.87/10
**Bachelor of Computer Science (BSc CS)** — DAVV Indore *(2014–2017)* | 69.78%

---

## ACHIEVEMENTS & CERTIFICATIONS

- Secured **AIR 69** in KIITEE-2017 (National MCA Entrance Exam — 50,000+ candidates).
- **Udacity Java Web Developer Nanodegree** — [Certificate](https://graduation.udacity.com/confirm/KRKPFPPL)
- **Design and Analysis of Algorithms** — NPTEL, IIT Madras (Elite Certificate)
- Certificate of Recognition for contribution to Vodafone Italy project.
- Awarded by Chief Minister of Madhya Pradesh for Academic Excellence.

---

<!--
TIER-1 OPTIMIZATION NOTES:
- Target: FAANG, Uber, Stripe, Atlassian, top startups (>$1B valuation)
- WHAT'S DIFFERENT FROM COMMON:
  1. Summary emphasizes DISTRIBUTED SYSTEMS, SCALE (50M users), CONCURRENCY
  2. Experience bullets focus on ARCHITECTURAL DECISIONS and WHY, not just WHAT
  3. Database-level locking explanation shows systems thinking (interviewer bait)
  4. Dual-purpose Kafka architecture shows end-to-end design capability
  5. DEK rotation + ShedLock shows distributed systems knowledge
  6. AIR 69 + NIT Trichy prominently placed (competitive aptitude matters for FAANG)
  7. GitHub link added (expected for Tier 1)
  8. Skills grouped to show DEPTH in distributed systems, concurrency, identity protocols
  9. Reindexing app framed as ARCHITECTURE decision, not just "built an app"
  10. No soft skills/team mentions — Tier 1 cares about TECHNICAL depth
- ATS keywords optimized for: distributed systems, event-driven, concurrent, scalable,
  Kafka consumer groups, OIDC, FIDO2, WebAuthn, system design
- Estimated ATS Score: 85-90% for senior Java backend roles at big tech
-->
