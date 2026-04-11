# Timeline Roadmap (Days & Weeks) — Common Foundation

## Realistic Day-by-Day Recovery Plan

> **Working Day**: 9 hours max (with breaks, real coding, reading, and thinking time)
> **Who**: A 5.6-year Java/Spring Boot developer recovering after 6-month gap
> **Reality**: Coding tasks take 2-3x longer than you think when you're rusty. This plan accounts for that.
> **Rule**: One working day = 9 productive hours. One week = 6 working days (1 day rest).

---

## Master Timeline at a Glance

| Phase | Focus | Min | Max |
|---|---|---|---|
| **Phase 1** | Resume & LinkedIn | 1 day | 1 day |
| **Phase 2** | Environment Setup & Warm-up | 1 day | 2 days |
| **Phase 3** | Core Java Revival | 5 days | 8 days |
| **Phase 4** | Spring Boot & Framework Revival | 5 days | 8 days |
| **Phase 5** | Database & SQL Revival | 3 days | 5 days |
| **Phase 6** | VFIT Project Revision | 2 days | 3 days |
| **Phase 7** | VFDE Project Revision | 3 days | 5 days |
| **Phase 8** | Kafka & Messaging Revival | 3 days | 4 days |
| **Phase 9** | DevOps & CI/CD Revival | 1 day | 2 days |
| **Phase 10** | DSA Warm-up | 6 days | 10 days |
| **Phase 11** | System Design Basics | 4 days | 6 days |
| **Phase 12** | New Tech (AI/GenAI/Cloud) | 3 days | 5 days |
| **Phase 13** | Mock Interviews & Practice | Ongoing (parallel) | Ongoing |
| **Phase 14** | Job Applications | Ongoing (parallel) | Ongoing |
| | **TOTAL** | **~5.5 weeks** | **~8.5 weeks** |

---

## Phase 1: Resume & LinkedIn (Day 1)

| # | Task | Time in Day | Done? |
|---|---|---|---|
| 1.1 | Read `01_Resume_Analysis_and_Improvements.md` — understand all weak points | Half day (morning) | ☐ |
| 1.2 | Read `02_Strong_Resume_Points_Bank.md` — select your best 12-15 bullets | | ☐ |
| 1.3 | Open your target tier DOCX — personalize all details, verify dates, add metrics | | ☐ |
| 1.4 | Run through ATS checker (resumeworded.com) — iterate until 80%+ score | Half day (afternoon) | ☐ |
| 1.5 | Update LinkedIn profile — headline, summary, experience to match resume keywords | | ☐ |
| 1.6 | Export final PDFs, save with proper naming | | ☐ |
| | **Total: 1 day** | | |

---

## Phase 2: Environment Setup & Warm-up (1-2 days)

| # | Task | Day | Done? |
|---|---|---|---|
| 2.1 | Verify Java 17, IntelliJ/Cursor, Maven, Git, Docker installed and working | Day 1 (morning) | ☐ |
| 2.2 | Create a Spring Boot app from start.spring.io — add web, JPA, H2 | Day 1 (morning) | ☐ |
| 2.3 | Write a simple GET /hello REST API — test with Postman/curl | Day 1 (midday) | ☐ |
| 2.4 | Add a JPA entity (User), repository, and a POST endpoint — test CRUD | Day 1 (afternoon) | ☐ |
| 2.5 | Write a JUnit test for your controller and service layer | Day 1 (afternoon) | ☐ |
| 2.6 | Initialize a Git repo, make 3 meaningful commits, push to GitHub | Day 1 (evening) | ☐ |
| 2.7 | Write a Dockerfile for the app, run `docker-compose up` (app + MySQL) | Day 2 (morning) | ☐ |
| 2.8 | **Checkpoint**: You've written and deployed code for the first time in 6 months | Day 2 | ☐ |

---

## Phase 3: Core Java Revival (5-8 days)

