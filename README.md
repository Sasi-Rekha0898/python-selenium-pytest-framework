# Python Selenium PyTest Automation Framework

## Overview

This project is a Selenium Automation Framework developed using Python and PyTest.

The framework is designed using Page Object Model (POM) and supports UI automation, reporting, reusable utilities, and CI/CD integration using GitHub Actions.

---

## Tech Stack

* Python
* Selenium WebDriver
* PyTest
* Allure Reports
* GitHub Actions
* Page Object Model (POM)

---

## Framework Features

* UI Automation Testing
* Page Object Model Design
* Reusable Utility Functions
* HTML / Allure Reporting
* Screenshot Capture on Failure
* CI/CD Integration
* API Mock Validation

---

## Project Structure

```bash
project/
│
├── .github/workflows/
├── config/
├── pages/
├── tests/
├── utils/
├── Screenshots/
│
├── pytest.ini
├── requirements.txt
└── students.json
```

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run Tests

```bash
pytest
```

---

## Generate Allure Report

```bash
allure serve allure-results
```

---

## CI/CD Integration

GitHub Actions is integrated to automatically run tests during code push.

---

## Author

Sasi Rekha
