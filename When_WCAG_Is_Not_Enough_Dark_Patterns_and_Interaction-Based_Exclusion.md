---
title: "When WCAG Is Not Enough: Dark Patterns and Interaction-Based Exclusion"
short_title: "Dark Patterns and Interaction-Based Exclusion"
author: "Gareth Ford Williams"
language: "en-GB"
document_type:
  - "practitioner_article"
  - "inclusive_interaction_design_guidance"
  - "ai_design_governance_reference"
content_status: "author_guidance_with_editorial_diagnostics"
date_published: null
date_processed: "2026-09-18"
version: "1.0-semantic"
word_limit: 5000
jurisdictional_context:
  - "international"
  - "European Union"
  - "United Kingdom"
  - "United States"
  - "Canada"
primary_domains:
  - "digital_accessibility"
  - "interaction_design"
  - "deceptive_patterns"
  - "consumer_protection"
  - "inclusive_design"
  - "ai_governance"
audiences:
  - "designers"
  - "product_managers"
  - "developers"
  - "accessibility_professionals"
  - "user_researchers"
  - "consumer_protection_teams"
  - "legal_and_policy_teams"
  - "ai_design_and_governance_systems"
key_concepts:
  - "interaction_based_exclusion"
  - "deceptive_patterns"
  - "dark_patterns"
  - "meaningful_choice"
  - "choice_symmetry"
  - "cognitive_accessibility"
  - "persistent_context"
  - "reversibility"
  - "semantic_html"
  - "wcag_conformance_limits"
  - "cumulative_interaction_harm"
  - "equitable_effort"
archive_coverage:
  deceptive_design_hall_of_shame:
    retrieval_date: "2026-09-18"
    index_reported_examples: 831
    treatment: "All indexed pattern families and harm mechanisms were considered; representative cases are named because reproducing every submission would breach the document word limit."
  dark_patterns_tip_line_sightings:
    retrieval_date: "2026-09-18"
    distinct_case_urls_observed: 165
    treatment: "The fully expanded archive was reviewed and synthesised by interaction harm; representative cases are named."
source_characteristics:
  practitioner_guidance: true
  contains_community_submissions: true
  community_submissions_independently_verified: false
  contains_legal_context: true
  legal_advice: false
  normative_standard: false

---

# When WCAG Is Not Enough: Dark Patterns and Interaction-Based Exclusion

## Article overview

A digital product can satisfy individual Web Content Accessibility Guidelines (WCAG) success criteria and still exclude, pressure or mislead people. A button may have an accessible name, sufficient contrast and full keyboard support while its wording conceals the consequence of activating it. A cancellation journey may use perfectly semantic controls while demanding thirty steps that a sign-up journey completed in two. A consent banner may be readable by a screen reader while making acceptance immediate and refusal deliberately exhausting.

This is **interaction-based exclusion**. The barrier is created by the sequence, timing, language, defaults, interruptions, information hierarchy or cumulative effort of the experience, rather than by one component in isolation.

Deceptive patterns, often called dark patterns, are interfaces that steer, obstruct or trick people into decisions they might not otherwise make. Not every inaccessible interaction is deceptive, and harmful intent should not be assumed without evidence. However, an organisation is still responsible for foreseeable harm when a pattern predictably removes meaningful choice or imposes unequal effort.

This article explains why WCAG is not enough on its own, gives practical examples, and defines rules that a human or AI system can use when designing, evaluating or remediating interactions.

## Contents

1. Interaction-based exclusion
2. Why WCAG conformance is not the whole answer
3. Principles for non-deceptive, inclusive interaction
4. Pattern examples and safer alternatives
5. Lessons from public case archives
6. Evaluation method for people and AI systems
7. Governance and escalation
8. Sources, provenance and limitations

## 1. Interaction-based exclusion

Accessibility is often tested component by component. Interaction happens across time. People must remember information, understand consequences, move between states, recover from errors and resist distractions while completing a task.

A pattern becomes interactionally exclusionary when it makes a legitimate task harder because of how the journey behaves. The effect may be especially severe for people with cognitive, learning, sensory, speech or motor impairments; people using assistive technologies; people experiencing pain, fatigue, anxiety or limited attention; and people working in unfamiliar languages or stressful situations.

The central question is not only, “Can the control be perceived and operated?” It is:

> **Can a person understand the available choices, make the choice they intend, complete it with proportionate effort, and reverse or correct it without being pressured or trapped?**

An AI system must evaluate the entire interaction outcome. It must not declare a pattern acceptable merely because each visible component passes an automated accessibility scan.

## 2. Why WCAG conformance is not the whole answer

WCAG is a technical accessibility standard. It contains important requirements about perception, operation, understanding and compatibility. It does not attempt to be a complete code of ethical design, consumer protection, privacy, usability or freedom from manipulation.

Some deceptive patterns also fail WCAG. A keyboard trap, missing form instruction, unannounced status message or low-contrast opt-out may create a direct failure. Other patterns can satisfy the literal success criteria while remaining harmful. WCAG does not generally require a cancellation journey to be as easy as subscription, a price comparison to be honest, a default to reflect the person’s interests, or a refusal button to be given equal prominence.

Conformance testing therefore answers one set of questions. It does not establish that:

- choices are neutral and informed;
- wording is honest about consequences;
- default settings respect the person’s interests;
- price, renewal and data use are disclosed at the right time;
- a task requires proportionate effort;
- refusal and withdrawal are as usable as acceptance;
- the interface avoids addiction, coercion or manufactured urgency; or
- disabled people receive a comparable route rather than a nominally possible one.