> Each topic gets a FULL half-day or full day because you need to actually code, debug, and internalize — not just read.

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 3.1 | **OOP Fundamentals** | Write class hierarchy (abstract class, interface, inheritance, polymorphism). Create 2-3 real examples. Understand `this`, `super`, method overriding vs overloading. | 1 day | 1 day | ☐ |
| 3.2 | **Collections (Part 1)** | HashMap (put, get, iterate, internal working), ArrayList (add, remove, iterate, grow), LinkedList (insert, delete, traverse). Write code for each — not just read, actually code and debug. | 1 day | 1.5 days | ☐ |
| 3.3 | **Collections (Part 2)** | TreeMap, PriorityQueue, HashSet, LinkedHashMap, ConcurrentHashMap. When to use which. Comparable vs Comparator. Collections.sort with custom comparator. | Half day | 1 day | ☐ |
| 3.4 | **Streams & Lambdas** | Lambda syntax, functional interfaces (Predicate, Function, Consumer, Supplier). Stream operations: filter, map, flatMap, reduce, collect, groupingBy, partitioningBy. Solve 8-10 practice problems. | 1 day | 1.5 days | ☐ |
| 3.5 | **Optional & Exception Handling** | Optional: of, ofNullable, map, flatMap, orElse, orElseThrow. Custom exceptions, try-with-resources, multi-catch. Write a service that uses Optional properly. | Half day | 1 day | ☐ |
| 3.6 | **Generics** | Generic class, generic method, bounded types, wildcards (? extends, ? super). Write a generic utility class. | Half day | Half day | ☐ |
| 3.7 | **Concurrency** | Thread creation (Runnable, Callable), ExecutorService (Fixed, Cached, Scheduled), CompletableFuture (thenApply, thenCompose, allOf). synchronized, volatile, Atomic classes. Write 3-4 concurrent programs. | 1 day | 1.5 days | ☐ |
| 3.8 | **Java 17 Features** | Records, sealed classes, pattern matching for instanceof, switch expressions, text blocks. Refactor old code to use new features. | Half day | 1 day | ☐ |
| 3.9 | **String Manipulation** | String methods, StringBuilder, regex basics. Solve 5 string problems (reverse, palindrome, anagram, substring search, character frequency). | Half day | 1 day | ☐ |

---

## Phase 4: Spring Boot & Framework Revival (5-8 days)

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 4.1 | **Spring Core (DI/IoC)** | @Component, @Service, @Repository, @Configuration, @Bean. Constructor injection vs field injection. Bean scopes (singleton, prototype). Write a project demonstrating all. | 1 day | 1 day | ☐ |
| 4.2 | **Spring REST & Validation** | Build full CRUD REST API. @RestController, @GetMapping, @PostMapping, @PathVariable, @RequestBody. Add @Valid, @NotNull, @Size, @Email. Custom error response with @ControllerAdvice, @ExceptionHandler. | 1 day | 1.5 days | ☐ |
| 4.3 | **Spring Data JPA** | Entity mapping (@Entity, @Table, @Column, @Id, @GeneratedValue). Relationships (@OneToMany, @ManyToOne, @ManyToMany). JpaRepository custom queries (@Query, derived query methods). Pagination (Pageable). Fetch type (LAZY vs EAGER). N+1 problem and @EntityGraph fix. | 1 day | 2 days | ☐ |
| 4.4 | **@Transactional Deep Dive** | Write services with @Transactional. Test propagation (REQUIRED, REQUIRES_NEW). Test isolation levels. Rollback rules. Understand proxy mechanism. | Half day | 1 day | ☐ |
| 4.5 | **Spring Security** | Add Spring Security to your CRUD app. Configure SecurityFilterChain. Username/password auth. JWT token generation and validation. @PreAuthorize, role-based access. | 1 day | 1.5 days | ☐ |
| 4.6 | **Profiles & Configuration** | application.yml vs application-dev.yml. @Profile, @ConfigurationProperties. Externalized config. Spring Actuator (/health, /info, /metrics). | Half day | Half day | ☐ |
| 4.7 | **Testing (Spring Boot)** | @SpringBootTest, @WebMvcTest with MockMvc, @DataJpaTest. Mockito: @Mock, @InjectMocks, when/thenReturn, verify, ArgumentCaptor. Write 8-10 meaningful tests. | 1 day | 1.5 days | ☐ |

---

