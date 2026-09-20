---
title: "EAA Evidence and Conformity Record Model"
subtitle: "A canonical Layer 3 model for assembling evidence, reaching controlled requirement conclusions, and governing European Accessibility Act claims"
version: "1.0"
date: "2026-09-20"
status: "Canonical evidence-control framework"
canonical_layer: "Layer 3"
authority_type: "Governance procedure and practitioner guidance"
legal_status: "Not legislation, regulator guidance, or legal advice"
jurisdiction_scope: "European Union; final decisions require applicable national implementing law"
prerequisites:
  - "An approved EAA Scope and Applicability Gate record"
related_frameworks:
  - "Accessibility Test-Led Delivery Framework for generic requirements, tests, executions, issues, exceptions, departures, and release decisions"
  - "Inclusive Digital Service Outcome Dataset for Layer 2 functional and experiential outcome findings"
decision_owners:
  legal_or_compliance_authority: "Named reviewer responsible for the legal route, interpretation, limitations, and permitted claim"
  accountable_product_or_service_owner: "Named owner responsible for implementation, corrective action, monitoring, and decisions within delegated authority"
ai_ingestion_guidance:
  - "Retrieve the approved Layer 1 applicability decision before using this model."
  - "Do not infer legal conformity from a test pass, WCAG conformance, user satisfaction, an automated score, a supplier statement, or the absence of complaints."
  - "Keep legal conformity, standards conformance, organisational policy, and user outcomes as separate findings."
  - "Preserve failures, uncertainty, limitations, exceptions, departures, and contradictory evidence; do not average them into a single score."
  - "Do not treat statistical significance as either mandatory for all evidence or sufficient for a legal conclusion."
  - "Do not approve a scope decision, exemption, legal limitation, conformity conclusion, or public claim. Route approval to the named human authority."
  - "When evidence, legal authority, jurisdiction, source status, or decision authority is missing, return 'cannot conclude' or 'legal review required'."
---

# EAA Evidence and Conformity Record Model

## Purpose

This document defines the evidence and decision records used after the [EAA Scope and Applicability Gate](EAA_Scope_and_Applicability_Gate.md) has established the relevant legal route. It provides a reconstructable path from an applicable legal requirement to evidence, a controlled conclusion, any public claim, and continuing monitoring.

The model is intended to prevent four errors:

1. treating one test, standard, audit, or research study as a complete legal conclusion;
2. allowing positive user evidence to erase an applicable legal or standards failure;
3. allowing a technical pass to conceal poor, unequal, or unacceptable real-world outcomes; and
4. making a broad compliance claim without recording its product or service scope, jurisdiction, version, period, limitations, and approval.

This is a governance procedure, not a legal opinion. Applicable national legislation and current authoritative material control the final legal decision.

## Non-negotiable rules

1. **Layer 1 controls scope.** Do not create an EAA conformity conclusion until an approved applicability decision identifies the subject, operator role, territory, national law, relevant dates, and applicable requirements.
2. **Each requirement receives its own conclusion.** Evidence about one clause, function, version, channel, territory, or population must not be generalised without a recorded basis.
3. **Different findings remain different.** A legal-requirement conclusion, standards result, organisational-policy decision, and user-outcome finding answer different questions.
4. **Evidence retains its limits.** Every evidence item must say what it supports, what it does not establish, and the scope in which it was obtained.
5. **Contradiction is visible.** Conflicting evidence produces investigation or `cannot conclude`; it must not be silently resolved by selecting the preferred result.
6. **A failure remains a failure.** An exception, risk acceptance, compensating measure, or positive outcome finding does not convert a failed standard or requirement test into a pass.
7. **Legal limitations use a legal route.** Exemptions, transitional provisions, fundamental-alteration assessments, disproportionate-burden assessments, and other statutory limitations are not ordinary product exceptions.
8. **Claims are narrower than evidence.** A conformity claim must not exceed the requirements, product or service boundary, release, jurisdictions, environments, and period supported by the approved record.
9. **Monitoring is part of the decision.** A conclusion is current only while its assumptions, evidence, implementation, suppliers, and legal sources remain materially unchanged.
10. **A human authority decides.** An AI system may organise evidence and identify gaps; it must not approve a legal conclusion or public claim.

## Relationship to the three layers

