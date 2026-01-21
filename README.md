<h1 align="center">Governing a High-Risk AI System with Responsible AI Controls</h1> 

<br />

![Governing a High-Risk AI System with Responsible AI Controls](https://github.com/user-attachments/assets/6e2865e8-d13e-4372-87f0-c07ee0829682)

<br>

## Introduction

<br>

In this Project I designed and documented a **Responsible AI Governance Framework** for a **High-Risk AI System** operating in a regulated financial services environment within the **UK & EU**.

The focus of this project was on **governance, accountability, risk assessment and control enforcement** - the elements required to deploy AI systems in a way that is **compliant and auditable**.

The use case I evaluated involved AI-assisted **customer onboarding and fraud risk scoring**, which is a scenario explicitly classified as **High Risk under the EU AI Act** due to its impact on individuals’ access to financial services.

This project demonstrates how to translate abstract Responsible AI principles into **practical and enforceable governance mechanisms.**

<br>

## 🎯 Business Context & Problem Statement

<br>

The organization faces three critical challenges:

- Manual customer onboarding reviews are **slow and inconsistent**

- Fraud losses continue despite existing controls

- Compliance teams cannot scale current review processes

<br>

The business proposes an AI solution to improve efficiency, but without governance, this would introduce **severe legal, ethical and reputational risks.**

<br>

## 🤖 Proposed AI Use Case

<br>

The proposed AI system would:
- Score new customer onboarding applications

- Recommend either:

  - Approval
  - Rejection
  - Enhanced due diligence

<br>

### AI Inputs

- Customer application data
  
- Transactional signals
  
- Device and behavioral metadata
  
- Historical fraud patterns

<br>

### Initial Business Goals

- Reduce onboarding time by ~60%
  
- Automate low-risk and high-risk decisions
  
- Escalate only borderline cases to humans

<br>

💡 This proposal triggers **mandatory Responsible AI governance review** due to its impact on individuals’ access to financial services.

<br>

<br>

## 🧭 AI Governance Operating Model

<br>

All AI systems must enter a formal governance pipeline before deployment.

<br>

### Key principle:

No AI system progresses without explicit risk assessment, ownership, and approval.

The operating model enforces:

- Risk-based classification
  
- Committee oversight
  
- Go / No-Go decisions
  
- Control enforcement proportional to impact

<br>

![AI Governance Operating Model](https://github.com/user-attachments/assets/1bcb6be3-1c69-4116-860e-2649cdf8bc21)

<br>

## 📝 Responsible AI Risk Assessment

<br>

A Responsible AI Risk Assessment is performed before any deployment decision.

<br>

### Assessment Scope

- Business impact
  
- Regulatory exposure

- Automation risk
  
- Responsible AI pillars:
  
  - Fairness
  - Accountability
  - Transparency
  - Safety & misuse

<br>

### Key Findings

| Risk Area | Assessment |
|------|---------|
| Business Impact | High - decisions affect access to financial servicesw |
| Data & Privacy | High - sensitive personal and financial data processed |
| Fairness | High - historical data may encode bias |
| Accountability | Medium - owners identified, escalation defined |
| Transparency | High - model decisions not fully explainable |
| Safety & Misuse | High - risk of automation bias and over-reliance |

#### Overall Risk Classification: HIGH

Supporting evidence and assessment artifacts are included in /risk-assessment.

<br>

## 🏛️ Governance Committee Review

<br>

The assessment is presented to a cross-functional AI Governance Committee:

- Head of Digital (Business Owner)
  
- CISO / Head of Security
  
- Head of GRC
  
- Legal & Compliance

<br>

The committee evaluates:

- Who is affected by decisions
  
- Regulatory exposure (EU AI Act – High Risk)
  
- Risk by Responsible AI pillar
  
- Control options and residual risk

<br>

### Decision Outcome

✅ **Approved with Conditions**

Full automation is explicitly **not permitted.**

<br>

<br>

## 🔐 Enforced Responsible AI Controls

</details> <details close> <summary> <h3> Control 1: Mandatory Human-in-the-Loop</h3> </summary>

- AI outputs are advisory only

- All rejections require human review

- Final accountability remains with humans

<br>

</details> <details close> <summary> <h3> Control 2: Tiered Decision Model</h3> </summary>

- Low risk → fast-track review

- Medium risk → analyst review

- High risk → senior analyst approval

<br>

</details> <details close> <summary> <h3> Control 3: Transparency & Evidence</h3> </summary>

- Logged:
  
  - Inputs
  - AI recommendations
  - Human overrides
    
- Evidence retained for:
  
  - Audits
  - Customer complaints
  - Regulatory inquiries

<br>

</details> <details close> <summary> <h3> Control 4: Acceptable Use Policy Enforcement</h3> </summary>

- AI cannot be the sole decision-maker
  
- Staff must document rationale when following AI advice
  
- Overrides are encouraged when judgment disagrees

(Policy included in /policies)

<br>

</details> <details close> <summary> <h3> Control 5: Ongoing Monitoring</h3> </summary>

- Quarterly fairness testing

- Drift detection

- Mandatory re-assessment if:
  - Model changes
  - Data sources change
  - Automation level changes

<br>

</details> <br>

## ✔️ Final Outcome

<br>

### Without Governance

- Full automation deployed
  
- High legal and reputational exposure
  
- Low trust in decisions

<br>

### With Governance

- AI safely integrated
  
- Human judgment preserved
  
- Compliance risk reduced
  
- Business value achieved responsibly

<br>

## 📎 Resources

<br>

- [Responsible AI Assessment Checklist](https://github.com/user-attachments/files/24740495/Responsible.AI.Assessment.Checklist.pdf)
  
- [Acceptable Use Policy for AI](https://github.com/user-attachments/files/24740427/Acceptable.Use.Policy.for.Artificial.Intelligence.AI.pdf)

<br>

<br>

<br>
