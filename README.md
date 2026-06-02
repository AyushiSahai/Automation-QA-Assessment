# Automation & QA Developer Assessment

## Candidate

Ayushi Sahai

## Task 1 – QA Report

Application Tested: OrangeHRM Demo

Completed:

* Tested major application workflows
* Identified 5 issues
* Assigned severity levels (High, Medium, Low)
* Performed root cause analysis for one issue

Key Issues Found:

* Incorrect success message after share action
* Numeric first name accepted
* Invalid contact number accepted
* Password reset returns 504 Gateway Timeout
* Helpful article feedback redirects to login page

## Task 2 – n8n Workflow

API Used:

* CoinGecko API

Workflow Steps:

1. Manual Trigger
2. HTTP Request (CoinGecko API)
3. Python Transformation
4. IF Condition (current_price > 1000)
5. Second HTTP Request
6. Google Sheets Output

Result:

* True Branch: Bitcoin, Ethereum
* False Branch: Tether, BNB, XRP

The workflow fetches cryptocurrency market data, filters records based on price, enriches selected records using a second API request, and stores results in Google Sheets.

## Repository Contents

* QA Report
* Workflow JSON
* Screenshots
* Documentation

Loom Video:
(Add Loom link here)
