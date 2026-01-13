# Autonomous Crawling Web Intelligence Agent.

## 🚀 Project Overview

The **Autonomous Crawling Web Intelligence Agent** is a **true agentic AI system** designed to autonomously explore websites, reason over their content, and answer user queries **only when verifiable evidence is found**.

Unlike traditional chatbots or simple tool-augmented LLMs, this system **plans, acts, evaluates, and iterates**—behaving like a real autonomous agent that navigates the web with a goal-driven mindset.

---

## ❓ Problem This Project Solves

Modern websites are large and information-dense. Users often need to:

* Scroll endlessly
* Click multiple pages
* Read irrelevant sections

…just to find one specific answer.

This project eliminates that friction by building an AI agent that:

* Explores the website on the user’s behalf
* Autonomously follows internal links
* Searches for evidence across multiple pages
* Returns a grounded answer—or explicitly says **NOT FOUND**

---

## 🏗️ System Architecture

```
User Query + Website URL
            ↓
        Planner Agent
            ↓
   Autonomous Navigation Loop
            ↓
   ┌───────────────┐
   │ Read Page     │
   │ Analyze       │
   │ Evaluate      │
   │ Decide        │
   └───────────────┘
            ↓
 Evidence Found? ── Yes ──→ Answer Generator
            │
            No
            ↓
   Discover & Prioritize Links
            ↓
        Visit Next Page
```

---

## 🔄 Agent Execution Flow 

1. **Goal Initialization:**
   The agent receives a website URL and a user question.

2. **Planning Phase:**
   A planning agent defines a clear navigation and verification strategy.

3. **Page Exploration:**
   The agent reads the current page and cleans its content.

4. **Evidence Evaluation:**
   A reasoning agent evaluates whether the page contains strong evidence.

5. **Decision Making:**

   * If evidence is found → stop crawling
   * If not → discover new internal links

6. **Autonomous Crawling:**
   The agent follows relevant links and repeats analysis.

7. **Final Answer Generation:**
   The agent answers using **only verified evidence** or explicitly returns **NOT FOUND**.

---

## 🛠️ Technologies Used

* **Python** (Programming Language)
* **Google Gemini API** (LLM reasoning)
* **BeautifulSoup** (HTML parsing)
* **Requests** (HTTP handling)
* **Google Colab** (execution environment)



