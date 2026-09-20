---
title: "EAA Scope and Applicability Gate"
subtitle: "A mandatory governance control before applying European Accessibility Act requirements to a product, service, website, application, or digital channel"
version: "1.0"
date: "2026-09-20"
status: "Canonical scope-control framework"
authority_type: "Governance procedure and practitioner guidance"
legal_status: "Not legislation, regulator guidance, or legal advice"
jurisdiction_scope: "European Union; final decisions require applicable national implementing law"
canonical_legal_source: "Directive (EU) 2019/882 and applicable national legislation"
decision_owner: "Named legal or compliance reviewer with the business or service accountable owner"
review_triggers:
  - "Change to the product, service, digital channel, economic-operator role, territory, contract, or customer population"
  - "Change to EU or national law, regulator guidance, enforcement practice, harmonised standards, common specifications, or transitional provisions"
  - "New exemption, fundamental-alteration, or disproportionate-burden claim"
  - "Material complaint, investigation, enforcement contact, or contradictory evidence"
ai_ingestion_guidance:
  - "Retrieve and complete this gate before applying any EAA requirement or making an EAA compliance claim."
  - "Do not assume that every website, online application, or mobile application is within EAA scope."
  - "Do not apply product requirements to a service channel, or service requirements to a product, without a recorded legal mapping."
  - "Do not treat Annex I Section VII functional performance criteria as universal requirements; record why they are applicable."
  - "Preserve exact legal wording and distinguish it from a paraphrase, design interpretation, organisational policy, and research evidence."
  - "Do not infer scope or compliance from WCAG conformance, a VPAT, an automated audit, user satisfaction, complaints, or the absence of complaints."
  - "Do not approve an exemption, exception, departure, fundamental alteration, or disproportionate burden. Route the matter to the named human authority."
  - "When national law, current source status, or applicability is missing, return 'legal review required' rather than inventing a conclusion."
---

# EAA Scope and Applicability Gate

## Purpose

This document defines the mandatory decision gate that must be completed before the European Accessibility Act is applied to a product, service, website, application, digital channel, requirement, test, or compliance claim.

It prevents three common errors:

1. treating every website or application as directly covered by the EAA;
2. applying a requirement from the wrong part of Annex I; and
3. treating design practice, technical conformance, or positive user evidence as a complete legal conclusion.

This is a governance procedure, not a legal opinion. The final scope and conformity decision must use the law and authoritative material applicable to the relevant Member State and service context.

## Non-negotiable rule

> No EAA requirement, exemption, conformity statement, or compliance claim may be applied until the organisation has recorded what is being supplied, the relevant economic-operator role, the potential Article 2 scope category, the applicable national law, the applicable Annex I sections, and the named human authority for the decision.

The presence of a website, online application, or mobile application is not itself sufficient to establish EAA scope. The digital channel must be connected to a covered product or service and assessed in its legal and operational context.

## Permitted gate outcomes

The gate must produce one of the following outcomes:

| Outcome | Meaning | Next action |
|---|---|---|
| `in scope` | The recorded product or service, organisation role, territory, channel, and relevant date are within the applicable national legislation. | Map the applicable Annex I clauses and evidence obligations. |
| `partly in scope` | Only defined products, services, features, territories, channels, contracts, or periods are covered. | Record the included and excluded boundaries separately. |
| `out of scope` | The recorded facts do not bring the subject within the identified EAA provisions. | Preserve the rationale; consider applying the Double FW inclusive-design baseline voluntarily. |
| `exempt or subject to a specific limitation` | A recognised exemption, transition, fundamental-alteration decision, disproportionate-burden decision, or other legal limitation may apply. | Record the exact legal basis, authorised decision, scope, evidence, notification or publication duties, review conditions, and expiry where applicable. |
| `legal review required` | National law, material facts, source status, or interpretation is absent, current applicability is uncertain, or authorities disagree. | Do not make an EAA compliance claim. Escalate to the named legal or compliance authority. |

An `out of scope` decision means that this EAA route has not been established. It does not mean that no other accessibility, equality, consumer, sector, procurement, employment, or contractual duty applies.

## Mandatory applicability record

### Gate 1 — Define the subject

Record:

- the product, service, feature, transaction, content, support function, and digital channel being assessed;
- whether the subject is supplied to consumers, employees, businesses, public bodies, or another population;
- the provider, supplier, contracting entities, and relevant third parties;
- the territories in which it is placed on the market, supplied, contracted, or used;
- the relevant release, contract, operating period, and assessment date; and
- the parts deliberately excluded from the decision.

Do not use a broad label such as “the website” when only a specific service or transaction is being assessed.

### Gate 2 — Identify the economic-operator role

Record whether the organisation acts as a:

- manufacturer;
- authorised representative;
- importer;
- distributor;
- service provider; or
- combination of roles.

The duties and evidence requirements differ by role. A group company, platform operator, reseller, supplier, and customer-facing service owner must not be assumed to hold the same legal responsibilities.

### Gate 3 — Identify the potential Article 2 category

Record the exact category that may bring the product or service within scope. Do not infer coverage merely because the subject is digital or available in the European Union.

