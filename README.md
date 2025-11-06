# 🧪 Mini Automation Project

This project automates website testing using **Python** and **Selenium WebDriver** following the Page Object Model (POM).

## 🚀 Features
- Automated functional testing
- Page Object Model (POM)
- PyTest-based execution with HTML reports

## 🧰 Tech Stack
- **Language:** Python
- **Libraries:** Selenium, PyTest
- **Tools:** Chrome, ChromeDriver, PyTest-HTML

## ✅ Prerequisites
- Python 3.10+ installed (checked with `python --version`)
- Google Chrome installed
- ChromeDriver auto-managed by Selenium 4 (no manual download needed in most cases)

## ⚙️ Setup
- pip install -r requirements.txt
- python -m pytest --html=reports/report.html --self-contained-html

## ▶️ Run Tests
Create reports folder (first time only):
mkdir reportsRun pytest and generate HTML report (Windows-safe):
python -m pytest --html=reports/report.html --self-contained-htmlOpen the report:
- `reports/report.html`


