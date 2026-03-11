# Day 3: Fit-to-Standard vs Custom
## How to Choose: Standard App, Extension, or Custom Build

In S/4HANA projects, one of the most important design decisions is whether to use **standard SAP** as-is, **extend** it, or build something **custom**. This session gives you a practical decision framework.

---

## 🎯 Learning Objectives

By the end of this session, you will:
- Explain what **fit‑to‑standard** means in SAP projects
- Compare **standard**, **extend**, and **custom** options with trade‑offs
- Identify common reasons teams choose custom (and why this can be risky)
- Connect fit‑to‑standard decisions to the **Simplification List** and upgrades

---

## Part 1: What Does “Fit-to-Standard” Mean?

**Fit‑to‑standard** means:
- Start with SAP’s **standard processes and apps**
- Run workshops to see how well they fit business needs
- Decide what needs to be configured vs extended vs changed in process

The mindset is:
> “Change the process to match SAP standard **when it makes sense**, and only customize when the value is worth the cost and risk.”

---

## Part 2: Three Options (Standard / Extend / Custom)

### Option A: Use Standard (Configure Only)

Use standard when:
- The requirement is common across many companies
- SAP already supports it with configuration
- You want faster delivery and simpler upgrades

Typical benefits:
- Lower risk
- Faster implementation
- Easier maintenance

### Option B: Extend Standard (Keep Core Clean)

Extend when:
- Standard is mostly correct, but small additions are needed (fields, validations, UI adaptations)
- You can add value without breaking upgrade paths

Typical benefits:
- Balanced approach (value + maintainability)

### Option C: Custom Build

Build custom when:
- The requirement is truly unique and provides strong competitive advantage
- Standard cannot reasonably support it even with extension
- The organization accepts higher cost and long‑term maintenance

Typical risks:
- More build and test effort
- Higher upgrade and regression testing burden
- Stronger dependency on specialized skills

---

## Part 3: A Simple Decision Checklist

When evaluating “standard vs custom”, ask:

1. **Business value**: Is this requirement high value or “nice to have”?
2. **Frequency**: How often will it be used (daily vs rare)?
3. **Users impacted**: How many users depend on it?
4. **Complexity**: How complex is the change?
5. **Upgrade impact**: What happens in the next S/4HANA upgrade?
6. **Alternatives**: Can we solve it by changing the process instead?

---

## Part 4: Why the Simplification List Matters Here

The **Simplification List** helps you understand:
- Which functions changed in S/4HANA
- Which old transactions are replaced
- Where custom code or old processes may break

Fit‑to‑standard decisions should consider:
- “If we customize this, will it be harder to upgrade later?”
- “Is SAP already moving in a direction that will replace our customization?”

---

## Part 5: Example Decisions

### Example 1 – Approvals on Mobile

- Requirement: managers approve POs on mobile
- Likely approach: standard Fiori approvals + configuration, maybe small extension

### Example 2 – A Unique Pricing Algorithm

- Requirement: company-specific pricing logic
- Possible approach: extension/custom logic, but must weigh:
  - value vs long-term maintenance
  - testing impact

---

## 📝 Knowledge Check

1. **In your own words, what does fit‑to‑standard mean?**  
   ___________________________________________  
   ___________________________________________

2. **Give one situation where using standard SAP is the best choice.**  
   ___________________________________________  
   ___________________________________________

3. **Give one situation where a custom build might be justified.**  
   ___________________________________________  
   ___________________________________________

4. **Why does customization usually increase long‑term cost?**  
   ___________________________________________  
   ___________________________________________

5. **How does the Simplification List influence fit‑to‑standard decisions?**  
   ___________________________________________  
   ___________________________________________

