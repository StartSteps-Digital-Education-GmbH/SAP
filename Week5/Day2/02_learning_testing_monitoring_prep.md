# Day 2: Testing and Monitoring (Foundations)
## Building Quality and Stability Into the Lifecycle

Testing and monitoring should not be “last-minute tasks.” In SAP projects, they are planned early and executed throughout the lifecycle.

This lesson builds from the Coursera 3 deck **Testing and monitoring** (slide 14) and connects to what you learned about deliverables on Day 1.

---

## 🎯 Learning Objectives

By the end of this session, you will:
- Explain why a **testing strategy** must be planned early
- Identify common **types of testing** in SAP implementations
- Describe what “monitoring” means before and after go‑live
- Connect testing and monitoring to lifecycle phases and key deliverables

---

## Part 1: Why Testing Strategy Starts Early

Testing is not only “UAT at the end.” If you delay planning:
- Test environments are not ready
- Test data is missing or unrealistic
- Defects appear late, when fixes are more expensive

A simple testing strategy clarifies:
- **What** will be tested (scope)
- **When** it will be tested (timeline)
- **Who** will test (roles)
- **How** results and defects will be handled (process/tools)

---

## Part 2: Common Testing Types (SAP Project View)

You may see:
- **Unit testing**: developers/configurators validate small parts
- **Integration testing**: end-to-end flows across modules/systems
- **Regression testing**: ensure changes didn’t break existing flows
- **Performance testing**: response time, throughput, batch jobs
- **Security testing**: roles/authorizations, data access controls
- **User Acceptance Testing (UAT)**: business users validate real scenarios

Key idea:
> Each testing type reduces a different kind of risk.

---

## Part 3: Monitoring – What Are We Watching?

Monitoring means observing the solution to keep it stable and predictable.

Common monitoring concerns:
- **Performance**: slow transactions, long-running jobs
- **Availability**: uptime, failed interfaces
- **Errors**: application logs, integration failures
- **Capacity**: memory/storage growth, spikes
- **Business signals** (when applicable): stuck orders, failed postings, queues

Monitoring matters most:
- During **go‑live and hypercare**
- During **continuous improvement** (to catch regressions and growth)

---

## Part 4: Where Testing and Monitoring Live in the Lifecycle

- **Project preparation / Blueprinting**
  - Define testing scope and roles
  - Identify environment needs and data needs

- **Realization**
  - Execute unit and integration tests
  - Fix defects and re-test

- **Final preparation**
  - Execute UAT and final regression checks
  - Confirm monitoring readiness for go-live

- **Go‑live and support**
  - Hypercare monitoring and rapid issue resolution

- **Continuous improvement**
  - Use monitoring insights to prioritize improvements

---

## 📝 Knowledge Check

1. Why is it risky to treat testing as “only UAT at the end”?  
   ___________________________________________  
   ___________________________________________

2. Name **three** testing types and the risk each reduces.  
   ___________________________________________  
   ___________________________________________

3. Give **two** examples of things you would monitor during hypercare.  
   ___________________________________________  
   ___________________________________________

4. In which lifecycle phase do you most strongly prepare for UAT, and why?  
   ___________________________________________  
   ___________________________________________

