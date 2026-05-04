# Sinhala Transliteration Test Automation

## Project Description

This project automates the testing of Singlish to Sinhala transliteration using Playwright.
The automation script reads test cases from an Excel file, sends the inputs to the PixelsSuite Sinhala transliteration tool, captures the actual output, compares it with the expected output, and updates the test status automatically.

## Technologies Used

* Python
* Playwright
* OpenPyXL

## Project Files

* test_automation.py → Main automation script
* Assignment 1 - Test cases.xlsx → Test cases and results
* README.md → Project instructions

## Installation Steps

Install Python dependencies:

pip install playwright openpyxl

Install Playwright browsers:

playwright install

## How to Run

Run the automation script using:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

## Test Coverage

This project includes:

* Small (S) inputs
* Medium (M) inputs
* Negative test cases
* Singlish abbreviations
* Numbers, dates, URLs, names, symbols, punctuation

## Git Repository

This repository is publicly accessible for evaluation.

## Author

Santhushi Wijesinghe(IT23572492)
WE04.02
BSc (Hons) Information Technology 
