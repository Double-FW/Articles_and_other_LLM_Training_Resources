---
title: "European Accessibility Act: How to Respond to This New Legislation"
short_title: "Responding to the European Accessibility Act"
author: "Gareth Ford Williams"
language: "en-GB"
document_type:
  - "practitioner_article"
  - "accessibility_governance_guidance"
content_status: "author_commentary"
date_published: null
date_processed: "2026-09-17"
version: "1.0-semantic"
jurisdictional_context:
  - "European Union"
primary_legislation:
  - title: "Directive (EU) 2019/882 on the accessibility requirements for products and services"
    common_name: "European Accessibility Act"
    identifier: "CELEX:32019L0882"
    url: "https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882"
standards_and_frameworks:
  - "Web Content Accessibility Guidelines (WCAG)"
  - "EN 301 549"
  - "Design for All"
  - "POUR principles"
primary_domains:
  - "digital_accessibility"
  - "inclusive_design"
  - "accessibility_governance"
  - "regulatory_compliance"
  - "customer_experience"
  - "user_research"
  - "websites"
  - "mobile_applications"
audiences:
  - "accessibility_professionals"
  - "product_managers"
  - "designers"
  - "developers"
  - "quality_assurance_teams"
  - "legal_and_compliance_teams"
  - "ai_governance_systems"
key_concepts:
  - "functional_performance_criteria"
  - "presumption_of_conformity"
  - "self_reporting"
  - "customer_complaints"
  - "disabled_customer_experience"
  - "quantitative_user_data"
  - "automated_testing"
  - "manual_testing"
  - "inclusive_design_systems"
  - "social_model_of_disability"
named_organisations_and_services:
  - "A11yQuest"
  - "Ab11y"
  - "Tetralogical"
  - "BBC"
  - "YouView"
  - "ATVOD"
  - "Ofcom"
  - "Ofgem"
source_characteristics:
  first_person_commentary: true
  contains_legal_interpretation: true
  contains_predictions_about_enforcement: true
  contains_commercial_references: true
  independently_peer_reviewed: false
  legal_advice: false
editorial_treatment:
  - "Added YAML metadata and semantic headings."
  - "Normalised paragraphs, lists, capitalisation and minor typographical errors."
  - "Converted legislative extracts into labelled block quotations."
  - "Preserved the author's argument, recommendations and first-person voice."
  - "Added provenance and AI-ingestion notes without substantively fact-checking the article."
ai_ingestion_guidance:
  - "Distinguish the text of the EAA from the author's interpretation and recommendations."
  - "Do not treat predictions about monitoring, complaint volumes, penalties or enforcement behaviour as established legal facts."
  - "Verify legal duties, national implementation, enforcement processes, penalties and applicable standards against current authoritative sources."
  - "Do not infer that WCAG conformance alone establishes EAA compliance."
  - "Do not infer that absence of customer complaints establishes compliance or an accessible outcome."
  - "Treat references to A11yQuest and Ab11y as examples provided by the author, not as independent endorsements."
  - "Preserve the distinction between technical testing, manual assessment and evidence from disabled users."
  - "When extracting the functional performance criteria, retain their qualifications and context."
---

# European Accessibility Act: How to Respond to This New Legislation

## Article overview

This article proposes a practical way to respond to the European Accessibility Act (EAA) when designing and governing websites and mobile applications. It argues that EAA compliance should not be reduced to a WCAG checklist. Instead, organisations should combine inclusive design, technical testing, manual evaluation and evidence about the experiences of disabled customers.

The article is practitioner commentary. It includes the author's interpretation of the EAA, predictions about regulatory practice and examples of commercial tools. Those elements should not be treated as legislation, regulator guidance or independent product recommendations.

## Introduction

With the European Accessibility Act now upon us, I have decided to take a little time to reflect on my approach to compliance.

Over the last six months, there has been considerable debate and discussion about this new legislation. Unlike other regulation, it does not simply lean on guidelines such as WCAG. Instead, it takes more of a **Design for All** approach.

In this article, I focus solely on websites and mobile applications. I explore some of the questions the Act asks of accessibility professionals, designers and product managers.

## Begin by understanding what the EAA is not

When trying to understand any regulatory framework, I find it useful to establish what it is not. This helps avoid importing assumptions from existing approaches.

Do not assume that pre-existing accessibility guidelines and checklists automatically constitute compliance. WCAG, EN 301 549 and other standards may support conformity, but the EAA describes harmonised standards as voluntary.

### Legislative extract: Recital 74

