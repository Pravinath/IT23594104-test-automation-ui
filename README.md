# Playwright UI Automation Test

Registration Number: IT23594104

This project automates one UI test scenario for Pixelssuite website.

## Automated Scenario

Feature: Image Format Conversion  
Scenario: Upload a valid PNG image and verify whether the preview is displayed.

## Tools Used

- Python
- Playwright
- OpenPyXL
- Google Chrome / Chromium

## Installation

pip install -U pip
pip install playwright openpyxl
playwright install

## Run Test

python image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000

## Output Files

- execution_results.csv
- results/preview_pass.png
