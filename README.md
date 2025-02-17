# Selenium_Project
Overview

This project automates various web interactions using Selenium WebDriver, including:

Login and Logout

Handling Popups and Alerts

Interacting with Checkboxes and Dropdowns

# Prerequisites
Ensure you have the following installed:

Python (>=3.x)

Selenium WebDriver

ChromeDriver (or appropriate driver for your browser)

Required dependencies from requirements.txt

Installation

Clone the repository:

git clone https://github.com/your-repo/selenium-automation.git
cd selenium-automation

Install dependencies:

pip install -r requirements.txt

Project Structure

selenium-automation/
│-- tests/
│   ├── test_login.py
│   ├── test_logout.py
│   ├── test_popups.py
│   ├── test_alerts.py
│   ├── test_checkboxes.py
│   ├── test_dropdowns.py
│-- drivers/
│-- utils/
│   ├── config.py
│   ├── base_test.py
│-- README.md

Features

1. Login and Logout

Automates user login and logout functionality.

Uses valid credentials stored in a configuration file.

2. Handling Popups and Alerts

Detects and interacts with JavaScript popups and alerts.

Handles confirmation alerts (accept/dismiss).

3. Working with Checkboxes

Selects and deselects checkboxes.

Validates selection state.

4. Handling Dropdowns

Selects options from dropdown menus.

Works with both static and dynamic dropdowns.

Running Tests