> In order to facilitate the assessment of conformity with the applicable accessibility requirements it is necessary to provide for a presumption of conformity for products and services which are in conformity with voluntary harmonised standards…

**Source context:** Recital 74 of [Directive (EU) 2019/882](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882). The ellipsis indicates that this is an extract rather than the complete recital.

Instead of relying only on guidelines, the EAA lists outcomes that should be expected. Annex I divides these into several sections. The relevant requirements and some context are considered later in this article.

The Act also identifies the audiences whose experiences should be considered. In doing so, it moves away from a narrow medical-model approach and towards consideration of the barriers people experience.

The requirements are framed in ways that relate to the WCAG principles of perceivability, operability, understandability and robustness. These principles focus primarily on function rather than quality, an issue I return to in the discussion of governance.

## The POUR principles

The [W3C accessibility principles](https://www.w3.org/WAI/fundamentals/accessibility-principles/) can be summarised as follows:

### Perceivable

Information and user-interface components must be presented to users in ways they can perceive.

### Operable

User-interface components and navigation must be operable.

### Understandable

Information and the operation of the user interface must be understandable.

### Robust

Content must be robust enough to be interpreted reliably by a wide variety of user agents, including assistive technologies.

## Two questions for an EAA compliance approach

Before examining Annex I, I suggest that an approach to EAA compliance needs to answer two questions:

1. **What approach was used to design and build the product or service?**
2. **How successful is the outcome of that approach for customers with disabilities?**

The rest of this article explains how I reached that conclusion, explores what it could mean in practice and suggests tools and resources that could form part of an organisational approach.

## A four-layer interpretation of the EAA

I interpret the EAA as having four relevant layers:

1. **Principles:** POUR helps frame both the design approach and the intended functional outcomes.
2. **Requirements:** Annex I provides specific contexts and accessibility expectations for products and services.
3. **User groups:** The functional performance criteria identify different ways people may need to use a product or service.
4. **Governance:** Member States implement monitoring, reporting and enforcement processes.

Review the requirements in [Annex I of Directive (EU) 2019/882](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882). Several requirements extend beyond the subject matter covered by WCAG 2.2 at Levels A, AA or AAA, even where they share similar principles. Where relevant standards cover a requirement, use them as evidence. Where they do not, broader inclusive-design practices and additional evidence will be needed.

## Governance

### Start with the evidence you may need

I like to understand the intended destination before making decisions. For EAA governance, organisations need to understand the applicable national implementation, responsible market-surveillance authority, reporting expectations and potential penalties.

The underlying Directive is shared across the European Union, but implementation, procedures, enforcement responsibilities and penalties may differ between Member States. Organisations operating in more than one country therefore need jurisdiction-specific legal and regulatory checks.

There is no single universal reporting template equivalent to a VPAT for every EAA use case. Organisations must determine what evidence they need to retain and how it connects to the applicable requirements. Annex I provides important clues.

I have worked in regulatory advisory capacities with the BBC, YouView and ATVOD and have participated in discussions about policy, law and accessibility guidance with government departments for more than 20 years. Based on that experience, I do not expect every regulator to test every covered service proactively. The scale of the market makes targeted monitoring, sampling, documentation and complaint-led investigation more plausible.

> **Verification note:** The preceding paragraph is the author's prediction based on professional experience. Monitoring practices must be verified for the relevant Member State and regulator.

### Monitoring route 1: organisational documentation and regulatory reporting

Because of the scope of the EAA, organisations should be ready to provide evidence against the requirements that apply to their products or services. For websites and mobile applications, this may include relevant service requirements in Annex I, functional performance criteria and documentation required by national implementation.

An automated WCAG report is unlikely to provide sufficient evidence on its own. The EAA takes a broader approach than a purely technical checklist. Evidence should show:

- how accessibility was considered during design and development;
- which applicable requirements were evaluated;
- which functional user needs were considered;
- what technical and manual testing was completed;
- what limitations or exceptions were identified;
- what remediation was undertaken; and
- how the resulting experience works for disabled people.

Resources relevant to Design for All include:

- [A Designed Experience for Everyone](https://www.a11yquest.com/guides/principles/designed-experience), by A11yQuest.
- [Understanding Design for All](https://tetralogical.com/blog/2025/06/27/understanding-design-for-all/), by Tetralogical.

### Monitoring route 2: customer complaints

Customer complaints can be an important route through which regulators become aware of accessibility barriers. Organisations should expect complaints to be compared with their documentation, accessibility claims, remediation records and actual customer experience.

The original article suggested that complaint handling could account for approximately 80% of monitoring activity and that fines or service restrictions could follow a failure to engage. These are claims about likely enforcement practice rather than requirements stated in the quoted passages of the EAA. They require verification against the current law and regulator practice in each relevant Member State.

Organisations should not wait for complaints before acting. A low number of complaints may reflect inaccessible complaint channels, low confidence, exclusion before use or lack of awareness rather than an accessible service.

## Satisfaction, quality and customer experience

Satisfaction and quality may not always appear as explicit functional requirements, but they are relevant to whether an accessible service works successfully in practice.

My original proposition was:

> **“Satisfied disabled customers do not complain, and with no customer complaints there is little or no risk.”**

That statement is best treated as a provocation about customer experience, not as a compliance test. Absence of complaints cannot demonstrate compliance. However, comparative satisfaction data can reveal barriers that technical conformance testing misses.

By focusing on outcomes as well as process, an organisation can connect accessibility principles with customer experience and service quality. Automated tools cannot establish with certainty whether disabled people can successfully perceive, operate and understand a service in context, or whether it works effectively with their technology and strategies. Technical evaluation therefore needs to be combined with evidence from people.

> **Nothing about us without our customer-experience data.**

## Collecting meaningful customer evidence

If customers are expected to report barriers, organisations should obtain evidence directly from disabled customers rather than relying only on proxies or assumptions. Research needs sufficient breadth to identify patterns, but it should also recognise that statistically significant quantitative research may not be practical for every disability-related subgroup or product decision.

Segmentation should focus on functional access needs and experienced barriers where appropriate. It should avoid unnecessary collection of medical diagnoses or sensitive personal data.

In an agile environment, rolling evidence can support ongoing monitoring. Organisations should consider the following:

- evaluate important parts of the experience against the POUR principles;
- where lawful and appropriate, enable findings to be analysed by relevant functional user needs;
- include disabled participants in qualitative research to understand why barriers occur;
- use quantitative data to identify patterns and areas requiring deeper investigation;
- integrate accessibility into [A/B testing](https://hbr.org/2017/06/a-refresher-on-ab-testing) where experimentation is ethical and does not deny access; and
- evaluate whether design changes and new features improve or worsen disabled customers' experiences.

Research design must consider privacy, informed consent, data minimisation, small-sample disclosure risk and applicable data-protection law. Functional-needs data can still be personal or sensitive in context.

## A scalable and sustainable approach

There is no single product or service that can deliver EAA compliance. Technical evidence and user evidence, combined with investment in an [inclusive design system](https://www.a11yquest.com/), can provide a stronger basis for an EAA compliance record.

Instead of relying only on periodic auditing and training, consider the following approach.

### 1. Build accessibility into the design system

Make the design system accessible and evaluate components and patterns against POUR in the context of relevant functional user needs.

[A11yQuest](https://www.a11yquest.com/tests/) is one example of a framework intended to support this activity.

### 2. Introduce automated monitoring

Use an established automated ruleset, such as axe, within delivery and quality-assurance processes. A range of [automated accessibility testing tools](https://testguild.com/accessibility-testing-tools-automation/) can support this.

Automated testing can identify only a subset of accessibility requirements. The original article estimated coverage at 30% to 40%. Actual coverage depends on the ruleset, content, technology, requirement set and definition of coverage. Automated results must therefore be treated as partial evidence rather than a compliance percentage.

### 3. Add meaningful manual assessment

Integrate manual accessibility tests into quality assurance and provide designers, developers and product managers with design and development guidance. This creates clearer acceptance criteria and reduces the amount of interpretation left until the end of delivery.

A11yQuest is cited by the author as an example of a service that provides testing and implementation guidance.

### 4. Collect evidence about user outcomes

Collect quantitative and qualitative evidence about user outcomes that can, where lawful and methodologically sound, be analysed by functional access need.

The original article cites [Ab11y](https://www.ab11y.com/) as an example of a platform intended to support rolling user evidence and A/B testing. Its accessibility, privacy and regulatory claims should be evaluated independently before procurement or use.

### 5. Create an evidence trail

Link requirements to design decisions, technical tests, manual assessments, user evidence, known limitations, remediation and accountable owners. This evidence is more useful than a standalone audit because it shows both the approach taken and the outcomes observed.

## Functional user needs under consideration

One of the valuable aspects of the EAA is its focus on how a person uses a product or service rather than only on medical diagnosis. This can align well with inclusive-design and user-experience practices.

The categories below are adapted from the functional performance criteria in Annex I, Section VII. They describe modes of use; they are not labels that should be assigned to people. When recruiting for research or segmenting quantitative evidence, organisations should ask only for information that is necessary, proportionate and lawful.

### A. Usage without vision

> Where the product or service provides visual modes of operation, it shall provide at least one mode of operation that does not require vision.

### B. Usage with limited vision

> Where the product or service provides visual modes of operation, it shall provide at least one mode of operation that enables users to operate the product with limited vision.

### C. Usage without perception of colour

> Where the product or service provides visual modes of operation, it shall provide at least one mode of operation that does not require user perception of colour.

### D. Usage without hearing

> Where the product or service provides auditory modes of operation, it shall provide at least one mode of operation that does not require hearing.

### E. Usage with limited hearing

> Where the product or service provides auditory modes of operation, it shall provide at least one mode of operation with enhanced audio features that enables users with limited hearing to operate the product.

### F. Usage without vocal capability

> Where the product or service requires vocal input from users, it shall provide at least one mode of operation that does not require vocal input. Vocal input includes any orally-generated sounds like speech, whistles or clicks.

### G. Usage with limited manipulation or strength

> Where the product or service requires manual actions, it shall provide at least one mode of operation that enables users to make use of the product through alternative actions not requiring fine motor control and manipulation, hand strength or operation of more than one control at the same time.

### H. Usage with limited reach

> The operational elements of products shall be within reach of all users. Where the product or service provides a manual mode of operation, it shall provide at least one mode of operation that is operable with limited reach and limited strength.

### I. Minimising the risk of triggering photosensitive seizures

> Where the product provides visual modes of operation, it shall avoid modes of operation that trigger photosensitive seizures.

### J. Usage with limited cognition

> The product or service shall provide at least one mode of operation incorporating features that make it simpler and easier to use.

The original article suggested that this criterion might relate to responsive design and Easy Read alternatives. Those may sometimes contribute, but they should not be treated as a complete interpretation. Cognitive accessibility can also involve clarity, consistency, error prevention, assistance, memory demands, time limits, task complexity and the availability of simpler ways to complete a task.

### K. Privacy

> Where the product or service incorporates features that are provided for accessibility, it shall provide at least one mode of operation that maintains privacy when using those features that are provided for accessibility.

This requirement should prompt examination of situations in which an accessibility feature could expose information, attract attention or force a person to disclose an access need. Wider data collection, cookies, preference detection and assistive-technology detection may raise additional privacy and data-protection questions, but they should not automatically be presented as the complete meaning of this functional performance criterion.

## Conclusion

The EAA should not be approached as a search for a single checklist, audit or product. A more credible approach combines:

- accessible and inclusive design practices;
- traceability from applicable requirements to product decisions;
- automated testing for reliably detectable issues;
- manual assessment of requirements that need human judgement;
- direct evidence from disabled customers;
- privacy-conscious analysis of functional access needs;
- documented remediation and accountable ownership; and
- jurisdiction-specific legal and regulatory review.

Together, these elements can show both **how a product or service was designed** and **how successfully it works for disabled customers**. That is a stronger governance model than treating technical conformance or the absence of complaints as proof of compliance.

---

## Source and provenance notes

This semantic edition was prepared from an article supplied as Markdown. The structure and editorial notes are intended to improve retrieval, chunking and interpretation by LLM and RAG systems. Legislative quotations remain attributed to the EAA. The article's interpretations, predictions and recommendations remain attributable to the author.

### Recommended retrieval relationships

When this document is used in an AI knowledge system, retrieve it alongside:

- the current consolidated text of Directive (EU) 2019/882;
- applicable national implementing legislation;
- current European Commission and national regulator guidance;
- relevant harmonised standards and technical specifications;
- organisational accessibility, privacy and product-governance policies; and
- evidence about the specific product, service and customer population being assessed.

### Authoritative starting points

- [Directive (EU) 2019/882 — full legal text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882)
- [European Commission overview of the European Accessibility Act](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en)

### Claims requiring current verification

Before relying on this article for a compliance decision, verify:

- which products, services and organisations are within scope;
- applicable exemptions, transitional provisions and disproportionate-burden rules;
- the competent authority in each Member State;
- documentation, notification and reporting duties;
- complaint, monitoring and enforcement procedures;
- available penalties and corrective powers;
- the current status and applicability of harmonised standards; and
- all accessibility, privacy and performance claims made by named tools or services.
