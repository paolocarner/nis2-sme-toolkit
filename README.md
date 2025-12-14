# NIS2 Compliance Package for SMBs

A comprehensive, open-source compliance toolkit for small and medium-sized businesses implementing the EU NIS2 Directive (Directive (EU) 2022/2555) cybersecurity requirements.

**Created by Paolo Carner, BARE Consulting**

---

## 📋 Overview

The NIS2 Directive establishes mandatory cybersecurity requirements for essential and important entities across the European Union. This package provides practical, actionable templates and tools to help organizations—particularly those with 50-250+ employees—achieve compliance efficiently.

### What Makes This Different

- **SMB-Focused**: Designed for organizations without dedicated compliance teams
- **Practical Over Theoretical**: Operational playbooks, not abstract frameworks
- **Efficiency-Oriented**: Highlights overlaps with GDPR and ISO 27001 to reduce duplication
- **Evidence-Based**: Uses regulatory language and actual Article references
- **Freely Available**: Released for community benefit



### Format Choice

Documents are provided in **RTF (Rich Text Format)** rather than proprietary formats to ensure:
- **Accessibility**: Can be opened with any word processor (LibreOffice, Word, Google Docs, etc.)
- **Version Control**: Text-based format works better with Git
- **Long-term Viability**: Open standard not tied to specific vendor
- **Editability**: Easy to customize without expensive software


---

## 📦 Package Contents

### 1. NIS2 Gap Assessment & Crosswalk Tool (Excel)
**File**: `NIS2_Gap_Assessment_Tool.xlsx`

Interactive 7-tab workbook for assessing compliance readiness and planning implementation.

**Tabs:**
- **Instructions**: User guide and scoring methodology
- **NIS2 Requirements**: All 21 Article 21(2) controls with baseline vs. enhanced implementations
- **Gap Assessment**: Interactive scoring tool (0-3 maturity scale) with automatic severity calculation
- **GDPR Crosswalk**: 11 overlap areas showing ~55% efficiency opportunity
- **ISO 27001 Crosswalk**: 12 control mappings showing ~75% alignment
- **Priority & Roadmap**: 12-month phased implementation plan (213 person-days estimated)
- **Compliance Dashboard**: Executive summary with roll-up metrics

**Use Case**: Initial assessment, roadmap planning, board reporting, ongoing tracking

---

### 2. NIS2 Executive Briefing (RTF)
**File**: `NIS2_Executive_Briefing.rtf`

12-page board/management presentation document covering regulatory obligations, timeline, and strategic response.

**Sections:**
- Executive Summary (key points for board consideration)
- NIS2 Directive Overview (regulatory objectives, timeline)
- Applicability Assessment (size criteria, sector classification)
- Legal & Financial Consequences (penalties, management accountability)
- Article 21 Security Requirements (all 10 mandatory measures)
- Implementation Roadmap (phased approach, effort estimates)
- Budget & Resource Considerations
- Regional Specifics (Belgium vs. Netherlands)
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
- **Containment Actions**: Incident-specific procedures (ransomware, data breach, DDoS, unauthorized access)
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

**Use Case**: Foundation policy for compliance program, board approval, audit evidence

---

## 🚀 Getting Started

### For Organizations New to NIS2

1. **Read the Executive Briefing** to understand regulatory requirements and timeline
2. **Complete the Gap Assessment Tool** to identify current state and priorities
3. **Review the Incident Response Playbook** to understand notification obligations
4. **Customize the Information Security Policy** as foundation for your program

### For Organizations with Existing Security Programs

1. **Use the Gap Assessment Tool** to map existing controls to NIS2 requirements
2. **Focus on GDPR and ISO 27001 Crosswalk tabs** to identify efficiency opportunities
3. **Integrate the Incident Response Playbook** with existing procedures (focus on 24/72h timelines)
4. **Adapt the Information Security Policy** to align with current governance

---

## 🔧 Customization Guide

All templates use `[ORGANIZATION NAME]` and similar placeholders that should be replaced with your specific information:

- `[ORGANIZATION NAME]` → Your legal entity name
- `[Chief Information Security Officer]` → Actual role title (may be "IT Manager," "Security Officer," etc.)
- `[Management Body / Board]` → Your governance structure
- `[Date]` → Actual effective dates

### Regional Customization

**Belgium**: 
- NIS2 is already law (since October 2024)
- Use CCB (Centre for Cybersecurity Belgium) contact information
- Notification procedures are active

