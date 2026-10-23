<div align="center">

# Tej Thimmaiah

<a href="https://github.com/TejThimmaiah">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=1F6FEB&center=true&vCenter=true&width=640&lines=KYC+%2F+CDD+Analyst+at+HSBC;AML+%26+Financial+Crime+Compliance;I+build+tools+that+make+KYC+faster;6+performance+awards+in+4.5+years" alt="KYC / CDD Analyst at HSBC · AML & Financial Crime Compliance · I build tools that make KYC faster" />
</a>

<p>
  <img src="https://img.shields.io/badge/Experience-4.5%20years-1F6FEB?style=flat-square" alt="4.5 years experience"/>
  <img src="https://img.shields.io/badge/Current-HSBC%20India-DB0011?style=flat-square" alt="HSBC India"/>
  <img src="https://img.shields.io/badge/Focus-AML%20%7C%20KYC%20%7C%20CDD%2FEDD-2EA043?style=flat-square" alt="AML, KYC, CDD/EDD"/>
  <img src="https://img.shields.io/badge/Location-Bengaluru%2C%20India-F78166?style=flat-square" alt="Bengaluru, India"/>
  <img src="https://img.shields.io/badge/Open%20to-AML%20%2F%20KYC%20%2F%20TM%20roles-8957E5?style=flat-square" alt="Open to AML / KYC / TM roles"/>
</p>

<a href="https://www.linkedin.com/in/tejthimmaiah/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:thimmaiah18tej@gmail.com"><img src="https://img.shields.io/badge/Email-thimmaiah18tej%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

## About me

I'm a financial crime compliance analyst with **4.5 years** at **HSBC** and **Accenture**, working across CDD/EDD, KYC, transaction monitoring, SAR investigations and sanctions screening.

At HSBC I complete **8+ end-to-end CDD/EDD reviews a day with 100% QA accuracy** for the Channel Islands & Isle of Man (CIIOM) market. Alongside casework, I build the tools that make KYC faster and more consistent. Three of them are now **approved and used across all markets**, and they earned the **IWPB Operations Automation Award (Q2 2026)**.

<table>
  <tr>
    <td align="center" width="25%"><h3>8+</h3>CDD/EDD reviews<br>per day</td>
    <td align="center" width="25%"><h3>100%</h3>QA accuracy</td>
    <td align="center" width="25%"><h3>&lt; 1.5 min</h3>per case with<br>my decision tools</td>
    <td align="center" width="25%"><h3>6</h3>performance awards<br>in 4.5 years</td>
  </tr>
</table>

---

## Tools I built at HSBC

> Click a tool to see what it does and how it works. Descriptions are kept high level; no internal rules, data or client information are shared here.

<details>
<summary><b>🧭 Source of Wealth Tier Identification Tool</b> &nbsp;·&nbsp; Excel / VBA rule engine &nbsp;·&nbsp; used across all markets</summary>
<br>

**Problem:** Deciding how much Source of Wealth evidence a customer needs meant reading a multi-factor policy matrix by hand for every case. It was slow and analysts could reach different answers.

**What I built:** A single-sheet rule engine. The analyst answers a short set of questions about the customer; the tool returns the SOW tier (Baseline / Standard / Enhanced) with the matching rule, in **under 1.5 minutes**.

- Encodes **55+ policy rules**, each verified against the master matrix and tested with scenario runs
- Locked formulas and workbook structure so the logic can't be changed by accident
- One-click reset so every new case starts from a clean, consistent default
- The analyst still reviews and owns the final decision

```mermaid
flowchart LR
    A[Analyst enters<br>customer factors] --> B{Rule engine<br>55+ verified rules}
    B --> C[SOW tier<br>Baseline / Standard / Enhanced]
    C --> D[Analyst confirms<br>and records rationale]
```
</details>

<details>
<summary><b>🛡️ PEP Standard vs High Risk Decision Tool</b> &nbsp;·&nbsp; used across all markets and by Onshore Safeguard teams</summary>
<br>

**Problem:** Classifying a Politically Exposed Person as Standard or High Risk depends on several factors, and inconsistent decisions create audit risk.

**What I built:** A guided decision tool that walks the analyst through the required factors and returns a consistent PEP risk outcome in **under 1.5 minutes**. Country risk stays a manual analyst judgement, because the reference list changes over time.

- Approved by management and adopted beyond my own team by the **Onshore Safeguard teams**
- Built to production standard from the requirements sheet, then refined with stakeholder feedback

```mermaid
flowchart LR
    A[PEP case] --> B[Guided factor checks]
    B --> C[Analyst country-risk judgement]
    C --> D{Decision logic}
    D --> E[Standard Risk]
    D --> F[High Risk]
```
</details>