Potentially relevant categories include specified consumer computer hardware and operating systems, certain self-service terminals, consumer terminal equipment, electronic communications services, services providing access to audiovisual media services, specified passenger-transport service elements, consumer banking services, e-books and dedicated software, and e-commerce services.

The category name is a routing decision, not the final legal conclusion. Definitions, exclusions, sector legislation, customer status, and national implementation must still be checked.

### Gate 4 — Identify applicable national law and authority

For every relevant Member State, record:

- the national implementing legislation and current version;
- the competent regulator, market-surveillance authority, or enforcement body;
- applicable definitions, exclusions, procedures, documentation duties, notification duties, penalties, and remedies;
- relevant binding decisions or current official guidance; and
- the legal or compliance reviewer who verified the information and the verification date.

The Directive provides the common EU framework. Operational compliance and enforcement must be assessed through the applicable national implementation and other relevant law.

### Gate 5 — Check dates and transitional provisions

Record:

- when the relevant national requirements began to apply;
- the date the product was placed on the market or the service began;
- relevant contract dates;
- whether an existing product, service, contract, or self-service terminal benefits from a transitional provision; and
- when any transition ends or must be reviewed.

Do not treat the principal application date as the only relevant date.

### Gate 6 — Check exclusions, exemptions, and legally controlled limitations

Check and document whether the national implementation recognises a relevant:

- exclusion from scope;
- exemption for a microenterprise providing services;
- transitional provision;
- fundamental-alteration assessment;
- disproportionate-burden assessment; or
- sector-specific limitation.

These are legally controlled decisions, not routine product exceptions. They must not be approved through ordinary release-risk delegation unless the applicable legal framework expressly permits that authority. The record must identify the exact legal basis, evidence, authorised decision-maker, affected scope, required notifications or publications, review conditions, and continuing duties.

Cost, inconvenience, delivery delay, low usage, a small research sample, or positive satisfaction data must not be treated as an exemption without the required legal assessment.

### Gate 7 — Route to the applicable Annex I sections

| Annex I section | Primary use | Application control |
|---|---|---|
| Section I | General requirements for covered products | Apply only to a covered product and the relevant product functions or information. |
| Section II | Additional requirements for specified products | Apply only to the relevant covered product category. |
| Section III | General requirements for covered services | Use as the general starting point for an in-scope service, including relevant service information, websites, applications, and support services. |
| Section IV | Additional requirements for specified services | Apply only to the relevant service category and functions. |
| Section V | Requirements concerning emergency communications to 112 | Apply only in the legally defined emergency-communications context. |
| Section VI | Requirements used by other Union acts | Apply only where the relevant legal route invokes them. |
| Section VII | Functional performance criteria | Use when the applicable requirements in Sections I to VI do not address one or more relevant design or performance functions, or where the legal framework otherwise permits their use. Record the gap and rationale. |

Do not convert Section VII into a universal user-group checklist detached from its legal role. It may also provide a valuable inclusive-design lens, but that broader use must be labelled as organisational policy or design interpretation rather than direct EAA obligation.

### Gate 8 — Approve and preserve the decision

The applicability record must identify:

- the legal or compliance reviewer;
- the business or service accountable owner;
- the decision date and evidence set;
- unresolved interpretation or factual questions;
- included and excluded scope;
- review triggers and next review date; and
- any required escalation.

The product or service owner may prepare the record but must not approve the legal scope decision unless formally authorised for that role. An AI system may assemble evidence and expose gaps but must not approve the decision.

## Clause-level requirement record

After the gate confirms that a legal route applies, create one record for each requirement.

| Field | Required content |
|---|---|
| Requirement ID | Stable local identifier. |
| Exact source | National provision and, where relevant, Directive article or Annex I clause. |
| Source version | Version or retrieval date. |
| Authority type | National law, Directive text, regulator material, harmonised standard, common specification, organisational policy, design interpretation, or research evidence. |
| Exact legal text | Preserved quotation where required, kept within its original context. |
| Plain-English interpretation | Clearly labelled interpretation, not presented as statutory wording. |
| Actor and subject | Economic operator, product, service, function, information, support channel, or digital channel to which it applies. |
| Applicability rationale | Facts and legal mapping supporting inclusion, partial inclusion, or exclusion. |
| Annex I route | Applicable section and clause, including the reason for any Section VII use. |
| Standard or technical relationship | Direct support, partial support, presumption of conformity within scope, informative relationship, or no established mapping. |
| Design relationship | Direct implementation, broader organisational policy, recommended practice, or design hypothesis. |
| Evidence required | Technical, manual, assistive-technology, process, documentation, and user-outcome evidence needed for the decision. |
| Known limitations and uncertainty | Gaps, contested interpretations, untested contexts, and populations missing from the evidence. |
| Permitted claim | The conclusion the evidence may support and any wording that is prohibited. |
| Owner and reviewer | Responsible owner, competent reviewer, and accountable decision authority. |
| Review controls | Monitoring, change triggers, review date, and expiry where applicable. |

## Source and authority distinctions

The following sources answer different questions and must not be collapsed into one authority label.

