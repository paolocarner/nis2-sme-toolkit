# NIS2 Compliance Package for SMBs

A practical, open-source compliance toolkit for small and medium-sized businesses implementing the EU NIS2 Directive (Directive (EU) 2022/2555) cybersecurity requirements.

**Created by Paolo Carner, BARE Consulting**

---

> **Looking for the interactive version?**
> The NIS2 Supplier Readiness Check — a guided assessment that identifies your specific exposure level and gaps — is available at **[bare-consult.com/nis2-vendor-check](https://www.bare-consult.com/nis2-vendor-check)**.
> This repository contains the underlying template library for organisations that want to self-implement.

---

## Overview

The NIS2 Directive establishes mandatory cybersecurity requirements for essential and important entities across the European Union. This package provides practical, actionable templates and tools to help organisations — particularly those with 50–250+ employees — achieve compliance efficiently.

### What Makes This Different

- **SMB-Focused**: Designed for organisations without dedicated compliance teams
- **Practical Over Theoretical**: Operational playbooks, not abstract frameworks
- **Efficiency-Oriented**: Highlights overlaps with GDPR and ISO 27001 to reduce duplication
- **Evidence-Based**: Uses regulatory language and actual Article references
- **Freely Available**: Released under CC BY 4.0 for community benefit

### Format Choice

Documents are provided in **RTF (Rich Text Format)** rather than proprietary formats to ensure:
- **Accessibility**: Can be opened with any word processor (LibreOffice, Word, Google Docs, etc.)
- **Version Control**: Text-based format works better with Git
- **Long-term Viability**: Open standard not tied to a specific vendor
- **Editability**: Easy to customise without expensive software

---

## Package Contents

### 1. NIS2 Gap Assessment & Crosswalk Tool (Excel)
**File**: `NIS2_Gap_Assessment_Tool.xlsx`

Interactive 7-tab workbook for assessing compliance readiness and planning implementation.

**Tabs:**
- **Instructions**: User guide and scoring methodology
- **NIS2 Requirements**: All 21 Article 21(2) controls with baseline vs. enhanced implementations
- **Gap Assessment**: Interactive scoring tool (0–3 maturity scale) with automatic severity calculation
- **GDPR Crosswalk**: 11 overlap areas showing ~55% efficiency opportunity for organisations already GDPR-compliant
- **ISO 27001 Crosswalk**: 12 control mappings showing ~75% alignment for organisations already certified
- **Priority & Roadmap**: 12-month phased implementation plan (213 person-days estimated)
- **Compliance Dashboard**: Executive summary with roll-up metrics

**Use Case**: Initial assessment, roadmap planning, board reporting, ongoing tracking

---

### 2. NIS2 Executive Briefing (RTF)
**File**: `NIS2_Executive_Briefing.rtf`

12-page board/management document covering regulatory obligations, timeline, and strategic response.

**Sections:**
- Executive Summary (key points for board consideration)
- NIS2 Directive Overview (regulatory objectives, timeline)
- Applicability Assessment (size criteria, sector classification)
- Legal & Financial Consequences (penalties, management accountability)
- Article 21 Security Requirements (all 10 mandatory measures)
- Implementation Roadmap (phased approach, effort estimates)
- Budget & Resource Considerations
- Regional Specifics (Belgium and Netherlands)
- Recommended Next Steps

**Use Case**: Board presentations, management briefings, compliance justification, budget requests

---

### 3. NIS2 Incident Response Playbook (RTF)
**File**: `NIS2_Incident_Response_Playbook.rtf`

20+ page operational playbook for managing cybersecurity incidents under Article 23 notification requirements.

**Key Content:**
- **Incident Classification Framework**: 4-level severity matrix with notification thresholds
- **7-Phase Process**: Detection → Classification → 24h Early Warning → Containment → Investigation → 72h Report → Recovery
- **Critical Timelines**: 24-hour early warning, 72-hour detailed notification, 1-month final report
- **Regional Procedures**: Belgium (CCB) and Netherlands (NCSC-NL) contact information
- **Roles & Responsibilities**: 6 key incident response roles with decision authority
- **Containment Actions**: Incident-specific procedures (ransomware, data breach, DDoS, unauthorised access)
- **Evidence Collection**: Forensic procedures and checklists
- **Tools & Templates**: Required documentation and readiness requirements

**Use Case**: Incident response operations, team training, compliance demonstrations, regulatory submissions

---

### 4. Information Security Policy (RTF)
**File**: `Policy_Information_Security.rtf`

3-page high-level master security policy template satisfying NIS2 Article 21(2)(a) requirements.

**Sections:**
- Purpose & Scope
- Regulatory Alignment (NIS2, GDPR, ISO 27001)
- Roles & Responsibilities
- Policy Statements (7 areas: Governance, Risk, Assets, Access, Incidents, Training, Third Parties)
- Implementation Guidance (Baseline vs. Enhanced maturity levels)
- Exceptions Process
- Compliance & Review
- Document Control

**Use Case**: Foundation policy for compliance programme, board approval, audit evidence

---

## Getting Started

### For Organisations New to NIS2

1. **Read the Executive Briefing** to understand regulatory requirements and timeline
2. **Complete the Gap Assessment Tool** to identify current state and priorities
3. **Review the Incident Response Playbook** to understand notification obligations
4. **Customise the Information Security Policy** as foundation for your programme

### For Organisations with Existing Security Programmes

1. **Use the Gap Assessment Tool** to map existing controls to NIS2 requirements
2. **Focus on the GDPR and ISO 27001 Crosswalk tabs** to identify efficiency opportunities
3. **Integrate the Incident Response Playbook** with existing procedures (focus on 24/72h timelines)
4. **Adapt the Information Security Policy** to align with current governance

---

## Customisation Guide

All templates use `[ORGANIZATION NAME]` and similar placeholders. Replace with your specific information:

- `[ORGANIZATION NAME]` → Your legal entity name
- `[Chief Information Security Officer]` → Actual role title (may be "IT Manager," "Security Officer," etc.)
- `[Management Body / Board]` → Your governance structure
- `[Date]` → Actual effective dates

### Regional Notes

**Belgium**
- NIS2 is enforceable (in force October 2024)
- Use CCB (Centre for Cybersecurity Belgium) contact information
- Notification procedures are active

**Netherlands**
- Cyberbeveiligingswet (Cbw) approved by Tweede Kamer on 15 April 2026
- Eerste Kamer (Senate) review is pending as of May 2026 — entry into force expected imminently
- The existing Wbni remains applicable until the Cbw enters into force
- Begin compliance preparation now — the law will apply with little transition time once enacted

**Other EU Member States**
- As of April 2026, 26 of 27 EU member states have enacted NIS2 into national law
- Verify current enforcement status and CSIRT contact information for your jurisdiction
- Check [ECSO NIS2 Transposition Tracker](https://ecs-org.eu/policy/nis2-directive-transposition-tracker/) for current status

---

## Scope of This Package

This package includes the master Information Security Policy as a foundation document. A full NIS2 compliance programme also requires subsidiary policies covering each Article 21(2) measure:

- Risk Management Policy (21.2.a)
- Incident Management Policy (21.2.b)
- Business Continuity & Disaster Recovery Policy (21.2.c)
- Third-Party Risk Management Policy (21.2.d)
- Secure Acquisition & Development Policy (21.2.e)
- Vulnerability Management Policy (21.2.f)
- Cryptography & Key Management Policy (21.2.g)
- Human Resources Security Policy (21.2.h)
- Access Control Policy (21.2.i)
- Asset Management Policy (21.2.j)
- Authentication Policy (21.2.k)

These can be developed using the Information Security Policy as a structural template. Organisations that need a complete, customised policy framework — or board-ready documentation — should consider engaging a qualified vCISO or security consultant.

---

## Important Disclaimers

### Not Legal or Regulatory Advice

This package provides educational resources and templates based on NIS2 requirements. It does **not** constitute:
- Legal advice on regulatory compliance
- Official guidance from competent authorities
- Certification or guarantee of compliance
- A replacement for qualified legal or cybersecurity counsel

Organisations should:
- Consult legal counsel for regulatory interpretation
- Engage qualified cybersecurity professionals for implementation
- Verify requirements with national competent authorities
- Adapt templates to their specific organisational context

### Limitations

- Templates are generic and require customisation
- Regulatory requirements may evolve
- National implementations vary by member state
- Organisational contexts differ significantly

### No Warranty

This package is provided "AS IS" without warranty of any kind. The authors and contributors assume no liability for any outcomes resulting from use of these materials.

---

## Contributing

Contributions are welcome:

- **Report Issues**: Found an error or regulatory misalignment? Open an issue
- **Submit Improvements**: Better wording, additional examples, enhanced guidance
- **Regional Specifics**: Help document member state implementation differences
- **Additional Templates**: Contribute additional policy templates or tools

### Contribution Guidelines

1. Maintain educational, vendor-neutral tone
2. Reference specific NIS2 articles when adding requirements
3. Provide both baseline and enhanced implementation examples where applicable
4. Include practical, actionable guidance
5. Test templates with real-world scenarios

---

## Resources

### Official NIS2 Sources
- [NIS2 Directive Text](https://eur-lex.europa.eu/eli/dir/2022/2555/oj) (EUR-Lex)
- [ENISA NIS2 Resources](https://www.enisa.europa.eu/)
- [ECSO NIS2 Transposition Tracker](https://ecs-org.eu/policy/nis2-directive-transposition-tracker/)

### Belgium
- [Centre for Cybersecurity Belgium (CCB)](https://ccb.belgium.be/)

### Netherlands
- [NCSC-NL](https://www.ncsc.nl/)
- [Cyberbeveiligingswet — Dutch Government](https://www.nldigitalgovernment.nl/nis2-directive-cyberbeveiligingswet-cbw/)

### Related Standards
- [GDPR Official Text](https://eur-lex.europa.eu/eli/reg/2016/679/oj)
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)

---

## License

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

You are free to:
- **Share**: Copy and redistribute the material
- **Adapt**: Remix, transform, and build upon the material

Under the following terms:
- **Attribution**: You must give appropriate credit to Paolo Carner, BARE Consulting

Full license: https://creativecommons.org/licenses/by/4.0/

---

## About the Author

**Paolo Carner — Founder & Principal vCISO, BARE Consulting B.V.**
CISSP · CCSP · ISSMP

Paolo is a cybersecurity consultant with 15+ years of enterprise security experience, specialising in compliance programmes for European tech scaleups. BARE Consulting provides fractional vCISO services to B2B SaaS companies navigating ISO 27001, SOC 2, NIS2, and DORA.

This toolkit was developed to make practical NIS2 guidance accessible to organisations without dedicated security teams.

**Website**: [bare-consult.com](https://www.bare-consult.com)
**Interactive tool**: [bare-consult.com/nis2-vendor-check](https://www.bare-consult.com/nis2-vendor-check)

---

## Version History

**Version 1.1** (May 2026)
- Updated Netherlands transposition status: Tweede Kamer approved Cyberbeveiligingswet on 15 April 2026; Eerste Kamer review pending
- Added redirect to live interactive tool at bare-consult.com/nis2-vendor-check
- Updated regional notes to reflect 26/27 EU member states now with enacted national law
- Reframed subsidiary policy section as scope boundary rather than outstanding work

**Version 1.0** (December 2025)
- Initial release
- 4 core components: Gap Assessment Tool, Executive Briefing, Incident Response Playbook, Information Security Policy
- Coverage for Belgium and Netherlands
- NIS2 Directive Article 21 & 23 focus
