# Daraz UI Testing — QA Portfolio Project

> Manual and exploratory test documentation for critical user flows on [Daraz.com.np](https://www.daraz.com.np) — Nepal's largest e-commerce platform.

---

## 🎯 Project Overview

This repository documents a structured QA effort targeting the highest-risk user flows on the Daraz platform. It was built to simulate a real-world QA engagement: identifying scope, writing test cases, logging locators, and tracking results — all using industry-standard documentation practices.

**Platform Under Test:** Daraz.com.np  
**Testing Type:** Manual UI Testing, Exploratory Testing, Regression Testing  
**Status:** Active — ongoing test case development  

---

## 🔍 Why These Areas Were Tested

Daraz processes thousands of transactions daily. The following flows were prioritized because a defect in any one of them directly causes lost revenue or user churn:

| Area | Risk if Broken |
|---|---|
| Login / Authentication | Users cannot access their account or complete purchases |
| Homepage Load & Navigation | First impression failure; high bounce rate |
| Cart — Add to Cart | Core conversion flow blocked |
| Checkout & Payment | Direct revenue loss; most critical flow |

---

## 📊 Test Metrics

| Metric | Value |
|---|---|
| Total Test Cases | 12 |
| Smoke Tests | 4 |
| Regression Tests | 6 |
| Exploratory / Notes | 2 |
| Locator Files | 2 |
| Test Result Format | Markdown (`.spec.md`), JavaScript spec stubs (`.spec.js`) |

---

## 🗂️ Repository Structure
Daraz-UI-Testing/
│
├── smoke-tests.spec.md          # Core smoke test suite (login, homepage, cart)
├── checkout-tests.spec.js       # Checkout flow test stubs (Cypress-ready structure)
├── checkout-test-notes.md       # Exploratory notes from checkout session
├── daraz-locators.json          # CSS/XPath selectors for key UI elements
├── payment-selectors.json       # Locators specific to the payment flow
└── regression-test-plan.md      # Full regression plan: scope, schedule, entry/exit criteria

---

## 🛠️ Tools & Stack

| Tool | Purpose |
|---|---|
| Git + GitHub | Version control and portfolio hosting |
| Markdown | Test case documentation |
| JSON | Locator/selector storage |
| JavaScript (stub) | Cypress-compatible test structure |
| Obsidian | Local knowledge base and command documentation |

---

## ▶️ How to Use This Repository

```bash
# 1. Clone the repository
git clone https://github.com/Kabisharai/Daraz-UI-Testing.git

# 2. Navigate into the project
cd Daraz-UI-Testing

# 3. Review the smoke test suite
cat smoke-tests.spec.md

# 4. Review the regression plan
cat regression-test-plan.md
```

> **Note:** This project currently contains manual test documentation. Cypress automation scripts are in active development.

---

## 👩‍💻 About

Built by **Kabisha Rai** as part of a structured QA engineering preparation program.  
Focused on developing production-ready testing habits before formal QA training.

**GitHub:** [github.com/Kabisharai](https://github.com/Kabisharai)
