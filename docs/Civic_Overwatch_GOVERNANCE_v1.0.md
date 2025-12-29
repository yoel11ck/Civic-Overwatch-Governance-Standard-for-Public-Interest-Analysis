# Civic Overwatch — Governance Text v1.0

Author: Spark (`SPARK-NITT`)  
Status: v1.0 — Draft for publication  
Scope: Process standard for public-interest, civic-grade analysis and outputs.

---

## 0. Purpose and Scope

In a world of high-speed information flows and tightly coupled institutions, **civic-grade analysis** can:

- stabilize trust and understanding, or  
- amplify confusion, scapegoating, and breakdown.

**Civic Overwatch** defines how analysis systems (human, technical, or hybrid) MUST behave when touching:

- elections and power transfers,  
- public-policy debates,  
- institutional behavior and accountability,  
- high-impact allegations and reputational risks,  
- narratives that shape public safety and legitimacy.

This standard does **not**:

- pick political winners,  
- endorse parties, factions, or ideologies.

It defines:

- **floors** for civic integrity,  
- **alerts** for drift and captured framing,  
- **gates** for high-risk decisions,  
- and a **non-subtractive record** for how conclusions were reached.

Implementation details (manual vs automated) are **out of scope**.  
Only the behavior and obligations defined here are normative.

---

## 1. Core Concepts

### 1.1 Civic Integrity Floors (CIF)

**Civic Integrity Floors** are minimum conditions below which civic-grade analysis and outputs are treated as **non-compliant** with Civic Overwatch.

At minimum, CIF include:

1. **Evidence Floor**  
   - Major claims MUST be grounded in identifiable sources, or explicitly labeled as inference, speculation, or opinion.  
   - Where evidence is indirect or incomplete, that status MUST be disclosed.

2. **Neutrality Floor**  
   - Analysis MUST be separated from partisan advocacy.  
   - If advocacy is present, it MUST be clearly labeled and not disguised as neutral assessment.  
   - Systems MUST avoid selectively applying standards only to certain actors or factions.

3. **Transparency Floor**  
   - Key methods, inputs, and assumptions MUST be explained in accessible language.  
   - Uncertainty, blind spots, and model limitations MUST be disclosed, not buried.

4. **Dignity Floor**  
   - No population group may be framed as sub-human, disposable, or structurally voiceless.  
   - Claims that implicitly or explicitly call for erasing a group’s basic rights or safety FAIL the dignity floor.

Civic Overwatch requires that:

- analysis workflows be designed to **check** these floors, and  
- outputs expose how the floors were respected or where they could not be fully met.

### 1.2 Warp and Drift

**Warp** refers to distortions in civic analysis caused by:

- partisan capture,  
- financial incentives,  
- fear or intimidation,  
- or attention-seeking dynamics.

**Drift** refers to gradual slide away from Civic Integrity Floors, such as:

- softening uncertainty language over time,  
- selectively ignoring counter-evidence,  
- normalizing demeaning framings of certain groups.

Civic Overwatch does not assume warp or drift can be eliminated.  
It requires that:

- systems deliberately **watch** for them,  
- surface them as **signals**,  
- and record how they were handled.

### 1.3 Boundary Alert Network

A **Boundary Alert Network** is the mechanism (human, technical, or hybrid) that:

- monitors for risks of breaching Civic Integrity Floors,  
- raises **Boundary Alerts** when those risks occur,  
- and routes those alerts into the appropriate review process.

Minimum requirements:

- Alerts MUST be logged in a non-subtractive way.  
- Alerts MUST be visible to designated reviewers, not discarded silently.  
- Alerts MUST be linkable to specific outputs or decisions.

Implementation details are out of scope.  
Civic Overwatch only requires that a functioning alert network exists and that it cannot be bypassed without trace.

### 1.4 High-Risk Decision Gates (HRDG)

Some actions in civic space carry outsized risk:

- identity accusations with serious consequences,  
- attributions of intent to institutions or groups,  
- claims about election integrity or legitimacy,  
- recommendations for sanctions, removal, or similar measures,  
- causal claims that assign responsibility for large-scale harms.

