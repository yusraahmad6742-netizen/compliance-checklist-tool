# Security Compliance Checklist Automation Tool

A self-assessment tool that walks a small business through 16 essential security controls, scores their compliance posture, and generates a prioritized remediation report.

**Live demo:** https://yusraahmad6742-netizen.github.io/compliance-checklist-tool/

## Problem Statement

Small businesses often don't know whether they meet basic security expectations — password policies, backups, MFA, and similar baseline controls. Manual checklists get created once and then forgotten, leaving real gaps unaddressed and undocumented.

## Solution

An interactive, single-page web tool that guides a business through a structured checklist, scores each answer, and produces a clear, prioritized report showing exactly where the biggest risks are and what to fix first.

## Framework Used

Controls are based on **CIS Controls v8, Implementation Group 1 (IG1)** — the "essential cyber hygiene" tier of the CIS framework, designed specifically for organizations with limited security resources and staff.

## Features

- 16 controls across 4 categories: Access Control, Backup, Network, and Awareness
- Simple Yes / Partial / No scoring per control, with a live running score as you go
- Automatically generated report with:
  - Overall compliance score and maturity band (Mature / Developing / At Risk)
  - Category-by-category score breakdown
  - A prioritized remediation roadmap, ordered by risk category, with a one-line fix for every gap
- Built-in sample profiles (a "mature" and a "weak" business) for quick demoing and testing
- Print / export-to-PDF report view
- No dependencies, no backend — runs as a single self-contained HTML file

## Tools & Technologies

- HTML, CSS, JavaScript (vanilla, no frameworks)
- CIS Controls v8 (IG1) as the assessment framework

## Sample Assessments

| Business | Score | Band |
|---|---|---|
| Riverside Bakery | 97% | Mature |
| Corner Hardware Co | 41% | At Risk |
Screenshots below:

<img width="1294" height="688" alt="WhatsApp Image 2026-09-20 at 8 54 31 AM" src="https://github.com/user-attachments/assets/2c7bdfe0-770d-41ba-8d01-a026627f8d67" />

<img width="1245" height="620" alt="WhatsApp Image 2026-09-20 at 8 57 45 AM" src="https://github.com/user-attachments/assets/1c467b04-988d-4c61-8391-328d7fefa5a0" />

## Challenges & How I Solved Them

- [e.g. "Deciding how to weight remediation priority — solved by sorting gaps by category risk (Access Control and Backup first) rather than just raw score."]
- [Add 1–2 more from your own build process]

## Future Improvements

- Persist assessments so a business can track progress over time
- Expand to the full CIS IG1 or IG2 control set
- Add PDF export with a formatted cover page instead of browser print
- Allow custom weighting per control for different industries

## Author

Yusra Ahmad , SafeX Internship, Week 3
