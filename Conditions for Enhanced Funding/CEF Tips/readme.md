# Conditions for Enhanced Funding (CEF) Tips & Best Practices

## General
- Typically, there is no need to perform separate demonstrations or develop slides for CEFs during the reviews. Providing the appropriate evidence and accounting for discussion time on the review agenda for additional questions from CMS is sufficient. Files uploaded to CMS Box as evidence for CEFs should not be redacted. This includes, but is not limited to, security risk assessments, penetration tests, screenshots, or reports that include PHI/PII.
-	The CEF tab of the Intake Form must be fully completed for both the Operational Readiness Review (ORR) and Certification Review (CR). However, if certain CEF requirements are met during the ORR, the state does not need to go over them during CR, unless there are significant changes to the system or a large time-lapse between ORR and CR (i.e., this may include an annual DR test or the biennial assessment provision).
-	Not every CEF requirement will apply to every system. For example, CEF 17 is related to Eligibility and Enrollment systems and does not apply to a Provider Management module. In this scenario, a state would mark the CEF as “Not Applicable” in the Intake Form and provide a brief explanation as to why the state believes the CEF is not applicable to their system.
-	The term “reporting” either refers to internal quality management, performance reporting, or federal reports (e.g., CMS-37, CMS-64, T-MSIS). In all instances, the system should improve reporting wherever possible in comparison to previous reporting efforts. In addition, the state maintains complete and accurate historical T-MSIS data for program evaluation and the continuous improvement of business operations. The state can demonstrate that data quality issues are meeting the targets for Outcomes Based Assessment (OBA) critical priority data quality checks, high priority data quality checks, and the expenditure data content category. The state should also demonstrate they are working in good faith to resolve issues identified during the file submissions. Generally, CMS will consider the state out of compliance with T-MSIS requirements if it is not meeting the targets for OBA criteria in critical priority data quality checks, high priority data quality checks, and the expenditure data content category and/or the state is not working in good faith to resolve any identified data quality issues. The state must meet all requirements outlined in the T-MSIS Reporting - Standard Operating Procedures (SOP) for any Large System Enhancements (LSEs) affecting T-MSIS reporting.

## Artifacts
-	As shown in the CEF Example Evidence column, 
    -	The most common artifacts for security related CEF are third-party penetration test results, security/privacy assessment report, and plan of action and milestones (POA&M).
    -	The most common artifacts for the non-security-related CEF are typically the APD (AoA and CBA), SS-A, vendor contracts, system design documents, 508 test results, T-MSIS concurrence, ConOps, Disaster Recovery Plans, and Disaster Recovery Test Report.

## 508 Compliance
-	States should produce an objective artifact (e.g., Voluntary Product Accessibility Templates (VPAT)) for their 508-compliance test reports. Alternative formats to VPATs are acceptable as long as the state has performed 508-compliance testing and provides the reports as evidence prior to a review. States can follow tools and techniques at https://www.section508.gov/test or https://accessibility.18f.gov. Note that a VPAT is not an audit, as an audit goes into much greater detail.

## System Architecture
-	States must show how open architecture and vendor communication allows the system to continue performing in a plug-and-play manner despite potential vendor turnover.
-	States should provide a systems diagram that explains its architecture and the interaction between various aspects of the overarching MES ecosystem to demonstrate the larger system structure and how business areas communicate.

## Using Contracts and APDs
-	Certain sections of contractual language with vendors typically contain system cost, leveraging current system functionality, and ownership information. Many times, states do not own the software, although they do own the data and bring that to the vendors; subscription fees are paid to vendors and are documented down to the line level in the APD. The state will need to discuss if the costs are appropriate for the implementation and ensure a data use agreement (DUA) is in place.
-	Certain sections of contractual language from the APD typically contain system cost, leveraging current system functionality, and ownership of data.

## ConOps
-	A Concept of Operations (ConOps) is a user-oriented document that “describes systems characteristics for a proposed system from a user’s perspective. A ConOps also describes the user organization, mission, and objectives from an integrated systems point of view and is used to communicate overall quantitative and qualitative system characteristics to stakeholders.” ConOps documents "should be updated periodically" to reflect evolving situations in the system.[^1]
-	A ConOps “describes the proposed system in terms of the user needs it will fulfill, its relationship to existing systems or procedures, and the ways it will be used. ConOps can be tailored for many purposes, for example, to obtain consensus among the acquirer, developers, supporters, and user agencies on the operational concept of a proposed system. Additionally, a ConOps may focus on communicating the user’s needs to the developer or the developer’s ideas to the user and other interested parties.”[^2]