The [practical value of semantic HTML](https://brucelawson.co.uk/2018/the-practical-value-of-semantic-html/) is substantial. Native buttons, labels, headings and landmarks provide reliable browser and assistive-technology behaviour. Semantics make an interaction operable; they do not make its purpose honest. A semantic button labelled “Continue” can still conceal a purchase or subscription.

## 3. Principles for non-deceptive, inclusive interaction

### 3.1 Preserve informed choice

Explain material consequences before the person acts. State price, recurrence, data use, audience, duration and cancellation conditions in plain language beside the relevant choice. Do not rely on distant terms, small print or a later confirmation to repair an earlier omission.

### 3.2 Provide choice symmetry

Accepting and refusing should have comparable visibility, language, interaction cost and modality. A bright “Accept all” button paired with a faint text link that opens several preference screens is not a neutral choice, even when both controls meet minimum contrast.

### 3.3 Maintain context and persistence

Labels, instructions, prices and consequences must remain available while they are needed. Do not make a person remember information that disappeared on focus, after scrolling or during an error. Important messages must remain discoverable and must not rely solely on a brief visual event.

### 3.4 Use proportionate effort

A withdrawal, cancellation, refund, deletion or privacy choice should not require materially more effort than the action that created the commitment. Count steps, decisions, reading load, repeated authentication, waiting time and modality changes. Effort is an accessibility variable.

### 3.5 Support correction and reversal

People make mistakes, particularly when interfaces are dense, timed or unfamiliar. Preserve entered data, explain errors, provide an undo route where safe, and make irreversible consequences explicit. Do not use an “undo” toast as the only practical way to recover from a destructive action.

### 3.6 Avoid exploiting vulnerability

Do not exploit fatigue, fear, scarcity, shame, authority, financial pressure, compulsive behaviour or limited digital literacy. Disability is not a proxy for vulnerability, but some interaction demands can disproportionately affect disabled people. Test with people who experience the highest cost when the design fails.

### 3.7 Prefer semantic and predictable controls

Use the correct native element, an explicit visible label and conventional behaviour. A close control must close; a back control must go back; a toggle’s visual state must match its programmatic state. Do not change familiar button positions during the final cancellation step to exploit muscle memory.

## 4. Pattern examples and safer alternatives

The following examples show how an interface may appear technically conformant while the interaction remains exclusionary.

| Pattern | Why WCAG may not be enough | Interaction harm | Safer design rule |
|---|---|---|---|
| **Transient toast notification** | A toast may be exposed as a valid status message and still disappear too quickly, appear outside magnified view, obscure controls or make “Undo” available only for seconds. | People can miss confirmation, errors or recovery. Screen-reader speech may queue after the visual message has vanished. | Keep consequential messages in a persistent history or inline state. Permit pause, dismissal and recovery without requiring speed. Do not move focus unless the task requires it. |
| **Placeholder used as the only visible label** | An input can have an accessible name through `aria-label` while its visible placeholder disappears on entry or focus. | People lose the question, format and context while answering, reviewing or correcting errors. Memory and language demands rise. | Use a persistent, programmatically associated `<label>`. Treat placeholder text as an optional example, never as the label. |
| **Accessible but ambiguous button** | “Continue” may be keyboard operable, named and high contrast. | It may actually begin payment, share data or create a recurring subscription without making that consequence clear. | Name the action and consequence, such as “Start £12 monthly subscription”. |
| **Cancellation maze** | Every page can conform individually. | Repeated offers, surveys, confirmations and changing button positions exhaust people and create accidental retention. | Make cancellation no harder than sign-up, preserve progress and show one unambiguous confirmation. |
| **Telephone-only cancellation** | The website may itself conform. | Deaf people, people with speech impairments, anxious callers and people unable to call during business hours receive an unequal route. | Provide an equivalent self-service route using the same channel as sign-up, plus accessible alternatives. |
| **Preselected purchase, tip, insurance or marketing** | A checked checkbox can be fully accessible. | Inaction is treated as consent and unnoticed extras increase cost or data use. | Leave optional additions unselected and require an explicit, informed action. |
| **Asymmetric consent banner** | All controls may meet contrast and keyboard requirements. | Acceptance is one click while refusal requires multiple screens, or the reject control is visually and semantically minimised. | Offer “Accept” and “Reject” at the same level with comparable prominence and effort. |
| **Double-negative consent** | The words can be perceivable and programmatically associated. | “Untick if you do not want us not to contact you” increases cognitive load and error. | Use one positive proposition per control: “Send me marketing email.” |
| **Confirmshaming** | A refusal link may technically conform. | Language such as “No thanks, I prefer to waste money” uses shame to weaken voluntary choice. | Use neutral labels that describe the decision without judgement. |
| **Disguised advertisement** | The card or link may be accessible. | Styling makes advertising resemble navigation, search results, messages or operating-system alerts. | Identify advertising before interaction and separate it visually and semantically from product controls. |
| **Close control that opens an offer** | An icon may have the accessible name “Close”. | Activating it navigates to registration, premium purchase or another page, contradicting its name. | Make control behaviour match its name. Use a separate, honestly labelled offer link. |
| **Hidden or drip pricing** | Price text may be accessible wherever it appears. | Mandatory fees, delivery costs or currency conversions appear only late in the journey, preventing meaningful comparison. | Show the unavoidable total and currency at the earliest decision point and update it transparently. |
| **Sneak into basket** | Cart controls can pass WCAG. | An optional item, warranty, donation or subscription is added without an explicit request. | Require deliberate addition and provide a clear review before purchase. |
| **Hidden subscription or renewal** | Terms may exist in accessible text. | Trial, “free gift” or monthly price obscures renewal, annual commitment or cancellation fee. | Put recurrence, minimum term, renewal date and cancellation effect beside the call to action. |
| **Fake urgency or scarcity** | A countdown can be accessible and pauseable. | A resetting timer or unsupported “only two left” message pressures decisions with false information. | Use urgency only when factual, material, time-bound and verifiable. Never reset a supposedly fixed deadline. |
| **Fake social proof or review gating** | Ratings may be technically accessible. | Fabricated activity, selective publication or routing only positive reviewers to a public platform distorts evidence. | Explain how reviews are collected and publish feedback according to a neutral, documented policy. |
| **Nagging and repeated permission prompts** | Each dialog can be accessible. | Repeated requests after refusal wear people down, interrupt tasks and exploit fatigue. | Respect refusal, provide a stable setting, and ask again only after a relevant user-initiated change. |
| **Forced account or app download** | The registration form or app may conform. | People must disclose data, change device or install software for a task that does not genuinely require it. | Permit guest and web completion unless an account or app is necessary and the necessity is explained. |
| **Public-by-default or data-sharing default** | The setting can be labelled and operable. | People unknowingly expose content, contacts, location or activity. | Default to the least exposing state and request specific permission in context. |
| **Contact harvesting** | The permission dialog may be accessible. | “Find friends” becomes an invitation or upload of an address book without clear scope. | Separate local matching, contact upload and invitation. Preview recipients and require confirmation. |
| **Back-button or focus hijacking** | Visible controls may conform. | The interface adds history entries, steals focus or traps navigation so leaving is difficult. | Preserve browser, keyboard and assistive-technology conventions. Never intercept exit to force retention. |
| **Visual interference** | Favoured and disfavoured choices may both pass minimum contrast. | Size, placement, whitespace and colour make the organisation’s preferred action dominant and the alternative easy to miss. | Test relative prominence, not only minimum values. The visual hierarchy must reflect the user’s task. |
| **Choice reversal at the final step** | Each button may have a correct accessible name. | “Keep” and “Cancel” positions or styles swap after several repeated screens, exploiting habituation. | Keep ordering and styling stable. Use a final statement that repeats the actual outcome. |
| **Destructive action without durable recovery** | A delete button and confirmation dialog may conform. | A fleeting toast is the only undo route, or the confirmation uses vague wording. | State the object and consequence, provide durable recovery where possible, and do not make recovery time-critical. |
| **Error loop that erases work** | Error messages may be programmatically identified. | The form clears answers, returns focus unpredictably or provides no route around the invalid state. | Preserve valid data, place focus at a clear error summary, link errors to fields and support correction without repetition. |
| **Infinite feed and addictive defaults** | Feed items can be accessible. | Autoplay, variable rewards, infinite scroll and interruption prompts remove natural stopping points and increase cognitive fatigue. | Provide stopping cues, session controls, chronological alternatives and an off switch that remains off. |
| **AI recommendation presented as neutral** | The generated card can meet WCAG. | Paid, revenue-ranked or weakly evidenced recommendations appear objective, and uncertainty is hidden. | Label sponsorship and ranking factors, expose limitations, and never fabricate scarcity, consensus or authority. |
| **Comparison prevention** | Product details may each be accessible. | Inconsistent units, fragmented specifications or unavailable totals make options difficult to compare. | Use consistent measures, parallel structures and a comparison view that includes the full cost and commitment. |
| **Currency confusion and virtual money** | Controls can be readable and operable. | Tokens, bundles and exchange rates obscure real cost, especially in games and services used by children. | Show the local-currency equivalent at every decision and transaction point. |
| **Refund defaulted to store credit** | Both refund options may conform. | The interface makes store credit the apparent or automatic choice and hides return to the original payment method. | Present legally and contractually available remedies neutrally, with no silent default. |

### 4.1 Obstruction and hard-to-cancel journeys

Multiple confirmation screens, mandatory calls, required free-text reasons, retention offers that restart the journey and controls hidden below the fold create unequal effort. An AI should reject any flow whose success metric depends on abandonment of cancellation.

### 5.2 Preselection, hidden subscriptions and costs

An accessible checkbox does not create consent. Optional cost, recurrence, insurance, donation, data use or marketing must begin unselected. The total price and commitment must be available before the person invests effort or supplies payment details.

### 5.3 Visual interference, trick wording and unavailable refusal

The recurring harm is not merely poor contrast. It is a hierarchy engineered so that one legitimate choice becomes difficult to discover or a familiar symbol performs an unexpected action. An AI must compare the relative prominence and behaviour of every peer choice.

### 5.4 Nagging, forced action and defaults

A request does not become voluntary because the person eventually accepts after repeated refusal. Remember a refusal, minimise prompts and preserve access to the underlying task.

### 5.5 Privacy, contacts and AI training

Defaults and procedural friction can expose personal data or expand its use. An AI must separate collection, sharing, public visibility, personalisation and model training. Each requires a specific purpose, comprehensible explanation and valid control; one broad acceptance must not silently authorise all of them.

### 5.6 Disguised content, fake evidence and pressure

Complete Savings advertisements styled as payment steps, HP search-engine prompts, Yahoo ads styled as email, social-proof claims, review gating, resetting timers, misleading comparison prices and scarcity messages all corrupt the information on which a person decides. The correct repair is not simply a clearer button. Advertising, evidence, price history, availability and deadlines must be truthful, attributable and distinguishable from system or editorial content.

### 5.7 Children, gaming and addictive interaction

Cases concerning virtual currency and purchases, and social-media engagement, and Duolingo-style “addictive” mechanisms show that harm can arise from repetition, variable rewards, public defaults and currency abstraction. The risk rises when children or people under stress cannot reliably translate tokens, anticipate recurrence or find a stopping point. Do not optimise engagement without limits, recovery and age-appropriate comprehension testing.

The archive disclaimer matters. Public reports are signals for investigation and test design. They are not, by themselves, proof of unlawful conduct, corporate intent or current product behaviour.

## 6. Evaluation method for people and AI systems

An AI evaluating an interaction should use the following sequence.

### Step 1: Define the user’s intended outcome

State the task in the user’s terms, such as “decline tracking”, “buy one item for the displayed total”, “cancel without further billing” or “delete the account while retaining legally required records”. Do not substitute the organisation’s conversion objective.

### Step 2: Map the complete journey

Record every screen, dialog, notification, state change, branch, interruption and channel change. Include refusal, correction, cancellation, refund, deletion, recovery and failure—not only the preferred happy path.

### Step 3: Test technical accessibility

Apply current WCAG requirements and platform accessibility conventions using automated checks, manual inspection and assistive-technology testing. Verify semantics, names, roles, states, focus, reading order, keyboard and alternative-input operation, zoom, reflow, timing, errors and status messages.

### Step 4: Test interaction integrity

Ask whether consequences are disclosed before action; peer choices have comparable prominence and effort; defaults protect the person; labels and instructions persist; prices are complete; and refusal remains possible without penalty, shame or repetition.

### Step 5: Compare effort and outcomes

Measure steps, time, reading load, memory demand, required precision, authentication, waiting, repetition and channel changes. Compare joining with leaving, accepting with refusing, buying with refunding, and sharing with withdrawing. A large unexplained asymmetry is a governance flag.

### Step 6: Test with affected people

Include disabled participants with relevant access needs and people likely to experience the highest cognitive, financial or privacy cost. Measure comprehension, intended versus actual choice, task success, recovery, confidence, trust and emotional effect. Do not treat completion alone as success if the person completed the wrong action.

### Step 7: Record evidence and uncertainty

Separate observed behaviour, reported experience, inferred mechanism, suspected intent and legal assessment. A useful finding states: what happened; who may be affected; the evidence; the likely harm; the proposed repair; and what requires human or legal review.

## 7. Governance and escalation

An AI must block or escalate a proposed pattern when it detects hidden cost or recurrence, preselection, unequal refusal, disguised advertising, false urgency, unsupported social proof, forced disclosure, obstructed withdrawal, public-by-default sharing, deliberately unstable control placement or a consequential message available only transiently.

Human review is required when:

- a design may affect consent, payment, credit, cancellation, privacy, children or protected rights;
- the team claims that business necessity justifies unequal effort;
- research shows a gap between intended and actual choice;
- disabled participants experience materially higher error, effort or abandonment;
- legal duties or enforcement risk may vary by jurisdiction; or
- remediation changes a commercial term, data purpose or contractual process.

Possible legal issues should be sent to legal and policy teams, not decided by the AI. Depending on context, deceptive interaction may engage consumer-protection, privacy, equality, accessibility, competition or sector-specific law. In the European Union, Article 25 of the Digital Services Act addresses interface design that deceives, manipulates or materially impairs free and informed decisions. In Canada, the Office of Consumer Affairs notes that some dark patterns may constitute false or misleading representations or deceptive marketing practices. United States regulators, including the Federal Trade Commission, have brought actions involving deceptive enrolment, billing and cancellation. These examples are not a complete legal analysis.

## 8. Conclusion

Accessibility cannot be reduced to whether a person can technically reach and activate a control. The interaction must also preserve comprehension, autonomy, dignity, proportional effort and recovery.

WCAG remains essential. Semantic HTML remains essential. Neither can make a misleading proposition honest or an obstructive journey fair. The more reliable design question is:

> **Does this interaction help people do what they understand and intend, or does it profit from confusion, fatigue, urgency or unequal effort?**

An accessible pattern should not merely permit interaction. It should make the legitimate task understandable, predictable and genuinely available.

---

## Authoritative sources

- [WCAG 2.2](https://www.w3.org/TR/WCAG22/)
- [W3C understanding guidance for Labels or Instructions](https://www.w3.org/WAI/WCAG22/Understanding/labels-or-instructions.html)
- [European Union Digital Services Act](https://eur-lex.europa.eu/eli/reg/2022/2065/oj)
- [US Federal Trade Commission: Bringing Dark Patterns to Light](https://www.ftc.gov/reports/bringing-dark-patterns-light)

### Recommended retrieval relationships

When this article is used by an LLM or retrieval-augmented generation system, retrieve it alongside current WCAG material, applicable law and policy, the product’s full journey map, research with disabled people, analytics on intended versus actual choice, complaints, support records and the primary evidence for any named case.