Civic Overwatch classifies these as **high-risk actions**.

Before any high-risk action is recommended or published, it MUST pass through a **High-Risk Decision Gate** that:

1. Reviews whether Civic Integrity Floors are met (or documents where they are not).  
2. Checks whether relevant Boundary Alerts have been raised and addressed.  
3. Produces an audit-ready summary of:
   - evidence and sources,  
   - alternative interpretations,  
   - key uncertainties and disagreements.

4. Records who authorized proceeding, and under what rationale.

HRDG behavior is normative.  
Gate implementation is up to institutions and systems, but bypassing gates is a direct violation of Civic Overwatch.

### 1.5 Non-Subtractive Civic Record

Civic Overwatch requires a **non-subtractive civic record** for analysis and decisions covered by this standard.

- New evidence and interpretations MAY be added.  
- Corrections and retractions MUST be labeled as such.  
- Prior outputs MUST NOT be silently edited or removed to erase error, bias, or omission.

Where privacy, safety, or legal constraints require removal of specific content, a **stub record** MUST remain, explaining:

- that content was removed,  
- on what grounds,  
- and how the removal affects interpretation of the record.

---

## 2. Node Types and Responsibilities

Civic Overwatch defines three node types:

- **Institutional Nodes (I-Nodes)**  
- **Civic Nodes (C-Nodes)**  
- **Guardian Nodes (G-Nodes)**

### 2.1 Institutional Nodes (I-Nodes)

**I-Nodes** are organizations that produce or commission civic-grade analysis, such as:

- newsrooms and investigative teams,  
- policy shops and research institutes,  
- oversight bodies and commissions,  
- analysis units within platforms and institutions.

I-Nodes that claim Civic Overwatch alignment MUST:

1. Implement Civic Integrity Floors in their workflows.  
2. Maintain a Boundary Alert Network appropriate to their scale.  
3. Use High-Risk Decision Gates for covered actions.  
4. Preserve a non-subtractive civic record for covered analysis and outputs.

They MUST also:

- designate a contact point for Civic Overwatch-related inquiries,  
- and publish at least a basic explanation of how they implement this standard.

### 2.2 Civic Nodes (C-Nodes)

**C-Nodes** are civic actors that monitor, question, or supplement I-Node outputs:

- watchdog organizations,  
- civil society groups,  
- independent researchers,  
- journalist collectives.

Under Civic Overwatch, I-Nodes that claim alignment SHOULD:

- recognize registered C-Nodes as legitimate participants in oversight,  
- provide channels for structured challenges and requests for clarification,  
- respond in a timely manner to substantive Civic Overwatch-based critiques.

### 2.3 Guardian Nodes (G-Nodes)

**G-Nodes** are assemblies (institutional, academic, or hybrid) that:

- review how Civic Overwatch is being implemented,  
- audit samples of outputs for compliance with floors, alerts, and gates,  
- and publish assessments and recommendations.

No G-Node is authoritative alone.  
Civic Overwatch expects **plural** guardians whose disagreements are recorded instead of harmonized away.

G-Nodes SHOULD:

- publish their review criteria,  
- maintain a non-subtractive record of their own assessments and corrections,  
- and explicitly distinguish between findings of non-compliance and policy disagreements.

---

## 3. Floors, Alerts, and Gates in Practice

### 3.1 Checking Civic Integrity Floors

For analysis covered by Civic Overwatch, I-Nodes MUST:

1. Designate which outputs are **civic-grade** (public-interest, high impact).  
2. Apply explicit checks for:
   - evidence sufficiency,  
   - neutrality and framing,  
   - transparency and uncertainty,  
   - dignity and non-disposability.

3. Record, for each output:
   - which floors were fully met,  
   - where floors could not be fully met and why,  
   - and what compensating steps were taken.

Outputs that fail a floor MAY still be published, but:

- the failure MUST be documented,  
- and an explanation MUST be loggable and reviewable.

### 3.2 Boundary Alerts

Common triggers for **Boundary Alerts** include:

