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

## Business Context & Problem Statement

<br>

The organization faces three critical challenges:

- Manual customer onboarding reviews are **slow and inconsistent**

- Fraud losses continue despite existing controls

- Compliance teams cannot scale current review processes

<br>

The business proposes an AI solution to improve efficiency, but without governance, this would introduce **severe legal, ethical and reputational risks.**

<br>

## Proposed AI Use Case

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

This proposal triggers **mandatory Responsible AI governance review** due to its impact on individuals’ access to financial services.

<br>

## AI Governance Operating Model

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

## 🧪 Responsible AI Risk Assessment

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

⚠️ Full automation is explicitly **not permitted.**

<br>

## 🔐 Enforced Responsible AI Controls

<br>

### Control 1: Mandatory Human-in-the-Loop

- AI outputs are advisory only

- All rejections require human review

- Final accountability remains with humans

<br>

### Control 2: Tiered Decision Model

- Low risk → fast-track review

- Medium risk → analyst review

- High risk → senior analyst approval

<br>

### Control 3: Transparency & Evidence

- Logged:
  
  - Inputs
  - AI recommendations
  - Human overrides
    
- Evidence retained for:
  
  - Audits
  - Customer complaints
  - Regulatory inquiries

<br>

### Control 4: Acceptable Use Policy Enforcement

- AI cannot be the sole decision-maker
  
- Staff must document rationale when following AI advice
  
- Overrides are encouraged when judgment disagrees

(Policy included in /policies)

<br>

### Control 5: Ongoing Monitoring

- Quarterly fairness testing

- Drift detection

- Mandatory re-assessment if:
  - Model changes
  - Data sources change
  - Automation level changes

<br>

## ✅ Final Outcome

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

## 📎 References

<br>

- Responsible AI Assessment Checklist (PDF)
  
- Acceptable Use Policy for AI
  
- Project Slides and Case Walkthrough








<br>

<br>

<br>

<br>





</details> <details close> <summary> <h3> 2️⃣ Responsible AI Risk Assessment</h3> </summary>

Conducted a structured Responsible AI Risk Assessment aligned with:

Fairness

Accountability

Transparency

Safety & misuse

Assessed:

Business impact

Data sensitivity

Automation risk

Human oversight requirements

Assigned an Overall Risk Rating: HIGH

📄 Full assessment available in /risk-assessment.

</details> <details close> <summary> <h3> 3️⃣ Governance Committee Review</h3> </summary>

Presented findings to a cross-functional AI Governance Committee:

Business Owner

Security (CISO / Risk)

Legal & Compliance

GRC

Evaluated:

Who is accountable for AI outcomes

Regulatory and compliance exposure

Residual risk after controls

Resulted in a Go / Conditional Go decision

</details> <details close> <summary> <h3> 4️⃣ Control Design & Enforcement</h3> </summary>

Designed governance and operational controls to mitigate identified risks

Controls scale based on risk level

Focus on preventing:

Automation bias

Unexplainable decisions

Loss of accountability

</details> <details close> <summary> <h3> 5️⃣ Policy & Operational Integration</h3> </summary>

Integrated Responsible AI controls into:

Acceptable Use Policy for AI

Incident response processes

Ongoing monitoring and reassessment

Ensured AI governance is enforced, not just documented

</details> <br>
Responsible AI Risk Assessment Summary
<br>
Risk Area	Assessment
Business Impact	High
Data Sensitivity	High
Fairness Risk	High
Transparency	High
Accountability	Medium
Safety & Misuse	High

📌 Overall Classification:
🔴 HIGH-RISK AI SYSTEM

Supporting artifacts and evidence are included in /risk-assessment.

<br>
Governance Controls Implemented
<details close> <summary> <h3> 🧑‍⚖️ Human-in-the-Loop Enforcement</h3> </summary>

AI outputs are recommendation-only

All negative or adverse outcomes require human review

Final accountability remains with a human decision-maker

</details> <details close> <summary> <h3> 🧠 Tiered Decision Model</h3> </summary>

Low-risk cases → expedited human validation

Medium-risk cases → analyst review

High-risk cases → senior approval

Prevents blind reliance on AI outputs

</details> <details close> <summary> <h3> 📊 Transparency & Auditability</h3> </summary>

Logged and retained:

Inputs

AI recommendations

Human decisions

Overrides

Evidence available for:

Audits

Regulators

Customer disputes

</details> <details close> <summary> <h3> 📜 Acceptable Use Policy for AI</h3> </summary>

Defines approved and prohibited AI uses

Explicitly forbids:

Fully autonomous high-impact decisions

Use of sensitive data without safeguards

Reinforces that AI is not a decision-maker

📄 Policy included in /policies.

</details> <details close> <summary> <h3> 🔄 Ongoing Monitoring & Reassessment</h3> </summary>

Periodic fairness testing

Drift detection

Mandatory reassessment if:

Model logic changes

Data sources change

Automation level increases

</details> <br>
Architecture & Governance Flow
<br> <p align="center"> <img src="PASTE_DIAGRAM_LINK_HERE" height="80%" width="80%" alt="AI Governance Flow"/><br /> <br /> <details close> <summary> <h3> 🏛️ AI Governance Operating Model</h3> </summary>

All AI systems enter a governance pipeline

High-risk systems require:

Formal risk assessment

Committee approval

Control enforcement

No deployment without explicit ownership and accountability

</details> <br>
Key Outcomes
<br>

✅ AI deployed with controlled automation
✅ Human judgment preserved
✅ Regulatory exposure reduced
✅ Decisions are explainable and auditable
✅ Governance scales with risk

<br>
Technologies, Frameworks & Governance Artifacts
<br>

Responsible AI Risk Assessment Checklist

AI Governance Operating Model

Acceptable Use Policy for Artificial Intelligence

Risk-based approval gates

Human-in-the-loop decision enforcement

EU AI Act (High-Risk AI alignment)

Enterprise risk management integration

<br>
Further Resources
<br>

📄 Responsible AI Assessment Checklist (PDF)

📄 Responsible AI Risk Assessment

📄 Acceptable Use Policy for AI

📊 Project Slides & Case Walkthrough

<br>
Conclusion
<br>

This project demonstrates how high-risk AI systems can be governed responsibly through structured risk assessment, enforceable controls, and clear accountability.

Rather than treating Responsible AI as an abstract concept, this approach operationalizes it into real governance decisions, ensuring AI delivers business value without compromising trust, compliance, or human responsibility.

<br>
