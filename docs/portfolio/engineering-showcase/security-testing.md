# 🛡️ Security Testing with OWASP ZAP

> Security is an essential aspect of software quality. My approach combines functional testing with vulnerability assessment to help identify security risks before production deployment.

---

# Overview

In addition to functional and automation testing, I perform baseline security assessments using OWASP ZAP to identify common web application vulnerabilities.

My goal is not to replace dedicated penetration testers but to integrate security validation into the QA process and support secure software development practices.

---

# Security Testing Areas

Typical assessments include:

- Passive Scanning
- Active Scanning
- Authentication Testing
- Session Management
- Cookie Security
- HTTP Header Validation
- SSL/TLS Verification
- Input Validation
- Injection Testing
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Security Misconfiguration
- Information Disclosure

---

# Tools

| Tool | Purpose |
|------|---------|
| OWASP ZAP | Security Assessment |
| Browser Proxy | Request Interception |
| Swagger/OpenAPI | Endpoint Discovery |
| Postman | API Validation |
| SQL | Backend Verification |

---

# Typical Workflow

```text
Target Application
        │
        ▼
Spider / Crawl
        │
        ▼
Passive Scan
        │
        ▼
Active Scan
        │
        ▼
Vulnerability Analysis
        │
        ▼
Risk Classification
        │
        ▼
Security Report
        │
        ▼
Developer Remediation
```

---

# Vulnerabilities Assessed

✔ Cross-Site Scripting (XSS)

✔ SQL Injection

✔ Missing Security Headers

✔ Cookie Flags

✔ Directory Browsing

✔ Authentication Weaknesses

✔ Session Issues

✔ Information Disclosure

✔ Insecure HTTP Methods

✔ Mixed Content

---

# Risk Classification

- High
- Medium
- Low
- Informational

---

# Deliverables

Typical outputs include:

- OWASP ZAP Scan Report
- Vulnerability Summary
- Risk Assessment
- Remediation Recommendations
- Evidence Screenshots

---

# Screenshots

### 📸 Automated Spider Mapping

![OWASP ZAP Spider](../../assets/images/engineering-showcase/zap/zap-spider.png)

This assessment demonstrates how OWASP ZAP automatically maps an application's attack surface by discovering pages, technologies, and API endpoints before active security testing begins.

[:fontawesome-brands-linkedin: Read the full LinkedIn article](https://www.linkedin.com/posts/michaeljndueso_softwaretesting-appsec-api-activity-7467699025568223233-DimF?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC0KOAMB4JNjVL1I3Cfum1yHcU8dfCVfy80){ .md-button .md-button--primary }

### 📸 Vulnerability Assessment

![OWASP ZAP Alerts](../../assets/images/engineering-showcase/zap/zap-alerts.png)

This scan highlights how vulnerabilities are prioritized using OWASP ZAP's Alerts dashboard, helping teams focus on the most critical security issues first.

[:fontawesome-brands-linkedin: Read the full LinkedIn article](https://www.linkedin.com/posts/michaeljndueso_websecurity-applicationsecurity-softwarequality-activity-7467832668865409024-IYpf?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC0KOAMB4JNjVL1I3Cfum1yHcU8dfCVfy80){ .md-button .md-button--primary }


## 📄 Sample Security Assessment HTML Report

View a sample OWASP ZAP vulnerability assessment report generated during an automated security scan.

![Sample Security Assessment HTML Report](../../assets/images/engineering-showcase/zap/zap-html-report.png){ .md-button .md-button--primary }


## 📄 Sample Performance Report

Below is an example of a performance report generated after executing a load test with Apache JMeter.

The report summarizes:

- Response Times
- Throughput
- Error Rate
- Requests per Second
- Latency
- Percentiles
- Performance Trends

📥 **Preview Sample PDF Report**

<iframe
    src="../assets/files/zap_report.pdf"
    width="100%"
    height="800px"
    style="border: 1px solid #ddd; border-radius: 8px;">
</iframe>

[:material-download: Download Resume (PDF)](../assets/files/zap_report.pdf){ .md-button .md-button--primary }

[:material-download: Download Resume (PDF)](../assets/files/Michael_Jackson_Ndueso_Resume.pdf){ .md-button .md-button--primary }
---

# Skills Demonstrated

- OWASP Top 10
- Vulnerability Assessment
- Web Security Testing
- Risk Analysis
- Security Reporting
- Secure SDLC

