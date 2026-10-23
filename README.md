# 🚀 CipherFlow — Enterprise Playwright & BDD Starter Kit

> **Save 40+ hours of framework setup.** A production-ready TypeScript test automation framework engineered for Senior SDETs, QA Leads, and Enterprise Engineering Teams.

---

### 📦 Get the Full Production Package
[![Buy on Gumroad](https://img.shields.io/badge/Buy_Full_Kit-Gumroad-FF90E8?style=for-the-badge&logo=gumroad)](YOUR_GUMROAD_PRODUCT_LINK_HERE)

> **License:** Commercial (Use across unlimited personal & team projects)

---

## 🎯 What's Included in the Full Kit?

- **Dual-Mode BDD Architecture:** Native `playwright-bdd` setup. Write plain-English Gherkin `.feature` files that run at full Playwright multi-worker speed.
- **Strict TypeScript & POM:** Clean Page Object Models with strict typing to prevent fragile selectors and test flakiness.
- **CI/CD Automation Matrix:** Pre-configured GitHub Actions workflow for parallel test runs and automatic artifact capture.
- **Enterprise Reporting:** Built-in HTML reports, video recordings, and trace viewer configs on failure.

---

## 📁 Repository Structure Preview

```text
cipherflow-playwright-starter/
├── src/
│   ├── pages/                   # Typed Page Object Models (POM)
│   │   ├── LoginPage.ts
│   │   └── DashboardPage.ts
│   ├── tests/                   # Native Spec Files
│   │   └── login.spec.ts
│   └── bdd/                     # BDD / Gherkin Module
│       ├── features/            # .feature Files
│       │   └── login.feature
│       └── steps/               # Step Definitions
│           └── login.steps.ts
├── .github/workflows/           # GitHub Actions CI Matrix
│   └── test-pipeline.yml
├── playwright.config.ts         # Multi-worker Playwright Config
└── bdd.config.ts                # BDD Compiler & Runner Config
# cipherflow-playwright-starter-preview



⚡ Quickstart Preview
# 1. Install dependencies
npm install

# 2. Run standard Playwright tests
npx playwright test

# 3. Run BDD Gherkin scenarios in parallel
npm run bdd


### 💳 [Get Instant Access to the Full .zip Package on Gumroad](https://cipherflow0.gumroad.com/l/oeggat?wanted=true)

