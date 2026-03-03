# Day 2: SAP Cloud Architecture and Tools
## SAP Cloud Architecture, Layers, and Key Tools

In this learning file you will connect **cloud strategy** to the **technical architecture** and the **tools** you will hear about often as an SAP Technology Consultant (SAP BTP, SAP Analytics Cloud, SAP Integration Suite, and more).

---

## 🎯 Learning Objectives

By the end of this session, you will:
- Describe the main **layers** of SAP Cloud Architecture (presentation, application, data, integration)
- Recognize the key **SAP cloud tools** and what they are used for
- Explain how **deployment models**, **scalability**, and **resource management** fit into the architecture
- Link at least **one tool** or architectural element to the afternoon **Coursera Course 2** topics

---

## Part 1: SAP Cloud Architecture – Big Picture

**SAP Cloud Architecture** is how SAP structures its cloud-based solutions so they are:
- Flexible and **scalable**
- Secure and **reliable**
- Able to **integrate** with many other systems

You can imagine four main **layers**:

| Layer | What it includes | Examples |
|-------|------------------|----------|
| **Presentation layer** | User interfaces and entry points | SAP Fiori apps, web UIs, mobile apps, Launchpad |
| **Application layer** | Business logic and processes | S/4HANA Cloud, SuccessFactors, Ariba, custom apps |
| **Data layer** | Databases and storage | SAP HANA Cloud, data warehouses, object storage |
| **Integration layer** | Connections between systems | SAP Integration Suite, APIs, event-based integrations |

These layers can run:
- Entirely in **SAP-managed cloud**
- In a **hyperscaler** (AWS, Azure, GCP) with SAP software
- In **hybrid** setups that combine on-premise and cloud components

---

## Part 2: Key SAP Cloud Tools (High-Level)

The slides list several **key tools**. Use this table as a quick reference:

| Tool | Short description | Typical use |
|------|-------------------|-------------|
| **SAP Business Technology Platform (BTP)** | Platform for developing, integrating, and extending SAP solutions | Build extensions, run custom apps, integrate data and processes |
| **SAP Analytics Cloud (SAC)** | Cloud analytics for reporting, planning, and predictive | Dashboards, analytics for management, planning scenarios |
| **SAP Integration Suite** | Integration platform to connect SAP and non-SAP systems | APIs, pre-built integration flows, event-driven integration |
| **SAP Data Intelligence** | Data integration and orchestration across sources | Connect and govern data from many systems for analytics and ML |
| **SAP Business Application Studio** | Cloud-based IDE for SAP development | Develop Fiori apps, extensions, and services on BTP |
| **SAP Solution Manager / SAP Cloud ALM** | Tools for lifecycle, monitoring, and operations | Monitor systems, manage changes, support operations |

> As a consultant, you usually do not configure every detail of these tools yourself –  
> but you **must know what they are for** and when to suggest them.

---

## Part 3: Deployment Models, Scalability, Elasticity, Resource Management

### Deployment Models (Revisited)

These models describe **where** the architecture runs:
- **Public cloud:** standardized services shared by multiple customers
- **Private cloud:** dedicated landscape for one customer
- **Hybrid cloud:** some systems on-premise, some in the cloud

### Scalability and Elasticity

- **Scalability** – ability to handle more load by adding resources (more CPU, memory, instances)
- **Elasticity** – ability to scale **up and down automatically** based on demand

For example:
- A retailer might automatically scale a cloud-based **webshop and analytics app** during a promotion.
- When traffic returns to normal, resources are scaled down to save cost.

### Resource Management

In SAP cloud environments, resource management includes:
- Monitoring CPU, memory, and storage usage
- Automatically starting/stopping services
- Tracking costs by system, project, or team

Operations teams often use:
- **Monitoring dashboards** (Solution Manager, SAP Cloud ALM, hyperscaler tools)
- **Budgets and alerts** for cloud spending

---

## Part 4: Cloud Architecture + Tools – Example Scenarios

Use the scenarios below to connect architecture and tools.

### Scenario 1 – Real-Time Analytics Dashboard

A company wants a **real-time sales dashboard** accessible from web and mobile.

- **Presentation layer:** Fiori app or web UI
- **Application layer:** SAP S/4HANA Cloud (sales processes)
- **Data layer:** SAP HANA Cloud + data models
- **Integration layer:** Integration between operational system and analytics
- **Tools involved:** SAP Analytics Cloud (dashboards), possibly Integration Suite or data replication

### Scenario 2 – Integrating SAP with a 3rd-Party Logistics Provider

A manufacturer uses a 3rd‑party logistics partner and wants **automatic shipment updates** in SAP.

- **Integration layer:** SAP Integration Suite connects SAP and the logistics API
- **Application layer:** S/4HANA Cloud for orders and deliveries
- **Data layer:** HANA Cloud stores shipment status
- **Tools involved:** SAP Integration Suite, monitoring via Solution Manager or Cloud ALM

---

## 📺 Optional Video – What Is SAP BTP?

To see one key tool in action, you can watch:

- **What is SAP BTP? \| Business Technology Platform**  
  `https://www.youtube.com/watch?v=eQrCx-zRJAs`

**While watching, note:**
1. Which capabilities of BTP are highlighted (data, analytics, integration, extension, etc.)?
2. How would you explain BTP to a **non-technical stakeholder** in one or two sentences?

> Your notes:
> ___________________________________________
> ___________________________________________

---

## 📝 Knowledge Check

1. **Name the four main layers of SAP Cloud Architecture and give one example for each layer.**  
   ___________________________________________

2. **Which SAP tool would you use to connect S/4HANA Cloud with a non-SAP CRM system, and why?**  
   ___________________________________________

3. **How does “elasticity” differ from just “scalability” in a cloud context? Give one simple example.**  
   ___________________________________________

4. **In the analytics dashboard scenario, which tools and layers are involved?**  
   ___________________________________________

5. **A customer wants to build a small custom app that extends S/4HANA Cloud without changing the core system. Which platform or tool would you mention first, and why?**  
   ___________________________________________

