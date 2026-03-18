# Day 3: Test Scenarios, Test Cases, and Test Scripts
## How Projects Turn “We Tested” Into Evidence

Even before you reach full testing execution, you need a shared language and structure for test documentation. This lesson prepares you for later topics in the deck (test scripts and documenting testing).

Based on Coursera 3 deck concepts:
- Developing test scripts (slide 22 content)
- Documenting testing (slide 23 content)

---

## 🎯 Learning Objectives

By the end of this session, you will be able to:
- Distinguish **test scenarios**, **test cases**, and **test scripts**
- Explain why a **test case repository** matters (traceability and reuse)
- Describe what good **testing documentation** should capture (results, defects, evidence)

---

## Part 1: The Three Levels

### Test Scenario (Business View)

A **test scenario** describes an end-to-end business flow.

Example:
> “Order‑to‑cash from order creation to invoice and payment.”

### Test Case (Specific Check)

A **test case** is a specific, verifiable test within a scenario.

Example:
> “Create a sales order with a valid customer and verify pricing is correct.”

### Test Script (Step-by-Step Execution)

A **test script** provides detailed steps a tester executes, including expected results.

Example:
> Steps in SAP GUI/Fiori to create the order, expected screen values, and expected accounting posting.

---

## Part 2: Test Case Repository (Why It Exists)

A test repository helps teams:
- Reuse test cases for **regression testing**
- Track execution status across sprints/waves
- Connect tests to **requirements** and **defects**

If tests live in scattered documents:
- You cannot prove coverage
- You cannot repeat tests reliably
- You lose learning when people leave the project

---

## Part 3: What “Documenting Testing” Should Include

Good testing documentation usually captures:
- Test ID, scenario, and case description
- Preconditions (data and roles)
- Steps and expected results
- Actual results and evidence (screenshots/logs when needed)
- Defect links (if failures occur)
- Retest outcome and sign‑off (when applicable)

---

## 📝 Knowledge Check

1. What is the difference between a **test scenario** and a **test case**?  
   ___________________________________________  
   ___________________________________________

2. Why do projects need a **test case repository**? Name two reasons.  
   ___________________________________________  
   ___________________________________________

3. Name three pieces of information that should be captured when **documenting testing results**.  
   ___________________________________________  
   ___________________________________________