**Netherlands**:
- Implementation expected Q2 2026
- Use NCSC-NL contact information (verify upon implementation)
- Begin compliance preparation now (don't wait for final legislation)

**Other EU Member States**:
- Check national transposition status
- Update CSIRT contact information
- Verify specific notification procedures

---

## 📚 Additional Policy Templates Needed

This package includes the master Information Security Policy. Organizations implementing NIS2 compliance will also need:

**Article 21(2) Coverage:**
- Risk Management Policy (21.2.a)
- Incident Management Policy (21.2.b) ⚠️ Critical
- Business Continuity & Disaster Recovery Policy (21.2.c) ⚠️ Critical
- Third-Party Risk Management Policy (21.2.d)
- Secure Acquisition & Development Policy (21.2.e)
- Vulnerability Management Policy (21.2.f)
- Cryptography & Key Management Policy (21.2.g)
- Human Resources Security Policy (21.2.h)
- Access Control Policy (21.2.i) ⚠️ Critical
- Asset Management Policy (21.2.j)
- Authentication Policy (21.2.k)

Organizations can develop these using the Information Security Policy as a structural template, or engage virtual CISO / security consulting services for policy development.

---

## ⚠️ Important Disclaimers

### Not Legal or Regulatory Advice

This package provides educational resources and templates based on NIS2 requirements. It does **not** constitute:
- Legal advice on regulatory compliance
- Official guidance from competent authorities
- Certification or guarantee of compliance
- Replacement for qualified legal or cybersecurity counsel

Organizations should:
- Consult legal counsel for regulatory interpretation
- Engage qualified cybersecurity professionals for implementation
- Verify requirements with national competent authorities
- Adapt templates to specific organizational context

### Limitations

- Templates are generic and require customization
- Regulatory requirements may evolve
- National implementations vary by member state
- Organizational contexts differ significantly

### No Warranty

This package is provided "AS IS" without warranty of any kind. The authors and contributors assume no liability for any outcomes resulting from use of these materials.

---

## 🤝 Contributing

Contributions are welcome! Ways to contribute:

- **Report Issues**: Found an error or regulatory misalignment? Open an issue
- **Submit Improvements**: Better wording, additional examples, enhanced guidance
- **Regional Specifics**: Help document member state implementation differences
- **Additional Templates**: Contribute additional policy templates or tools
- **Translations**: Help translate materials for broader accessibility

### Contribution Guidelines

1. Maintain educational, vendor-neutral tone
2. Reference specific NIS2 articles when adding requirements
3. Provide both baseline and enhanced implementation examples where applicable
4. Include practical, actionable guidance
5. Test templates with real-world scenarios

---

## 📖 Resources

### Official NIS2 Sources
- [NIS2 Directive Text](https://eur-lex.europa.eu/eli/dir/2022/2555/oj) (EUR-Lex)
- [ENISA NIS2 Resources](https://www.enisa.europa.eu/)

### Belgium
- [Centre for Cybersecurity Belgium](https://ccb.belgium.be/)
- Belgian NIS2 Implementation (October 2024)

### Netherlands  
- [NCSC-NL](https://www.ncsc.nl/)
- Dutch NIS2 Implementation (expected Q2 2026)

### Related Standards
- [GDPR Official Text](https://eur-lex.europa.eu/eli/reg/2016/679/oj)
- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)

---

## 📄 License

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

You are free to:
- **Share**: Copy and redistribute the material
- **Adapt**: Remix, transform, and build upon the material

Under the following terms:
- **Attribution**: You must give appropriate credit to Paolo Carner, BARE Consulting

For commercial use, organizational customization, or derivative works, attribution is required but no additional permissions are needed.

Full license: https://creativecommons.org/licenses/by/4.0/

---

## 👤 About the Author

**Paolo Carner, BARE Consulting**

Paolo is a cybersecurity consultant specializing in European SMB compliance, providing virtual CISO (vCISO) services for organizations implementing NIS2, GDPR, ISO 27001, and other frameworks. 

This package was developed to make enterprise-grade compliance guidance accessible to organizations without dedicated security teams.

**BARE ALLIANCE**: A collaborative network of independent European cybersecurity experts sharing knowledge and resources.

---

## 📮 Contact & Support

- **Issues & Questions**: Use GitHub Issues for template questions or clarifications
- **Professional Services**: Organizations needing implementation support should consider engaging qualified vCISO or security consulting services
- **Community**: Share your experiences and learnings to help others

---

## 🔄 Version History

**Version 1.0** (December 2025)
- Initial release
- 4 core components: Gap Assessment Tool, Executive Briefing, Incident Response Playbook, Information Security Policy
- Coverage for Belgium and Netherlands
- NIS2 Directive Article 21 & 23 focus

---

## 🙏 Acknowledgments

Thanks to the cybersecurity community for knowledge sharing that makes resources like this possible. Special recognition to organizations advancing open compliance frameworks and tools.

---

**Remember**: NIS2 compliance is a journey, not a destination. Start early, plan thoroughly, and build security into your operations rather than treating it as a checkbox exercise. Good cybersecurity practices benefit everyone—regulatory compliance is just one positive outcome.
