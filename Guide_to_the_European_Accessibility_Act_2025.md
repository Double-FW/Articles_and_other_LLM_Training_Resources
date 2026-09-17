---
title: "A Guide to the European Accessibility Act 2025"
short_title: "European Accessibility Act 2025 Guide"
author: "Gareth Ford Williams"
language: "en-GB"
document_type:
  - "practitioner_guide"
  - "accessibility_governance_guidance"
  - "regulatory_commentary"
content_status: "author_guidance_with_legal_diagnostics"
date_published: null
date_processed: "2026-09-17"
regulatory_date_context: "The principal EAA requirements applied from 28 June 2025, subject to scope, exemptions and transitional provisions."
version: "1.0-semantic"
jurisdictional_context:
  - "European Union"
primary_legislation:
  - title: "Directive (EU) 2019/882 on the accessibility requirements for products and services"
    common_name: "European Accessibility Act"
    identifier: "CELEX:32019L0882"
    url: "https://eur-lex.europa.eu/eli/dir/2019/882/oj/eng"
standards_and_frameworks:
  - "Web Content Accessibility Guidelines (WCAG)"
  - "EN 301 549"
  - "EN 17161"
  - "Design for All"
  - "POUR principles"
primary_domains:
  - "digital_accessibility"
  - "inclusive_design"
  - "regulatory_compliance"
  - "accessibility_governance"
  - "websites"
  - "mobile_applications"
  - "customer_experience"
audiences:
  - "accessibility_professionals"
  - "designers"
  - "product_managers"
  - "developers"
  - "quality_assurance_teams"
  - "legal_and_compliance_teams"
  - "service_owners"
  - "ai_governance_systems"
key_concepts:
  - "scope_determination"
  - "covered_services"
  - "accessibility_requirements"
  - "presumption_of_conformity"
  - "service_provider_information"
  - "market_surveillance"
  - "functional_performance_criteria"
  - "customer_complaints"
  - "technical_and_user_evidence"
  - "continuous_conformity"
source_characteristics:
  first_person_commentary: true
  contains_legal_interpretation: true
  contains_predictions_about_enforcement: true
  contains_commercial_references: true
  source_text_incomplete: true
  independently_peer_reviewed: false
  legal_advice: false
editorial_treatment:
  - "Added YAML metadata and semantic headings."
  - "Normalised paragraphs, lists, punctuation and typographical errors."
  - "Preserved the author's practical and human-centred argument."
  - "Rebuilt the scope, Annex I and governance sections around the Directive's actor- and service-specific structure."
  - "Separated legal requirements, interpretation, recommended practice and enforcement predictions."
  - "Removed an unsupported claim that approximately 80% of enforcement will be complaint-led."
  - "Corrected the description of service-provider documentation as universal self-reporting."
  - "Qualified quotations that were detached from their product or service context."
  - "Added provenance and AI-ingestion guidance."
ai_ingestion_guidance:
  - "Treat this document as practitioner guidance, not as legal advice or a substitute for national implementing law."
  - "Determine whether the organisation, product, service and digital channel are in scope before applying EAA requirements."
  - "Do not assume that every website or mobile application is covered by the EAA."
  - "Do not apply product requirements in Annex I Sections I and II directly to a service website or app without a valid legal mapping."
  - "Distinguish service-provider information duties from regulatory reporting, market surveillance, complaints and conformity documentation for products."
  - "Do not treat WCAG conformance, a VPAT or an automated audit as proof of EAA compliance."
  - "Do not state that WCAG, EN 301 549 or EN 17161 are irrelevant; identify whether a current harmonised standard or technical specification creates a presumption of conformity for the requirement in question."
  - "Treat the POUR relationship as conceptual alignment, not as proof that the EAA formally incorporates WCAG."
  - "Do not infer that absence of complaints demonstrates accessibility or compliance."
  - "Verify national authorities, procedures, penalties, exemptions, transitional measures and cited standards at the time of use."
  - "Preserve exact statutory wording and context when extracting EAA requirements."
