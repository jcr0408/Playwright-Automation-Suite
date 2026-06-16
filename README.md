Playwright-Automation-Suite
A robust, end-to-end (E2E) automation testing suite built with Playwright and TypeScript. This project demonstrates professional-grade QA practices by automating critical user workflows for [Insert Website Name Here, e.g., SauceDemo].

🚀 Technical Highlights
Architecture: Implemented the Page Object Model (POM) to ensure modularity and high reusability of selectors and methods.

Reliability: Utilized Playwright’s auto-waiting features to eliminate flaky tests and race conditions.

Efficiency: Configured parallel test execution to significantly reduce the total regression suite run time.

Debugging: Integrated Playwright Trace Viewer to provide detailed post-failure analysis including DOM snapshots, network logs, and video recordings.

Cross-Browser Support: Validated core functionality across Chromium, Firefox, and WebKit.

🛠 Tech Stack
Framework: Playwright

Language: TypeScript

Assertion Library: Playwright Test

Reporting: Allure / Playwright HTML Reporter

📋 Test Scenarios
This suite covers 10 critical test cases:

Authentication: Successful login, invalid credentials handling, and logout flow.

Product Management: Sorting items, filtering, and verifying product details.

Checkout Flow: Adding items to the cart, verifying cart totals, and completing the checkout process.

Negative/Edge Cases: Handling empty cart scenarios and input validation.

🏃‍♂️ Getting Started
Prerequisites
Node.js (LTS version)

Installation
Bash
# Clone the repository
git clone https://github.com/jcr0408/Playwright-Automation-Suite.git

# Install dependencies
npm install

# Run tests
npx playwright test

# Demonstration
🎥 Demonstration