## Phase 5: Database & SQL Revival (3-5 days)

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 5.1 | **SQL Basics Revival** | SELECT, WHERE, ORDER BY, GROUP BY, HAVING, LIMIT, DISTINCT. JOINs: INNER, LEFT, RIGHT, FULL. Solve 10 basic queries on a practice DB. | 1 day | 1 day | ☐ |
| 5.2 | **SQL Intermediate** | Subqueries (IN, EXISTS, correlated). CTEs (WITH clause). Window functions (ROW_NUMBER, RANK, LAG, LEAD). Self-JOIN. Solve 10 medium queries. | 1 day | 1.5 days | ☐ |
| 5.3 | **Indexing & Optimization** | B-tree indexes, composite indexes. EXPLAIN ANALYZE. Slow query identification. Index vs full table scan. Practice query tuning on 3 slow queries. | Half day | 1 day | ☐ |
| 5.4 | **Transactions & Liquibase** | ACID properties. Isolation levels (Read Uncommitted → Serializable). Locking (row vs table, pessimistic vs optimistic). Write Liquibase changesets: create table, add column, add index, rollback. | Half day | 1 day | ☐ |
| 5.5 | **Review VFIT/VFDE DB Notes** | Read VFIT_04, VFIT_06, VFDE_06, VFDE_12. Understand schema: mt_user, mt_group, mt_account, mt_sub, ext_*_atr. | Half day | Half day | ☐ |

---

## Phase 6: VFIT Project Revision (2-3 days)

| # | Task | Day | Done? |
|---|---|---|---|
| 6.1 | Read VFIT_01 (tech stack) + VFIT_02 (REST APIs) + VFIT_03 (detailed flows) | Day 1 (morning, ~3 hrs) | ☐ |
| 6.2 | Read VFIT_06 (core tables) + VFIT_11 (Liquibase guide) | Day 1 (midday, ~2 hrs) | ☐ |
| 6.3 | Read VFIT_13 (migration workflow) + VFIT_14 (reindexing) + VFIT_REINDEX_01 | Day 1 (afternoon, ~3 hrs) | ☐ |
| 6.4 | Work through PROJECT_REVISE_01_VFIT: Phases 3-6 (REST APIs, services, integrations, security) | Day 2 (full day) | ☐ |
| 6.5 | Practice explaining VFIT architecture aloud (draw diagram, 2-min summary, 2 challenge stories) | Day 3 (half day) | ☐ |

---

## Phase 7: VFDE Project Revision (3-5 days) — MOST CRITICAL

| # | Task | Day | Done? |
|---|---|---|---|
| 7.1 | Read VFDE_01 (tech stack) + VFDE_02 (architecture, ~35 pages — take your time) | Day 1 (full day) | ☐ |
| 7.2 | Read VFDE_03 (process flows, ~40 pages) + VFDE_04 (Kafka, ~25 pages) | Day 2 (full day) | ☐ |
| 7.3 | Read VFDE_05 (REST/OIDC/FIDO2) + VFDE_08 (integration index) + VFDE_08a-08d (top 4 integrations) | Day 3 (full day) | ☐ |
| 7.4 | Work through PROJECT_REVISE_02_VFDE: Phases 3-7 (auth protocols, Kafka, process flows, integrations) | Day 4 (full day) | ☐ |
| 7.5 | Practice interview readiness: Draw architecture, explain Kafka flow (3 min), explain Add Contract flow, 3 STAR challenge stories | Day 5 (full day) | ☐ |

---

## Phase 8: Kafka & Messaging Revival (3-4 days)

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 8.1 | **Kafka Fundamentals** | Topic, Partition, Consumer Group, Offset, Broker, Replication. Read documentation + draw diagrams. | 1 day | 1 day | ☐ |
| 8.2 | **Hands-on: Local Kafka** | Set up Kafka via Docker (3 brokers + Zookeeper). Create topic, produce messages from CLI, consume from CLI. Use kafka-console-producer/consumer. | Half day | 1 day | ☐ |
| 8.3 | **Spring Kafka Implementation** | Write a Spring Boot producer (KafkaTemplate) and consumer (@KafkaListener). Configure consumer group, error handler, retry. Produce JSON objects, consume and save to DB. | 1 day | 1.5 days | ☐ |
| 8.4 | **VFDE Kafka Review** | Re-read VFDE_04. Map the 5 Solstice topics to your understanding. Practice explaining the dual-purpose architecture. Understand DB-level locking (SolsticeProcessingAccountLockDao). | Half day | Half day | ☐ |