---

# A Guide to the European Accessibility Act 2025

## Article overview

The European Accessibility Act (EAA) establishes accessibility requirements for specified products and services placed on the European Union market. Its principal requirements began to apply from 28 June 2025, subject to its scope, national implementing law, exemptions and transitional provisions.

This guide focuses on websites and mobile applications used to deliver services covered by the EAA. It proposes a practical, human-centred response that combines legal mapping, inclusive design, technical evaluation, manual assessment and evidence from disabled customers.

The central argument remains important:

> **WCAG conformance alone does not establish EAA compliance.**

However, the reverse conclusion would also be wrong. WCAG and standards such as EN 301 549 can provide important technical methods and evidence. Where a standard or part of a standard is formally harmonised and cited for relevant EAA requirements, it may provide a presumption of conformity within its scope. Legal and standards specialists should confirm the current position.

## What this guide covers

This guide is intended to help accessibility professionals, designers, product managers and service owners understand:

- the questions they should ask internally;
- whether a website or app is connected to a service within scope;
- how the Directive and Annex I are structured;
- how standards can support—but not replace—legal analysis;
- what evidence service providers should retain;
- how customer evidence can complement technical assessment; and
- how to build a sustainable governance approach.

## Start with what the EAA is not

When trying to understand a regulatory framework, I often begin with what it is not. This reduces the risk of importing assumptions from an existing compliance process.

The EAA does not simply state that every covered organisation must achieve a named WCAG conformance level, complete a VPAT or implement EN 301 549 or EN 17161 in full. The legal duties are the applicable accessibility requirements in the Directive as transposed into national law.

Standards still matter. Article 15 of the Directive provides for a presumption of conformity where products and services conform to relevant harmonised standards, or parts of them, whose references have been published in the *Official Journal of the European Union*. Common specifications may also be relevant in defined circumstances.

### Legislative context: Recital 74

> In order to facilitate the assessment of conformity with the applicable accessibility requirements, it is necessary to provide for a presumption of conformity for products and services which are in conformity with voluntary harmonised standards…

