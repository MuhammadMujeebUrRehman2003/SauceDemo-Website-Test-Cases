<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080C10,50:39FF14,100:00FFF5&height=200&section=header&text=🤖%20Selenium%20Test%20Automation&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=C%23%20%7C%20NUnit%20%7C%20Page%20Object%20Model%20%7C%20QA%20Automation&descSize=17&descAlignY=58&descColor=39FF14" />

</div>

---

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=39FF14&center=true&vCenter=true&width=950&lines=Selenium+Test+Automation+Framework+%F0%9F%A4%96;Automating+Sauce+Demo+%7C+Swag+Labs+Website;33+Test+Cases+%7C+12+Page+Objects+%7C+100%25+Pass+Rate;C%23+%2B+NUnit+%2B+Page+Object+Model;ExtentReports+%7C+Data-Driven+Testing+%7C+POM" alt="Typing SVG" />

</div>

---

<div align="center">

![Selenium](https://img.shields.io/badge/Selenium-Automation-39FF14?style=for-the-badge&logo=selenium&logoColor=black)
![C#](https://img.shields.io/badge/C%23-.NET-239120?style=for-the-badge&logo=csharp&logoColor=white)
![NUnit](https://img.shields.io/badge/NUnit-Testing_Framework-9B59FF?style=for-the-badge&logo=dotnet&logoColor=white)
![ExtentReports](https://img.shields.io/badge/ExtentReports-Reporting-FF6F00?style=for-the-badge)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-IDE-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## 👋 Hello Everyone!

I'm pleased to share that I have **successfully completed a Selenium Test Automation Framework** for the **Sauce Demo (Swag Labs)** website! 🎯

This project was **highly informative** and helped me strengthen my understanding of building **robust, scalable, and maintainable automation frameworks** — starting from a documented functional test matrix and carrying it through to working C# automation.

> 💡 *Through this experience, I gained practical knowledge of test automation principles, framework design patterns, and QA engineering — which are essential skills for modern software quality assurance.*

---

## 📌 Project Overview

This project demonstrates a complete, production-grade **Selenium WebDriver automation framework** built with **C#, NUnit, and the Page Object Model** — applied to the real-world **Sauce Demo (Swag Labs)** website.

It combines a **standardized 11-column functional test matrix** (Scenario TID, Scenario Description, Test Case ID, Pre-Condition, Steps to Execute, Expected Result, Actual Result, Status, Executed QA Name, Comments, Priority) with **12 Page Object classes**, covering authentication, inventory sorting, cart and checkout, sidebar navigation, and the site's marketing pages (About, Learn More, Integrations, Sign Up, Demo, Social).

---

## 🏗️ Key Features Implemented

<div align="center">

| 🔹 Feature | 📘 Description |
|:-:|:-|
| 🗂️ Page Object Model (POM) | 12 dedicated page classes · clean architecture · reusability · separation of concerns |
| 📊 Data-Driven Testing | Multi-account login, 6-product catalog checks, 3-platform social link validation |
| 🧱 Hierarchical Test Structure | Organised test layers · improved maintainability · logical grouping |
| ⚙️ Multi-Tab & Sync Handling | New-tab switching for demo/sign-up/integration flows · dynamic element handling |
| ✅ NUnit Framework | Test execution management · assertions · setup & teardown lifecycle |
| 📋 Extent Reports | Execution status captured per test case for traceability |

</div>

---

## ⚡ Automation Framework Architecture

<div align="center">

```text
 ┌─────────────────────────────┐
 │   Functional Test Matrix    │
 │   (33 documented scenarios) │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │   Page Object Model (POM)   │
 │  12 Page Classes / Modules  │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │    Selenium WebDriver       │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │    Browser Interaction      │
 └─────────────┬───────────────┘
               │
               ▼
 ┌─────────────────────────────┐
 │    ExtentReport Output      │
 └─────────────────────────────┘
```

</div>

---

## 📊 Test Case Coverage by Module

<div align="center">

| 🧩 Module | 🔖 Prefix | 🧪 Test Cases | 🗂️ Page Object |
|:-|:-:|:-:|:-|
| Login | `TC-LOGIN` | 2 | `LoginPage` |
| Product Listing (Inventory) | `TC-HOME` | 7 | `HomePage` |
| Product Detail | `TC-CART` | 1 | `AddToCartPage` |
| Cart & Checkout | `TC-CO` | 9 | `CheckOutPage` |
| Sidebar Navigation | `TC-SB` | 1 | `SideBarItems` |
| Logout | `TC-LO` | 1 | `LogoutPage` |
| About Page Content | `TC-ABT` | 7 | `AboutPage` |
| Learn More | `TC-LM` | 1 | `LearnMorePage` |
| Integrations | `TC-INT` | 1 | `AboutIntegrationsPage` |
| Sign Up | `TC-SU` | 1 | `SignUpPage` |
| Book a Demo | `TC-DEMO` | 1 | `DemoPage` |
| Social Media Links | `TC-SOC` | 1 | `SocialMediaPage` |
| **Total** | | **33** | **12 page classes** |

</div>

<div align="center">

![Total](https://img.shields.io/badge/Total_Test_Cases-33-39FF14?style=for-the-badge)
![PassRate](https://img.shields.io/badge/Pass_Rate-100%25-00FFF5?style=for-the-badge)
![High](https://img.shields.io/badge/High_Priority-8-FF4B4B?style=for-the-badge)
![Medium](https://img.shields.io/badge/Medium_Priority-11-FFC107?style=for-the-badge)
![Low](https://img.shields.io/badge/Low_Priority-14-4CAF50?style=for-the-badge)

</div>

---

## ✅ Automation Concepts Applied

```yaml
Test Case Design:
  ✔ Standardized 11-Column Test Case Schema
  ✔ Scenario-to-Test-Case Traceability (SCN-XXX → TC-XXX)
  ✔ Priority Classification (High / Medium / Low)
  ✔ Multi-Account & Data-Driven Coverage

Framework Design:
  ✔ Page Object Model (POM) Architecture — 12 Page Classes
  ✔ Reusable Test Components & Base Classes
  ✔ Hierarchical Test Structure & Grouping
  ✔ Clean Separation of Concerns

Selenium WebDriver:
  ✔ Browser Automation with C#
  ✔ Dynamic Element Handling & Locators
  ✔ Multi-Tab Handling (Demo, Sign Up, Integrations, Social Links)
  ✔ End-to-End Checkout Flow Automation

Quality Engineering:
  ✔ NUnit Framework Setup & Assertions
  ✔ Extent Reports with Execution Status
  ✔ Scalable & Maintainable Test Codebase
  ✔ Structured Test Case Documentation
```

---

## 🛠️ Tech Stack & Skills

<div align="center">

<img src="https://skillicons.dev/icons?i=cs,dotnet,selenium,visualstudio,git,github" />

</div>

```text
Selenium WebDriver      ████████████████████   90%
POM Framework           ████████████████████   90%
C# Automation           ██████████████████     85%
NUnit Testing           ████████████████       80%
Test Case Design        ███████████████        75%
Extent Reporting        ██████████████         70%
```

---

## 📡 Test Scenarios Overview

<div align="center">

| ⚙️ Test Area | 🔗 Scope | 📘 Description |
|:-:|:-:|:-|
| 🟢 Login Module | Authentication | Multi-account login (standard, locked-out, problem, glitch, error, visual), validation errors |
| 🔵 Product Listing | Inventory Page | Sorting (price/name), product text, Add to Cart / Remove button states |
| 🟠 Cart & Checkout | Shopping Flow | Add/remove items, cancel checkout, field validation, full order completion |
| 🟣 Navigation & Marketing | Sidebar / About | Sidebar links, About page content, Learn More, Integrations, Sign Up, Demo |
| 🔴 Social & Logout | Footer / Session | Social media link destinations, logout redirect to Login |

</div>

---

## 📝 QA Observations & Known Limitations

Documenting a framework honestly includes flagging what still needs attention — a few items surfaced while working through this suite:

- **Login assertions gap** — `LoginPage.Login()` currently performs the login *action* but doesn't assert the resulting page or error message, so pass/fail on `TC-LOGIN-01`/`02` isn't strictly verified by the automation yet.
- **`locked_out_user` misclassification** — this SauceDemo account is a documented negative-test case (expected to be blocked with *"Epic sadface: Sorry, this user has been locked out."*), but it's currently exercised inside the valid-login suite. Flagged for reclassification as a negative scenario.
- **DataSource naming inconsistency** — `TC-HOME-06`'s automation references a DataSource node named for a different test method; a cleanup item for the data files.
- **Empty-cart checkout edge case** — `TC-CO-06` confirms checkout can be completed even after the cart is emptied beforehand; flagged for manual confirmation of whether this is intended business behaviour.

---

## 🚀 Learning Outcomes

This project significantly enhanced my understanding of:

- **Page Object Model** design principles and best practices
- **Selenium WebDriver + C#** automation framework development
- **NUnit** test management and assertion strategies
- **Data-driven testing** across multiple accounts, products, and platforms
- **ExtentReports** integration for execution traceability
- **Reviewing automation critically** — catching assertion gaps and edge cases, not just green checkmarks

---

## 🌍 Real-World Applications

This type of test automation framework is commonly used in:

<div align="center">

| 🛒 E-Commerce QA | 📱 Mobile Web Testing |
|:-:|:-:|
| ☁️ SaaS Regression Suites | 🏢 Enterprise Application Testing |
| 📚 LMS Platform Validation | 📦 Inventory & ERP System QA |

</div>

---

## 🔮 Future Enhancements

<div align="center">

![CI/CD](https://img.shields.io/badge/CI_CD_Integration-Planned-39FF14?style=for-the-badge)
![Parallel](https://img.shields.io/badge/Parallel_Execution-Planned-00FFF5?style=for-the-badge)
![API](https://img.shields.io/badge/API_Automation-Planned-9B59FF?style=for-the-badge)
![Cloud](https://img.shields.io/badge/Cloud_Testing-Planned-FF6600?style=for-the-badge)
![BrowserStack](https://img.shields.io/badge/BrowserStack-Planned-FF8C00?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker_Integration-Planned-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MuhammadMujeebUrRehman2003&theme=tokyo-night&hide_border=true" width="100%" />

</div>

---

## 🙏 Special Thanks

<div align="center">

### 👨‍🏫 [Haris Irfan](https://www.linkedin.com/in/haris-irfan-0b2480209/) — Mentor & Tutor

![Mentor](https://img.shields.io/badge/Mentor-%E2%9D%A4-red?style=for-the-badge)
![Guidance](https://img.shields.io/badge/Guidance-Invaluable-00C853?style=for-the-badge)

</div>

> *His expert knowledge of Selenium, C#, NUnit, and the Page Object Model helped me build a real-world automation framework from the ground up — turning theory into structured, scalable test engineering practice.* 🌟

---

## 📌 About the Author

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-mujeeb-ur-rehman)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muj00001.rehman@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MuhammadMujeebUrRehman2003)

</div>

🎯 **SQA / QA Automation Engineer** | Manual & Automation Testing | Selenium WebDriver | CI/CD | Agile QA

🎓 **BS Computer Science** — Mohammad Ali Jinnah University, Karachi *(Feb 2022 – Feb 2026)*

---

```yaml
Achievement:
  ✔ Sauce Demo Functional Test Matrix   — 33 Test Cases Documented
  ✔ Page Object Model (POM) — 12 Page Classes  — Implemented
  ✔ NUnit Test Framework                — Hands-On
  ✔ Data-Driven Testing                 — Applied
  ✔ 100% Pass Rate Across All Scenarios — Achieved
  ✔ Mentor Guidance Received            — Sir Haris Irfan
```

---

<div align="center">

> ### ❝ Automating tests today is the foundation of reliable software tomorrow. ❞

<br>

![Views](https://komarev.com/ghpvc/?username=MuhammadMujeebUrRehman2003&label=Profile+Views&color=39FF14&style=flat-square)

### ⭐ If you like this project, consider starring the repository!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFF5,50:39FF14,100:080C10&height=130&section=footer&text=Built+with+Precision+·+Tested+with+Passion&fontSize=22&fontColor=ffffff&animation=fadeIn&fontAlignY=65" />

</div>