| Source type | What it can establish | What it cannot establish alone |
|---|---|---|
| Applicable national law and authoritative decisions | Binding duties, scope, procedures, exemptions, enforcement, and remedies in the relevant jurisdiction. | Whether the implementation works successfully for every disabled user in practice. |
| Directive (EU) 2019/882 | The common EU framework, covered categories, obligations, Annex structure, and transposition requirements. | A complete jurisdiction-specific conclusion without national implementation and relevant facts. |
| Harmonised standards or common specifications | Technical methods and, where legally recognised, a presumption of conformity within their stated scope. | Duties or outcomes outside their scope, or an unrestricted conclusion about the entire product or service. |
| WCAG and other technical standards | Structured criteria and evidence for many digital accessibility barriers. | EAA scope, every EAA duty, complete service conformity, or satisfactory user outcomes. |
| Double FW inclusive-design baseline | A broader organisational expectation covering functional and experiential outcomes. | A statement that every rule is directly required by the EAA. |
| Research and operational evidence | Real task outcomes, effort, errors, recovery, autonomy, privacy, equivalence, satisfaction, complaints, and contextual barriers. | Legal scope, statutory interpretation, or automatic permission to disregard an applicable requirement. |

## Alternative solutions, exceptions, and evidence-based departures

An alternative technical solution may support conformity where the applicable legal framework permits it and the solution satisfies the relevant accessibility requirement, including any required equivalent or increased accessibility. Record the exact legal route, affected function, comparison method, evidence, uncertainty, and authorised conclusion.

This must be distinguished from:

- an **exception**, which accepts a known unresolved failure or residual disadvantage and does not itself establish legal conformity;
- an **evidence-based departure from organisational policy**, which selects a different design approach because proportionate evidence supports an equal or better outcome; and
- a **fundamental-alteration or disproportionate-burden decision**, which is a legally controlled assessment with its own evidence, authority, notification, review, and continuing-duty requirements.

Statistical significance can strengthen a general outcome claim when the sample and study design support population-level inference. It does not independently determine legal scope, erase a failed requirement, or prove that rare but severe exclusion does not exist.

## Minimum EAA evidence pack

For an in-scope subject, retain:

- the completed scope and applicability record;
- applicable national legislation, current authoritative material, and source dates;
- clause-level requirement mappings;
- any exclusion, exemption, transition, fundamental-alteration, or disproportionate-burden record;
- standards and technical specifications used, including their legal status and scope;
- design requirements and decisions;
- automated results with declared limitations;
- manual and assistive-technology evaluation;
- relevant disabled-user and operational evidence;
- known limitations, remediation plans, exceptions, and evidence-based departures;
- support-service and accessible-alternative information;
- complaints, incidents, corrective action, and monitoring;
- decision ownership, delegated authority, approval, and review records; and
- the conformity or service information required by the applicable law.

Evidence must remain current as the service, product, law, standards, suppliers, technology, and customer journeys change.

## AI and autonomous-system controls

An AI or autonomous governance system using EAA material must:

1. retrieve this gate before retrieving design requirements or test procedures;
2. request the missing product, service, actor, territory, date, and national-law facts;
3. preserve the difference between exact legal text and interpretation;
4. label every rule by authority type and applicability;
5. retrieve the exact applicable Annex I clause rather than generalising from another product or service category;
6. state uncertainty and return `legal review required` when the evidence cannot support a conclusion;
7. keep EAA conformity, standards conformance, organisational policy, usability, autonomy, equivalence, satisfaction, and enjoyment as distinct findings;
8. prevent positive research, low complaint levels, or automated passes from being treated as proof of compliance;
9. identify the required human decision-maker and escalation route; and
10. preserve a reconstructable record of sources, versions, facts, reasoning, evidence, and approval.

## Applicability decision template

```yaml
decision_id: ""
assessment_date: ""
product_or_service: ""
feature_or_channel: ""
customer_or_user_population: ""
territories: []
economic_operator_roles: []
potential_article_2_category: ""
national_implementing_law:
  jurisdiction: ""
  title: ""
  version_or_date: ""
  source_url: ""
competent_authority: ""
relevant_dates_and_transitions: []
exclusions_or_exemptions: []
applicable_annex_sections: []
applicable_requirements: []
included_scope: []
excluded_scope: []
decision: "in scope | partly in scope | out of scope | exempt or subject to a specific limitation | legal review required"
rationale: ""
evidence_references: []
unresolved_questions: []
legal_or_compliance_reviewer: ""
business_or_service_accountable_owner: ""
decision_date: ""
review_triggers: []
next_review_date: ""
```

## Authoritative starting points

- [Directive (EU) 2019/882 — EUR-Lex](https://eur-lex.europa.eu/eli/dir/2019/882/oj)
- [European Commission overview of the European Accessibility Act](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en)
- [A Guide to the European Accessibility Act 2025](Guide_to_the_European_Accessibility_Act_2025.md)

The Directive and Commission overview are starting points. The current national implementation, responsible authorities, legally recognised standards or specifications, and official guidance must be verified for the actual decision.