**Source context:** This is an extract from Recital 74 of [Directive (EU) 2019/882](https://eur-lex.europa.eu/eli/dir/2019/882/oj/eng). The full recital and operative provisions should be read before relying on it.

The better question is not “Which checklist is the law?” but:

> **Which legal requirements apply to this service, and what evidence demonstrates that we meet them?**

## Establish scope before testing

A website or mobile application is not covered merely because it is available in the EU. The digital channel must be considered in relation to an in-scope product or service, the organisation's role and the relevant national legislation.

### Services commonly relevant to websites and apps

The Directive covers specified services, including:

- electronic communications services, subject to defined exclusions;
- services providing access to audiovisual media services;
- certain elements of air, bus, rail and waterborne passenger-transport services;
- consumer banking services;
- e-books and dedicated software; and
- e-commerce services.

This list is a starting point, not a complete scope opinion. Definitions in Article 3, exclusions, sector rules and national implementation matter.

### Scope questions

Before applying a test framework, record:

1. What product or service is being provided?
2. Which Article 2 category may bring it into scope?
3. Is the organisation a manufacturer, authorised representative, importer, distributor or service provider?
4. Which Member State laws and authorities apply?
5. Is the provider a microenterprise providing services and therefore potentially exempt under Article 4(5)?
6. Do transitional provisions affect an existing contract, product or terminal?
7. Has a fundamental-alteration or disproportionate-burden assessment been claimed, and is it documented correctly?
8. Which parts of Annex I apply to the specific service and channel?

An accessibility audit should not begin by assuming the answer to these questions.

## Outcomes, standards and the POUR relationship

The EAA describes accessibility outcomes and functional expectations. Its terminology closely aligns with the familiar WCAG principles of perceivable, operable, understandable and robust, but the Directive should not be represented as simply adopting WCAG or the POUR framework wholesale.

### Perceivable

Information and interface elements need to be available in forms people can perceive.

### Operable

Controls, navigation and interactions need to be usable through relevant modes of operation.

### Understandable

Information and interactions need to be comprehensible and predictable enough to use.

### Robust and interoperable

Digital information and interactions need to work reliably with relevant user agents and assistive technologies.

WCAG can provide detailed success criteria and techniques for many web and app barriers. It does not necessarily address every EAA duty concerning service information, support services, sector-specific functionality, organisational practices or functional performance.

## Two key questions for monitoring

Taking this into account, I believe an effective monitoring and evidence process should centre on two questions:

1. **What approach was used to design, build, procure, operate and maintain the website or app?**
2. **How successful is the resulting service for disabled customers?**

The first question examines governance and implementation. The second examines outcomes. Neither is sufficient alone.

## A practical four-layer model

The original article described four EAA layers. For operational use, the model can be refined as follows.

### Layer 1: Scope and legal requirements

Identify the covered service, economic operator, national law, applicable Annex I sections, exemptions and transitional rules.

### Layer 2: Standards and implementation methods

Map each applicable legal requirement to relevant harmonised standards, technical specifications, WCAG criteria, design-system rules, manual tests and organisational controls.

### Layer 3: Functional and customer outcomes

Evaluate whether people with different functional access needs can perceive, operate, understand and complete the service, including with assistive technologies and adaptations.

### Layer 4: Governance and evidence

Maintain the information, records, monitoring, complaints, corrective action and cooperation needed to demonstrate and sustain conformity.

## Read Annex I—but map it before applying it

Annex I is essential, but individual clauses should not be lifted out and applied to every website or app. Its sections have different purposes.

| Annex I section | Primary purpose | Digital-service relevance |
|---|---|---|
| Section I | General accessibility requirements for covered products | Relevant to products, not automatically to a service website or app |
| Section II | Additional product requirements | Apply according to the type of covered product |
| Section III | General accessibility requirements for covered services | Core starting point for in-scope services, including service information, websites, mobile apps and support services |
| Section IV | Additional requirements for specific services | Apply only to the relevant service category, such as electronic communications, audiovisual access, transport, banking, e-books or e-commerce |
| Section V | Emergency communications to 112 | Specific to the most appropriate public-safety answering point |
| Section VI | Accessibility requirements used by other Union acts | Relevant where Article 24 applies |
| Section VII | Functional performance criteria | Used when applicable Sections I–VI requirements do not address one or more design or performance functions |

This structure corrects a common mistake: product requirements concerning physical controls, reach, volume or device-level settings should not be presented automatically as direct requirements for every service website or mobile app.

## General service requirements for websites and apps

For covered services, Section III of Annex I is the general starting point. In plain English, the service provider should consider the following areas.

### Information about the service

Information explaining how the service works should be accessible. Depending on the content, this includes appropriate sensory channels, understandable presentation, perceivability, text alternatives for non-text content and formats that can support alternative presentation.

### Websites, online applications and mobile applications

Websites and apps used to provide the service should be accessible in a consistent and adequate way. The Directive refers to perceivability, operability, understandability and robustness, and to adaptability and interoperability with assistive technologies.

### Support services

Help desks, call centres, technical support, relay services and training services—where available—should provide accessible information about the service and its compatibility with assistive technologies.

### Service-specific requirements

Section IV adds requirements according to the service. For example, an e-commerce service has different additional duties from an e-book service, consumer banking service or service providing access to audiovisual media.

The AI or assessor MUST retrieve the exact applicable clause rather than generalise from another sector.

## Functional performance criteria

Section VII describes functional modes of operation, including use:

- without vision;
- with limited vision;
- without perception of colour;
- without hearing;
- with limited hearing;
- without vocal capability;
- with limited manipulation or strength;
- with limited reach;
- while minimising the risk of photosensitive seizures;
- with limited cognition; and
- while maintaining privacy when using accessibility features.

These criteria are not merely research personas or a replacement for every specific requirement. Under the Directive, they have a defined role when accessibility requirements in Sections I–VI do not address one or more design or performance functions.

They can still provide a valuable inclusive-design lens, but legal application and design use should be distinguished.

## Governance: what evidence are you working towards?

The EAA does not create one identical enforcement process in every Member State. It harmonises accessibility requirements, while Member States establish competent authorities, procedures and penalties through national law. Procedures and enforcement practice can therefore differ.

The original article described a universal “self-reporting model.” That is too broad. The Directive creates different documentation and information duties for products and services.

### Service-provider information

Article 13 and Annex V require service providers to ensure conformity and make specified information available. In practical terms, the service provider should be able to explain:

- the applicable accessibility requirements;
- how the service meets them;
- how the service is designed and operated;
- which standards or technical specifications were applied, where relevant;
- how continuous conformity is maintained; and
- what corrective action is taken when non-conformity is identified.

The information must be accessible and retained for as long as the service operates. The exact national implementation and any regulator-prescribed form must be checked.

### Product conformity is different

Covered products involve product-specific conformity assessment, technical documentation, an EU declaration of conformity and CE marking. These controls should not be conflated with the information duties of a service provider.

### Complaints and market surveillance

Member States must establish procedures for checking compliance, following up complaints or reports, and verifying corrective action. Complaints may therefore be an important enforcement trigger, but the claim that approximately 80% of enforcement will arise from complaints was unsupported and has been removed.

Regulators may also act through surveillance, investigation, sampling or sector-specific processes. An organisation should not assume that it is safe until someone complains.

## What a defensible evidence pack should contain

There is no single EU-wide checklist that replaces legal analysis. A practical evidence pack for a covered service should include:

- a documented scope and applicability decision;
- the relevant national implementing law and competent authority;
- a clause-level mapping of applicable Annex I requirements;
- any exemption, transition, fundamental-alteration or disproportionate-burden analysis;
- standards and technical specifications used, with version and legal status;
- design-system requirements and design decisions;
- automated-test results with limitations;
- manual accessibility assessments;
- assistive-technology and platform testing;
- evidence from disabled users;
- information about support services and accessible alternatives;
- known limitations and remediation plans;
- complaints, incidents and corrective actions;
- ownership, approval and review records; and
- the accessible service information required by Article 13 and Annex V.

This evidence should be maintained as the service changes. A report assembled once and then abandoned does not demonstrate continuous conformity.

## User feedback: valuable but not the only evidence

Feedback from disabled customers is essential for understanding real experience. It can reveal barriers, effort, loss of confidence and poor service outcomes that a technical audit does not capture.

However, “ask disabled users” is not the only way to verify every requirement. Evidence should be triangulated:

| Evidence | What it contributes | Limitation if used alone |
|---|---|---|
| Automated testing | Repeatable detection of specific machine-testable failures | Covers only a subset and cannot judge many contextual outcomes |
| Manual expert testing | Context, semantics, interaction and requirement interpretation | May not represent lived experience or every technology |
| Assistive-technology testing | Compatibility and operability with selected configurations | Cannot cover all users, settings or strategies |
| Qualitative user research | Reasons, experience, effort and emotional impact | Does not establish prevalence or complete legal conformity |
| Quantitative customer evidence | Patterns, trends and comparisons over time | Requires careful sampling and may not explain causation |
| Complaints and support data | Actual reported barriers and operational failures | Under-reporting and inaccessible channels can conceal problems |

Research should recruit people with relevant access needs without reducing them to functional categories. Functional modes are useful for coverage; disability identity and lived experience remain important.

Statistical significance is not a prerequisite for learning from disabled people. Small qualitative samples can expose critical barriers. Quantitative claims, however, should disclose sample size, population, uncertainty and methodology.

## Using POUR in customer evidence

POUR can provide a useful organising framework for feedback, provided it is not treated as the complete legal test.

### Perceivable questions

- Could the customer obtain all necessary information?
- Were alternatives available in the required form?
- Did presentation remain effective after personalisation?

### Operable questions

- Could the customer complete every task using their preferred input method?
- Were controls, time limits and recovery processes manageable?
- Could the customer move between the app, authentication and support without losing access?

### Understandable questions

- Were instructions, labels, errors and consequences clear?
- Could the customer predict what would happen next?
- Was assistance available before failure became irreversible?

### Robust and interoperable questions

- Did the service work with relevant browsers, platforms, user agents and assistive technologies?
- Did accessibility survive updates, embedded third-party content and payment or identity services?

## Recommended delivery approach

### 1. Determine scope and ownership

Legal, compliance, product and accessibility teams should agree which services and channels are covered, which requirements apply and who owns each decision.

### 2. Build a requirements map

Map the applicable national law and Annex I clauses to standards, design requirements, tests, evidence and accountable owners.

### 3. Embed requirements in the design system

Use accessible components, content patterns and interaction rules. Test components in realistic service journeys, not only in isolation.

### 4. Combine automated and manual testing

Automated checks are useful for repeatable detection, but they provide partial evidence. Manual tests and human judgement are required for context, meaning, usability and many legal requirements.

### 5. Include disabled people

Use disabled customer research to understand functional and emotional experience. Ensure recruitment, consent, research tools and participation are accessible.

### 6. Monitor continuous conformity

Track releases, regressions, complaints, support issues, third-party changes and remediation. Reassess when the service, law, standard or customer journey changes.

### 7. Maintain accessible service information

Keep the information required for service-provider conformity current, accurate and publicly available in an accessible form.

## Recommended reading

- [A Designed Experience for Everyone](https://www.a11yquest.com/guides/principles/designed-experience), by A11yQuest.
- [Understanding Design for All](https://tetralogical.com/blog/2025/06/27/understanding-design-for-all/), by Tetralogical.
- [European Commission overview of the European Accessibility Act](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en).
- [Directive (EU) 2019/882](https://eur-lex.europa.eu/eli/dir/2019/882/oj/eng).

## Conclusion

The EAA is about both **approach** and **outcome**, but compliance is not merely the by-product of good intentions or inclusive design. It requires a defensible mapping between the law, the covered service, design decisions, implementation, testing, customer experience and maintained evidence.

Organisations should:

- invest in inclusive design systems;
- use continuous automated and manual testing;
- include disabled people in research and governance;
- gather proportionate evidence about customer outcomes;
- maintain accessible conformity information; and
- verify the requirements of every relevant Member State.

Done well, this can produce more than a compliance record. It can produce better products and services. But the legal conclusion must still be demonstrated rather than assumed.

> **Nothing about us without our data as customers—and nothing about compliance without traceable evidence.**


### Recommended retrieval relationships

When this document is used in an AI knowledge system, retrieve it alongside:

- the current text of Directive (EU) 2019/882;
- the implementing law and regulator guidance for each relevant Member State;
- current harmonised standards and European Commission standardisation material;
- sector-specific EU and national law;
- organisational scope decisions and conformity information;
- accessibility test evidence and design-system documentation; and
- qualitative and quantitative evidence from disabled customers.

### Claims requiring current verification

Before relying on this guide for a compliance decision, verify:

- whether the product, service, provider and digital channel are within scope;
- the definitions and exclusions applicable to the service;
- microenterprise and other exemptions;
- transitional arrangements;
- the national competent authority and enforcement procedure;
- documentation, notification and publication duties;
- penalty and corrective-action powers;
- the legal status and scope of any cited standard or technical specification;
- the use of fundamental-alteration or disproportionate-burden provisions; and
- whether later EU or national guidance changes the interpretation used here.
