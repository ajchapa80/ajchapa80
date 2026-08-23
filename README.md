# A.J. Chapa

## Cybersecurity | Information Technology | Security Operations

I enjoy figuring out why something failed, proving what happened, and documenting the solution clearly enough that someone else can follow it.

I recently completed the academic requirements for a Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals, with degree conferral expected in September 2026. Alongside school, I have been building practical experience in security operations, endpoint monitoring, alert investigation, Python automation, Windows and Linux administration, networking, and IT support.

My professional background also includes leadership, public-sector security operations, policy compliance, incident awareness, troubleshooting, customer service, and working in environments where reliability and clear communication matter.

Much of my current technical work is documented through **Project Athenaeum**, a hands-on portfolio that has grown from basic system administration labs into a structured cybersecurity development environment.

---

## What I'm Working On

My current focus is the point where IT troubleshooting, security monitoring, and practical automation meet.

- IT support and technical troubleshooting
- Security operations and alert investigation
- SIEM and Wazuh monitoring
- Windows endpoint telemetry
- Python security automation
- Vendor-neutral security-data processing
- Structured alert records and traceability
- Deterministic alert triage and decision routing
- Evidence-quality and missing-data validation
- Windows and Linux administration
- Networking and vulnerability assessment
- CompTIA Security+ preparation

---

## Featured Project

### [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)

Project Athenaeum started as a way to organize my hands-on cybersecurity work. Sixteen completed labs later, it has become the technical foundation for a much larger security project.

The progression has been intentional:

`Build the lab → Monitor the endpoint → Generate security events → Process alerts → Validate the data → Preserve traceability → Triage the condition → Decide what should happen next`

Along the way, I have worked with:

- VirtualBox lab environments
- Linux and Windows administration
- Authorized web and network security testing
- Wazuh endpoint monitoring
- Controlled security-event generation
- Python-based security-data processing
- Multiple-alert batch processing
- Missing and malformed data
- Failure isolation
- Vendor-neutral JSON alert records
- Source-to-record traceability
- Deterministic cybersecurity triage
- Repeatable testing and validation

The public repository contains sanitized labs, working code, controlled test data, validation evidence, screenshots, and documentation.

---

## Current Project Milestone

### Lab 16 — Alert Triage and Decision Logic

Security alerts rarely arrive with perfect information.

Some match conditions we already understand. Some are missing evidence. Some look unusual. Others simply do not support a confident conclusion yet.

Lab 16 asked a practical question:

**How should a security system decide what happens next without guessing?**

I built a deterministic triage layer that takes the structured alert records created in Lab 15 and routes them toward the next appropriate stage.

The system:

- Preserves the original `AR-...` alert-record identity
- Creates a separate `TR-...` triage-decision identity
- Classifies conditions as `KNOWN_COMMON`, `INSUFFICIENT_DATA`, `UNUSUAL`, or `UNKNOWN`
- Routes records toward `POLICY_EVALUATION` or `INVESTIGATION`
- Gives missing material evidence priority over familiar-looking patterns
- Keeps technical severity separate from the actual triage decision
- Preserves uncertainty rather than inventing an answer
- Records why each decision was made
- Performs no remediation or defensive action

The controlled validation processed five records with **zero failures**:

```text
2 KNOWN_COMMON
1 INSUFFICIENT_DATA
1 UNUSUAL
1 UNKNOWN

2 POLICY_EVALUATION
3 INVESTIGATION
```

A second complete run reproduced the same decisions, preserved every original alert-record identity, generated new triage-decision identities, and left the first run intact.

**Final Lab 16 validation: PASS**

One of the most important lessons from this lab is simple:

> A HIGH-severity alert is not automatically malicious, and a LOW-severity alert is not automatically safe.

Severity is one signal. Evidence still has to support the decision.

Lab 16 is intentionally a **decision-routing layer, not a remediation layer**. A `KNOWN_COMMON` classification does not mean benign or resolved, and `POLICY_EVALUATION` does not authorize an action.

---

## Business Guardian

Project Athenaeum is also helping me develop a larger cybersecurity concept called **Business Guardian**.

The long-term goal is an affordable security platform for smaller organizations that may not have dedicated cybersecurity staff.

