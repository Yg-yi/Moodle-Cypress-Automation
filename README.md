# Moodle LMS End-to-End Automated Testing

This repository contains an automated regression testing suite developed for core Moodle activity modules using the **Cypress** framework. The project aims to validate input handling, functional constraints, and data integrity across key user flows.

---

## 📌 Project Overview
* **Target System**: Moodle LMS (Core Activity & Component Modules)
* **Testing Framework**: Cypress
* **Scope**: Validated **30 core input fields** across **6 functional modules** to ensure system robustness and catch regression errors.

---

## 📂 Tested Modules & Scope
1. **User Authentication**: Login security, session handling, and invalid credential prompts.
2. **Dashboard**: Navigation boundaries and state rendering.
3. **Account Management**: Profile data validation and update flows.
4. **Quiz Module**: Question form inputs and submission validations.
5. **Course Management**: Module creation and input constraints.
6. **Assignment Module**: Submission text fields and file upload bounds.

---

## ⚙️ Tech Stack & Tools
* **Test Automation**: Cypress
* **Environment**: Node.js CLI / JavaScript
* **Version Control**: Git / GitLab / GitHub

---

## 🚀 How to Run the Tests Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yg-yi/Moodle-Cypress-Automation.git
   ```
   
2. **Navigate to the project directory:**
   ```cd moodle-cypress-automation
   ```
   
3. **Install dependencies:**
   ```npm install
   ```
   
4. **Open Cypress Test Runner:**
   ```npx cypress open
   ```
