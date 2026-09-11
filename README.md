<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080C10,50:39FF14,100:00FFF5&height=200&section=header&text=🛒%20Sauce%20Demo%20Functional%20Test%20Suite&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=C%23%20%7C%20NUnit%20%7C%20Selenium%20%7C%20Page%20Object%20Model&descSize=17&descAlignY=58&descColor=39FF14" />

</div>

---

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=39FF14&center=true&vCenter=true&width=950&lines=Sauce+Demo+(Swag+Labs)+Functional+Test+Suite+%F0%9F%9B%92;33+Test+Cases+%7C+12+Modules+%7C+100%25+Pass+Rate;Login+%C2%B7+Catalog+%C2%B7+Cart+%26+Checkout+%C2%B7+Marketing+Pages;Data-Driven+%7C+Page+Object+Model+%7C+Honest+QA+Notes" alt="Typing SVG" />

</div>

---

<div align="center">

![Selenium](https://img.shields.io/badge/Selenium-WebDriver-39FF14?style=for-the-badge&logo=selenium&logoColor=black)
![C#](https://img.shields.io/badge/C%23-.NET-239120?style=for-the-badge&logo=csharp&logoColor=white)
![NUnit](https://img.shields.io/badge/NUnit-Test_Framework-9B59FF?style=for-the-badge&logo=dotnet&logoColor=white)
![POM](https://img.shields.io/badge/Page_Object_Model-Framework-00FFF5?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 👋 Hello Everyone!

I'm pleased to share my **functional test suite for Sauce Demo (Swag Labs)**! 🎯

This project documents **33 functional test cases across 12 modules** of [saucedemo.com](https://www.saucedemo.com/) — covering the classic login → catalog → cart → checkout flow, plus the site's newer marketing pages (About, Learn More, Integrations, Sign Up, Book a Demo) — each test case mapped to a Page Object Model automation method.

> 💡 *This suite isn't just a list of green checkmarks. Where the automation currently executes the steps without fully asserting the outcome, I've documented that gap directly in the test notes instead of hiding it — because a test suite is only as trustworthy as its weakest assertion.*

---

## 📌 Project Overview

This document tracks functional test coverage for **Sauce Demo (Swag Labs)**, a well-known e-commerce practice site, using a standardized **11-column test case schema**: Scenario ID, Description, Test Case ID, Pre-Condition, Steps to Execute, Expected Result, Actual Result, Status, Executed By, Comments, and Priority.

Every test case is cross-referenced to the **Page Object Model** class and method that automates it, spanning authentication, product catalog behavior, cart and checkout logic, sidebar navigation, and the site's marketing/content pages.

---

## 🏗️ Key Highlights

<div align="center">

| 🔹 Aspect | 📘 Detail |
|:-:|:-|
| 🧾 Total Test Cases | 33 |
| 🗂️ Functional Modules Covered | 12 |
| ✅ Pass Rate | 100% (33/33) |
| 🤖 Automation Coverage | 100% (33/33 mapped to POM methods) |
| 🔁 Data-Driven Cases | 14 (6 products, 6 login accounts, 3 social platforms) |
| 🩺 Documented Coverage Gaps | 4 (see QA Notes below) |
| 👤 Executed By | Mujeeb (QA) |

</div>

---

## ⚡ Test Design & Automation Workflow

<div align="center">

```text
 ┌─────────────────────────────┐
 │   Functional Test Matrix    │
 │    (33 documented cases)    │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │   Page Object Model (POM)   │
 │      12 Page Classes        │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │    Selenium WebDriver       │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │   NUnit Execution + Assert  │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │  Status Logged + Gaps Noted │
 └─────────────────────────────┘
```

</div>

---

## 🗂️ Module-Wise Test Case Breakdown

<div align="center">

```text
Cart & Checkout      ████████████████████  9 (27.3%)
Products / Home      ████████████████░░░░  7 (21.2%)
About Page           ████████████████░░░░  7 (21.2%)
Login                ████░░░░░░░░░░░░░░░░  2 ( 6.1%)
Product Detail       ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Book a Demo          ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Social Media Links   ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Sidebar Navigation   ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Logout               ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Learn More           ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Integrations         ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
Sign Up              ██░░░░░░░░░░░░░░░░░░  1 ( 3.0%)
```

</div>

| # | Module | Test Case Prefix | Count | Page Object |
|:-:|:-|:-:|:-:|:-|
| 1 | Login | `TC-LOGIN-XX` | 2 | `LoginPage` |
| 2 | Products / Home | `TC-HOME-XX` | 7 | `HomePage` |
| 3 | Product Detail | `TC-CART-XX` | 1 | `AddToCartPage` |
| 4 | Cart & Checkout | `TC-CO-XX` | 9 | `CheckOutPage` |
| 5 | Book a Demo | `TC-DEMO-XX` | 1 | `DemoPage` |
| 6 | Social Media Links | `TC-SOC-XX` | 1 | `SocialMediaPage` |
| 7 | Sidebar Navigation | `TC-SB-XX` | 1 | `SideBarItems` |
| 8 | Logout | `TC-LO-XX` | 1 | `LogoutPage` |
| 9 | About Page | `TC-ABT-XX` | 7 | `AboutPage` |
| 10 | Learn More | `TC-LM-XX` | 1 | `LearnMorePage` |
| 11 | Integrations | `TC-INT-XX` | 1 | `AboutIntegrationsPage` |
| 12 | Sign Up | `TC-SU-XX` | 1 | `SignUpPage` |

---

## 🎯 Priority Distribution

<div align="center">

```text
High     ███████████░░░░░░░░░  8 (24.2%)
Medium   ████████████████░░░░ 11 (33.3%)
Low      ████████████████████ 14 (42.4%)
```

</div>

High-priority cases sit on the **critical path** — login across all six account types, the full checkout completion flow, blank-field checkout validation, and logout — while Medium covers catalog sorting and cart mechanics, and Low covers the marketing/content pages and supplementary links.

---

## 🤖 Automation Mapping

All 33 test cases are automated using a **Page Object Model (POM)** structure — one class per application page/component, with a matching `*TestCases` class per module:

```yaml
Page Objects:
  ✔ LoginPage
  ✔ HomePage
  ✔ AddToCartPage
  ✔ CheckOutPage
  ✔ SideBarItems
  ✔ LogoutPage
  ✔ AboutPage
  ✔ LearnMorePage
  ✔ AboutIntegrationsPage
  ✔ SignUpPage
  ✔ DemoPage
  ✔ SocialMediaPage

Data-Driven Coverage:
  ✔ 6 SauceDemo account types  (standard, locked-out, problem, performance-glitch, error, visual)
  ✔ 6 catalog products         (name rendering, sort order, Add to Cart / Remove state)
  ✔ 3 social platforms         (Twitter/X, Facebook, LinkedIn)
```

---

## 🩺 QA Notes & Recommended Follow-ups

Part of writing an honest test suite is naming what still needs work. Four items flagged during this pass:

- **Login assertions** — `LoginPage.Login()` currently runs the action steps only, without asserting the resulting page or error text. `locked_out_user` should be treated as a dedicated negative scenario and explicitly checked against its *"Epic sadface: Sorry, this user has been locked out."* message.
- **Error-message verification** — invalid-credential test data is supplied but not yet asserted against the on-screen `[data-test="error"]` element; closing this gap would make the negative-login case fully self-verifying.
- **Test data labeling** — the Add-to-Cart button-text test's data source currently reuses the XML node named for the Remove-button test; worth renaming for clarity.
- **Empty-cart checkout** — the checkout flow currently completes successfully even when the cart is emptied immediately beforehand; flagged for manual confirmation of whether that's intended business logic.

---

## 🚀 Learning Outcomes

This project strengthened my understanding of:

- **Structured test case design** — turning a mixed e-commerce + marketing-site application into a traceable, prioritized test matrix
- **Page Object Model** architecture across 12 page classes, including multi-tab flows (Book a Demo, Sign Up, Integrations, Social links)
- **Data-driven testing** across multiple account types, products, and external platforms
- **Honest QA reporting** — documenting automation coverage gaps as part of the deliverable rather than only reporting green results
- **Negative and boundary testing** — validating blank-field checkout errors and locked-account behavior

---

## 🌍 Real-World Applications

This kind of functional test matrix mirrors QA work commonly done for:

<div align="center">

| 🛒 E-Commerce Checkout Flows | 🔐 Multi-Account Authentication Testing |
|:-:|:-:|
| 📦 Catalog / Inventory Systems | 📚 Marketing & Content Page Validation |
| ☁️ SaaS Regression Suites | 🏢 Enterprise Web Applications |

</div>

---

## 🔮 Future Enhancements

<div align="center">

![Assertions](https://img.shields.io/badge/Assertion_Hardening-Planned-39FF14?style=for-the-badge)
![CI/CD](https://img.shields.io/badge/CI%2FCD_Integration-Planned-00FFF5?style=for-the-badge)
![CrossBrowser](https://img.shields.io/badge/Cross_Browser_Testing-Planned-9B59FF?style=for-the-badge)
![Reporting](https://img.shields.io/badge/Extent_Reporting-Planned-FFC107?style=for-the-badge)

</div>

---

## 🙏 Special Thanks

<div align="center">

### 👨‍💼 [Haris Irfan](https://www.linkedin.com/in/haris-irfan-0b2480209/) — Mentor

![Mentor](https://img.shields.io/badge/Mentor-%E2%9D%A4-red?style=for-the-badge)
![Guidance](https://img.shields.io/badge/Guidance-Invaluable-00C853?style=for-the-badge)

</div>

> *His guidance on structuring a Page Object Model framework — and on treating unverified assertions as a defect, not a detail — shaped how this suite was built.* 🌟

---

## 📌 About the Author

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-mujeeb-ur-rehman)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muj00001.rehman@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MuhammadMujeebUrRehman2003)

</div>

🎯 **SQA / QA Automation Engineer** | Manual & Automation Testing | Page Object Model | Agile QA

🎓 **BS Computer Science** — Mohammad Ali Jinnah University, Karachi *(Feb 2022 – Feb 2026)*

---

```yaml
Achievement:
  ✔ Sauce Demo Functional Test Matrix   — 33 Test Cases, 100% Pass
  ✔ Page Object Model — 12 Page Classes — Implemented
  ✔ Data-Driven Coverage                — Applied
  ✔ Documented Assertion Gaps           — Flagged for hardening
  ✔ Mentor Guidance Received            — Haris Irfan
```

---

<div align="center">

> ### ❝ A test suite that only shows passes isn't finished — it's just not looking hard enough yet. ❞

<br>

![Views](https://komarev.com/ghpvc/?username=MuhammadMujeebUrRehman2003&label=Profile+Views&color=39FF14&style=flat-square)

### ⭐ If this project helped or inspired you, consider starring the repository!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFF5,50:39FF14,100:080C10&height=130&section=footer&text=Tested+with+Precision+·+Documented+with+Honesty&fontSize=22&fontColor=ffffff&animation=fadeIn&fontAlignY=65" />

</div>
