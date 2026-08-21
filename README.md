# A.J. Chapa

## Cybersecurity and Information Technology Professional

I am completing a Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals while building practical experience in security operations, alert investigation, endpoint monitoring, Python security automation, Windows and Linux administration, networking, and IT support.

My background includes leadership, public-sector security operations, troubleshooting, policy compliance, documentation, incident awareness, customer service, and working in environments where reliability and clear communication matter.

My current technical development is centered on hands-on SOC, cybersecurity, and IT work documented through Project Athenaeum.

## Current Focus

- IT support and technical troubleshooting
- Security operations and alert investigation
- SIEM and Wazuh monitoring
- Windows endpoint telemetry
- Python security automation
- Vendor-neutral security-data normalization
- Structured alert records and traceability
- Deterministic alert triage and decision routing
- Evidence-quality and missing-data validation
- Multiple-alert processing and failure isolation
- Severity-independent security decision logic
- Uncertainty preservation and investigation routing
- Deterministic testing and validation
- Human-in-the-loop security decision support
- Windows and Linux administration
- Networking and vulnerability assessment
- CompTIA Security+ preparation

## Featured Project

### [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)

Project Athenaeum is my hands-on cybersecurity and information technology portfolio.

Labs 01 through 16 are complete and published with technical documentation, working project files, sanitized test data, validation evidence, screenshots, and selected project artifacts.

The project has progressed through:

- Technical documentation and isolated lab design
- Linux and Windows administration
- Authorized web and network security testing
- Windows endpoint monitoring with Wazuh
- Controlled security-event generation
- Structured security-data analysis
- Python-based alert processing
- Deterministic software testing and validation
- Vendor-neutral alert normalization
- Multiple-alert batch processing
- Missing- and malformed-data handling
- Failure isolation and non-destructive processing
- Structured JSON alert records
- Persistent source-to-record traceability
- Deterministic alert triage
- Evidence-quality-first decision logic
- Separate alert and triage decision identities
- Next-stage security workflow routing
- Repeat-processing and overwrite-protection validation

### Current Project Milestone

The newest completed public project is **Lab 16 — Alert Triage and Decision Logic**.

Lab 16 extends the validated Lab 15 alert-record foundation into deterministic, vendor-neutral cybersecurity triage.

The implementation:

- Preserves original `AR-...` alert-record identities
- Creates separate `TR-...` triage-decision identities
- Classifies supported conditions as `KNOWN_COMMON`, `INSUFFICIENT_DATA`, `UNUSUAL`, or `UNKNOWN`
- Routes records toward `POLICY_EVALUATION` or `INVESTIGATION`
- Gives material evidence-quality problems priority over recognizable patterns
- Keeps technical severity separate from triage classification
- Preserves uncertainty instead of guessing
- Records chronological decision history
- Performs no remediation or defensive action

Controlled validation processed five records with zero failures:

`2 KNOWN_COMMON / 1 INSUFFICIENT_DATA / 1 UNUSUAL / 1 UNKNOWN`

Routing produced:

`2 POLICY_EVALUATION / 3 INVESTIGATION`

A second complete execution reproduced the same results, preserved the original alert-record identities, generated new triage-decision identities, and left previous output intact.

**Final Lab 16 validation: PASS**

Lab 16 demonstrates decision routing, not remediation. A known/common classification does not mean an alert is benign or resolved, and policy evaluation does not authorize defensive action.

Private Business Guardian development continues separately. Production investigation, policy, approval, defensive-action, verification, audit, tenant, and other proprietary product capabilities remain private.

## Home Lab

My current lab infrastructure includes:

- Windows 11 host computer
- Oracle VirtualBox
- Kali Linux security workstation
- Ubuntu Linux practice virtual machine
- Metasploitable 2 vulnerable target
- Windows 11 administration lab
- VirtualBox Internal Network: `CyberLab`
- CyberLab subnet: `192.168.56.0/24`
- BusinessGuardian-Win11-Workstation: `192.168.70.10/24`
- Wazuh Monitoring Server: `192.168.70.20/24`
- Active Wazuh Windows endpoint agent
- VirtualBox Internal Network: `BusinessGuardianLab`
- BusinessGuardianLab subnet: `192.168.70.0/24`
- NAT and isolated internal-network segmentation
- Local Wazuh dashboard access through VirtualBox port forwarding
- Clean recovery snapshots for major deployment stages

## Validated Lab Capabilities

- Isolated virtual-network deployment
- Windows and Linux administration
- Authorized vulnerability and network testing
- End-to-end Windows-to-Wazuh monitoring
- Controlled Windows event and alert generation
- Structured security-data review
- Python-based alert processing
- Vendor-neutral alert normalization
- Multiple-alert batch processing
- Missing- and malformed-data validation
- Per-alert failure isolation
- Structured JSON alert records
- Non-sensitive alert-record identifiers
- Source ID and timestamp preservation
- Ordered processing history
- Source-to-record traceability
- Deterministic alert triage
- Separate triage-decision identities
- Evidence-quality-first rule evaluation
- Severity-independent classification
- Explicit uncertainty preservation
- Investigation and policy-evaluation routing
- Non-destructive source handling
- Output overwrite protection
- Deterministic acceptance testing
- Repeat-processing validation
- Live read-only Wazuh evidence validation
- Human-reviewed consequential security decisions

## Development Approach

My project work follows a build, validate, document, and extend approach.

- Preserve validated work rather than rebuilding it unnecessarily
- Define expected behavior before implementation when practical
- Test changes before treating them as stable
- Preserve stable baselines before adding new capabilities
- Keep source-specific data separate from reusable processing logic
- Use deterministic logic for core parsing, validation, normalization, and control decisions
- Identify missing or malformed information rather than fabricate values
- Preserve source evidence and traceability
- Keep human review involved in consequential security decisions
- Publish only sanitized, portfolio-appropriate material

## Education and Development

- Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals — degree conferral expected September 2026
- InfoSec Labs Pre-Security Fundamentals Certificate
- InfoSec Labs Alert Investigation Specialist training
- CompTIA Security+ preparation
- Ongoing SOC, EDR, SIEM, endpoint-monitoring, Python, networking, Windows, Linux, and IT support practice
- Continued hands-on development through Project Athenaeum

## Professional Goals

My immediate goal is to begin in an IT support, SOC analyst, cybersecurity support, or public-sector IT role where I can apply practical troubleshooting, documentation, endpoint-monitoring, and security-analysis skills while continuing to build real-world technical experience.

My longer-term goal is to advance into more technical security and systems responsibilities while continuing to develop practical cybersecurity tooling, automation, and investigation skills.

Ultimately, I want to build cybersecurity technology that helps smaller organizations monitor, understand, investigate, and respond to security activity. My long-term goal is to develop systems that can perform supported defensive actions when policy and authorization permit, while keeping consequential decisions under appropriate human control and verifying that actions actually resolved the issue.

## Connect With Me

- [LinkedIn Profile](https://www.linkedin.com/in/aj-chapa-a5bb46277)
- [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)
- Additional projects and technical work are available through my GitHub repositories.