<details>
<summary><b>🎯 CDD/EDD QC/QA Sampling Tool</b> &nbsp;·&nbsp; one-click &nbsp;·&nbsp; used daily by QC teams across markets</summary>
<br>

**Problem:** QC and QA analysts had to work out by hand which closed cases needed a quality check, and what share of the closed report was CDD vs EDD.

**What I built:** A one-click tool that reads the closed-case report, applies the sampling rules (**20% of EDD, 10% of CDD, plus all high-risk third country customers**) and filters by market, so each QC team sees only its own sample. It includes a charts view of the CDD/EDD split.

```mermaid
flowchart LR
    A[Closed-case report] --> B[Classify CDD / EDD]
    B --> C[Apply sampling rules]
    C --> D[Filter by market]
    D --> E[QC / QA sample<br>+ charts]
```
</details>

<details>
<summary><b>📊 Team performance dashboards</b> &nbsp;·&nbsp; Power BI + Power Automate &nbsp;·&nbsp; team of 17</summary>
<br>

Daily and monthly MI on productivity, quality and SLA performance, refreshed automatically, giving team leads clear visibility without manual reporting.
</details>

---

## Experience

```mermaid
timeline
    title Career
    2022 : Accenture · Regulatory Compliance Analyst
         : Compliance Avenger Award (FY22 Q1)
    2023 : Star of Business Award (FY23)
    2024 : Best Performer Award (FY24)
    2025 : Star of Business Award (FY25)
         : Joined HSBC India · CDD Analyst, IWPB KYC
    2026 : IWPB Operations Apex Award (Q1)
         : IWPB Operations Automation Award (Q2)
```

<details open>
<summary><b>HSBC India</b> · Customer Due Diligence (CDD) Analyst, IWPB KYC · <i>Jul 2025 – Present</i></summary>
<br>

- End-to-end CDD/EDD reviews for the **CIIOM** market: ID&V, beneficial ownership, source of wealth / source of funds, PEP, sanctions and adverse-media checks, customer risk rating
- **8+ reviews a day with 100% QA accuracy**; periodic and trigger-event reviews within SLA
- Raise **Unusual Activity Reports (UARs)** when a customer's transactions look suspicious during review
- Designed and built three KYC decision and QC tools now **used across all markets**
- Built Power BI / Power Automate MI for a **team of 17**
- Support the QC team with quality checks; track team e-learning and monthly knowledge-test completion
</details>

<details>
<summary><b>Accenture</b> · Regulatory Compliance Analyst · <i>Apr 2022 – Jun 2025</i></summary>
<br>

- Investigated **10–15 transaction monitoring alerts a day** for a US client (Google), tracing the origin and destination of funds
- Authored and filed **8+ Suspicious Activity Reports (SARs) per quarter** with narrative, evidence and escalation recommendation
- Sanctions, PEP and watchlist screening across multiple tools
- KYC, KYB and CDD reviews and onboarding verification, including fraudulent document detection
- KYC quality reviews and process improvement; earned the Accenture **People Leadership Credential (Level 1)**
</details>

---

## Awards

| Award | Issued by | Date |
|---|---|---|
| 🤖 IWPB Operations **Automation** Award, Q2 2026 | HSBC | Sep 2026 |
| 🏆 IWPB Operations **Apex** Award, Q1 2026 | HSBC | May 2026 |
| 🌟 Star of Business, FY25 | Accenture | Jun 2025 |
| 🥇 Best Performer, FY24 | Accenture | Sep 2024 |
| 🌟 Star of Business, FY23 | Accenture | Sep 2023 |
| 🛡️ Compliance Avenger, FY22 Q1 | Accenture | Aug 2022 |

---

## Skills

<table>
  <tr>
    <td valign="top" width="33%">
      <b>Financial crime</b><br><br>
      CDD / EDD · KYC / KYB<br>
      Beneficial ownership<br>
      Source of wealth / funds<br>
      PEP assessment<br>
      Sanctions &amp; adverse media<br>
      Customer risk rating
    </td>
    <td valign="top" width="33%">
      <b>Investigations</b><br><br>
      Transaction monitoring<br>
      Fund tracing<br>
      SAR writing &amp; filing<br>
      Unusual Activity Reports (UAR)<br>
      Fraudulent document detection<br>
      Audit-ready documentation
    </td>
    <td valign="top" width="33%">
      <b>Automation &amp; data</b><br><br>
      <img src="https://img.shields.io/badge/Excel%20%2F%20VBA-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel / VBA"/>
      <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/>
      <img src="https://img.shields.io/badge/Power%20Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" alt="Power Automate"/>
      <img src="https://img.shields.io/badge/UiPath-FA4616?style=flat-square&logo=uipath&logoColor=white" alt="UiPath"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML"/>
      <img src="https://img.shields.io/badge/Oracle%20Cloud-C74634?style=flat-square&logo=oracle&logoColor=white" alt="Oracle Cloud"/>
      <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
    </td>
  </tr>
