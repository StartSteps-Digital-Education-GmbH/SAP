# Day 1: Baseline Configuration + Deploy Technical Design
## Turning Baseline Into a Deployable, Testable Setup

This lesson covers the remaining Coursera 3 slides around:
- **Setting up baseline configuration and integrations** (slide 21)
- **Deploy the technical solution design** (slide 22)

Slide focus (instructor reference): **21–22**.

---

## 🎯 Learning Objectives

By the end, you will be able to:
- Define **baseline configuration** and explain why it must be stable
- Describe how **integrations** are prepared for testing
- Explain what “deploy technical solution design” means in practice
- Connect deployment decisions to later testing and go-live readiness

---

## Part 1: Baseline Configuration and Integrations (Slide 21)

“Baseline” means the minimum stable setup the team can build on reliably.

Baseline configuration typically includes:
- Agreed configuration foundations (what is allowed and what is standardized)
- Core setup needed for consistent behavior across environments
- A stable integration structure (so interfaces can be tested)

Integrations in baseline planning include:
- Interfaces identified (what connects to what)
- Connectivity basics prepared so testing can start
- Monitoring/alerting considerations so issues are visible

---

## Part 2: Deploy the Technical Solution Design (Slide 22)

Deploying the technical solution design means moving agreed design decisions into a working implementation setup:
- Apply configuration
- Deliver required integrations
- Prepare the technical solution so it can be tested end-to-end

A practical mindset:
> Deployment is not “the last step before go-live.” It is the step that makes testing possible.

---

## Part 3: How This Feeds Test Scripts

Once baseline + deploy are ready:
- Test scenarios can be executed consistently
- Test scripts produce evidence (pass/fail + logs)
- Defects can be triaged quickly and re-tested with less rework

---

## 📝 Knowledge Check

1. What is the difference between “baseline” and “final go-live” readiness?  
   ___________________________________________

2. Name two reasons stable baseline helps testing.  
   ___________________________________________

3. When deploying technical design, what should be ready so you can write/execute test scripts?  
   ___________________________________________

4. Give one integration-related risk if baseline integrations are not prepared.  
   ___________________________________________

