# Google Sheets Dashboards

> A collection of live-updating, QA, operational, security, automation, and reporting dashboards built using Google Sheets.

---

# 1. Customer Support & Agent Performance Analytics

### 📊 System Overview
A live operational dashboard engineered to track helpdesk efficiency, categorize support incoming streams, and visualize ticket lifecycles. It delivers real-time granular visibility into individual agent productivity alongside historical ticket volumes aggregated across multiple timelines (Daily, Weekly, Monthly, Yearly, and All-Time) to pinpoint trending technical vulnerabilities.

### 🎛️ Core Engineering & Formulas Used
The dashboard automatically pulls data from multiple Google Sheets, processes it using formulas, and updates reports in real time:
*   `IMPORTRANGE` — Dynamically syncs raw support data from separate cross-functional sheets safely.
*   `FILTER` & `UNIQUE` — Dynamically isolates and groups core data points (like category trends and agent lists) without hardcoding values.
*   `COUNTIFS` & `SUMIFS` — Drives the conditional matrix calculations that populate the multi-timeline performance maps.
*   `IFERROR` — Ensures clean data presentation by systematically catching null calculations or empty date ranges.

### 🖥️ Live Dashboard Preview
<div style="text-align:center; margin: 2rem 0;">
  <iframe
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTPtjfBegnpAEkAX0WuWuFuD9iL52h17Olrsp52k1g6LpD98vrRlflhPwfQ8kzPQgHHoF6Z4dRWeyYQ/pubhtml?widget=true&headers=false"
    width="100%"
    height="700"
    frameborder="0"
    style="border:1px solid #ddd; border-radius:12px;">
  </iframe>
</div>

---

# 2. Security Controls & Compliance Checklist

### 📊 System Overview
A centralized compliance tracking index used to audit application security controls against industry standards (such as OWASP requirements). This tracker ensures security testing loops are explicitly validated across features before production sign-off, mapping risks directly to mitigation statuses.

### 🎛️ Core Engineering & Formulas Used
*   `VLOOKUP` — Cross-references security vulnerabilities and standard controls against an isolated central threat-model database.
*   `COUNTA` & `COUNTIFS` — Calculates dynamic compliance percentage gauges, tracking completed security passes vs. open risks.

### 🖥️ Live Dashboard Preview
<iframe src="https://docs.google.com/spreadsheets/d/1bjxsn9R7I8LyJEVB9on-HCp6SR1TjEieKweMkDf6BtM/htmlembed?gid=2010772764&widget=false&chrome=false&headers=false" width="100%" height="500px" style="border: 1px solid #e1e4e8; border-radius: 6px;"></iframe>

---

# 3. Master Test Repository

### 📊 System Overview
A unified testing lifecycle repository combining test suite planning with an active defect management board. It dynamically links executed test cases to reported bugs, giving technical teams an instant visualization of current test run progress, blockages, defect distribution metrics, and severity breakdown charts.

### 🎛️ Core Engineering & Formulas Used
*   `COUNTIFS` — Aggregates real-time charts displaying the breakdown of bug severities (Critical, High, Medium, Low) and execution states (Passed, Failed, Blocked).
*   `COUNTA` & `SUM` — Powers the main test execution completion gauges and calculates defect density scores across specific components.

### 🖥️ Live Dashboard Preview
<iframe src="https://docs.google.com/spreadsheets/d/1cnIXlHmMrBGfOh8ImdLzUmAC4utfdSt3RY5k3OE3VnQ/htmlembed?gid=1222779837&widget=false&chrome=false&headers=false" width="100%" height="550px" style="border: 1px solid #e1e4e8; border-radius: 6px;"></iframe>

---
# 4. Defect Management Dashboard

### 📊 System Overview
A unified testing lifecycle repository combining test suite planning with an active defect management board. It dynamically links executed test cases to reported bugs, giving technical teams an instant visualization of current test run progress, blockages, defect distribution metrics, and severity breakdown charts.

### 🎛️ Core Engineering & Formulas Used
*   `COUNTIFS` — Aggregates real-time charts displaying the breakdown of bug severities (Critical, High, Medium, Low) and execution states (Passed, Failed, Blocked).
*   `COUNTA` & `SUM` — Powers the main test execution completion gauges and calculates defect density scores across specific components.

### 🖥️ Live Dashboard Preview
<iframe src="https://docs.google.com/spreadsheets/d/1cnIXlHmMrBGfOh8ImdLzUmAC4utfdSt3RY5k3OE3VnQ/htmlembed?gid=567141784&widget=false&chrome=false&headers=false" width="100%" height="550px" style="border: 1px solid #e1e4e8; border-radius: 6px;"></iframe>

---
# 5. Product Automation Coverage Report

### 📊 System Overview
A high-level quality metrics sheet designed for product stakeholders. This reporting asset monitors the footprint of automated testing (Cypress/Playwright) against the manual testing matrix, calculating core percentages of automated regression stability, build pass rates, and overall automation ROI.

### 🎛️ Core Engineering & Formulas Used
*   `COUNTIFS` — Breaks down automated test distribution profiles across individual feature modules and functional areas.
*   `SUM` & `COUNTA` — Computes overall code automation coverage weights, giving stakeholders a clear, data-backed view of release confidence.

### 🖥️ Live Dashboard Preview
<iframe src="https://docs.google.com/spreadsheets/d/1cWvHRYbP210qHKPwidVLdXgQfvcZLS0ZLS29qJeT150/htmlembed?gid=1060002094&widget=false&chrome=false&headers=false" width="100%" height="500px" style="border: 1px solid #e1e4e8; border-radius: 6px;"></iframe>

## Skills Demonstrated

Throughout these dashboards I applied:

• Google Sheets Automation
• Dashboard Design
• Formula Engineering
• Process Automation
• Data Analysis
• Data Visualization
• QA Metrics
• Defort Tracking
• Test Management
• Operational Reporting
• Stakeholder Reporting
• Performance Monitoring
• Security Compliance Tracking
• Automation Coverage Reporting