---

## Phase 9: DevOps & CI/CD Revival (1-2 days)

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 9.1 | **Docker** | Write multi-stage Dockerfile. Understand layers, caching. Write docker-compose.yml for app + MySQL + Kafka. Build and run. | Half day | 1 day | ☐ |
| 9.2 | **Git Advanced** | Practice: branch, merge, rebase, cherry-pick, stash, revert, reset. Resolve a merge conflict. Understand GitFlow vs trunk-based. | Half day | Half day | ☐ |
| 9.3 | **Maven & Jenkins** | Multi-module Maven project structure. Profiles. Review Jenkinsfile pipeline stages (build, test, SonarQube, deploy). | Half day | Half day | ☐ |

---

## Phase 10: DSA Warm-up (6-10 days)

> **Reality**: Each problem takes 30-60 min (understand, code, debug, understand solution). Budget 5-6 problems per day max.

| # | Topic | Problems to Solve | Min | Max | Done? |
|---|---|---|---|---|---|
| 10.1 | **Arrays** | Two Sum, Best Time to Buy/Sell Stock, Contains Duplicate, Max Subarray, Product of Array Except Self | 1 day | 1.5 days | ☐ |
| 10.2 | **Strings** | Valid Palindrome, Longest Common Prefix, Anagram Check, Reverse String, Longest Substring Without Repeating Chars | 1 day | 1.5 days | ☐ |
| 10.3 | **HashMap/Set** | Two Sum (hash), Group Anagrams, Frequency Count, Contains Duplicate II, Intersection of Two Arrays | Half day | 1 day | ☐ |
| 10.4 | **Linked List** | Reverse LL, Detect Cycle, Merge Two Sorted, Remove Nth from End, Middle of LL | 1 day | 1.5 days | ☐ |
| 10.5 | **Stack/Queue** | Valid Parentheses, Min Stack, Implement Queue using Stacks, Next Greater Element | Half day | 1 day | ☐ |
| 10.6 | **Binary Search** | Basic BS, Search Insert Position, Search Rotated Array, First/Last Position | Half day | 1 day | ☐ |
| 10.7 | **Trees** | Max Depth, Inorder Traversal, Symmetric Tree, Level Order Traversal, Validate BST | 1 day | 1.5 days | ☐ |
| 10.8 | **Sorting** | Implement Merge Sort, Quick Sort. Understand their time complexity. Sort problems. | Half day | 1 day | ☐ |
| 10.9 | **Sliding Window + Two Pointers** | Max Subarray Sum (window), Container With Most Water, 3Sum | Half day | 1 day | ☐ |

---

## Phase 11: System Design Basics (4-6 days)

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 11.1 | **Building Blocks** | Load Balancer, Caching (Redis, CDN), Database (SQL vs NoSQL, sharding, replication), Message Queue, Rate Limiter, API Gateway. Study each with examples. | 1 day | 2 days | ☐ |
| 11.2 | **CAP Theorem & Trade-offs** | CAP, eventual consistency, ACID vs BASE. Consistent hashing. Study + write notes. | Half day | 1 day | ☐ |
| 11.3 | **Design Practice (Classic)** | Design URL Shortener. Design Notification System. Step by step: requirements → estimation → high-level → deep dive → bottlenecks. | 1 day | 1.5 days | ☐ |
| 11.4 | **Design Your Own Project** | Design ULM Identity Platform at scale. Use your VFDE knowledge. Draw architecture, explain Kafka sync, auth flows, integration hub. | 1 day | 1 day | ☐ |
| 11.5 | **Microservices Patterns** | API Gateway, Circuit Breaker, Saga, CQRS, Event Sourcing, Outbox Pattern, 12-Factor App. Conceptual review + relate to VFDE. | Half day | 1 day | ☐ |

---

## Phase 12: New Tech Introduction (3-5 days)

