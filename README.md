<h1 align="center">Zakaria Dbaba</h1>

<p align="center">
  <strong>Backend Java / Cloud-Native Software Engineer</strong><br/>
  Java 21 • Spring Boot 3 • Kafka • Kubernetes • AWS
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/zakaria-dbaba/">LinkedIn</a> •
  <a href="https://zakariadbaba.netlify.app/">Portfolio</a> •
  <a href="mailto:zakaria-dbaba@hotmail.com">Email</a>
</p>

---

## About Me

Software Engineer with around **4 years of professional experience**, focused on backend development and cloud-native systems.

I work primarily with **Java and Spring Boot**, building APIs and distributed services with an emphasis on consistency, reliability, observability and production readiness. I am particularly interested in event-driven architectures, Kafka-based systems, container orchestration and the engineering decisions behind scalable backend platforms.

```text
Java / Spring Boot  →  Distributed Systems  →  Kafka  →  Kubernetes  →  Cloud
```

## Featured Project

### [EventFlow](https://github.com/zakaria-source/eventflow) — Event-Driven Order Processing Platform

A production-style Java backend built around the failure modes that appear in real distributed systems rather than around CRUD screens.

**Java 21 · Spring Boot 3 · Kafka · PostgreSQL · Flyway · Testcontainers · OpenTelemetry · Docker · Kubernetes**

What it demonstrates:

- **Transactional Outbox** for PostgreSQL/Kafka consistency
- Multi-replica outbox workers using **`FOR UPDATE SKIP LOCKED` + expiring claim leases**
- **At-least-once delivery** with atomic, concurrency-safe consumer idempotency
- Separate **publisher DLT** and **consumer poison-message DLT** with bounded retries
- W3C trace-context propagation across **HTTP → PostgreSQL Outbox → Kafka → Consumer**
- Micrometer / OpenTelemetry tracing, Prometheus metrics and Actuator health probes
- Flyway-managed schema evolution
- Real PostgreSQL + Kafka integration tests with **Testcontainers**
- Docker Compose, Kubernetes manifests and GitHub Actions CI
- Architecture Decision Records documenting the trade-offs

The test suite includes concurrent duplicate delivery, concurrent outbox claiming, lease recovery after simulated worker failure, end-to-end Kafka projection, trace-context persistence and poison-message recovery.

→ **[Explore EventFlow](https://github.com/zakaria-source/eventflow)**

### TrackMyJob — Job Application Dashboard

A supporting frontend project for tracking applications, response metrics, follow-ups and upcoming interviews.

**Angular 19 · TypeScript · RxJS · Angular Material · Chart.js**

→ **[Live demo](https://trackmyjob-zakaria.netlify.app/)**

> The source repository is currently private; the public demo is linked here intentionally.

## What I Build

- Backend services with **Java 17/21** and **Spring Boot 3**
- REST APIs and distributed service architectures
- Event-driven workflows with **Apache Kafka**
- Persistence layers with **PostgreSQL, SQL and Hibernate**
- Containerized workloads with **Docker and Kubernetes**
- Cloud-native delivery on **AWS**
- Automated CI/CD pipelines and infrastructure with **Terraform**
- Testable systems using **JUnit, TDD, integration tests and Testcontainers**

## Core Stack

| Area | Technologies |
|---|---|
| Backend | Java 17/21, Spring Boot 3, Spring Cloud, Hibernate |
| Architecture | REST, Microservices, Event-Driven Architecture, DDD, Hexagonal Architecture |
| Messaging & Data | Apache Kafka, PostgreSQL, SQL |
| Reliability | Transactional Outbox, Idempotency, Retry/DLT, Failure Recovery |
| Observability | Micrometer, OpenTelemetry, Prometheus, Actuator |
| Cloud & Platform | AWS, Docker, Kubernetes, Terraform |
| Delivery | Git, CI/CD, GitHub Actions, Jenkins |
| Quality | JUnit, TDD, Testcontainers, Integration Testing |

## Engineering Principles

I prefer systems where architectural decisions are explicit and explainable:

- **Consistency before convenience** when data crosses system boundaries
- **Idempotency by design** for at-least-once messaging
- **Clear boundaries** between domain logic and infrastructure
- **Bounded failure handling** instead of infinite retries
- **Automated tests** around critical behavior and integration boundaries
- **Observable services** that can be diagnosed in production
- **Simple designs first**, with complexity introduced only when the problem justifies it

## Current Focus

I am concentrating this GitHub around fewer, deeper projects that demonstrate real backend engineering decisions rather than collecting small tutorial repositories.

Current areas of work include:

- Java / Spring Boot system design
- Kafka reliability and distributed-systems patterns
- Kubernetes deployment and operational concerns
- Cloud-native architecture on AWS
- Data structures and algorithm practice in Java

## Contact

I am open to backend Java, platform and cloud-native engineering opportunities.

- LinkedIn: https://www.linkedin.com/in/zakaria-dbaba/
- Portfolio: https://zakariadbaba.netlify.app/
- Email: zakaria-dbaba@hotmail.com

---

<p align="center">
  <strong>Backend engineering • Distributed systems • Cloud-native delivery</strong>
</p>
