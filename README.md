# 🚀 Python Playwright Automation Suite

[![Build Status](https://github.com/galmatalon/python-playwright/actions/workflows/playwright-ci.yml/badge.svg)](https://github.com/galmatalon/python-playwright/actions)
[![Coverage Status](https://coveralls.io/repos/github/galmatalon/python-playwright/badge.svg)](https://coveralls.io/github/galmatalon/python-playwright)
[![Allure Report](https://img.shields.io/badge/Allure-Report-blue)](https://galmatalon.github.io/python-playwright/allure-report/)

A modern, robust end-to-end testing framework using Python and Playwright - delivering reliable, multi-browser test automation with interactive Allure reports.

---

## 🎯 Project Snapshot

A futuristic-themed banner summarizing success on the tested site, combining glowing technology visuals with the target application - symbolizing reliability, speed, and achievement.

---

## 🔍 Project Overview

This test suite leverages Python with Playwright to automate comprehensive browser testing across Chromium, Firefox, and WebKit. It integrates seamlessly with GitHub Actions and uses Allure to generate insightful and interactive HTML reports.

---

## 🎯 Purpose

- Validate critical user journeys on your web application  
- Ensure consistent cross-browser behavior  
- Deliver detailed insights into test outcomes via visual, step-by-step reporting

---

## 🛠️ Technologies Used

- **Python 3.9+**
- **Playwright for Python** - cross-browser automation
- **pytest** - test runner
- **allure-pytest** - enhanced reporting
- **GitHub Actions** - CI/CD orchestration  
- **Coveralls** - code coverage tracking  

---

## 📦 Installation & Usage

Clone the repo and install requirements:
```bash
git clone https://github.com/galmatalon/python-playwright.git
cd python-playwright
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Run tests locally:
```bash
pytest --alluredir=allure-results
allure serve allure-results
```

Browse the live Allure report:  
➡️ https://galmatalon.github.io/python-playwright/allure-report/

---

## 📂 Project Structure

```
├── tests/                 # Playwright test scripts (multi-browser configs)
├── pages/                 # Page Object Model abstractions
├── allure-results/        # Raw results for HTML report generation
├── playwright.config.py   # Configuration (reporters, browsers, retries)
├── requirements.txt       # All dependencies
└── .github/workflows/     # CI config for GitHub Actions
```

---

## ✅ What Does It Test?

- Multi-browser navigation across Chromium, Firefox, WebKit  
- User interactions: form inputs, button clicks, navigation flows  
- Assertions on UI components, content presence, and accessibility  
- Integration with Allure: screenshots, step logging, environment metadata

---

## 📊 CI & Reporting

- **GitHub Actions** runs tests on every push and PR  
- **Build status**: visible via badge  
- **Coverage**: monitored using Coveralls  
- **Allure Report**: deployed via GitHub Pages - includes interactive charts, history trends, and attached screenshots  
- View the live report: https://galmatalon.github.io/python-playwright/allure-report/

<!-- include an actual screenshot of the Allure report here -->
![Allure Dashboard](https://galmatalon.github.io/python-playwright/assets/allure-snapshot.png)

---

## 🧩 Strengths & Highlights

- ✅ **Cross-browser consistency** across 3 major engines  
- ✅ **Rich, interactive test insights** (steps, attachments, history)  
- ✅ **Fully CI/CD-integrated** with clean automation flow  
- ✅ **Modular codebase** following page object pattern  
- ✅ **Readable & maintainable test structure** - easy to extend and adapt

---

## ⚙️ Configuration & Customization

- Set browser retry limits and headless/mode in `playwright.config.py`  
- Customize Allure meta-data (owner, severity, links) via pytest fixtures  
- Extend Page Objects under `pages/` to adapt to new app functionality

---

## 📢 Get Involved

⭐ If you like this project, give it a star!  
✉️ Submit issues, feature requests, or ideas  
📬 Contribute via PRs - your help is welcome!  
📣 Send me feedback or questions - always glad to connect.

---

## 📎 Links & Contacts

- 🔗 **LinkedIn**: [Gal Matalon](https://www.linkedin.com/in/gal-matalon/)  
- 📚 **Automation School**: [automation.co.il](https://automation.co.il/)  
- 🌐 **Demo & Allure Report**: [Live Report](https://galmatalon.github.io/python-playwright/allure-report/)

---

## 📜 License

This project is released under the **MIT License**. See `LICENSE` for details.

---

## 🧭 What's Next?

- Add mobile viewport testing and visualize results  
- Explore parallel test execution for speed improvements  
- Integrate with bug-tracking systems (Jira/TMS links in Allure)  
- Enhance coverage metrics and add reporting to Coveralls directly

---

> “Building reliable, maintainable automation is key to accelerating delivery and ensuring quality. This project demonstrates that ambition.” 🚀
