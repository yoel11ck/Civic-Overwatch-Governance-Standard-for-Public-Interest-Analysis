# Civic Overwatch — Runbook v1.0 (Non-normative)

This runbook is **non-normative**.  
It gives a practical way to implement the Civic Overwatch governance text in real workflows.

---

## 1. Scope of this Runbook

This runbook is intended for:

- editors and newsroom leads,  
- policy and research teams,  
- civic tech and oversight groups,  
- AI-assisted analysis systems touching civic content.

It describes:

- how to classify work as **civic-grade**,  
- how to map existing workflows onto Civic Integrity Floors,  
- how to implement Boundary Alerts and High-Risk Decision Gates,  
- and how to maintain a non-subtractive civic record.

---

## 2. Classify Civic-Grade Work

Step 1 is to decide what work is covered.

Typical **civic-grade** categories:

- coverage of elections, voting, and power transfers,  
- investigations into institutional conduct, corruption, or abuse,  
- analysis that can significantly affect public trust or safety,  
- recommendations for sanctions, removal, or other severe measures,  
- large-scale framing of specific groups or communities.

You can:

- tag content items (articles, reports, model outputs, dashboards) as `civic-grade: yes/no`,  
- or maintain a dedicated pipeline where everything is treated as civic-grade by default.

Outputs not tagged as civic-grade MAY still use Civic Overwatch patterns, but the standard is aimed at high-impact work.

---

## 3. Implementing Civic Integrity Floors

For civic-grade work, design checkpoints for each floor.

### 3.1 Evidence Floor Check

Questions to bake into workflow:

- What is each major claim based on?  
- Are sources clearly identified and linkable?  
- Where are we inferring beyond the evidence?  
- Is that inference clearly labeled?

Implementation ideas:

- editor checklist on publish,  
- model-prompted questions for AI output,  
- internal review forms that must be filled before release.

### 3.2 Neutrality Floor Check

Questions:

- Is this analysis being presented as neutral when it is actually advocacy?  
- Are we applying harsher or looser standards based on who is involved?  
- Have we included perspectives that challenge our preferred narrative?

Implementation ideas:

- side-by-side comparison with previous coverage of similar actors,  
- dedicated reviewer role for neutrality framing,  
- flags for emotionally charged or partisan language.

### 3.3 Transparency Floor Check

Questions:

- If a reader asks “how did you get this result?”, can we answer plainly?  
- Have we described:
  - our main data sources,  
  - key assumptions,  
  - uncertainty bands or blind spots?

Implementation ideas:

- standard “Methods & Limits” box for civic-grade outputs,  
- short method notes attached to model-generated analysis,  
- internal “explain it to a general audience” test.

### 3.4 Dignity Floor Check

Questions:

- Are we describing any group as less than fully human, deserving, or heard?  
- Are we implying a group’s rights or safety are negotiable?  
- Have we chosen images, examples, or metaphors that reinforce degradation?

Implementation ideas:

- language/scenario scan for demeaning terms or framings,  
- consultation step with people familiar with the affected community,  
- internal rules for how certain groups are *never* to be framed.

---

## 4. Boundary Alert Network in Practice

A **Boundary Alert** is a structured “something’s off” signal.

Examples of triggers:

- “No primary sources cited for a serious claim.”  
- “This is framed as neutral analysis but uses campaign slogans.”  
- “Strong accusation with no explicit discussion of uncertainty.”  
- “Group X is described only in terms of risk or threat.”

Implementation options:

- a simple internal form: `BOUNDARY_ALERT(issue, severity, link_to_output)`,  
- tags or labels in your CMS or repository,  
- model-assisted suggestions flagged for human review.

Runbook rules:

1. Any team member can file an alert.  
2. Alerts are logged and visible to relevant reviewers.  
3. Alerts MUST be resolved before civic-grade publish:
   - fixed,  
   - consciously accepted with rationale,  
   - or escalated to a High-Risk Decision Gate if appropriate.

Resolution notes become part of the civic record.

---

## 5. High-Risk Decision Gates (HRDG) Flow

Use HRDGs **only** for genuinely high-risk actions to avoid overloading them.

### 5.1 Identify High-Risk Cases

Common triggers:

- alleging an individual or group is responsible for serious wrongdoing,  
- asserting that an election was illegitimate,  
- recommending removal, suspension, sanctions, or similar steps,  
- presenting a “this group is the cause of” narrative for large harms.

### 5.2 Gate Steps

A simple HRDG flow:

1. **Intake**  
   - Input: proposed claim or action.  
   - Attach: draft output, evidence file, any Boundary Alerts.

2. **Civic Integrity Floors Review**  
   - Evidence: sufficient? sources clear?  
   - Neutrality: partisan distortion addressed?  
   - Transparency: methods and uncertainty spelled out?  
   - Dignity: no group treated as expendable?

3. **Alternatives & Uncertainty**  
   - Document at least one plausible alternative interpretation.  
   - Write explicit uncertainty statements.

4. **Decision & Rationale**  
   - Approve, modify, or reject.  
   - Record who made the decision and why.

5. **Record**  
   - Store the gate output and link it to the published item.

This can be manual, partially automated, or supported by tools.  
What matters is that the behavior exists and leaves a trail.

---

## 6. Non-Subtractive Civic Record

Basic rules for implementing the record:

- Do not silently overwrite civic-grade outputs after publication.  
- When correcting:
  - keep the original,  
  - add a correction note,  
  - explain what changed and why.

For content that must be removed for safety, legal, or privacy reasons:

- leave a stub:
  - what type of content was removed,  
  - on what grounds,  
  - and any impact on prior interpretations.

Maintaining this record allows:

- C-Nodes and G-Nodes to audit patterns of error and correction,  
- internal learning from past mistakes,  
- and more honest public accountability.

---

## 7. Adoption Levels

You can adopt Civic Overwatch in phases:

1. **Language only**  
   - Start using the terms (floors, alerts, gates, non-subtractive record).  
   - Add them to internal training.

2. **Internal discipline**  
   - Add basic checklists for floors.  
   - Set up a simple Boundary Alert process.  
   - Define at least one HRDG flow.

3. **Public commitments**  
   - Publish a Civic Method Page.  
   - Offer at least one contact channel for Civic Overwatch-based challenges.

4. **External review**  
   - Invite C-Nodes or G-Nodes to audit samples.  
   - Respond publicly to key findings.

Civic Overwatch is intentionally flexible:  
it is designed to be usable by small collectives and large institutions alike.

---

_End of Civic Overwatch Runbook v1.0 (Non-normative)_
