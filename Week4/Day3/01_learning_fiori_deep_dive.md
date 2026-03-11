# Day 3: SAP Fiori Deep Dive
## Principles, Elements, Launchpad, Guidelines, and UX Testing

Today we go deeper into **SAP Fiori** and how it is used in real S/4HANA projects: not just “what it is”, but how you make design choices and validate UX.

---

## 🎯 Learning Objectives

By the end of this session, you will:
- Explain core **Fiori design principles** and why they matter
- Describe **Fiori elements** and how they speed up consistent app delivery
- Explain the role of the **Fiori Launchpad** in role‑based access and navigation
- Recognize key **design guidelines** and what “good Fiori UX” looks like
- Understand what **UX testing** means for SAP apps and when to do it

---

## Part 1: Fiori Design Principles (What “Good UX” Means)

Fiori is designed to make SAP work:
- **Role-based**: users only see what they need for their job
- **Simple**: focus on key tasks; reduce unnecessary fields and steps
- **Responsive**: works across devices and screen sizes
- **Coherent**: consistent patterns across apps

As a consultant, you should be able to turn these principles into decisions like:
- Which tasks go on the Launchpad for each role?
- Which KPIs should be on an overview page vs hidden in reports?
- What should be mandatory vs optional on a form?

---

## Part 2: Fiori Elements (Why Teams Use It)

**Fiori elements** are prebuilt templates and floorplans that help teams build apps faster and more consistently.

Typical benefits:
- Consistent UX patterns (tables, filters, object pages)
- Faster delivery for standard scenarios
- Less custom UI code (when the app fits a standard floorplan)

In practice, teams often:
- Prefer **standard Fiori apps** first
- If needed, use **Fiori elements** to extend or build apps in a consistent way

---

## Part 3: Fiori Launchpad (How Users Actually Work)

The **Launchpad** is the role‑based home screen. It:
- Provides navigation to apps
- Supports role-based content (tiles/cards)
- Supports personalization (within limits)

Design questions:
- Which apps should be visible for each role?
- Which tiles should be “must have” vs optional?
- Do we need separate catalogs for different roles (e.g. buyer vs approver)?

---

## Part 4: App Types and When to Use Them

| App type | Best for | Example |
|---------|----------|---------|
| **Transactional** | Doing work (create/change/approve) | Approve purchase orders, create sales orders |
| **Analytical** | Monitoring and decisions | KPI dashboard, backlog overview |
| **Fact sheet** | Context about a business object | Customer details, material overview |

In real projects, users typically need a **mix**:
- Managers: analytical + approvals (transactional)
- Operational users: transactional + fact sheet context

---

## Part 5: Design Guidelines and UX Testing

### Design Guidelines (Practical)

Good Fiori design usually means:
- One screen = one main purpose (avoid “do everything” screens)
- Clear naming of tiles and actions (“Approve PO”, not “Transaction Z123”)
- Minimal required fields (reduce cognitive load)
- Consistent navigation and terminology

### UX Testing (Practical)

**UX testing** means checking the app with real users or representatives:
- Can they complete the task quickly?
- Do they understand labels and steps?
- Is it usable on mobile when needed?

When to test:
- Early prototypes (to avoid building the wrong thing)
- Before go‑live (to avoid adoption problems)
- After changes (to confirm improvements)

---

## 📺 Suggested Videos

- **Introducing SAP Fiori – SAP Learning Video**  
  `https://learning.sap.com/courses/technical-implementation-and-operation-i-of-sap-s-4hana-and-sap-business-suite/introducing-sap-fiori-3`

- **SAP Fiori: Tips & Tricks for users of SAP S/4HANA**  
  `https://www.youtube.com/watch?v=EvvFlR4l-8c&t=1554s`

If you watch a video, note:
1. Which design principles you see in the examples
2. One UX decision that seems important for adoption

> Notes:  
> ___________________________________________  
> ___________________________________________

---

## 📝 Knowledge Check

1. **Name three Fiori design principles and explain one in your own words.**  
   ___________________________________________  
   ___________________________________________

2. **What problem do Fiori elements solve for project teams?**  
   ___________________________________________  
   ___________________________________________

3. **Give one example of when you would use a transactional app vs an analytical app.**  
   ___________________________________________  
   ___________________________________________

4. **Why is UX testing valuable before go‑live?**  
   ___________________________________________  
   ___________________________________________

