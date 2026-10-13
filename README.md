Build a complete, polished, fully interactive frontend prototype for my Phase 2 college project.

PROJECT TITLE:
“AI-Powered Continuous Cyber Risk Quantification and Investment Optimization Platform”

IMPORTANT:
This is ONLY a frontend prototype for Phase 2 review.
DO NOT create or require any backend, database server, API server, authentication server, cloud service, or external API.

The application must work completely in the browser using realistic MOCK DATA and local frontend state.

The UI should look like a real enterprise cybersecurity product, not like a basic student dashboard.

==================================================
1. CORE PROJECT PURPOSE
==================================================

The platform helps a company answer two questions:

1. “How much money could cyberattacks potentially cost us?”
2. “If we have a limited security budget, where should we spend it to reduce the most expected loss?”

The system should visually demonstrate this workflow:

Security Data
→ AI/ML Analysis
→ Risk Quantification
→ Financial Risk
→ Security Investment Optimization
→ Recommended Actions
→ Continuous Risk Monitoring

Use these concepts throughout the UI:

- Vulnerabilities
- Threats
- Assets
- Exploit likelihood
- Expected annual loss
- Loss magnitude
- FAIR-style risk calculation
- Monte Carlo simulation
- Security controls
- Budget optimization
- ROSI
- Risk reduction
- Continuous monitoring

Do NOT claim that real AI models or real cybersecurity feeds are connected.
Clearly use realistic simulated/demo data.

==================================================
2. TECH STACK
==================================================

Use:

- React
- TypeScript
- Tailwind CSS
- Recharts or another suitable charting library
- Lucide React icons

Keep the project clean and component-based.

No backend.

Use local mock JSON/data objects and React state.

==================================================
3. OVERALL DESIGN
==================================================

Create a premium cybersecurity/SOC-style interface.

Design language:

- Dark enterprise cybersecurity theme
- Deep navy / charcoal background
- Subtle blue/cyan accent colors
- Red/orange only for danger/warning states
- Glass-like cards where appropriate
- Clean spacing
- Thin borders
- Soft shadows
- Professional typography
- Minimal animations
- No excessive gradients
- No cartoonish elements
- No unnecessary illustrations

The interface should feel similar to a professional:

Cyber Risk Management Platform
Security Operations Dashboard
Enterprise Risk Analytics System

It should NOT look like:

- A gaming dashboard
- A crypto dashboard
- A generic admin template
- A simple college project

Make it visually impressive enough for a Phase 2 project review.

==================================================
4. APPLICATION STRUCTURE
==================================================

Create a left sidebar navigation.

Sidebar:

Logo:
“CYBERIQ”

Subtitle:
“Continuous Risk Intelligence”

Navigation:

• Overview
• Risk Quantification
• Threat Intelligence
• Assets
• Security Controls
• Investment Optimizer
• Monte Carlo
• What-If Analysis
• Recommendations

Bottom sidebar:

System Status
● Monitoring Active

Main top bar:

Page title
Search
Last updated time
“Refresh Analysis” button
Notification icon
Profile/demo user

==================================================
5. OVERVIEW DASHBOARD
==================================================

This is the main landing page.

Header:

“Cyber Risk Command Center”

Subtitle:

“Continuous financial quantification and security investment intelligence”

Top KPI cards:

1. Current Expected Annual Loss
₹1.15 Cr

2. 95% VaR
₹3.10 Cr

3. Active Critical Risks
7

4. Security Budget
₹30 Lakh

5. Potential Risk Reduction
₹60 Lakh

Each KPI should have:

- Large value
- Small descriptive text
- Trend indicator
- Appropriate icon

Example:

Expected Annual Loss
₹1.15 Cr
↓ 18.4% from previous analysis

==================================================
6. RISK TREND CHART
==================================================

Create an interactive line/area chart.

Title:

“Expected Annual Loss — 30 Day Trend”

X axis:
Days

Y axis:
₹ Loss

Use realistic mock values.

Allow hover tooltips.

Include a small indicator:

“Risk decreasing”

==================================================
7. RISK BREAKDOWN
==================================================

Create a chart showing expected loss by threat.

Threats:

