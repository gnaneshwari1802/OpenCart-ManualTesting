# Manual Testing OpenCart WebApp
This project is dedicated to manual testing of the OpenCart web application. It includes test cases, test plans, and documentation to guide manual testers in evaluating the functionality and usability of OpenCart.

## Features:
1. A comprehensive set of manual test cases.
2. Test plans and documentation for organized testing.
3. Instructions for performing manual tests on OpenCart.


## Getting Started:

1. Clone this repository.
2. Review the provided test cases and test plans.
3. Follow the documented steps to execute manual tests on OpenCart.

## Project Structure:

| File Name | Description |
|--------------|-------------|
| FRS(OpenCart).pdf   | This PDF likely contains the Functional Requirements Specification (FRS) document for OpenCart, outlining the functional and non-functional requirements of the software. |
| Test Plan (OpenCart).pdf   | This PDF is likely a Test Plan document for OpenCart, providing an overview of the testing strategy, objectives, scope, and schedule for testing the software. | 
| OpenCart-Test Scenarios .xlsx | This Excel file likely contains test scenarios for OpenCart, which describe various situations and conditions that need to be tested to ensure the software functions correctly. | 
| OpenCart-TestCases.xlsx | This Excel file probably contains a set of test cases specifically related to web registration functionality in OpenCart. It likely includes detailed steps, expected results, and test data. |
| OpenCart-TestExecution Results.xlsx | This Excel file probably contains a set of test executions specifically related to web registration functionality in OpenCart. It likely includes detailed steps, test data, expected results, actual results, priority, test results, and comments. |
| RTM (Opencart).xlsx | This Excel file probably contains the Requirement Traceability Matrix document related to web registration functionality in OpenCart. It likely includes requirement ID, requirement description, test scenario ID and description, test cases, test result, defect ID, and also the summary report. |
| OpenCart-BugReport.xlsx | This Excel file is likely used for tracking and documenting software bugs and issues found during testing. It may include details such as bug descriptions, severity, status, and steps to reproduce. |

## Contributions:

Contributions are welcome! Feel free to submit issues, enhancements, or suggestions to improve the manual testing process for OpenCart.
Happy Manual Testing! 🚀

# Manual Testing Project

## Project Introduction

### **Functionality Understanding & Exploration**
- **FRS (Functional Requirement Specification)**: Understanding the project's functional aspects, such as eCommerce features like login, product search, cart addition, payment, and delivery.
- **Effort Estimation**: Estimating the time and resources required for testing.
- **Test Plan Writing**: Defining test objectives, scope, resources, and scheduling.
- **Test Scenarios & Test Cases**: Writing detailed test scenarios and test cases to cover different functionalities.
- **Environment Setup & Build Deployment**: Setting up the required environment, such as MySQL database, Apache server (XAMPP), etc.

### **Test Execution & Bug Reporting**
- **Test Execution**: Performing tests and logging results.
- **Bug Reporting & Tracking**: Identifying bugs and tracking them using tools like Jira.
- **Sanity Testing, Re-Testing, and Regression Testing**: Verifying bug fixes, ensuring new code doesn’t break existing functionality, and performing sanity checks.
- **Test Sign-off**: Concluding the testing process after meeting the required quality standards.

### **Project vs Product**
- **Project**: The specific effort to develop a solution (e.g., an eCommerce app).
- **Product**: The end result (e.g., the eCommerce platform itself).

---

## Tools & Technology

- **Frontend**: OpenCart frontend URL (`http://localhost/opencart/upload/`), using MySQL and Apache (XAMPP).
- **Backend**: Admin panel and management through an intranet application.
- **Bug Reporting Tools**: Jira (with Zephyr plugin for test management).

---

## Agile Testing & Jira Tool

### **Agile Testing**
- **Iterative and Incremental Approach**: Agile allows for faster release cycles and accepts changes even after development has started.
- **Scrum Methodology**: Using Scrum in Agile, which includes various roles like Product Owner, Scrum Master, Development, and QA teams.
- **Scrum Activities**: Planning sprints, conducting scrum meetings (daily stand-ups), and reviewing sprints at the end of each cycle.

### **Jira Tool Integration**
- **Jira Setup**: Installing and configuring Jira for agile project management.
- **Epic/User Stories**: Creating epics and user stories to define the work.
- **Backlogs**: Managing the product backlog and sprint backlog to prioritize tasks.
- **Sprint Management**: Creating sprints, assigning stories, and managing their lifecycle.
- **Test Management with Zephyr**: Writing and executing test cases, managing test cycles, and generating reports.

### **Burndown Chart & Story Points**
- **Story Points**: Estimating the effort for each story, usually using the Fibonacci series (0, 1, 2, 3, 5, 8).
- **Burndown Chart**: Tracking the progress of work remaining in a sprint.

---

## Testing Activities in Jira & Zephyr Plugin

1. **Jira Test Management**: 
   - **Creating Test Cases**: Manually writing test cases and importing them into Jira.
   - **Executing Test Cases**: Running test cases and updating their status (Pass/Fail/Blocked).
   - **Test Cycles**: Adding test cases to cycles and running them in Jira.
   - **Reporting & Traceability Matrix**: Generating reports and ensuring traceability between requirements, test cases, and defects.

2. **Bug Tracking**:
   - **Bug Logging in Jira**: Creating, tracking, and resolving bugs as they are identified during testing.

---

## Key Agile Terminology

- **User Story**: Represents a feature or module in the software.
- **Epic**: A larger body of work, made up of several user stories.
- **Sprint**: A time-boxed period to complete a set of user stories.
- **Scrum Meeting**: Daily stand-ups to discuss progress.
- **Sprint Retrospective**: A meeting to reflect on the sprint and improve the process.
- **Story Points**: Rough estimation of the effort for a user story.
- **Burndown Chart**: A visual representation of remaining work in a sprint.

---

## References & Tools

- **Jira Tool**: [Jira Cloud (Free Version)](https://www.atlassian.com/software/jira/free)
- **Zephyr Plugin for Jira**: For test management in Jira.
- **XAMPP**: Apache, MySQL, and PHP server setup for local environments.
- **OpenCart**: E-commerce platform used for testing scenarios.

---

## Setup & Installation

### **Prerequisites**
- **MySQL Database**
- **Apache Server** (XAMPP)
- **Jira Tool**: For managing Agile workflows.
- **Zephyr Plugin**: For test case management in Jira.

### **Steps**
1. **Install XAMPP**: Set up MySQL and Apache server on your local machine.
2. **Install OpenCart**: Set up OpenCart eCommerce platform at `http://localhost/opencart/upload/`.
3. **Install Jira**: Use the free version of Jira for agile project management.
4. **Install Zephyr Plugin**: Integrate Zephyr with Jira for test management.
5. **Configure Database**: Access via `http://localhost/phpmyadmin/`.

---

## Conclusion

This repository documents the manual testing process for an eCommerce application using Agile methodologies and Jira for test management. By following the outlined steps and using the provided tools, you can efficiently plan, execute, and track testing activities while accommodating changes and collaborating with the team.