| # | Topic | Tasks Included | Min | Max | Done? |
|---|---|---|---|---|---|
| 12.1 | **AI/GenAI Concepts** | What are LLMs, tokens, temperature, context window, prompt engineering. Use ChatGPT/Cursor effectively. Understand hallucinations, guardrails. | 1 day | 1 day | ☐ |
| 12.2 | **Spring AI Basics** | Chat Client, streaming responses, function calling. Build a simple chatbot with Spring AI. RAG concept (embeddings, vector store, chunking). | 1 day | 2 days | ☐ |
| 12.3 | **Cloud Fundamentals** | AWS: EC2, S3, RDS, SQS/SNS, Lambda — conceptual understanding. Kubernetes: Pod, Deployment, Service, Ingress — conceptual. | 1 day | 2 days | ☐ |

---

## Phase 13: Mock Interviews (Ongoing — Start from Week 3)

| # | Activity | Frequency | Time per Session | Done? |
|---|---|---|---|---|
| 13.1 | Coding challenge: 3 LeetCode Easy/Medium problems | Daily | ~3 hours (after Phase 10) | ☐ |
| 13.2 | Project walkthrough: Explain VFDE to mirror/friend | 2x per week | ~1 hour | ☐ |
| 13.3 | System design mock: 1 problem | 1x per week (after Phase 11) | ~2 hours | ☐ |
| 13.4 | Behavioral prep: Practice STAR stories | 1x per week | ~1 hour | ☐ |
| 13.5 | Spring Boot conceptual quiz (online) | 2x per week | ~1 hour | ☐ |
| 13.6 | SQL challenge: 5 medium queries | 1x per week | ~2 hours | ☐ |

---

## Phase 14: Job Applications (Parallel — Start from Week 2)

| # | Task | When | Time | Done? |
|---|---|---|---|---|
| 14.1 | Apply to 5-10 Tier-3 companies (safety net) | After Phase 3 complete | 1 day | ☐ |
| 14.2 | Apply to 5-10 Tier-2 companies (sweet spot) | After Phase 7 complete | 1 day | ☐ |
| 14.3 | Apply to 3-5 Tier-1 companies (stretch goal) | After Phase 10 complete | Half day | ☐ |
| 14.4 | Track in spreadsheet + follow up weekly | Ongoing | 30 min/day | ☐ |

---

## Week-by-Week Calendar View

| Week | Days | What You're Doing | Key Milestone |
|---|---|---|---|
| **Week 1** | Day 1-6 | Phase 1 (Resume) + Phase 2 (Setup) + Phase 3 start (Java OOP, Collections) | First code in 6 months written |
| **Week 2** | Day 7-12 | Phase 3 finish (Streams, Concurrency, Java 17) + Phase 4 start (Spring DI, REST) | Java confidence back. Start applying Tier 3. |
| **Week 3** | Day 13-18 | Phase 4 finish (JPA, Security, Testing) + Phase 5 (SQL) | Spring Boot fluency back |
| **Week 4** | Day 19-24 | Phase 6 (VFIT) + Phase 7 (VFDE) | Both projects fresh in memory |
| **Week 5** | Day 25-30 | Phase 8 (Kafka) + Phase 9 (DevOps) + Phase 10 start (DSA: Arrays, Strings, HashMap) | Kafka hands-on done. Start applying Tier 2. |
| **Week 6** | Day 31-36 | Phase 10 continue (LL, Stack, Trees, Sorting, Sliding Window) | DSA muscle memory returning |
| **Week 7** | Day 37-42 | Phase 11 (System Design) + Phase 12 start (AI/GenAI) | System design basics covered |
| **Week 8** | Day 43-48 | Phase 12 finish (Cloud) + Phase 13 intensive (Mocks) | Foundation COMPLETE. Interview-ready. |

---

## Daily 9-Hour Schedule Template

| Time | Activity | Hours |
|---|---|---|
| 9:00 - 12:00 | Core skill revision (current Phase) | 3 hrs |
| 12:00 - 12:30 | Break | - |
| 12:30 - 14:00 | DSA practice (from Phase 10 onwards, else more core skill) | 1.5 hrs |
| 14:00 - 14:30 | Lunch break | - |
| 14:30 - 17:00 | Project revision / Notes reading (Phase 6-7) or Hands-on coding | 2.5 hrs |
| 17:00 - 17:15 | Break | - |
| 17:15 - 19:00 | New tech / System Design / Mock prep | 1.75 hrs |
| 19:00 - 19:15 | Daily review: What I learned, what's pending | 0.25 hrs |
| | **Total** | **9 hours** |

---
