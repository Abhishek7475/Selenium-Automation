Automated User Creation and Login Flow with Selenium

This repository contains a Python script that automates the process of bulk user creation, login, and initial setup for a web application using Selenium WebDriver.

Features

- Bulk User Creation: Automates the creation of multiple users (stress_1 to stress_500) through a web-based admin interface.
- Automated Login: Logs in as each newly created user using the generated credentials.
- Password Management: Captures system-generated passwords and updates them to a predefined password.
- Security Setup: Automatically sets security questions and answers for each user.
- DOB and Profile Setup: Fills in required profile fields like date of birth.
- Robust Waiting: Utilizes explicit waits for reliable element interaction.

Use Cases

- Stress testing user creation and login workflows.
- Automating repetitive QA tasks for web applications.
- Populating test environments with bulk users.

Technologies Used

- Python
- Selenium WebDriver
- ChromeDriver

Getting Started

1. Install dependencies:
   pip install selenium
2. Update user credentials and URLs as needed in the script.
3. Run the script:
   python your_script.py

Notes

- Ensure ChromeDriver is installed and added to your PATH.
- Update element locators if your web application UI changes.

