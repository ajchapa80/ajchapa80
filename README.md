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
- Python-based alert explanation
- Multiple-alert processing
- Security-data normalization and validation
- Vendor-neutral alert-processing architecture
- Platform-neutral severity handling
- Missing-field and malformed-data validation
- Per-alert failure isolation
- Batch processing and reporting
- Source traceability and overwrite protection
- Software testing and deterministic validation
- Human-in-the-loop security decision support
- Incident investigation and documentation
- Windows and Linux administration
- Networking and vulnerability assessment
- CompTIA Security+ preparation

## Featured Project

### [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)

Project Athenaeum is my hands-on cybersecurity and information technology portfolio.

Labs 01 through 14 are completed and published with technical documentation, working project files, testing evidence, sanitized screenshots, and selected validation artifacts.

The project has progressed through:

- Technical documentation and lab organization
- Isolated VirtualBox cybersecurity environments
- Linux and Windows administration
- Authorized web-security testing
- Nmap network and service discovery
- Windows endpoint monitoring with Wazuh
- Controlled security-event generation
- Alert review and structured security-data analysis
- Python-based alert explanation
- Software testing and validation
- Vendor-neutral security-data normalization
- Requirements-driven security-tool design
- Multiple-alert batch processing
- Failure isolation and validation handling
- Individual report and batch-summary generation
- Repeatability and overwrite-protection testing

### Current Project Milestone

The newest completed project is **Lab 14: AI Alert Explainer v2 Multiple Alert Processing**.

Lab 14 implemented the architecture designed during Lab 13 and moved the project from single-alert processing to a validated multiple-alert workflow.

The implementation can:

- Discover multiple supported alert files during one execution
- Translate Wazuh-specific data into a normalized alert structure
- Apply platform-neutral severity categories
- Identify missing and malformed information
- Distinguish normal processing, warnings, and failed validation
- Isolate individual failures so one bad alert does not stop the batch
- Generate unique individual analyst reports
- Create batch-level processing summaries
- Preserve source traceability
- Protect previous output from overwrite
- Require human review before security conclusions are made

Lab 14 was tested against acceptance criteria defined before implementation.

The expected result was matched exactly:

- 5 alerts discovered
- 2 processed normally
- 2 processed with warnings
- 1 failed validation
- 4 individual reports created
- 1 batch summary created

A second complete execution produced the same processing result without overwriting the first run.

Labs 11 and 12 remain preserved as the validated single-alert MVP baseline. Lab 13 remains the v2 requirements and design baseline. Lab 14 establishes the validated multiple-alert processing baseline.

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

### Validated Lab Capabilities

- Isolated virtual-network deployment
- Static IPv4 configuration
- Windows and Linux administration
- Authorized vulnerability testing
- Nmap service and network scanning
- End-to-end Windows-to-Wazuh monitoring
- Controlled Windows event and Wazuh alert generation
- Alert-detail, rule-field, and structured security-data review
- Sanitized security-data preparation
- Functional Python AI Alert Explainer MVP
- Plain-language alert report generation
- Missing-file and empty-file testing
- Missing alert-field testing
- Wazuh severity-logic validation
- Stable baseline restoration and verification
- Vendor-neutral normalized alert processing
- Wazuh-to-normalized field translation
- Platform-neutral severity normalization
- Multiple-alert batch processing
- Missing and malformed data validation
- Per-alert failure isolation
- Unique individual report generation
- Batch-summary generation
- Source traceability
- Non-destructive source handling
- Output overwrite protection
- Deterministic acceptance testing
- Repeatable processing validation
- Human-reviewed security decision support

All cybersecurity exercises are performed using personally owned or authorized systems in isolated lab environments.

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

- Bachelor of Science in Cybersecurity with a concentration in Project Management Fundamentals — expected September 2026
- InfoSec Labs Pre-Security Fundamentals Certificate
- InfoSec Labs Alert Investigation Specialist training
- CompTIA Security+ preparation
- Ongoing SOC, EDR, SIEM, endpoint-monitoring, Python, networking, Windows, Linux, and IT support practice
- Continued hands-on development through Project Athenaeum

## Professional Goals

My immediate goal is to begin in an IT support, SOC analyst, cybersecurity support, or public-sector IT role where I can apply practical troubleshooting, documentation, endpoint-monitoring, and security-analysis skills while continuing to build real-world technical experience.

My longer-term goal is to advance into more technical security and systems responsibilities while continuing to develop practical cybersecurity tooling, automation, and investigation skills.

Ultimately, I want to build a cybersecurity and security-services business focused on helping smaller organizations better understand, investigate, and respond to security activity while keeping consequential decisions under appropriate human control.

## Connect With Me

- [LinkedIn Profile](https://www.linkedin.com/in/aj-chapa-a5bb46277)
- [Project Athenaeum](https://github.com/ajchapa80/project-athenaeum)
- Additional projects and technical work are available through my GitHub repositories.
