## Hi there 👋

# Chaitanya Rangavajhala – Engineering Leader
Quantitative Platforms | Securitized Products | Distributed Systems

**New York, NY** · [Email](mailto:crangavajhala@gmail.com) · [LinkedIn](https://www.linkedin.com/in/chaitanya-rangavajhala)

Engineering leader with 15+ years building and owning large-scale front-office platforms for pricing, risk, and quantitative analytics in fixed-income and securitized products.

Led global teams delivering systems for Sales & Trading, Quants, and Risk — from real-time loan-level valuation across 150M+ assets to reproducible research environments used by thousands of practitioners.

Hands-on with distributed systems, cloud-native infrastructure, and real-time streaming platforms, combined with deep domain expertise in securitized products (agency/non-agency MBS, CMBS, ABS, CRT, and whole loans).

---

## Platform Leadership & Modernization

Led modernization of enterprise-scale real-time data and analytics platforms, scaling them for high-volume workloads while improving reliability, operability, and developer velocity.

Focus areas included:

- **Real-time streaming platforms:** Evolved messaging abstractions from application-embedded clients to platform-managed consumption models, balancing latency, reliability, operational ownership, and developer experience at scale.
- **Temporal & AsOf data access:** Designed systems supporting consistent historical and real-time views, informed by bi-temporal financial data models and unified intraday/end-of-day architectures.
- **Scalable storage & caching:** Applied distributed caching and in-memory compute patterns to support low-latency analytics, with change-driven propagation to maintain consistency under load.
- **Change data capture & propagation:** Leveraged source-level CDC patterns to enable low-latency updates while addressing ordering guarantees, schema evolution, and recovery scenarios.

---

### Hybrid Python–C++ Quant Engine Architecture

Designed and owned production quantitative engines for front-office valuation, risk, and scenario analysis in securitized products — blending a **Python modeling layer** (shim with custom extensions) for rapid iteration and user overrides with a **high-performance C++ core** for compute-intensive projections.

- **Python Layer (Shim & Custom Extensions)**:  
  Built expressive Python DSL enabling custom prepayment S-curves, CDR vectors, loss-severity schedules, HPA forecasts, and scenario overrides — delivering rapid prototyping, reproducibility, and model governance for quants and analysts.

- **C++ Core Engine**:  
  Implemented low-latency, matrix-oriented projection engine in modern C++ for path-dependent stochastic simulations (Monte Carlo paths), optimized for numerical stability, parallel execution, and scalability across millions of securities.

This hybrid approach achieves **developer velocity and modeling flexibility** (Python) with **deterministic performance and reliability** (C++) — a best-practice pattern in leading quantitative finance platforms.

---

## Open-Source Contributions

Most work is proprietary, but I contribute to open-source when it solves meaningful problems at scale:

- **BinderHub** (Kubernetes-native research platform)  
  Community maintainer with responsibility for ongoing development, enterprise integrations, and operational reliability.

- **Vitess** (CNCF-graduated distributed database)  
  Authored and merged upstream pull requests improving query planner performance and observability, adopted in large-scale production environments:

  - https://github.com/vitessio/vitess/pull/18903
  - https://github.com/vitessio/vitess/pull/17342
  - https://github.com/vitessio/vitess/pull/17508
  - https://github.com/vitessio/vitess/pull/17468
  - https://github.com/vitessio/vitess/pull/19000

These contributions reflect production-driven improvements developed and validated in large-scale financial systems, then generalized and upstreamed to the open-source community.

---

## Private Work

Most platform work has been proprietary; architectural approaches, design trade-offs, and lessons learned are discussed conceptually and in an NDA-compliant manner.

---

## Let's Connect

- **LinkedIn:** https://www.linkedin.com/in/chaitanya-rangavajhala
- **Email:** crangavajhala@gmail.com