The idea is to eventually help a business move through a complete security lifecycle:

```text
Security Event
      ↓
Normalize and Validate
      ↓
Preserve Evidence and Traceability
      ↓
Triage
      ↓
Investigate When Needed
      ↓
Policy / Approval
      ↓
Authorized Defensive Action
      ↓
Verify the Result
      ↓
Document and Audit
```

Private Business Guardian development has already progressed beyond the public portfolio labs. A live read-only Wazuh evidence connector was validated against my isolated lab using both server and indexed evidence paths.

**257 automated tests passed, and final live validation returned PASS.**

The actual connector implementation, investigation workflows, production triage logic, policy and approval systems, defensive-action logic, verification mechanisms, tenant architecture, and other proprietary product work remain private.

Project Athenaeum shows the sanitized engineering progression without duplicating the private product.

---

## Home Lab

My current lab gives me a controlled place to build, break, troubleshoot, validate, and restore systems without touching production environments.

Current infrastructure includes:

- Windows 11 host computer
- Oracle VirtualBox
- Kali Linux security workstation
- Ubuntu Linux practice VM
- Metasploitable 2 vulnerable target
- Windows 11 administration workstation
- Wazuh monitoring server
- Active Wazuh Windows endpoint agent
- Isolated `CyberLab` network
- Isolated `BusinessGuardianLab` network
- NAT and internal-network segmentation
- Local Wazuh dashboard access
- Recovery snapshots at major deployment stages

The environment has supported everything from Linux fundamentals and Nmap scanning to live Windows telemetry, Wazuh evidence collection, Python processing, and deterministic security-triage validation.

---

## What I've Validated

I try not to describe something as working simply because the code runs once.

My labs increasingly use frozen expected results, controlled test data, repeat executions, failure cases, source preservation checks, and documented validation before a capability is treated as stable.

Validated work now includes:

- End-to-end Windows-to-Wazuh monitoring
- Controlled Windows security-event generation
- Python-based alert processing
- Vendor-neutral alert normalization
- Multiple-alert processing
- Missing and malformed data handling
- Per-alert failure isolation
- Structured JSON alert records
- Non-sensitive record identifiers
- Source ID and timestamp preservation
- Ordered processing history
- Alert-to-decision traceability
- Deterministic triage classifications
- Evidence-quality-first rule evaluation
- Severity-independent decision logic
- Investigation and policy-evaluation routing
- Output overwrite protection
- Repeat-processing validation
- Live read-only Wazuh evidence collection

---

## How I Build

My development process is straightforward:

**Build → Test → Validate → Document → Preserve → Extend**

A few rules guide the work:

- Nothing gets built twice.
- Preserve a validated baseline before adding the next capability.
- Define expected behavior before implementation when practical.
- Treat logs, alerts, and external security data as untrusted input.
- Never fabricate missing evidence.
- Keep source-specific integrations separate from reusable processing logic.
- Use deterministic logic for core security decisions.
- Keep consequential actions appropriately human-controlled.
- Do not call something resolved until the result has been verified.
- Publish only sanitized, portfolio-appropriate material.

---

## Education and Development

- Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals — degree conferral expected September 2026
- InfoSec Labs Pre-Security Fundamentals Certificate
- InfoSec Labs Alert Investigation Specialist training
- CompTIA Security+ preparation
- Continued hands-on SOC, SIEM, EDR, endpoint-monitoring, Python, networking, Windows, Linux, and IT support practice

---

## Where I'm Headed

My immediate goal is to move into an IT support, SOC analyst, cybersecurity support, or public-sector IT role where I can contribute practical troubleshooting, documentation, endpoint-monitoring, and security-analysis skills while continuing to grow technically.

Longer term, I want to take on deeper security and systems responsibilities while continuing to build practical cybersecurity tooling and automation.

Ultimately, I want to build security technology that helps smaller organizations understand what is happening in their environment and respond safely. That includes systems capable of performing supported defensive actions when policy and authorization permit, while keeping consequential decisions under appropriate human control and verifying that the action actually solved the problem.

---

## Connect With Me

- [LinkedIn Profile](https://www.linkedin.com/in/aj-chapa-a5bb46277)
- [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)
- Additional projects and technical work are available through my GitHub repositories.