## Business Continuity & Disaster Recovery
-	A Business Continuity Plan (BCP) and Disaster Recovery (DR) plan should be reviewed annually. A BCP/DR exercise is strongly recommended to be performed annually and should be performed prior to go-live (unless following MARS-E which requires annually). States must have a BCP/DR plan prior to production go-live.  The BCP/DR test results should be provided for ORR, as well as the state’s plan to remediate any findings identified during the exercise.
-	States can hold a tabletop BCP/DR test to meet this provision. However, states should plan for the simulation (end-to-end) testing to ensure their contractors can meet the state’s defined Recovery Time Objective and Recovery Point Objective.
-	Any deficiencies found during the IT system level DR test must be documented in the POA&M (see Reference section below for example template).

## Security & Privacy
-	Internal security and privacy personnel that is not part of the original MES Design, Development, and Implementation (DDI) team can be the independent assessor to evaluate the security and privacy risk posture of the MES module provided they have appropriate qualifications to evaluate the implementation of security and privacy controls. The internal state staff must be familiar with Health Insurance Portability and Accountability Act (HIPAA) regulations, NIST standards, and other applicable federal privacy and cybersecurity regulations and guidance. They must also meet the assessor independence and objectivity qualifications. Furthermore, they must be capable of performing penetration testing and vulnerability scans.
-	States should provide a Security and Privacy Assessment Report (SAR) and Penetration Test report completed by an independent assessor on a periodic basis, at a minimum of every two years per 45 C.F.R. § 95.621(f)(3), to ensure that appropriate, cost-effective safeguards are incorporated into new and existing systems. State agencies must perform risk analyses whenever significant system changes occur. Additional information about meeting security and privacy requirements can be found in the Framework for the Independent Third-Party Security and Privacy Assessment Guidelines for Medicaid Enterprise Systems, also known as Appendix D in the SMC SMDL Guidance Document.
-	Typically, a third-party assessor entity is an independent security and privacy assessment organization, but a SMA’s sister agency can also be leveraged if they have the capabilities and skills to perform this task within the project timeline. DDI vendors cannot perform the security/privacy assessment on their own solution.
-	A third-party Penetration Test is recommended to be performed annually or whenever there are major changes to the system affecting external interfaces, otherwise, at a minimum, of every two years per 45 C.F.R. § 95.621(f)(3). 
-	The purpose of a Security Control Assessment (SCA) is to determine whether the security and privacy controls are implemented correctly, operate as intended, and produce the desired outcomes for meeting the security and privacy requirements of the application or system. The SCA also identifies areas of risk that require the state’s attention and remediation. An independently conducted SCA provides an understanding of:
    -	the MES application or system’s compliance with the state security and privacy control requirements.
    -	the underlying infrastructure’s security posture.
    -	any application and/or system security, data security, and privacy vulnerabilities to be remediated to improve the MES’s security and privacy posture.
    -	the state’s adherence to its security and privacy program, policies, and guidance.
