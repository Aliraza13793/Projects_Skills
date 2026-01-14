---
name: salary-management
description: A skill for managing employee salary information including starting, stopping, correcting, and editing employee details. Claude should use this skill when asked to handle employee salary data, manage salary heads for different designations, update employee information, or process salary-related changes. Use when creating, modifying, or maintaining employee salary records with proper formatting and designation-based salary structures.
license: Complete terms in LICENSE.txt
---

# Salary Management Skill

This skill helps manage employee salary information with proper formatting and standardized processes for starting, stopping, correcting, and editing employee data.

## When to use this skill

Use this skill when handling:
- Employee onboarding (starting salary records)
- Employee termination (stopping salary records)
- Correcting employee information (name, CNIC, designation, etc.)
- Editing salary details or personal information
- Managing salary heads for different designations
- Creating standardized employee records
- Updating designation-based salary structures

## How to use this skill

1. **Identify the action type** from the request (start, stop, correct, edit employee record)
2. **Gather necessary employee details** (name, age, CNIC, designation, account number, salary)
3. **Reference the standard salary structure** for the employee's designation
4. **Follow the formatting guidelines** outlined in the references
5. **Validate the information** matches the required format
6. **Process the requested action** (add, update, remove, or modify employee record)

## Standard Employee Information Format

Employee records should follow this structure:
```
Name of Employee: [EMPLOYEE NAME]
Age: [AGE]
CNIC: [CNIC NUMBER]
Designation: [DESIGNATION]
Account Number: [ACCOUNT NUMBER]
Salary: [SALARY AMOUNT]
```

## Salary Heads by Designation

Standard salary amounts for different positions:
- Accountant: Rs. 90,000
- Receptionist: Rs. 45,000
- Sr. Clerk: Rs. 65,000
- Jr. Clerk: Rs. 55,000
- Medical Officer: Rs. 150,000
- Assistant: Rs. 78,000
- Computer Operator: Rs. 53,000
- Telephone Operator: Rs. 48,000
- Aya: Rs. 39,000
- Ward Boy: Rs. 39,000
- Naib Qasid: Rs. 39,000

## Keywords
salary management, employee records, salary heads, employee information, designation salaries, employee onboarding, employee termination, salary updates, employee data management, payroll management