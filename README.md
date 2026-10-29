# Health Data Analysis Dashboard

Professional responsive university mini-project using Flask, SQLite, NumPy, Pandas and Chart.js.

## Features
- Dashboard KPI cards, age histogram, demographics chart and age/cholesterol scatter plot.
- Patient records: create, view, search, filter by gender/age, edit and delete.
- Analytics page with correlation matrix and scatter charts for age, blood pressure, cholesterol, glucose and BMI.
- CSV import/export and downloadable sample template.
- SQLite database created automatically; includes 60 synthetic demo records.
- Responsive colored interface; charts update when records change.

## Run on Windows / VS Code
1. Extract this ZIP and open its folder in VS Code.
2. Open Terminal (Command Prompt or PowerShell) in VS Code.
3. Run these commands:
   ```bat
   py -m venv .venv
   .venv\Scripts\activate
   python -m pip install -r requirements.txt
   python app.py
   ```
   If `py` is not recognized, use `python` instead.
4. Open http://127.0.0.1:5000 in your browser.
5. Or double-click `run.bat`.

## CSV columns
Required: `patient_code,name,age,gender,systolic_bp,diastolic_bp,cholesterol,glucose,bmi`
Optional: `diagnosis`. Duplicate patient codes are skipped.

## Important
Seeded records are synthetic examples for demonstration, not real patient records. This is an educational analytics project and must not be used for diagnosis or treatment. Only import authorized, de-identified data approved for university use.
