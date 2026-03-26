# Day 4: Introducing Joule

## SAP’s AI copilot in the ecosystem

This file is **self-contained**. You do **not** need access to an SAP system to complete the learning or the day’s exercises.

For optional deeper reading, SAP publishes a structured introduction in the learning journey *Provisioning and Implementing Joule* — unit **Introducing Joule**: [Introducing Joule on SAP Learning](https://learning.sap.com/learning-journeys/provisioning-and-implementing-joule/introducing-joule).

---

## Learning objectives

By the end of this session, you will be able to:

- Describe **Joule** in plain language (what problem it solves for users)
- Explain why SAP positions it as **one copilot** across the SAP cloud landscape
- List the qualities SAP emphasizes for its AI offerings (**relevant, reliable, responsible**)
- Recognize **where Joule is typically available** (cloud context) vs what is **not** in scope for typical Joule delivery (e.g. classic on-premise-only scenarios)

---

## What is Joule?

**Joule** is SAP’s **AI copilot**: a way for users to work with SAP cloud solutions using **natural language** and guided assistance, with a **consistent experience** across supported applications.

In consultant language:

- It is a **productivity and guidance layer** on top of SAP business processes and data.
- It is designed to help users **get tasks done** (execute, navigate, find answers, and increasingly analyze) **inside** the SAP cloud products where it is enabled.

Think of it as: **one assistant concept** that can surface in different SAP UIs (depending on product and rollout), rather than a separate “chat-only” app disconnected from your processes.

---

## Why “one copilot for the SAP ecosystem” matters

For customers and consultants, a single copilot direction helps with:

- **Consistent UX patterns** — users learn one interaction style instead of many disconnected bots.
- **Shared principles** — security, grounding, and governance can be applied consistently.
- **Roadmap clarity** — SAP can extend capabilities across cloud products over time.

You will still see **differences by product** (what Joule can do in SuccessFactors vs S/4HANA Cloud depends on released capabilities and configuration), but the **concept** is unified.

---

## Relevant, reliable, responsible (how SAP frames quality)

These three words are useful when you talk to customers:

1. **Relevant**  
   Answers and actions should match the user’s **role**, **permissions**, and **context** (which app, which task, which data they are allowed to see).

2. **Reliable**  
   Outputs should be **grounded** in trustworthy sources (SAP knowledge, customer-approved documents, business data the user may access)—not “made up” facts presented as truth.

3. **Responsible**  
   Includes **data handling commitments**, **guardrails** for misuse, and design choices that keep **humans in control** (approval workflows, review steps, and clear limitations).

When a customer asks “Is it safe?”, your answer should connect to **authorization**, **grounding**, **logging/audit expectations**, and **human oversight**—not only “it uses AI.”

---

## What you should *not* assume (consultant hygiene)

- **Capability claims**: Always tie statements to **what is released** for a given product and tenant type. Roadmaps change; your job is to be precise.
- **On-premise**: Joule is positioned for **SAP cloud applications**; do not promise Joule for legacy on-premise stacks unless SAP explicitly documents otherwise for that scenario.
- **Magic automation**: Natural language does not remove the need for **good process design**, **testing**, **roles**, and **change management**.

---

## Knowledge check

1. In two sentences, explain Joule to a business user who has never heard of it.  
   ___________________________________________  
   ___________________________________________

2. Why does SAP emphasize **one copilot** across the ecosystem (two reasons)?  
   ___________________________________________  
   ___________________________________________

3. Give one example of **“relevant”** vs **“reliable”** in practice (not the same example for both).  
   Relevant: ___________________________________________  
   Reliable: ___________________________________________

4. Name one risk if a project treats Joule as “just a chatbot” without governance.  
   ___________________________________________