| Layer | Governing question | Output consumed by the next layer |
|---|---|---|
| Layer 1 — EAA Scope and Applicability Gate | Which law, jurisdiction, operator role, product or service category, dates, Annex I route, and limitations apply? | Approved applicability decision and clause-level requirement records. |
| Layer 2 — Inclusive digital service outcomes | What functional and experiential outcomes should the service deliver, including outcomes not fully represented by a technical standard? | Outcome definitions, measures, affected populations, research findings, and organisational-policy expectations. |
| Layer 3 — this model | What does the combined evidence establish, what remains uncertain or unresolved, who may decide, and what may be claimed? | Requirement conclusions, conformity decision, controlled claim, monitoring, and corrective action. |

The layers do not override one another. Layer 2 evidence may reveal that a technically conforming implementation still produces exclusion, excessive effort, loss of autonomy, or an inequivalent outcome. It may also support an alternative design or an evidence-based departure from organisational policy. It cannot remove an applicable legal obligation or rewrite the result of a standards test.

## Relationship to the Accessibility Test-Led Delivery Framework

The [Accessibility Test-Led Delivery Framework](https://github.com/Double-FW/QA_Accessibility_Testing/blob/main/Accessibility_Test_Led_Delivery_Framework.md) supplies the generic delivery records and controls for requirements, repository test references, local procedures, mappings, automated implementations, executions, issues, exceptions, baseline departures, release decisions, result vocabulary, evidence minimums, and quality gates.

This document adds the EAA-specific decision layer. It references those delivery records instead of duplicating them. Where the frameworks overlap:

- use ATLF result values for individual test executions;
- use this model for legal-requirement and conformity conclusions;
- retain the source identity and version of every ATLF record; and
- record an explicit relationship rather than copying one result into several meanings.

## Evidence and decision chain

The minimum traceability chain is:

> applicability decision → legal requirement → interpretation → standard or design mapping → test execution and evidence item → requirement conclusion → issue, exception, departure, alternative solution, or legal limitation where relevant → conformity conclusion → controlled claim → monitoring and corrective action

Every link is many-to-many unless the evidence demonstrates otherwise. A single test can support several requirements; a single requirement can need several methods, environments, states, and evidence sources.

## Record types

| Record | Purpose | Minimum content |
|---|---|---|
| Applicability decision | Establish the approved Layer 1 route. | Decision ID; outcome; subject; operator role; territories; national law; applicable dates; Annex I route; included and excluded scope; decision authority; review triggers. |
| Legal requirement | Preserve the applicable obligation. | Requirement ID; exact national source; Directive or Annex relationship where relevant; source version; exact text; actor; subject; applicability; required evidence; owner. |
| Requirement interpretation | Explain how the requirement applies without presenting interpretation as law. | Interpretation ID; requirement link; plain-English interpretation; facts and assumptions; authority type; author; reviewer; uncertainty; date and version. |
| Standards or specification mapping | State how a standard, common specification, technical criterion, or method relates to the requirement. | Mapping ID; source and version; legal status; mapped provision; relationship; coverage limits; reviewer. |
| Design or policy mapping | Connect legal requirements to design decisions or broader organisational expectations. | Mapping ID; requirement or outcome link; design rule or policy source; relationship; applicability; known limits. |
| Evidence item | Preserve an observation, source, analysis, artefact, or dataset with its provenance and limits. | Evidence ID; category; source; date; version; method; scope; observation; supports; does not establish; quality and confidence; owner; location; retention. |
| Test execution | Record an individual evaluation using the ATLF vocabulary. | ATLF execution ID and the ATLF evidence minimum. |
| Requirement conclusion | Decide what the evidence establishes for one legal requirement in a defined scope. | Conclusion ID; requirement; scope; evidence set; result; rationale; contradictions; limitations; confidence; reviewer; approval; review triggers. |
| User-outcome finding | Record functional or experiential evidence without converting it into a legal conclusion. | Layer 2 finding ID; `IDSO` outcome ID; population and task; context; method; observation; uncertainty; affected scope; action; relationship to requirements. |
| Issue | Record an unmet expected outcome or implementation defect. | ATLF issue record plus legal-requirement and user-outcome links where relevant. |
| Exception | Record temporary acceptance of an unresolved failure or residual disadvantage. | ATLF exception record, including authorised approval, compensating action, monitoring, review date, and expiry. |
| Evidence-based departure | Record an alternative to an organisational or design baseline when equal or better outcomes are supported. | ATLF baseline-departure record, including the non-legal baseline, evidence, uncertainty, claim limits, monitoring, and review. |
| Alternative technical solution | Record a different technical route asserted to satisfy an applicable requirement where the legal framework permits it. | Legal route; requirement; comparison basis; equal or increased accessibility evidence where required; standards result; affected users and functions; uncertainty; reviewer and approval. |
| Legal limitation | Record an exclusion, exemption, transition, fundamental-alteration decision, disproportionate-burden decision, or other legally controlled limitation. | Exact legal basis; facts; evidence; scope; authority; notifications or publications; continuing duties; review; expiry where relevant. |
| Conformity conclusion | Aggregate requirement conclusions without erasing their differences. | Decision ID; scope; jurisdictions; release; applicable requirement set; conclusions; unresolved items; legal limitations; confidence; decision authority; validity and review. |
| Public claim | Control wording derived from the conformity conclusion. | Claim ID; exact wording; intended audience and channel; scope; exclusions; evidence and conclusion links; owner; legal or compliance approval; publication and withdrawal dates. |
| Monitoring event | Reassess a conclusion after time, change, feedback, or new evidence. | Event ID; trigger; affected records; evidence; assessment; corrective action; owner; date; status; next review. |

## Identifier, version, and relationship rules

- Give every record a stable, namespaced identifier and version.
- Never reuse a retired identifier for a different subject or meaning.
- Preserve the identity and version of the source law, standard, dataset, test, build, environment, and artefact.
- Use explicit relationships such as `establishes scope for`, `interprets`, `maps to`, `supports`, `partially supports`, `contradicts`, `evaluates`, `limits`, `supersedes`, and `triggers review of`.
- A link means only the named relationship. A WCAG mapping does not automatically mean that the criterion fully evaluates the legal requirement.
- Superseding a record does not delete its history. Preserve the previous decision, reason for change, approving authority, and effective dates.

### Layer 2 to Layer 3 status control

Layer 2 findings must not be translated automatically into legal-requirement conclusions. In particular:

- `supported` does not mean `supported as met`;
- `not supported` identifies a user-outcome problem but does not by itself identify the failed legal clause;
- `insufficient evidence` may support `cannot conclude` only when the missing evidence is material to that requirement; and
- `not relevant with rationale` never means `not applicable by approved scope decision`. Legal non-applicability requires the approved Layer 1 record.

Layer 3 must retain the outcome and finding IDs, assess their relevance to the exact requirement, and record the human reasoning.

## Evidence item requirements

Each evidence item must record:

- the decision question it was collected to inform;
- its source, author or collector, date, version, and accessible location;
- the product, service, feature, task, state, content, territory, population, and time period covered;
- the method, environment, technologies, sample, and material assumptions;
- the observation or source statement, separated from interpretation;
- the requirement, outcome, issue, or decision it supports or contradicts;
- what the item cannot establish on its own;
- quality limitations, bias, missing populations, missing environments, and uncertainty;
- the competent reviewer and review date;
- retention, access, confidentiality, and personal-data controls; and
- whether later evidence has superseded or materially contradicted it.

Evidence must be accessible to the people who need to review it. Where recordings or visual artefacts are retained, provide a searchable text account of the material observations.

## Evidence categories and their limits

| Evidence category | It may support | It cannot establish alone |
|---|---|---|
| Applicable legislation and authoritative decisions | Legal scope, duties, procedures, limitations, enforcement, and required information in the relevant jurisdiction. | Whether the implementation succeeds for users in practice. |
| Directive (EU) 2019/882 | The shared EU framework, covered categories, operator obligations, and Annex structure. | A complete jurisdiction-specific conclusion without the national implementation and relevant facts. |
| Harmonised standards or common specifications | Technical methods and, where the legal conditions are met, a presumption of conformity within their stated scope. | Matters outside that scope or a blanket conclusion about an entire product or service. |
| WCAG and other technical standards | Repeatable criteria for many digital accessibility barriers and a recognised technical baseline. | EAA scope, every applicable EAA obligation, or the full quality and equality of a service experience. |
| Design and implementation artefacts | Intended behaviour, architecture, component contracts, content, and implemented controls. | Actual operation in every state, environment, or user context. |
| Automated evaluation | Repeatable detection of supported rules and regressions in the scanned scope. | Complete accessibility, task success, understandable interaction, or valid treatment of untested states. |
| Manual technical evaluation | Behaviour requiring human inspection, including interaction, semantics, content, sequence, and alternatives. | Every assistive-technology or real-world user outcome outside the tested scope. |
| Assistive-technology evaluation | Behaviour with declared technologies, versions, settings, tasks, and environments. | Performance across all technologies, users, configurations, and contexts. |
| Research with disabled people | Task success, effort, errors, recovery, comprehension, autonomy, privacy, dignity, equivalence, predictability, satisfaction, and relevant enjoyment. | Legal interpretation, automatic standards conformance, or population prevalence beyond what the design and sample support. |
| Quantitative research and analytics | Patterns, rates, comparisons, reach, and change where the measurement and sample are valid. | The cause of a barrier, the absence of rare severe exclusion, or legal permission to disregard a requirement. |
| Complaints, support, incidents, and operational evidence | Experienced barriers, recurring failures, workarounds, harm, and change over time. | The absence of barriers when reporting channels are unused or inaccessible. |
| Supplier evidence | Supplier methods, claims, known limitations, roadmaps, and contractual commitments. | Independent proof for critical workflows unless validated to the level required by risk. |
| Corrective-action and monitoring evidence | Whether remediation was implemented, retested, sustained, and controlled after change. | The validity of an earlier claim outside the monitored scope or period. |

### Qualitative, quantitative, and statistically significant evidence

The method must fit the decision question.

- A small qualitative study may reveal a severe barrier, an unexpected workaround, loss of autonomy, or a design requirement. Its sample may not support a prevalence estimate.
- A statistically significant quantitative result may strengthen a population-level comparison when the study design, sample, measure, and effect size are appropriate. Significance does not prove practical importance, inclusion of under-represented users, or legal conformity.
- Absence of an observed problem is not proof that no problem exists, particularly for rare but severe exclusion.
- Triangulation across technical, behavioural, qualitative, quantitative, operational, and complaint evidence normally supports a stronger decision than one source alone.

No fixed sample size or statistical threshold applies to every decision. The record must explain why the evidence is proportionate to the claim being made.

## Results and conclusion vocabularies

### Test execution result

Use the ATLF values without changing their meanings:

`Pass`, `Fail`, `Cannot tell`, `Not applicable`, `Not tested`, `Blocked`, and `Tool error`.

A test result describes the declared test scope and environment. It is not, by itself, a legal conclusion.

### Legal-requirement conclusion

| Conclusion | Meaning |
|---|---|
| `supported as met` | Sufficient, current, and coherent evidence supports the requirement for the declared scope. |
| `not met` | Evidence shows that the requirement is not satisfied in some or all of the declared scope. |
| `cannot conclude` | Evidence is missing, insufficient, stale, contradictory, or too uncertain for the proposed conclusion. |
| `not applicable by approved scope decision` | The approved Layer 1 decision establishes that the requirement does not apply to the declared scope. Preserve the decision link and rationale. |
| `not assessed` | The requirement is applicable but evaluation has not been completed. This is not a pass. |

Use `legal review required` as a routing status when the applicable law, interpretation, authority, or legal effect is unresolved. It is not a substitute for a conclusion.

### Confidence

Record confidence as `high`, `moderate`, `low`, or `insufficient`, with a written rationale. Consider:

- coverage breadth and representativeness;
- fidelity of the version, state, environment, and user context;
- repeatability and consistency;
- source authority and currency;
- reviewer competence and independence;
- unresolved `cannot tell`, blocked, or untested results;
- contradictory evidence; and
- the size and consequence of the proposed claim.

Confidence is not a percentage score and must not turn a negative or incomplete conclusion into a positive one.

## Reaching a requirement conclusion

A requirement may be concluded `supported as met` only when:

1. the approved applicability record and exact legal source are current;
2. the interpretation and any standards relationship are explicit and reviewed;
3. the evidence methods cover the material functions, states, environments, information, and support channels required by the clause;
4. all material evidence is traceable to the relevant release or operating version;
5. failures, contradictions, limitations, and missing populations have been assessed rather than omitted;
6. no unresolved item prevents the proposed conclusion;
7. any alternative technical solution follows a permitted legal route and has the required comparison evidence; and
8. the named competent human reviewer has recorded the conclusion and confidence.

Where one part of the scope is supported and another is not, split the conclusion by feature, channel, territory, version, or period. Do not use an average result.

## User-outcome findings

Layer 2 findings should consider, where relevant:

- task completion and accuracy;
- time and effort;
- errors, prevention, and recovery;
- comprehension and predictability;
- autonomy and freedom from unnecessary reliance on another person;
- privacy and control over personal information;
- dignity and avoidance of stigma;
- equivalence of outcome, timeliness, cost, and service quality;
- satisfaction and confidence; and
- enjoyment where it is a material purpose of the service.

A positive user-outcome finding does not change a legal or standards result. A negative finding can require further investigation, corrective action, a broader organisational response, or reconsideration of whether the implementation actually satisfies the applicable legal requirement.

## Distinct decision routes

| Route | What it means | Effect on a failed result | Required authority |
|---|---|---|---|
| Remediation | The implementation is corrected and retested. | A new passing execution may supersede the earlier implementation state; history remains. | Product, engineering, QA, and relevant reviewers under the delivery model. |
| Exception | A known unresolved failure or residual disadvantage is accepted temporarily. | The failure remains a failure. | Accountable owner within documented delegation, or escalation authority. |
| Evidence-based departure | An alternative to an organisational or design baseline is supported by equal or better outcomes in context. | It does not change a standards result or waive law. | Accountable owner within authority, with legal or compliance review where obligations may be affected. |
| Alternative technical solution | A different solution is asserted to meet the applicable legal requirement through a legally permitted route. | The original standards result remains recorded; the legal conclusion depends on the applicable route and evidence. | Named legal or compliance reviewer and accountable owner. |
| Legal limitation | A statutory exclusion, exemption, transition, fundamental-alteration assessment, disproportionate-burden assessment, or similar control limits an obligation. | It does not make the inaccessible feature pass. | Authority required by the applicable national law and organisational delegation. |

Cost, schedule, low usage, low complaint volume, supplier difficulty, positive satisfaction data, or a small sample does not by itself establish any legal limitation.

## Conformity conclusion

A conformity conclusion must state:

- the exact product, service, feature, transaction, information, support function, and channels assessed;
- the economic-operator role and accountable legal entity;
- the jurisdictions and national implementing laws used;
- the release, build, configuration, suppliers, environments, and assessment period;
- the approved applicability decision and complete applicable requirement set;
- the result and confidence for every requirement;
- unresolved failures, `cannot conclude` items, untested areas, exceptions, departures, alternative solutions, and legal limitations;
- known excluded scope and evidence limitations;
- corrective action and monitoring commitments;
- the competent reviewer, legal or compliance authority, accountable owner, approval date, and delegated authority; and
- validity period, review date, and change triggers.

An aggregate conclusion must never hide an unresolved requirement. If the evidence does not support the proposed scope, narrow the conclusion or use `cannot conclude`.

### Product and service evidence

Product and service obligations and documentation routes are not interchangeable. For a covered product, the record may need to link technical documentation, conformity-assessment material, the EU declaration of conformity, and marking information where applicable. For a covered service, the record may need to link the information explaining how the service meets the applicable requirements, service-delivery evidence, and continuing conformity controls. Determine the precise records, retention, language, notification, and publication duties from the applicable national law and operator role.

## Claim controls

Do not publish an unqualified statement such as `EAA compliant` unless the authorised reviewers have established that its full implied scope is accurate and legally supportable. The absence of a stated boundary can make a claim broader than the evidence.

Prefer scoped wording such as:

> Evidence supports conformity with the listed requirements for the identified service functions, release, jurisdictions, environments, and assessment period, subject to the recorded limitations and continuing monitoring.

The exact wording must be adapted to the legal context and approved conclusion. A public claim must:

- identify or link to its material scope and date;
- remain consistent with unresolved issues and legal limitations;
- avoid presenting WCAG conformance as equivalent to complete EAA conformity;
- avoid presenting an accessibility statement, VPAT, automated score, certification, or supplier claim as broader proof than it provides;
- name the owner responsible for correction or withdrawal; and
- be reviewed when any monitoring trigger occurs.

## Minimum decision bundle

Before approving a conformity conclusion or claim, retain:

- the approved Layer 1 applicability decision;
- current national legislation and authoritative sources used;
- the complete clause-level requirement set and interpretations;
- standards, specifications, design rules, and mapping records;
- the relevant ATLF requirements, procedures, executions, issues, exceptions, departures, and release decision;
- evidence items and user-outcome findings with provenance and limits;
- alternative-solution and legal-limitation records where applicable;
- a requirement-by-requirement conclusion and confidence rationale;
- the aggregate conformity conclusion;
- approval and delegation records;
- the exact wording and scope of any public claim; and
- monitoring, complaint, incident, corrective-action, and review arrangements.

## Stop conditions

Do not approve a conformity conclusion or public claim when:

- the Layer 1 record is absent, unapproved, stale, or inconsistent with the assessed subject;
- the applicable national law, jurisdiction, operator role, dates, or requirement set is missing;
- an applicable requirement is `not met`, `cannot conclude`, or `not assessed` and the proposed wording would imply otherwise;
- a material test is blocked, has a tool error, or lacks required human evaluation;
- conflicting evidence has no documented resolution or claim limitation;
- a standards mapping is being treated as proof without execution evidence;
- positive user evidence is being used to erase a legal or standards failure;
- a negative user-outcome finding that may affect the requirement has not been investigated;
- an exception, departure, alternative solution, or legal limitation lacks the correct authority and required evidence;
- the record cannot be traced to the relevant release, configuration, territory, or period;
- the decision-maker lacks documented authority; or
- monitoring, corrective action, expiry, or review controls required by the decision are absent.

## Roles and approval

| Role | Responsibility in this model |
|---|---|
| Product or service team | Prepares scope facts, implementation records, evidence links, issues, actions, and proposed conclusions. |
| QA or competent evaluator | Classifies test results, assesses evidence quality, preserves uncertainty, and recommends requirement conclusions. |
| Accessibility specialist | Challenges interpretations, method selection, evidence coverage, and complex functional or user-outcome findings. |
| Research | Produces ethical user evidence, states sample and method limits, and avoids unsupported population claims. |
| Legal or compliance reviewer | Confirms the applicable legal route, national sources, legal interpretations, limitations, and permitted claim. |
| Accountable product or service owner | Owns corrective action and approves decisions within documented delegated authority. |
| Executive or enterprise-risk authority | Decides matters above delegation thresholds or with systemic, high-impact, or legally sensitive exposure. |
| Disabled participants and representatives | Provide essential evidence and challenge; they do not carry the organisation's compliance or risk-acceptance accountability. |
| AI or automated system | Retrieves, validates, cross-references, and identifies gaps; it does not exercise approval authority. |

Independence must be proportionate to risk. Record when the same person designed, implemented, evaluated, and approved a material item, and reflect that limitation in confidence.

## Monitoring and corrective action

A monitoring event is required when any of the following may affect the conclusion:

- a material release, configuration, content, journey, component, or supplier change;
- a new territory, customer group, operator role, contract, or channel;
- a change to EU or national law, official guidance, enforcement practice, harmonised standards, or common specifications;
- a complaint, incident, enforcement contact, or material support pattern;
- new test, research, analytics, or operational evidence;
- contradictory evidence or a failed regression;
- an exception, limitation, approval, or evidence item reaching its review date or expiry; or
- loss of an accessible alternative or compensating measure.

The event record must identify the affected conclusions and claims, immediate protection or correction, owner, target date, retest, approval, and whether a public statement must be amended or withdrawn.

## AI and autonomous-system controls

An AI system using this model must:

1. retrieve the approved applicability decision and current source versions first;
2. preserve quotations separately from interpretations and generated summaries;
3. label every source by authority type and jurisdiction;
4. maintain separate fields for test results, requirement conclusions, user outcomes, policy decisions, and claims;
5. surface missing, stale, contradictory, and out-of-scope evidence;
6. avoid calculating a single accessibility or compliance score that conceals material failures;
7. retain negative and minority findings, including rare but severe barriers;
8. recommend proportionate additional evidence and identify what question it would answer;
9. return `cannot conclude` or `legal review required` when the record cannot support a decision;
10. identify the named human approver and prevent autonomous approval or publication; and
11. preserve an audit trail of source retrieval, transformations, reasoning inputs, versions, and human decisions.

## Evidence item template

```yaml
evidence_id: "EAA-EV-"
version: ""
decision_question: ""
category: ""
source:
  title: ""
  authority_type: ""
  jurisdiction: ""
  version_or_date: ""
  location: ""
collected_by: ""
collected_on: ""
scope:
  product_or_service: ""
  features_or_tasks: []
  states_and_environments: []
  territories: []
  populations: []
  period: ""
method:
  description: ""
  technologies: []
  sample: ""
  assumptions: []
observation: ""
supports: []
contradicts: []
does_not_establish: []
limitations_and_uncertainty: []
quality_review:
  confidence: "high | moderate | low | insufficient"
  rationale: ""
  reviewer: ""
  review_date: ""
retention_and_access: ""
superseded_by: ""
```

## Requirement conclusion template

```yaml
conclusion_id: "EAA-RC-"
version: ""
applicability_decision_id: ""
legal_requirement_id: ""
declared_scope:
  product_or_service: ""
  functions_and_channels: []
  release_or_period: ""
  territories: []
interpretation_id: ""
standards_and_design_mappings: []
test_execution_ids: []
evidence_ids: []
user_outcome_findings:
  - finding_id: "IDSO-F-"
    outcome_id: "IDSO-"
    relationship_to_requirement: "supports | partially supports | contradicts | contextual evidence"
issues: []
exceptions: []
departures: []
alternative_solutions: []
legal_limitations: []
result: "supported as met | not met | cannot conclude | not applicable by approved scope decision | not assessed"
rationale: ""
contradictory_evidence: []
known_limits: []
confidence:
  level: "high | moderate | low | insufficient"
  rationale: ""
reviewer: ""
decision_authority: ""
decision_date: ""
review_triggers: []
next_review_date: ""
```

## Conformity conclusion template

```yaml
decision_id: "EAA-CD-"
version: ""
legal_entity_and_operator_role: ""
applicability_decision_id: ""
scope:
  product_or_service: ""
  functions_and_channels: []
  release_configuration_or_period: ""
  territories: []
  environments: []
national_laws_and_source_versions: []
applicable_requirement_ids: []
requirement_conclusion_ids: []
unresolved_items: []
exceptions_and_departures: []
alternative_solutions_and_legal_limitations: []
overall_decision: "supported within stated scope | not supported | cannot conclude"
confidence:
  level: "high | moderate | low | insufficient"
  rationale: ""
permitted_claim_ids: []
corrective_action_and_monitoring: []
competent_reviewer: ""
legal_or_compliance_authority: ""
accountable_owner: ""
delegation_basis: ""
approval_date: ""
review_triggers: []
next_review_date: ""
```

## Public claim template

Create a separate claim record for each materially different statement, audience, language, territory, or publication channel. Approval of a conformity conclusion permits only the wording and scope recorded here; it does not authorise later paraphrases automatically.

```yaml
claim_id: "EAA-CL-"
version: ""
record_status: "draft | approved | published | superseded | withdrawn"
conformity_decision_id: "EAA-CD-"
requirement_conclusion_ids: []
evidence_ids: []
exact_wording: ""
claim_type: "public statement | accessibility information | tender response | contract statement | internal assurance | other"
audience: ""
publication_channel: ""
language: ""
scope:
  product_or_service: ""
  functions_and_channels: []
  release_configuration_or_period: ""
  territories: []
material_exclusions_and_limitations: []
owner: ""
legal_or_compliance_approver: ""
accountable_owner: ""
approval_date: ""
publication_date: ""
review_date: ""
withdrawal_date: ""
withdrawal_reason: ""
review_triggers: []
supersedes: ""
superseded_by: ""
```

## Sources and related material

- [Directive (EU) 2019/882 — official text](https://eur-lex.europa.eu/eli/dir/2019/882/oj)
- [European Commission — European Accessibility Act overview](https://commission.europa.eu/strategy-and-policy/policies/justice-and-fundamental-rights/disability/european-accessibility-act-eaa_en)
- [EAA Scope and Applicability Gate](EAA_Scope_and_Applicability_Gate.md)
- [Inclusive Digital Service Outcome Dataset](https://github.com/Double-FW/Inclusive_and_Effective_Design/blob/main/Inclusive_Digital_Service_Outcome_Dataset.md)
- [Guide to the European Accessibility Act 2025](Guide_to_the_European_Accessibility_Act_2025.md)
- [Accessibility Test-Led Delivery Framework](https://github.com/Double-FW/QA_Accessibility_Testing/blob/main/Accessibility_Test_Led_Delivery_Framework.md)

## Use limitation

This model supports disciplined evidence and decision-making. It does not replace the exact Directive text, applicable national legislation, current regulator or market-surveillance material, harmonised standards or common specifications, competent accessibility evaluation, or legal advice for a particular product, service, operator, jurisdiction, or dispute.
