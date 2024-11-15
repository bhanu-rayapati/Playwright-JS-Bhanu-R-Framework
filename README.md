# Playwright-JS-Bhanu-R-Framework

Welcome to the **Playwright-JS-Bhanu-R-Framework**, a custom-built data-driven testing framework using Playwright and JavaScript. This framework is designed from scratch to provide flexibility, scalability, and efficient test execution for modern web applications.

## 🚀 Features

- **Data-Driven Testing**: 
  - Supports parameterization using **JSON** and **MS-Excel** for robust and reusable test cases.
- **Custom Folder Structure**: 
  - Organized for easy scalability and maintenance.
- **Playwright Best Practices**: 
  - Implements Playwright's API effectively for seamless web automation.
- **Dynamic Test Management**: 
  - Built-in support for dynamic test cases tailored to project needs.
- **Effective Logging**: 
  - Utilizes **Winston logger** for efficient logging and debugging.
- **Flexible Test Data Creation**:
  - Employs **Faker.js** for generating dynamic random test data.

## 🗂️ Folder Structure
Here's the folder structure:
```
📁 Playwright-JS-Bhanu-R-Framework/
│
├── 📁 tests/
│   ├── 📁 e2e/
│   │   ├── module1-tests.spec.js
│   │   └── module2-tests.spec.js
│   └── 📁 api/
│       └── api-tests.spec.js
│
├── 📁 pageobjects/
│   ├── login-page.js
│   ├── module1-page.js
│   └── module2-page.js
│
├── 📁 helpers/
│   ├── database.js
│   ├── excel-reader.js
│   ├── faker.js
│   ├── printandsave.js
│   └── stepmanager.js
│
├── 📁 config/
│   ├── config-1.json
│   ├── config-2.json
│   └── config-3.json
│
├── 📁 locators/
│   ├── module1-locators.js
│   └── module2-locators.js
│
├── 📁 testdata/
│   ├── data.js
│   └── excel-data.xlsx
│
├── 📁 logs/
│   ├── winston-logger.js
│   └── logfile.log
│
├── 📁 reports/
│   ├── 📁 allure-results/
│   └── 📁 allure-report/
│       └── report.html
│
├── 📁 utilities/
│   └── 📁 autoit/
│       ├── clickenter
│       ├── saveprintoutputas
│       └── setdefaultprinter
│
├── 📁 test-output/
│   ├── 📁 screenshots/
│   └── 📁 saved-passes/
│
├── package.json
└── playwright.config.js
```


## 📅 Upcoming Updates

I plan to commit the complete code soon after altering project-specific sensitive data. Stay tuned for the full implementation.

## 📜 Prerequisites

- **Node.js** (v16 or higher)
- **Playwright** (latest version)
- **MS Excel Parser** (e.g., `xlsx` npm package)
- **Additional dependencies** (to be specified in `package.json`)

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Playwright-JS-Bhanu-R-Framework.git


