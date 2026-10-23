# IRCTC QA Testing Project

A Quality Assurance (QA) testing project focused on validating key workflows of the IRCTC railway ticket booking platform. This project includes manual test cases, UI automation using Selenium and Playwright, test documentation, screenshots, and test reports.

## Project Overview

The objective of this project is to evaluate important railway booking workflows, identify potential defects, and demonstrate practical knowledge of software testing methodologies and automation tools.

## Features Covered

- Train search and availability
- User login and validation
- Train selection
- Passenger details
- Payment workflow
- Booking confirmation
- Test execution documentation
- Defect reporting and evidence screenshots

## Technologies Used

- **Python** — Programming language
- **Selenium** — Browser automation
- **Playwright** — Web UI automation
- **Pytest** — Test execution framework
- **Git and GitHub** — Version control and project hosting

## Project Structure

```text
IRCTC-QA-Testing/
├── automation/
│   ├── selenium/
│   ├── playwright/
│   └── config/
├── screenshots/
├── reports/
├── docs/
│   └── IRCTC_evidence_report.pdf
├── .gitignore
├── pytest.ini
├── requirements.txt
└── README.md
```

*The directory structure above is illustrative; adjust it to match the files in your repository.*

## Getting Started

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Tests

For Pytest-based tests:

```bash
pytest
```

Run only after checking the test configuration and ensuring the relevant browser and application prerequisites are available.

## Test Documentation

The project includes test cases with identifiers, preconditions, test steps, expected results, priorities, test data, execution status, and defect-reporting details.

Screenshots and the evidence report provide supporting documentation for the scenarios covered by the project.

## Test Execution Status

Test status should reflect actual execution results. Scenarios that have not been executed are marked accordingly. Payment and booking confirmation scenarios may be documented as test designs rather than completed live transactions.

## Important Notes

- This is an independent QA testing project.
- IRCTC is a third-party platform; this repository is not affiliated with or endorsed by IRCTC.
- Do not use real payment details or complete unauthorized transactions during testing.
- Test results should be reported only when supported by actual execution evidence.

## Learning Outcomes

- Writing structured manual test cases
- Understanding QA processes and defect reporting
- Automating browser workflows with Selenium and Playwright
- Using Python and Pytest for test execution
- Organizing screenshots, reports, and test documentation
- Managing project files with Git and GitHub

## Author

**Shahul Rashid T**

MCA Graduate | Aspiring QA / Software Test Engineer