-	At the completion of the SCA, the assessor provides a Security and Privacy Assessment Report (SAR) to the state’s Business Owners, Chief Information Officer (CIO)/Chief Information Security Officer (CISO), who are then responsible for providing the report to CMS. The SAR allows the assessor to communicate the assessment results to several audience levels, ranging from executives to technical staff. The SAR is not a living document. The SAR is a snapshot, findings and vulnerabilities identified should not be added to, removed, or redacted from the SAR.
-	The SAR provides state’s executives, business owners, key stakeholders, and CMS the most objective information possible to make an informed, risk-based, authorization decision. 
-	The SAR should contain a summary of findings that includes ALL findings from the assessment to include documentation reviews, control testing, scanning, penetration testing, interview(s), etc.
-	Only one final SAR should be submitted to CMS. Once that SAR has been submitted and CMS has no additional comments or edits on the SAR, the state and/or MES vendor should not submit additional SARs.
-	All weaknesses/findings/vulnerabilities identified must be in a Plan of Action and Milestones (POA&M) and tracked to closure. The POA&M is a key document in the information security/privacy continuous monitoring activities for managing ongoing security/privacy risk posture for the IT environment.  The POA&M must be submitted with the applicable evidence. Similar findings can be consolidated, just include if and how findings were consolidated on the POA&M; include SAR reference numbers if applicable.  Ensure weakness source references in detail to include type of audit/assessment and applicable date range. Ensure the weakness description is as detailed as possible to include location/server/etc., if applicable. Ensure scheduled completion dates, Milestones with dates, and appropriate risk levels are included. Note: all of the Security and Privacy Assessment Workbook (SAW) findings must be documented in the POA&M, the SAW should not be used as the POA&M as it does not typically include the necessary detail.
-	There is no mandatory required POA&M template based on SMC guidelines.  State can use industry best practice POA&M template such as [FedRAMP POA&M template](https://www.fedramp.gov/2022-06-28-update-poam-template/) or Affordable Care Act (ACA) Administering Entity (AE) POA&M template (see Reference section below). 
-	Ensure risk level determination is properly calculated, especially when weaknesses are identified as part of the Center for Internet Security (CIS) Top 18 Critical Security Controls and/or Open Web Application Security Project (OWASP) Top 10 Web Application Security Risks.
-	CMS expects the state and their MES vendor to ensure appropriate safeguards of the electronic protected health information and personally identifiable information are implemented and maintained. There should be no known, unmitigated very high-risk (critical) or high weaknesses or vulnerabilities. Managing Critical/High weaknesses/vulnerabilities to proper closure is part of the information security continuous monitoring activities. If a state has open Critical/High weaknesses or vulnerabilities during ORR/CR, CMS will issue a Corrective Action Plan (CAP) expecting the state to address those weaknesses/vulnerabilities within 90 days of CR.
-	The term “privacy and security documentation” is used for the CEF 9 and 12 evidence, as well as the Required Artifact called “Independent Security Audit” – although the terms to refer to them may be different, these files are not different files but can be used multiple times.
-	HITRUST certification can be utilized as a SAR. However, a separate independent, third-party penetration test report is still needed unless it is explicitly included in the HITRUST results.
-	Typically, SSAE Type 2 SOC-1 or SOC-2 are not comprehensive enough to demonstrate the security and privacy risk posture for the MES environment, but states have the authority to make an informed risk tolerance decision to leverage these reports. Please ensure the proper scoping of these complementary assessment frameworks provides sufficient assessment boundary to cover the MES IT environment.  It must cover all 5 trusting principles (security, confidentiality, processing integrity, availability, and privacy).
-	If the state cannot provide the evidence for CEF 9, 12, and 18, at least 2 weeks prior to the ORR, the state must develop/use their own Risk Acceptance form as part of their internal governance processes. This risk acceptance would be used to complete the ORR with the understanding the evidence will be submitted when requesting to schedule the CR.
-	The Eligibility and Enrollment (E&E) module has two regulatory authorities: both ACA and HIPAA. MMIS modules follow HIPAA and typically utilize NIST 800-53 (latest revision). E&E uses the MARS-E guidance. Only the state can require that the MMIS modules use MARS-E. 
    -	Any module following MARS-E would have an independent assessment subset and independent penetration test every year (instead of every other year when following NIST). The annual security and privacy assessment requirement, mandated by CMS, requires all security and privacy controls attributable to a system be assessed over a three (3)-year period. To meet this requirement, a subset of the security and privacy controls shall be tested each year so that all controls are tested during a three (3)-year period.
-	The penetration test and a vulnerability scan are two different types of testing. Vulnerability scans look at known risks within the code and infrastructure, while the penetration test simulates a form of hacking. CMS recommends a vulnerability scan, as part of the internal vulnerability management practice, be ran internally monthly, at a minimum. CMS also recommends a third-party independent penetration test be conducted annually, but no less than every two years per 45 C.F.R. § 95.621(f)(3). When faced with conflicting regulations or requirements the most stringent requirement must be followed.

## Continuous Monitoring Activity
-	State and/or MES vendors should provide, at minimum, annual POA&M submissions to CMS as objective evidence for meeting the operational security/privacy metrics reporting.
-	Under HIPAA standards, states must require, through business associate agreements, that contractors and other entities that perform claims processing, third party, or other payment or reimbursement services on their behalf protect the privacy and security of PHI/PII. In so doing, states should ensure that their business associates update their procedures as necessitated by environmental or operational changes affecting security and privacy safeguards. The HIPAA Breach Notification Rule, 45 C.F.R. § 164.400-414, requires HIPAA covered entities and their business associates provide notification following a breach of unsecured protected health information. Similar breach notification provisions implemented and enforced by the Federal Trade Commission (FTC) apply to vendors of personal health records and their third-party service providers, pursuant to section 13407 of the Health Information Technology for Economic and Clinical Health (HITECH) Act.
-	In addition to the above HIPAA requirements, the state, in turn, should immediately report a security or privacy incident or breach, whether discovered by its own staff or reported by a contractor, to the CMS State Officer and CMS IT Service Desk at cms_it_service_desk@cms.hhs.gov. If a state is unable to report breaches to the CMS IT Service Desk via email, the state can contact the CMS IT Service Desk by phone at (800) 562-1963 or (410) 786-2580.
-	The monthly project status report should include important security and privacy events. For example, completing a system security plan (SSP), or managing important steps in completing the independent third-party security and privacy audit and penetration test prior to ORR.

## Additional Resources
- [SMC SMDL Guidance Document](https://www.medicaid.gov/medicaid/data-and-systems/downloads/smc-certification-guidance.pdf)
- [MES Testing Guidance Framework](https://www.medicaid.gov/medicaid/data-and-systems/downloads/mes-testing-guidance-framework.pdf)
- [Operational Report Workbook](https://github.com/CMSgov/CMCS-DSG-DSS-Certification/raw/main/Operational%20Report%20Workbook.xlsx)
- [Transformed Medicaid Statistical Information System (T-MSIS)](https://www.medicaid.gov/medicaid/data-systems/macbis/transformed-medicaid-statistical-information-system-t-msis/index.html)
- [Section 508 Guidance](https://www.section508.gov/test)
- [Accessibility Guidance](https://accessibility.18f.gov)
- [Incident Response](https://www.cms.gov/about-cms/information-systems/privacy/incident-response)
- [Address Gaps in Cybersecurity: HHS OCR releases crosswalk between HIPAA Security Rule and NIST Cybersecurity Framework and NIST SP 800-53 controls](https://www.hhs.gov/guidance/sites/default/files/hhs-guidance-documents//nist-csf-to-hipaa-security-rule-crosswalk-02-22-2016-final.pdf)
- [Risk assessment determination and scale as defined in NIST SP 800-30 Revision 1](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-30r1.pdf), see Appendix G (Likelihood of Occurrence), H (Impact), and I (Risk Determination)
- [PERM](https://www.cms.gov/data-research/monitoring-programs/improper-payment-measurement-programs/payment-error-rate-measurement-perm)
- [Enrollment data performance indicator report](https://www.medicaid.gov/medicaid/national-medicaid-chip-program-information/medicaid-chip-enrollment-data/monthly-medicaid-chip-application-eligibility-determination-and-enrollment-reports-data/index.html)

## References
- [42 C.F.R. § 433.112](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-C/part-433/subpart-C/section-433.112)
- [42 C.F.R. § 433.116](https://www.ecfr.gov/current/title-42/chapter-IV/subchapter-C/part-433/subpart-C/section-433.116)
- [45 C.F.R. §164.308](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C/section-164.308)
- [45 C.F.R. § 95.621](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-A/part-95/subpart-F/subject-group-ECFR8ea7e78ba47a262/section-95.621)
- [Medicaid.gov SMC Site](https://www.medicaid.gov/medicaid/data-systems/certification/streamlined-modular-certification/index.html)
- [State Medicaid Director Letter #22-001](https://www.medicaid.gov/sites/default/files/2023-06/smd22001.pdf)
- [State Medicaid Director Letter #06-022](https://downloads.cms.gov/cmsgov/archived-downloads/SMDL/downloads/SMD092006.pdf)
- [State Medicaid Manual](https://www.cms.gov/Regulations-and-Guidance/Guidance/Manuals/Paper-Based-Manuals-Items/CMS021927)
- [Business Associates](https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/business-associates/index.html)
- [Voluntary Product Accessibility Template (VPAT)](https://www.itic.org/policy/accessibility/vpat), see the latest WCAG version 
- [State Self-Assessment (SS-A)](https://www.medicaid.gov/medicaid/data-systems/medicaid-information-technology-architecture/medicaid-information-technology-architecture-framework/index.html)
- [Example Risk Acceptance Form](https://www.cms.gov/files/document/poamprocedurepdf) (see Attachment D) 
- [Example Concept of Operations template](https://www.nasa.gov/reference/appendix-s-concept-of-operations-annotated-outline/)
- [FedRAMP POA&M template](https://www.fedramp.gov/2022-06-28-update-poam-template/)
- ACA AE templates are posted in CMS zONE which requires additional access. Please ask your state's ACA E&E ISSO for these templates.  

[^1]: [IEEE Computer Society, March 19, 1998, IEEE Guide for Information Technology—System Definition—Concept of Operations (ConOps) Document (IEEE Std 1362-1998)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=761853).
[^2]: [Office of Management and Budget, December 5, 1994, Operational Concept Description (OCD), Data Item Description DI-IPSC-81430](https://www.dau.edu/cop/se/documents/operational-concept-description-ocd-data-item-description-did).
