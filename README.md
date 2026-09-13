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
- Least-privilege security automation
- Durable, auditable response workflows
- Independent verification and controlled rollback
- Evidence-quality and missing-data validation
- Windows and Linux administration
- Networking and vulnerability assessment
- CompTIA Security+ preparation

Next phases expand Business Guardian toward incident reporting, technician operations, AI-assisted investigation, governed adaptive learning, and secure multi-customer operations. These are planned directions, not completed product capabilities.

---

## Featured Project

### [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)

Project Athenaeum started as a way to organize my hands-on cybersecurity work.

Twenty-six labs later, it has become the technical foundation for a much larger security project. Project Athenaeum is completed and published through **Lab 26 — First Dashboard-Controlled Defensive Action**.

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
      ↓
Define the Safety Contract for Controlled Execution
      ↓
Present the Workflow in a Customer Dashboard
      ↓
Prove Authorization and Target Identity
      ↓
Reserve and Execute a Fixed Defensive Action
      ↓
Verify the Outcome Independently
      ↓
Require Separate Authorization for Rollback
      ↓
Restore, Verify, and Audit
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
- Browser-based dashboards with organization-scoped access
- Durable SQLite-backed lifecycle state
- Proof-gated, at-most-once defensive-action dispatch
- Independent verification and separately authorized rollback

The public repository contains sanitized labs, working code, controlled test data, representative outputs, validation evidence, screenshots, and technical documentation.

---

## Current Project Milestone

### Lab 26 — First Dashboard-Controlled Defensive Action

Business Guardian successfully demonstrated its first dashboard-controlled defensive action in an authorized isolated test environment.

The milestone used one fixed defensive capability rather than arbitrary command execution. It required explicit authorization and deterministic pre-execution proof of the organization, target, action, approval, capability, policy, permissions, freshness, and lifecycle state before dispatch.

```text
Dashboard-Proposed Action
      ↓
Deterministic Proof and Explicit Authorization
      ↓
Durable Reservation
      ↓
Exactly One Controlled Defensive Action
      ↓
Independent Outcome Verification
      ↓
Resolution Eligibility Without Automatic Closure
      ↓
Separately Authorized Rollback
      ↓
Exactly One Rollback and Independent Restoration Verification
```

The workflow independently verified the intended result, preserved human closure as a separate decision, then restored and independently verified the original safe state. Durable lifecycle history recorded the process, automatic retry and redispatch remained prohibited, and AI remained advisory rather than execution-authoritative.

Earlier live-validation issues exposed an observation-timing problem. The system failed closed before mutation, the related verification path was corrected, and focused validation passed before the successful controlled retry. That sequence demonstrated safe failure, evidence-driven correction, and successful revalidation.

**Final Lab 26 technical result: COMPLETED AND PUBLISHED**

This is a controlled engineering demonstration, not a claim of production readiness or autonomous remediation. The public repository contains the sanitized Lab 26 architecture, results, and portfolio evidence; product-level implementation remains private.

---

## Business Guardian

Project Athenaeum is also helping me develop a larger cybersecurity concept called **Business Guardian**.

The long-term goal is an affordable, vendor-neutral, AI-assisted security operations platform designed to help smaller organizations understand and respond to security conditions more effectively. The work emphasizes explainable investigation, deterministic safety controls, human-governed response actions, independent verification, auditability, and future learning from verified outcomes.

The intended lifecycle is:

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
Independent Verification
      ↓
Rollback When Required
      ↓
Document and Audit
```

Project Athenaeum publicly demonstrates selected pieces of that progression through sanitized labs.

Private Business Guardian development contains the product-level implementation.

Validated public milestones now demonstrate structured evidence handling, deterministic triage, human-controlled authorization, organization-scoped dashboard workflows, one fixed defensive capability, independent outcome verification, separately authorized rollback, and auditable lifecycle history.

Business Guardian intentionally keeps recommendation, authorization, execution, independent verification, rollback, and final resolution as separate workflow states. It does not expose arbitrary remediation authority, and AI remains advisory.

The private repository is where product-level work belongs, including areas such as:

- Production connectors and adapters
- Investigation workflows
- Proprietary decision and business-risk logic
- Customer and tenant policy configuration
- Production approval workflows
- Controlled defensive-action orchestration
- Independent verification logic
- Controlled rollback mechanisms
- Tenant architecture
- Proprietary orchestration
- Sensitive configuration

Project Athenaeum publicly demonstrates selected, sanitized engineering milestones without publishing the commercial implementation.

Business Guardian remains under development and is not presented as production ready. Planned next phases include incident reporting, technician-facing operations, AI-assisted investigation, governed adaptive learning, and tenant-isolated customer workflows; those capabilities are not yet claimed as implemented.

---

## Home Lab

My home lab gives me a controlled place to build, break, troubleshoot, validate, and restore systems without touching production environments.

Current infrastructure includes:

- Windows 11 host computer
- Oracle VirtualBox
- Microsoft Hyper-V for authorized isolated Business Guardian validation
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

The environment has supported everything from Linux fundamentals and Nmap scanning to Windows telemetry, Wazuh evidence collection, Python processing, structured alert records, deterministic triage, policy and approval validation, live end-to-end investigation testing, and controlled execution-boundary design.

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
- Browser-based, organization-scoped customer workflows
- Durable SQLite-backed lifecycle and administration state
- Deterministic proof and fixed-capability action control
- Durable reservation, at-most-once dispatch, and independent verification
- Separately authorized rollback and immutable lifecycle history

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
- Do not confuse successful execution with successful verification.
- Treat rollback as reversal, not proof that the original security problem is resolved.
- Do not call something resolved until the result has been independently verified.
- Preserve audit history rather than overwriting prior decisions or outcomes.
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

The work leading into that capability matters just as much as the execution itself.

A security system should be able to prove:

```text
Was the action authorized?
        ↓
Was it executed as intended?
        ↓
Did independent evidence verify the result?
        ↓
If it failed, was rollback required and successful?
        ↓
Is there enough evidence to consider the condition resolved?
```

And there is one rule I want to preserve all the way through that lifecycle:

> **Nothing is resolved until the result is verified.**

---

## Connect With Me

- [LinkedIn Profile](https://www.linkedin.com/in/adolph-chapa-a5bb46277)
- [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)
- Additional projects and technical work are available through my GitHub repositories.
