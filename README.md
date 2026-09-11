<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080C10,50:39FF14,100:00FFF5&height=200&section=header&text=🛒%20Sauce%20Demo%20Test%20Automation&fontSize=32&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=C%23%20%7C%20NUnit%20%7C%20Page%20Object%20Model%20%7C%20QA%20Automation&descSize=17&descAlignY=58&descColor=39FF14" />

</div>

---

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=39FF14&center=true&vCenter=true&width=950&lines=Sauce+Demo+(Swag+Labs)+Functional+Test+Suite+%F0%9F%A4%96;33+Test+Cases+%7C+12+Modules+%7C+100%25+Pass+Rate;C%23+%2B+NUnit+%2B+Page+Object+Model;Data-Driven+Testing+%7C+ExtentReports+%7C+POM;Login+%7C+Cart+%26+Checkout+%7C+Marketing+Pages" alt="Typing SVG" />

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

I'm pleased to share my **Sauce Demo (Swag Labs) Functional Test Automation** project! 🎯

This project covers **33 documented test scenarios across 12 modules** of the [Sauce Demo](https://www.saucedemo.com/) site — from the classic login/cart/checkout e-commerce flow through to its newer marketing and content pages — automated with a **C# + NUnit + Page Object Model** framework.

> 💡 *Beyond automating the happy path, this suite documents real engineering trade-offs found along the way — including a couple of assertion gaps worth fixing — which I've captured directly in the test notes rather than glossing over.*

---

## 📌 Project Overview

This project demonstrates a complete, production-style **Selenium WebDriver automation framework** built with **C#, NUnit, and the Page Object Model**, applied to the **Sauce Demo (Swag Labs)** website.

Each of the 33 documented scenarios is tracked through a **standardized 11-column test case schema** (Scenario TID, Scenario Description, Test Case ID, Pre-Condition, Steps to Execute, Expected Result, Actual Result, Status, Executed QA Name, Comments, Priority) and mapped 1:1 to a Page Object method, covering authentication, product catalog behaviour, cart/checkout logic, navigation, and the site's marketing/content pages.

---

## 🏗️ Key Features Implemented

<div align="center">

| 🔹 Feature | 📘 Description |
|:-:|:-|
| 🗂️ Page Object Model (POM) | 12 page classes (LoginPage, HomePage, CheckOutPage, AboutPage, etc.) · clean separation of test logic and locators |
| 📊 Data-Driven Testing | Product-list and multi-account scenarios parameterised across all 6 catalog products / 6 login account types |
| 🧱 Structured Test Case Design | 33 scenarios analysed and documented before automation · positive, negative & functional coverage |
| ✅ NUnit Framework | Test execution management, assertions, setup & teardown lifecycle |
| 📋 Extent Reports | Execution status captured per test case for traceability |
| 🩺 Honest QA Notes | Gaps in current assertion coverage documented directly in the test matrix, not hidden |

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
| Products / Home | `TC-HOME` | 7 | `HomePage` |
| Product Detail | `TC-CART` | 1 | `AddToCartPage` |
| Cart & Checkout | `TC-CO` | 9 | `CheckOutPage` |
| Book a Demo | `TC-DEMO` | 1 | `DemoPage` |
| Social Media Links | `TC-SOC` | 1 | `SocialMediaPage` |
| Sidebar Navigation | `TC-SB` | 1 | `SideBarItems` |
| Logout | `TC-LO` | 1 | `LogoutPage` |
| About Page | `TC-ABT` | 7 | `AboutPage` |
| Learn More | `TC-LM` | 1 | `LearnMorePage` |
| Integrations | `TC-INT` | 1 | `AboutIntegrationsPage` |
| Sign Up | `TC-SU` | 1 | `SignUpPage` |
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
  ✔ Positive, Negative & Functional Scenario Coverage

Framework Design:
  ✔ Page Object Model (POM) Architecture — 12 Page Classes
  ✔ Reusable Test Components & Base Classes
  ✔ Data-Driven Execution (6 login accounts, 6 catalog products, 3 social platforms)
  ✔ Clean Separation of Concerns

Selenium WebDriver:
  ✔ Browser Automation with C#
  ✔ New-Tab / Multi-Window Handling (Book a Demo, Sign Up, Social Links, Integrations)
  ✔ Dynamic Element Handling & Locators

Testing:
  ✔ NUnit Framework Setup & Assertions
  ✔ Test Lifecycle Management (Setup/Teardown)
  ✔ Extent Reports with Execution Status
  ✔ Gap Analysis — documented assertion coverage limitations for future hardening
```

---

## 🛠️ Tech Stack & Skills

<div align="center">

<img src="https://skillicons.dev/icons?i=cs,dotnet,selenium,visualstudio,git,github" />

</div>

```text
Selenium WebDriver      ████████████████████   90%
Page Object Model       ████████████████████   90%
C# Automation           ██████████████████     85%
Test Case Design        ██████████████████     85%
NUnit Testing           █████████████████      80%
Extent Reporting        ██████████████         70%
```

---

## 📡 Test Scenarios Overview

<div align="center">

| ⚙️ Test Area | 🔗 Scope | 📘 Description |
|:-:|:-:|:-|
| 🟢 Login Module | Authentication | All 6 SauceDemo account types, invalid/blank credential validation |
| 🔵 Product Catalog | Products (Home) Page | Sorting (price/name asc-desc), product listing, Add to Cart / Remove button states |
| 🟠 Cart & Checkout | Shopping Cart | Add/remove items, cancel checkout, full order completion, field-level validation errors |
| 🟣 Navigation & Session | Sidebar / Logout | Sidebar menu links, logout-and-return-to-login flow |
| 🔴 Marketing & Content | About / Learn More / Integrations / Sign Up / Demo / Social | Headings, button text, and new-tab destinations across the site's content pages |

</div>

---

## 🌐 Modules Covered

- **Login** — all six SauceDemo test accounts (standard, locked-out, problem, performance-glitch, error, visual), invalid-credential and blank-field validation
- **Products / Home** — product name rendering, 4-way sorting (price/name, ascending/descending), Add to Cart ↔ Remove button state toggling across all 6 products
- **Product Detail** — locating and opening each catalog product from the inventory list
- **Cart & Checkout** — add/remove from cart, Continue Shopping, cancel checkout, full order completion, empty-cart edge case, First Name / Last Name / Postal Code validation
- **Sidebar Navigation & Logout** — hamburger menu, "All Items" link, logout back to the Login page
- **About Page** — main title, tagline, header links, close/cross banner behaviour, Sign Up and Book a Demo button text
- **Learn More / Integrations / Sign Up / Book a Demo** — new-tab destinations and headings for each outbound content page
- **Social Media Links** — Twitter/X, Facebook, and LinkedIn icons opening the correct external domain

---

## 🩺 QA Notes & Recommended Follow-ups

Documenting gaps honestly is part of the process — a few items flagged during this pass for future hardening:

- **Login assertions** — `LoginPage.Login()` currently performs the action steps only, without asserting the resulting page or error message. `locked_out_user` in particular should be treated as a negative scenario and explicitly blocked with its "Epic sadface" message.
- **Error message verification** — the invalid-credential test data isn't yet checked against the on-screen `[data-test="error"]` element; an explicit assertion would close this gap.
- **Test data wiring** — the Add-to-Cart button-text test currently reuses a `[DataSource]` node named for the Remove-button test; worth renaming for clarity.
- **Empty-cart checkout** — checkout currently completes even if the cart is emptied right before proceeding; flagged for manual confirmation of intended business logic.

---

## 🚀 Learning Outcomes

This project significantly enhanced my understanding of:

- **Structured test case analysis** — translating a mixed e-commerce + marketing-site application into a traceable, prioritised scenario matrix
- **Page Object Model** design across 12 distinct page classes, including multi-tab flows
- **Data-driven testing** across multiple account types, products, and social platforms
- **NUnit** test management, assertions, and lifecycle handling
- **Honest test reporting** — documenting automation coverage gaps as part of the deliverable, not just green checkmarks
- **ExtentReports** integration for execution traceability

---

## 🌍 Real-World Applications

This type of test automation approach is commonly used in:

<div align="center">

| 🛒 E-Commerce QA | 📱 Web Application Testing |
|:-:|:-:|
| ☁️ SaaS Regression Suites | 🏢 Enterprise Application Testing |
| 📚 Content/Marketing Site Validation | 📦 Multi-Account Auth Testing |

</div>

---

## 🔮 Future Enhancements

<div align="center">

![CI/CD](https://img.shields.io/badge/CI_CD_Integration-Planned-39FF14?style=for-the-badge)
![Parallel](https://img.shields.io/badge/Parallel_Execution-Planned-00FFF5?style=for-the-badge)
![Assertions](https://img.shields.io/badge/Assertion_Hardening-Planned-9B59FF?style=for-the-badge)
![CrossBrowser](https://img.shields.io/badge/Cross_Browser_Testing-Planned-FF6600?style=for-the-badge)

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
  ✔ Sauce Demo Functional Test Matrix          — 33 Test Cases Documented
  ✔ Page Object Model (POM) — 12 Page Classes  — Implemented
  ✔ C# + NUnit Automation Suite                — Hands-On
  ✔ Data-Driven Testing                        — Applied
  ✔ 100% Pass Rate Across All Scenarios        — Achieved
  ✔ Mentor Guidance Received                   — Sir Haris Irfan
```

---

<div align="center">

> ### ❝ A well-documented test case is the blueprint every automated script should follow. ❞

<br>

![Views](https://komarev.com/ghpvc/?username=MuhammadMujeebUrRehman2003&label=Profile+Views&color=39FF14&style=flat-square)

### ⭐ If you like this project, consider starring the repository!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFF5,50:39FF14,100:080C10&height=130&section=footer&text=Built+with+Precision+·+Tested+with+Passion&fontSize=22&fontColor=ffffff&animation=fadeIn&fontAlignY=65" />

</div>
