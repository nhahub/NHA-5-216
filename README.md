# NHA-5-216
Project Proposal Template
Project: Automated UI Testing for an E-Commerce Website
Objective: To write a clean, maintainable, and automated suite of UI tests for the key user journeys of a public e-commerce website.
Description: Using Selenium WebDriver, we will develop automated test scripts to verify the functionality of a live e-commerce website. The project focuses on core testing skills: identifying user flows, writing scripts, adding verifications (assertions), and structuring the code for reusability.
Tools & Design: Selenium WebDriver for browser automation, a Page Object Model (POM) design to separate UI locators from test logic, and a structured test suite for organized execution and reporting.
Technologies to Use: Selenium WebDriver, Test Case Development, and Python as the programming language.
Team Members & Responsibilities:
Reham Hesham Roshdy Mohamed – Test Environment & Login/Checkout Flow Lead: sets up the Selenium environment, selects the target website, and leads automation of the login and checkout journeys.
Mai Ramadan Mahmoud Ahmed – Test Case Design & Assertions Lead: writes manual test cases, implements the product search/add-to-cart automation, and adds detailed assertions across all scripts.
Amr Abdelhamed Mohamed – Framework & Reporting Lead: manages waits/test data stability, leads the Page Object Model refactor, organizes the test suite, and prepares the final summary report.
Week 1: Environment Setup and First Test Script
Install Selenium WebDriver and the appropriate browser driver (e.g., ChromeDriver) — Reham
Select a target public e-commerce demo website (e.g., Sauce Labs "Swag Labs") — Reham
Write the first test script to open the homepage and verify the page title — Mai
Create the basic project folder structure to organize test scripts — Amr
Review and validate that the environment runs successfully — All members
Deliverables:
A working local environment where Selenium tests can run.
A single, successful test script that launches a browser and performs a simple check.
A document identifying the target website for the project.
Week 2: Automating Core User Journeys
Write manual test cases for the login and search/add-to-cart journeys — Mai
Automate the login user journey with a Selenium script — Reham
Automate the product search and add-to-cart user journey — Mai
Implement Selenium waits to ensure scripts run reliably — Amr
Test and debug all scripts as a team — All members
Deliverables:
An automated test script for the user login process.
An automated test script for searching for and adding an item to the cart.
Test scripts that run reliably without random timing-related failures.
Week 3: Testing the Checkout Flow and Using Assertions
Automate the checkout process: cart verification and dummy checkout details — Reham
Add detailed assertions to all test scripts (e.g., cart item counter) — Mai
Handle and manage test data such as usernames and passwords — Amr
Cross-check assertions and checkout flow together — All members
Deliverables:
A complete, automated test script for the checkout flow.
All test scripts updated with clear pass/fail conditions using assertions.
Week 4: Code Refactoring and Final Reporting
Refactor scripts using the Page Object Model (POM) design pattern — Amr
Organize all tests into a single, runnable test suite — Amr
Execute the full test suite and analyze results — Reham
Write the final summary report covering tests, coverage, and results — Mai
Deliverables:
Fully refactored test code organized using the Page Object Model.
A final summary report detailing the project's test coverage and outcomes.
A clean, maintainable, and well-documented testing project.
