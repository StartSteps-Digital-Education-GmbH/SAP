# Day 1: Optional – Data Modeling Basics in SAP HANA
## What It Is and Why It Matters

**(Optional)** Use this short page to reinforce **data modeling** in SAP HANA. You can do this on your own or in pairs.

---

## What Is Data Modeling in SAP HANA?

**Data modeling** in SAP HANA is the design of how data is **structured**, **related**, and **transformed** so that applications and reports get the right data in the right shape. Instead of every report reading raw tables directly, you create **views** (e.g. calculation views, analytical views) that combine and aggregate data in a way that makes sense for the business.

- **Graphical modeling:** You use visual tools to build data models (e.g. drag-and-drop tables, joins, calculations) so that even complex logic is easier to understand and maintain.
- **Data flows:** You define how data moves from source tables through transformations to the final view that reporting tools or apps use.

---

## Why It Matters

- **Consistency:** Everyone uses the same definitions (e.g. “revenue,” “customer”) when the model is shared.
- **Performance:** Well-designed models let HANA run queries faster (e.g. by pre-aggregating or organizing data).
- **Maintainability:** When business rules change, you update the model in one place instead of in many reports.

---

## Quick Match: Terms to Definitions

**Instructions:** Match each term to its short description. Write the letter in the blank.

| # | Term | Your answer (A–C) |
|---|------|-------------------|
| 1 | Calculation view | _____ |
| 2 | Graphical modeling | _____ |
| 3 | Data flow | _____ |

**Descriptions:**

- **A** – A view in SAP HANA that can combine multiple sources and define calculations and aggregations for reporting and analytics.
- **B** – Building data models using visual tools (e.g. diagrams) instead of writing all logic in code.
- **C** – The path data follows from source tables through transformations to the final view or output.

**Answers:** 1–A, 2–B, 3–C

---

## One Question

**When might a company need to create or change a data model in SAP HANA?**  
*(Think: new report, new KPI, new data source, or a change in how “revenue” or “customer” is defined.)*

> ___________________________________________
> ___________________________________________