</table>

---

## Founder · Bastion Helix

<div align="center">
  <a href="https://bastionhelix.com"><img src="https://img.shields.io/badge/Bastion%20Helix-Software%20for%20the%20tools%20teams%20already%20use-101322?style=for-the-badge" alt="Bastion Helix: Software for the tools teams already use"/></a>
</div>

<br>

Alongside my compliance career, I founded **[Bastion Helix](https://bastionhelix.com)**, an independent software company in Bengaluru. It builds apps for the tools teams already use: Chrome, Jira and AI agents. I design, build and launch the products myself.

<table>
  <tr>
    <td valign="top" width="50%">
      <b>📸 <a href="https://bastionhelix.com/capture">Bastion Helix Capture</a></b><br>
      <img src="https://img.shields.io/badge/Status-Live%20on%20Chrome%20Web%20Store-2EA043?style=flat-square" alt="Live on Chrome Web Store"/><br><br>
      Chrome extension that sends bug reports with screenshots or replays straight to Jira, GitHub or Linear.
    </td>
    <td valign="top" width="50%">
      <b>📋 <a href="https://bastionhelix.com/tables">Bastion Helix Tables</a></b><br>
      <img src="https://img.shields.io/badge/Status-Live-2EA043?style=flat-square" alt="Live"/><br><br>
      Chrome and Edge extension that turns any web table into Excel, CSV or Google Sheets data in one click.
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <b>🔎 <a href="https://bastionhelix.com/lens">Bastion Helix Agent Lens</a></b><br>
      <img src="https://img.shields.io/badge/Status-API%20live-2EA043?style=flat-square" alt="API live"/><br><br>
      API and MCP server that lets AI agents check whether they may use a web page, then read its content.
    </td>
    <td valign="top" width="50%">
      <b>🧩 <a href="https://bastionhelix.com/jira">Bastion Helix for Jira</a></b><br>
      <img src="https://img.shields.io/badge/Status-In%20Atlassian%20Marketplace%20review-D29922?style=flat-square" alt="In Atlassian Marketplace review"/><br><br>
      Seven Jira Cloud tools on one licence, running inside Atlassian.
    </td>
  </tr>
</table>

<div align="center">
  <a href="https://bastionhelix.com"><img src="https://img.shields.io/badge/Visit-bastionhelix.com-101322?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Visit bastionhelix.com"/></a>
</div>

---

## Personal projects

<sub>Private builds. Code is not public.</sub>

| Project | What it is | Built with |
|---|---|---|
| **Finance Meridian** | Finance education website, including a "Jargon Buster" that explains financial terms in plain language | HTML, AI API |
| **Nifty 50 short-sell agent** | Agent that scans Nifty 50 stocks for short-sell signals | Python |

---

## Education &amp; certifications

<details>
<summary><b>Education</b></summary>
<br>

| Degree | Institution | Years | Score |
|---|---|---|---|
| MBA, HR Management &amp; Finance | Jain (Deemed-to-be University), Bengaluru | 2021 – 2023 | 71.82% |
| B.Com, Accounting &amp; Taxation | New Horizon College, Bengaluru | 2017 – 2020 | 83.35% |
</details>

<details>
<summary><b>Certifications</b></summary>
<br>

- UiPath Automation Business Analyst Associate, UiPath Academy (Jun 2025)
- People Leadership Credential, Level 1, Accenture (Apr 2025)
- Accounting Fundamentals, Corporate Finance Institute (Feb 2022)
- Advanced Microsoft Excel, Systems Domain (May 2020)
- Cybersecurity fundamentals: Palo Alto Networks, Fortinet, Microsoft &amp; LinkedIn (2025)
</details>

---

## Building in public

<div align="center">

**488 contributions in the last year** · **3 live products under Bastion Helix** · **3 tools in live use at HSBC**

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TejThimmaiah/TejThimmaiah/output/github-contribution-grid-snake-dark.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/TejThimmaiah/TejThimmaiah/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

<div align="center">
  <b>Open to AML, KYC, transaction monitoring and financial crime roles in Bengaluru.</b><br>
  <a href="https://www.linkedin.com/in/tejthimmaiah/">LinkedIn</a> · <a href="mailto:thimmaiah18tej@gmail.com">thimmaiah18tej@gmail.com</a>
</div>