Ransomware
Data Breach
Phishing
Credential Theft
Insider Threat
DDoS

Example values:

Ransomware → ₹60L
Data Breach → ₹45L
Phishing → ₹10L
Credential Theft → ₹18L
Insider Threat → ₹12L
DDoS → ₹8L

Use a professional bar chart.

==================================================
8. TOP CYBER RISKS
==================================================

Create a table/card section:

“Top Risks Requiring Attention”

Columns:

Risk
Asset
Likelihood
Potential Loss
Expected Loss
Severity
Action

Example:

Ransomware
Customer Database
30%
₹2.0 Cr
₹60 L
Critical
View

Critical Web Vulnerability
Public Web Server
24%
₹1.4 Cr
₹33.6 L
Critical
Patch

Phishing
Employee Accounts
50%
₹20 L
₹10 L
High
Mitigate

Each “View” button must work and open a detailed risk modal.

==================================================
9. RISK QUANTIFICATION PAGE
==================================================

Create a dedicated page explaining the financial risk calculation visually.

Header:

“Risk Quantification Engine”

Show:

Likelihood × Loss Magnitude
=
Expected Annual Loss

Example:

Ransomware

Annual Frequency:
0.30

Loss Magnitude:
₹2.0 Cr

Expected Annual Loss:
₹60 L

Make this visually clear.

Add a section:

“FAIR Risk Model”

Show:

Loss Event Frequency
↓
Threat Event Frequency
↓
Vulnerability
↓
Loss Event
↓
Loss Magnitude

Use a clean visual flow.

==================================================
10. MONTE CARLO SIMULATION PAGE
==================================================

Create a professional simulation page.

Title:

“Monte Carlo Risk Simulation”

Subtitle:

“10,000 simulated scenarios”

Display:

Average Annual Loss
₹68 L

95% VaR
₹3.10 Cr

Maximum Simulated Loss
₹5.02 Cr

Create a histogram/distribution chart.

X axis:
Annual Loss

Y axis:
Number of Scenarios

Add a vertical marker for:

95% VaR

Add a button:

“Run Simulation”

When clicked:

- Show a short loading animation
- Change simulation status to “Completed”
- Slightly vary mock values
- Update chart
- Show toast notification:
“Simulation completed successfully”

This must be frontend-only.

==================================================
11. THREAT INTELLIGENCE PAGE
==================================================

Create a page showing simulated threat intelligence.

Cards:

Critical Vulnerabilities
Active Exploits
Threat Events
Newly Detected Risks

Create a vulnerability table:

CVE ID
Asset
CVSS
EPSS
Exploit Status
Risk
Action

Example:

CVE-2026-XXXX
Public Web Server
9.8
0.91
Known Exploited
Critical
Patch Now

CVE-2026-YYYY
Employee Laptop
8.6
0.72
High Probability
High
Review

When clicking a vulnerability, open a detail modal.

==================================================
12. ASSET INVENTORY PAGE
==================================================

Create an enterprise asset table.

Assets:

Customer Database
Public Web Server
Employee Laptops
Internal API
File Server
Cloud Storage

Columns:

Asset
Type
Criticality
Exposure
Current Risk
Owner
Status

Use status badges:

Protected
At Risk
Critical

Clicking an asset should open an asset detail drawer/modal.

==================================================
13. SECURITY CONTROLS PAGE
==================================================

Show available security controls.

Controls:

MFA
EDR
Immutable Backups
Security Awareness Training
Database Encryption
Network Segmentation
Web Application Firewall

Each control card should show:

Control name
Cost
Expected risk reduction
Implementation difficulty
Coverage
ROSI

Example:

MFA

Cost:
₹10 L

Expected Risk Reduction:
₹28 L

ROSI:
180%

Button:
“Add to Plan”

Clicking it should add/remove the control from the investment plan.

==================================================
14. INVESTMENT OPTIMIZER PAGE
==================================================

This is one of the MOST IMPORTANT pages.

Make this page visually impressive.

Header:

“Security Investment Optimizer”

Show:

Available Budget

₹30 L

Current Expected Loss

₹1.15 Cr

Optimized Expected Loss

₹55 L

Potential Loss Avoided

₹60 L

Create a budget slider.