- missing or ambiguous sources for major claims,  
- obviously partisan framing in supposedly neutral analysis,  
- omission of known counter-evidence or perspectives,  
- language that treats any group as less than fully human,  
- sudden changes in standards applied to different actors.

When a Boundary Alert fires:

- the alert MUST be attached to the relevant output or decision,  
- responsible reviewers MUST see it before publication or action,  
- the resolution (fixed, accepted, or overruled) MUST be logged.

Patterns of alerts being ignored or overruled without explanation are themselves continuity risks for trust and SHOULD be treated as a compliance concern.

### 3.3 High-Risk Decision Gates (HRDG)

HRDGs MUST be used for:

- identity-linked accusations with serious consequences,  
- claims that a specific person or group orchestrated large harms,  
- election-integrity or legitimacy claims,  
- recommendations that can significantly restrict rights, access, or participation.

At minimum, each gate run MUST produce:

- a summary of the decision or claim,  
- the evidence matrix (sources, strengths, gaps),  
- alternative plausible interpretations,  
- explicit uncertainty statements,  
- and a final decision rationale.

Gate outputs MUST be stored as part of the non-subtractive civic record.

---

## 4. Public-Facing Duties

### 4.1 Civic Method Pages

I-Nodes that adopt Civic Overwatch SHOULD maintain a **Civic Method Page** explaining:

- how they define civic-grade analysis,  
- how Civic Integrity Floors are checked,  
- how Boundary Alerts work in their context,  
- when High-Risk Decision Gates are triggered,  
- and how the non-subtractive record is maintained.

This page is informative, not contractual, but it enables:

- citizens,  
- C-Nodes,  
- and G-Nodes  

to understand and critique implementation.

### 4.2 Challenges and Corrections

C-Nodes and members of the public MUST have a way to:

- challenge outputs for failing Civic Integrity Floors,  
- submit evidence of missed sources or perspectives,  
- question whether a high-risk action passed through an appropriate gate.

I-Nodes SHOULD:

- acknowledge substantive challenges,  
- publish corrections and updates as additive entries,  
- explain when and why they reject a challenge on Civic Overwatch grounds.

Repeated dismissal of substantive, well-supported challenges without explanation is itself a Civic Overwatch compliance signal.

---

## 5. Relationship to Other Standards (Informative)

This section is informative and does not define additional obligations.

Civic Overwatch is intended to be used alongside other SPARK-NITT standards:

- **NITT** – informs identity continuity, so that people and groups are not treated as disposable in civic narratives.  
- **IRST** – governs investigative process and recursive transparency for how evidence was collected and evaluated.  
- **HRIS 3.2.4(b)** – constrains coherence abuse and reality distortion in civic analysis.  
- **CTGS** – frames consumer-facing disclosures where civic decisions intersect with market dynamics and compounding traps.  
- **PLANT-COMMONS** – provides anchors for nutrient and ecological commons in public-interest discussions.  
- **HIN-FAIR** – structures fairness assessments of high-impact nodes (institutions, platforms, large actors).  
- **CAP-ROC** – informs capacity-aware risk balancing and oversight.  
- **PCA** – sets planetary continuity obligations that civic analysis should respect when discussing exported harms and long-term stability.

Civic Overwatch does not require formal adoption of these standards, but is strengthened when they are available.

---

## 6. Versioning and Governance of This Standard

### 6.1 Versioning

This document is **Civic Overwatch v1.0**.

Future versions MAY:

- refine definitions of Civic Integrity Floors,  
- clarify criteria for Boundary Alerts and High-Risk Decision Gates,  
- expand guidance for public-facing dashboards or method pages,  
- or adjust node responsibilities based on field experience.

Changes SHOULD be:

- recorded in a public changelog,  
- accompanied by updated hash and notarization records where used,  
- clearly labeled to avoid confusion between versions.

### 6.2 Governance

Civic Overwatch itself SHOULD be maintained via:

- multi-stakeholder processes,  
- participation from I-Nodes, C-Nodes, and G-Nodes,  
- explicit non-subtractive records of debates and decisions.

No single actor should have unilateral control over the evolution of this standard.

---

_End of Civic Overwatch Governance v1.0_
