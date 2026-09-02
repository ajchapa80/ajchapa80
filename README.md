# A.J. Chapa
## Cybersecurity | Information Technology | Security Operations

I enjoy figuring out why something failed, proving what happened, and documenting the solution clearly enough that someone else can follow it.

I recently completed the academic requirements for a Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals, with degree conferral expected in September 2026.

Alongside school and full-time work, I have been building practical experience in security operations, endpoint monitoring, alert investigation, Python automation, Windows and Linux administration, networking, IT support, and security-focused software development.

My professional background also includes public-sector security operations, team leadership, policy compliance, incident awareness, troubleshooting, customer service, and working in environments where reliability, judgment, and clear communication matter.

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
- Deterministic alert triage
- Security workflow routing
- Policy evaluation and authorization controls
- Human approval workflows
- Fail-closed security design
- Evidence-quality and missing-data validation
- Windows and Linux administration
- Networking and vulnerability assessment
- CompTIA Security+ preparation

---

## Featured Project

### [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)

Project Athenaeum started as a way to organize my hands-on cybersecurity work.

Eighteen completed labs later, it has become the technical foundation for a much larger security project.

The progression has been intentional:

```text
Build the Lab
      ↓
Monitor the Endpoint
      ↓
Generate Security Events
      ↓
Process and Normalize Alerts
      ↓
Validate the Data
      ↓
Preserve Identity and Traceability
      ↓
Triage the Condition
      ↓
Route the Decision
      ↓
Evaluate Policy
      ↓
Require Approval When Necessary
      ↓
Determine Whether Action Is Allowed
      ↓
Validate Live Evidence End to End
      ↓
Route Conservatively to Human Review
```

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
- Policy evaluation
- Approval-state processing
- Fail-closed authorization logic
- Repeatable testing and validation
- Live endpoint-to-investigation traceability
- Read-only evidence-connector validation

The public repository contains sanitized labs, working code, controlled test data, representative outputs, validation evidence, screenshots, and technical documentation.

---

## Current Project Milestone

### Lab 18 — Controlled Adversary Simulation and End-to-End Detection Validation

Labs 15–17 validated the alert-record, triage, policy, and approval controls individually. Lab 18 tested whether those boundaries still held when the project processed live telemetry from the isolated lab.

The validated path was:

```text
Controlled Kali activity
      ↓
Windows endpoint evidence
      ↓
Wazuh detection and traceability
      ↓
Business Guardian read-only evidence collection
      ↓
Investigation workflow
      ↓
HUMAN_REVIEW_REQUIRED
```

Two independent, timestamped runs reproduced the same end-to-end path. Source and endpoint traceability were preserved, and the existing private Business Guardian investigation workflow collected the supporting evidence without duplicating its implementation in the public repository.

The private validation baseline remained **264/264 tests passed**.

**Final Lab 18 technical validation: PASS**

The result demonstrates an integrated security-engineering workflow, not a production-ready security product. Evidence routed conservatively to `HUMAN_REVIEW_REQUIRED`; no remediation or defensive action was executed, and nothing was marked resolved.

Project Athenaeum is now completed and published through **Lab 18** while the product-level implementation remains private.

---

## Business Guardian

Project Athenaeum is also helping me develop a larger cybersecurity concept called **Business Guardian**.

The long-term goal is an affordable security platform designed to help smaller organizations that may not have dedicated cybersecurity staff understand and respond to security conditions more effectively.

The larger lifecycle looks like this:

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

Project Athenaeum publicly demonstrates selected pieces of that progression through sanitized labs.

Private Business Guardian development contains the product-level implementation.

One private milestone involved validating a read-only Wazuh evidence connector against my isolated lab using both server and indexed evidence paths.

That private baseline has since grown to **264/264 tests passed** and remained passing during Lab 18's two live end-to-end validation runs.

The private repository retains areas such as:

- Production connectors
- Investigation workflows
- Production triage logic
- Customer policy catalogs
- Approval workflows
- Business-risk logic
- Action-selection logic
- Defensive-action adapters
- Verification mechanisms
- Rollback logic
- Tenant architecture
- Proprietary orchestration
- Sensitive configuration

Project Athenaeum shows meaningful engineering progress without publishing the commercial implementation.

---

## Home Lab

My home lab gives me a controlled place to build, break, troubleshoot, validate, and restore systems without touching production environments.

Current infrastructure includes:

- Windows 11 host computer
- Oracle VirtualBox
- Microsoft Hyper-V for the validated three-VM Lab 18 environment
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

The environment has supported everything from Linux fundamentals and Nmap scanning to Windows telemetry, Wazuh evidence collection, Python processing, structured alert records, deterministic triage, and policy/approval validation.

---

## What I've Validated

I try not to describe something as working simply because the code runs once.

My labs increasingly use frozen expected results, controlled test data, repeat executions, failure cases, source-preservation checks, safety boundaries, and documented validation before a capability is treated as stable.

Validated work now includes:

- End-to-end Windows-to-Wazuh monitoring
- Controlled Windows security-event generation
- Python-based alert processing
- Vendor-neutral alert normalization
- Multiple-alert processing
- Missing and malformed-data handling
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
- Policy Decision records
- Approval Records
- `AR → TR → PD → AP` traceability
- Explicit approval-state handling
- Investigation-gate protection
- Unsupported-action denial
- Fail-closed authorization behavior
- Output overwrite protection
- Repeat-processing validation
- Live read-only Wazuh evidence collection
- Repeatable live endpoint-to-investigation validation
- Conservative routing to `HUMAN_REVIEW_REQUIRED`

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
- Do not treat technical severity as a verdict.
- Do not treat a recommendation as authorization.
- Require explicit approval when policy requires it.
- Fail closed when safe authorization cannot be established.
- Keep consequential actions appropriately human-controlled.
- Do not call something resolved until the result has been verified.
- Publish only sanitized, portfolio-appropriate material.

---

## Education and Development

- Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals — academic requirements completed, degree conferral expected September 2026
- InfoSec Labs Pre-Security Fundamentals Certificate
- InfoSec Labs Alert Investigation Specialist training
- CompTIA Security+ preparation
- Continued hands-on SOC, SIEM, EDR, endpoint-monitoring, Python, networking, Windows, Linux, and IT support practice

---

## Where I'm Headed

My immediate goal is to move into an IT support, SOC analyst, cybersecurity support, or public-sector IT role where I can contribute practical troubleshooting, documentation, endpoint-monitoring, security-analysis, and automation skills while continuing to grow technically.

Longer term, I want to take on deeper security and systems responsibilities while continuing to build practical cybersecurity tooling and automation.

Ultimately, I want to build security technology that helps smaller organizations understand what is happening in their environment and respond safely.

That includes systems capable of eventually performing supported defensive actions when policy and authorization permit, while keeping consequential decisions under appropriate human control.

And there is one rule I want to preserve all the way through that lifecycle:

> **Nothing is resolved until the result is verified.**

---

## Connect With Me

- [LinkedIn Profile](https://www.linkedin.com/in/adolph-chapa-a5bb46277)
- [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)
- Additional projects and technical work are available through my GitHub repositories.
