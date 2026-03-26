# Day 4: Grounding and document grounding
## Why answers need sources (conceptual)

This lesson explains **grounding** in consultant-friendly terms. You can complete everything **without** SAP access.

Optional SAP context: the *Introducing Joule* unit describes grounding and document grounding at a high level — [Introducing Joule on SAP Learning](https://learning.sap.com/learning-journeys/provisioning-and-implementing-joule/introducing-joule). The next unit in the same journey, **Understanding Joule Architecture and Extensibility**, goes deeper if you choose to explore later.

---

## Learning objectives

By the end of this session, you will be able to:

- Explain **grounding** without jargon-heavy ML detail
- Describe **document grounding** and why customers care (policies, HR, enablement)
- Connect grounding to **trust**, **citations**, and **reduced hallucination risk**
- List practical **data governance** questions to ask before enabling document grounding

---

## What is “grounding”?

**Grounding** means: the assistant’s answer is **anchored** to **retrieved, permitted sources** (help content, business documents, structured business data the user may access)—rather than purely “guessing” from general language patterns.

Why teams talk about grounding in enterprise AI:

- It improves **accuracy** for organization-specific facts
- It supports **traceability** (“where did this answer come from?”)
- It aligns with **compliance** expectations (use approved sources)

---

## What is document grounding?

**Document grounding** extends grounding to **customer-owned documents** stored in connected repositories (for example, policy libraries). Users ask questions; the system retrieves relevant excerpts and responds with an answer that can **reference those sources**.

Consultant framing:

- It turns “our policies live in SharePoint / file shares” into **searchable, Q&A style help**—with governance.
- It is powerful for **HR**, **travel**, **IT security policies**, **SOPs**, and onboarding content.

---

## Embeddings and vectors (one paragraph, enough for consulting conversations)

To find relevant text quickly, systems often:

1. Split documents into chunks
2. Convert chunks into **vector representations** (“embeddings”) that capture meaning
3. Compare a user question to those vectors to retrieve the **most relevant chunks**
4. Pass those chunks to the model to produce an answer **grounded** in what was retrieved

You do **not** need to implement this as a consultant—but you should recognize:

- **Quality of documents** matters (outdated PDFs → wrong answers)
- **Security** matters (wrong repository connection → wrong exposure)
- **Language and versioning** matter (policy v3 vs v4)

---

## Governance questions (ask early)

Before recommending document grounding, clarify:

- Who **owns** the documents and approves updates?
- How do we handle **retention** and **legal holds**?
- What is **in scope** vs **out of scope** (e.g., confidential legal advice)?
- How will we test **answer quality** and handle **escalations**?

---

## Knowledge check

1. Explain grounding to a CFO in **two sentences**.
   ___________________________________________
   ___________________________________________

2. Give one benefit and one risk of document grounding.
   Benefit: ____________________________________
   Risk: ________________________________________

3. Why do citations / source references matter for enterprise trust?
   ___________________________________________

4. Name two document-quality issues that cause bad Joule answers even if the AI model is strong.
   ___________________________________________
   ___________________________________________

