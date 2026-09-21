# Manual Web Testing — Practice Software Testing

**Tester:** Anna Kozhevnikova

## About the Project

This is a manual web testing portfolio project based on the **Practice Software Testing** web application.

The project demonstrates a complete manual QA workflow:

**Functional analysis → Test Checklist → Smoke Testing → Exploratory Testing → Defect Investigation → Bug Reporting → Test Reporting**

The main goal of the project was to practice finding, investigating, documenting, and explaining problems in a web application.

## Application Under Test

[Practice Software Testing](https://practicesoftwaretesting.com/)

## Testing Scope

The following functional areas were covered:

- Navigation
- Product pages
- Product search
- Sorting and filters
- Pagination
- User registration
- Sign in / Sign out
- User account
- Favorites
- Invoices
- Profile
- Contact form
- Shopping cart
- Checkout
- Payment
- Guest checkout
- Chat Assistant
- Live Shop Activity

The project focuses on **manual functional, UI, and exploratory testing**.

## Testing Activities

### 1. Functional Test Checklist

A detailed functional checklist was created covering:

- Positive and negative scenarios
- Required and optional fields
- Input validation
- Boundary and data variations
- Navigation
- UI behavior
- State persistence
- Search
- Sorting and filtering
- Pagination
- Shopping cart
- Checkout and payment

The checklist contains detailed conditions to be checked during manual testing.

### 2. Smoke Testing

A smoke test set of **49 critical checkpoints** was selected from the functional checklist and executed against the application.

| Result | Count |
|---|---:|
| PASS | 29 |
| FAIL | 8 |
| BLOCKED | 1 |
| N/A | 11 |
| **Total** | **49** |

**10 defects were documented during smoke testing.**

`N/A` means that the check was not applicable to the tested scope/build.

One checkout checkpoint was marked **BLOCKED** because an application issue prevented the test from reaching the Payment section.

The complete execution results are available in the Smoke Test Execution file.

### 3. Exploratory Testing

Exploratory testing was performed in addition to the structured checklist.

The exploration focused on:

- Home page
- Product pages
- Search and filters
- Shopping cart
- Favorites
- Chat Assistant
- UI behavior
- Functional behavior
- Areas requiring requirement clarification

Findings were investigated and documented separately from the structured smoke testing results.

### 4. Defect Reporting

**10 defects** identified during smoke testing were documented as Jira bug reports.

Each defect includes:

- Bug ID
- Description
- Actual Result
- Expected Result
- Supporting evidence

The repository contains both:

- screenshots of the defects found in the application
- screenshots of the corresponding Jira bug reports

## Project Structure

```text
Manual-Web-Testing-Practice-Software-Testing/
│
├── BUG-Reports/
│   ├── BUG-01.png
│   ├── BUG-02.png
│   └── ...
│
├── Bug-Evidence/
│   ├── BUG-01_Evidence.png
│   ├── BUG-02_Evidence.png
│   └── ...
│
├── Test-Documentation/
│   ├── Functional-Test-Checklist.docx
│   ├── Smoke-Test-Execution.xlsx
│   ├── Smoke-Testing-Report.docx
│   └── Exploratory-Testing-Findings.docx
│
└── README.md
```

## Defects Found During Smoke Testing

The smoke test execution revealed defects affecting several functional areas, including:

- Navigation
- Sorting
- Product actions
- Shopping cart
- Checkout progression

The corresponding evidence and Jira bug reports are available in the repository.

## Tools

- Manual Web Testing
- Jira
- Microsoft Excel
- Microsoft Word
- Practice Software Testing

## QA Skills Demonstrated

- Functional test analysis
- Test checklist design
- Smoke testing
- Manual test execution
- Exploratory testing
- Defect investigation
- Actual vs. Expected Result analysis
- Visual defect evidence
- Jira bug reporting
- Linking test execution results to defects
- Test reporting and documentation

## Project Outcome

This project demonstrates the complete workflow of a manual web testing task — from analyzing application functionality and preparing test coverage to executing tests, investigating defects, documenting evidence, and reporting results.

It represents hands-on practice in **Manual QA / Web Testing** using a real web application environment.