Example:

Budget:
₹30 L

Allow user to move the slider between:

₹5 L → ₹1 Cr

When the budget changes, update the recommended controls and estimated risk reduction using frontend calculations/mock logic.

Show:

“Recommended Investment Plan”

Rank controls by optimization score.

Example:

1. MFA
₹10 L
Risk Reduction: ₹28 L
ROSI: 180%

2. Immutable Backups
₹8 L
Risk Reduction: ₹22 L
ROSI: 175%

3. Security Training
₹5 L
Risk Reduction: ₹10 L
ROSI: 100%

4. EDR
₹15 L
Risk Reduction: ₹25 L
ROSI: 67%

Include checkboxes/toggles for controls.

Show a comparison:

BEFORE
Expected Loss:
₹1.15 Cr

AFTER
Expected Loss:
₹55 L

Risk Reduction:
52.2%

Create a before-vs-after bar chart.

==================================================
15. WHAT-IF ANALYSIS PAGE
==================================================

Create an interactive scenario simulator.

Title:

“What-If Security Investment Analysis”

Allow the user to select controls.

Example:

☑ MFA
☑ Immutable Backups
☐ EDR
☑ Security Training
☐ Database Encryption

Show dynamically:

Investment:
₹23 L

Expected Loss Before:
₹1.15 Cr

Expected Loss After:
₹62 L

Loss Avoided:
₹53 L

ROSI:
130%

Add button:

“Apply Scenario”

When clicked, update the scenario summary and show:

“Scenario saved for review”

==================================================
16. RECOMMENDATIONS PAGE
==================================================

Create an AI-style recommendation center.

IMPORTANT:
Do not falsely claim that a real AI model is running.

Label the section:

“AI-Assisted Risk Recommendations”

Cards:

🔴 Critical

“Patch the public-facing vulnerability”

Reason:
High exploit probability combined with high asset exposure.

Estimated Loss Avoided:
₹33.6 L

Priority:
Immediate

---

🟠 High

“Enable MFA for privileged accounts”

Estimated Cost:
₹10 L

Expected Loss Reduction:
₹28 L

ROSI:
180%

---

🟡 Medium

“Conduct security awareness training”

Estimated Cost:
₹5 L

Expected Loss Reduction:
₹10 L

Each recommendation should have:

View Details
Accept
Dismiss

Buttons must work.

==================================================
17. CONTINUOUS MONITORING
==================================================

Create a visible system status component.

Example:

● Continuous Monitoring Active

Last Analysis:
2 minutes ago

Next Analysis:
In 8 minutes

Data Sources:
6

Risk Engine:
Operational

Optimizer:
Ready

Create a “Refresh Analysis” button.

When clicked:

1. Show loading state.
2. Update “Last Analysis”.
3. Slightly modify demo risk values.
4. Update dashboard cards/charts.
5. Show toast:

“Risk analysis refreshed successfully”

==================================================
18. NOTIFICATION SYSTEM
==================================================

Create functional notifications.

Example:

“Critical vulnerability detected”
“Risk increased by ₹12 L”
“Optimization recommendation updated”
“Monte Carlo simulation completed”

Clicking the notification icon should open a notification panel.

==================================================
19. GLOBAL SEARCH
==================================================

Add a search box in the top navigation.

Search across:

- Assets
- Vulnerabilities
- Risks
- Security Controls
- Recommendations

Show matching results in a dropdown.

==================================================
20. MODALS / DRAWERS
==================================================

Use reusable modal/drawer components.

Required:

Risk Details Modal
Asset Details Modal
Vulnerability Details Modal
Control Details Modal
Recommendation Details Modal

Do not navigate to unnecessary pages for every small detail.

==================================================
21. INTERACTION REQUIREMENTS
==================================================

THIS IS VERY IMPORTANT.

The UI must actually work.

Do not create static screenshots disguised as a dashboard.

Functional interactions should include:

- Sidebar navigation
- Page switching
- Search
- Refresh Analysis
- Run Monte Carlo
- Budget slider
- Control selection
- Investment plan updates
- What-if analysis
- Risk detail modal
- Asset detail modal
- Vulnerability detail modal
- Recommendation accept/dismiss
- Notifications
- Tooltips
- Charts
- Tabs
- Toggle buttons
- Toast messages

