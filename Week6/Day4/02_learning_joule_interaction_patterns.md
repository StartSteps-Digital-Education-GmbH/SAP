# Day 4: Joule interaction patterns

## Transactional, navigational, informational, analytical

This lesson builds on `01_learning_introducing_joule.md`. All activities here can be completed **without** SAP system access.

Optional SAP reading (same journey as Day 4): [Introducing Joule on SAP Learning](https://learning.sap.com/learning-journeys/provisioning-and-implementing-joule/introducing-joule).

---

## Learning objectives

By the end of this session, you will be able to:

- Describe the **four interaction patterns** Joule is designed around
- Match real user intents to the best pattern (even when multiple could apply)
- Explain why **not every task** should be forced into natural language

---

## The four patterns (conceptual)

SAP describes Joule supporting multiple ways users work. A practical consultant framing:

### 1) Transactional interactions

User wants to **do something in the backend process** via natural language assistance—often **create / read / update / delete** style work *when supported* for that product.

Examples (illustrative, not a promise of availability):

- “Show purchase orders I need to approve” and then **approve** with confirmation steps  
- HR workflows where supported (e.g., tasks tied to SuccessFactors scenarios, depending on release)

**Consultant note:** transactional patterns must respect **authorizations**, **approval rules**, and **auditability**.

---

### 2) Navigational interactions

User wants help **getting to the right screen** or **next best step** in the UI—especially helpful for **occasional users** who don’t know the menu structure.

Examples:

- “Take me to the screen where I manage vendor bank details.”  
- “Where do I release a blocked billing document?”

**Consultant note:** navigation still needs **training** and **process clarity**—Joule helps, but doesn’t replace process documentation.

---

### 3) Informational interactions

User wants **answers** grounded in knowledge—often policy/help/enablement content.

Two common flavors:

- **SAP-managed knowledge** (e.g., help and enablement content made available through Joule concepts)  
- **Customer-owned knowledge** via **document grounding** (covered more on Day 5)

**Consultant note:** informational answers should show **why** an answer is trustworthy (sources, citations where available).

---

### 4) Analytical interactions

User wants **insights** from data—trends, comparisons, explanations—within the guardrails of what they are allowed to see.

**Consultant note:** analytics scenarios are sensitive to **data definitions**, **security**, and **interpretation risk** (“the chart says X” ≠ “the business decision is Y”).

---

## Choosing the right pattern (simple rules)

Ask:

1. Is the user trying to **execute** a process outcome? → often **transactional**  
2. Are they lost in the UI? → **navigational**  
3. Are they asking **what/why/how** based on documents/help? → **informational**  
4. Are they asking for **metrics/trends**? → **analytical**

Many real requests are **mixed**. Your job in workshops is to **decompose** them:  
“What is the user actually trying to achieve?” → then decide the safest UX path.

---

## Knowledge check

1. Define each pattern in **one sentence** (your own words):

- Transactional: ___________________________________________  
- Navigational: ___________________________________________  
- Informational: ___________________________________________  
- Analytical: ___________________________________________

2. User says: “Why did margin drop last quarter?” Which pattern is primary? What could go wrong if you answer without clarifying definitions?  
   ___________________________________________  
   ___________________________________________

3. Give one task you would **not** push into conversational UI (and why).  
   ___________________________________________

4. Why must transactional Joule scenarios still support **human oversight** in many cases?  
   ___________________________________________
