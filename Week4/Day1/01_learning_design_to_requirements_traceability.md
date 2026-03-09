# Day 1: Design to Requirements Traceability
## Connecting Business Requirements, Design, Configuration, and Tests

This session builds on your Week 3 work on **designing an SAP solution** and **SAP Activate**. We focus on how to keep a clear **line of sight** from business requirements to design decisions, configuration, and testing.

---

## 🎯 Learning Objectives

By the end of this session, you will:
- Explain what **requirements traceability** means in an SAP project
- Describe how requirements link to **solution design**, **technical specifications**, and **test cases**
- Recognize where traceability shows up in **SAP Activate** phases (Prepare, Explore, Realize)
- Understand why good traceability reduces **project risk** and supports **change management**

---

## Part 1: What Is Requirements Traceability?

**Requirements traceability** is the ability to:
- Start from a **business requirement** and see which parts of the **design**, **configuration**, **interfaces**, and **tests** implement it
- Start from a **design or technical element** and see **which requirements** it supports

In practice this helps you:
- Check that all critical requirements are **covered**
- Understand the **impact** when requirements change
- Justify design and build decisions to stakeholders

---

## Part 2: Traceability Across SAP Activate Phases

Link traceability to the **SAP Activate** phases:

| Phase | Traceability focus |
|-------|--------------------|
| **Prepare** | Capture initial high‑level requirements and scope; set up basic tracking (e.g. requirements list or backlog) |
| **Explore** | Refine requirements in fit‑to‑standard workshops; link requirements to **solution design** and **process flows** |
| **Realize** | Configure and develop according to design; link configuration and developments to **requirements** and **test cases** |

Examples:
- A requirement like “Managers must approve purchase orders via mobile” should be visible in:
  - Design docs (which **Fiori app or process** is used)
  - Technical specs (how the app is configured and integrated)
  - Test cases (how you will confirm it works)

---

## Part 3: Traceability Artefacts

Traceability does not need to be complicated. It can live in:

- A **requirements log** or backlog (e.g. spreadsheet, Jira, ALM tool)
- The **solution blueprint** (trace requirements to processes and design decisions)
- **Technical specifications** (mention requirement IDs they implement)
- **Test cases and scripts** (reference requirement IDs)

Example of simple trace links:
- Requirement ID **R‑101** → Process “Approve Purchase Orders” → Design section 3.2 → Tech spec T‑12 → Test case TC‑05.

When something changes (e.g. R‑101 is updated), you can quickly see:
- Which processes, designs, technical specs, and tests might be impacted.

---

## Part 4: Why Traceability Matters

Good traceability helps you:
- Avoid **missing requirements** in design and build
- Evaluate **impact of changes** more accurately
- Support **audits** or formal approvals
- Communicate clearly with:
  - Business stakeholders (which requirements are covered)
  - Technical teams (why something is implemented a certain way)

Poor traceability can lead to:
- Surprises in testing or UAT
- Rework late in the project
- Disagreements about **what was agreed** in the design

---

## 📝 Knowledge Check

1. **In your own words, what is requirements traceability and why is it important in an SAP project?**  
   ___________________________________________  
   ___________________________________________

2. **Name two SAP Activate phases where traceability work is especially important, and explain what happens there.**  
   ___________________________________________  
   ___________________________________________

3. **Give one example of how a requirement can be traced through design, technical spec, and test case.**  
   ___________________________________________  
   ___________________________________________

4. **What could happen if a major requirement is not properly traced into design and tests?**  
   ___________________________________________  
   ___________________________________________