Every button should either perform a meaningful frontend action or be intentionally disabled with a clear reason.

No dead buttons.

==================================================
22. DEMO DATA
==================================================

Use a consistent fictional company.

Company name:

“NovaCore Technologies”

Assets:

Customer Database
Public Web Server
Employee Laptops
Internal API
File Server
Cloud Storage

Threats:

Ransomware
Data Breach
Phishing
Credential Theft
Insider Threat
DDoS

Initial financial risk:

Expected Annual Loss:
₹1.15 Cr

95% VaR:
₹3.10 Cr

Budget:
₹30 Lakh

Optimized Expected Loss:
₹55 Lakh

Keep all numbers internally consistent across pages.

==================================================
23. CURRENCY
==================================================

Use Indian Rupees.

Display naturally:

₹1.15 Cr
₹60 L
₹30 L
₹10 L

Do not use dollars.

==================================================
24. RESPONSIVE DESIGN
==================================================

The application must work properly on:

Desktop
Laptop
Tablet

Primary target is a desktop/laptop presentation screen.

Make charts and tables readable.

==================================================
25. PRESENTATION MODE
==================================================

Add a small “Presentation Mode” button.

When enabled:

- Hide unnecessary navigation clutter
- Expand dashboard
- Increase important KPI visibility
- Make charts larger
- Keep the interface clean for projector/demo use

==================================================
26. LOADING / EMPTY / ERROR STATES
==================================================

Create polished states for:

Loading analysis
Simulation running
No search results
No notifications
Action completed

Use skeleton loaders and subtle animations.

==================================================
27. UI QUALITY REQUIREMENTS
==================================================

Prioritize:

1. Professional visual hierarchy
2. Consistent spacing
3. Consistent typography
4. Clear charts
5. Readable numbers
6. Meaningful interactions
7. Smooth but subtle animations
8. Responsive layout
9. Consistent mock data
10. Realistic cybersecurity terminology

Avoid:

- Huge unnecessary headings
- Excessive rounded cards
- Excessive gradients
- Random icons
- Fake 3D graphics
- Overloaded screens
- Long paragraphs
- Lorem ipsum
- Generic dashboard filler text

==================================================
28. IMPORTANT PROJECT FLOW
==================================================

The UI must make this complete story obvious:

DATA
↓
AI / ML ANALYSIS
↓
RISK QUANTIFICATION
↓
MONTE CARLO
↓
FINANCIAL RISK
↓
SECURITY CONTROLS
↓
INVESTMENT OPTIMIZATION
↓
RECOMMENDATIONS
↓
SECURITY TEAM ACTION
↓
CONTINUOUS REFRESH

Create a visual “Risk Intelligence Pipeline” component on the Overview page showing this flow.

==================================================
29. DEMO SCENARIO
==================================================

Build the UI around this scenario:

Company:
NovaCore Technologies

Current Expected Annual Loss:
₹1.15 Cr

Top Risk:
Ransomware

Likelihood:
30%

Potential Loss:
₹2 Cr

Expected Loss:
₹60 L

Available Security Budget:
₹30 L

The optimizer evaluates:

MFA — ₹10 L
Immutable Backups — ₹8 L
Security Training — ₹5 L
EDR — ₹15 L
Database Encryption — ₹12 L

The recommended plan should demonstrate that a limited ₹30 L budget can reduce expected loss significantly.

Make the numbers believable and consistent.

==================================================
30. FINAL REQUIREMENT
==================================================

Generate the complete working frontend application.

Do not stop at generating a visual mockup.

Create:

- All React components
- All pages
- Navigation
- Mock data
- Charts
- State management
- Modals
- Interactions
- Animations
- Responsive layout

Everything should run locally without a backend.

The final result should feel like a real enterprise product called:

“CYBERIQ — Continuous Cyber Risk Intelligence”

It should be impressive enough for a 3rd-year engineering Phase 2 project review and easy for me to demonstrate live to faculty evaluators.

Before finishing, verify that there are NO dead buttons, NO broken navigation links, NO undefined data, and NO backend/API dependency.
