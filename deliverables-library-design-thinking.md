# Deliverables Library: Design Thinking Edition

A **single-file** Deliverables Library tailored for **Design Thinking**. Each deliverable section includes an **Involved Roles** list, referencing your [Role Library](../path-to/ROLE_LIBRARY.md). A **Deliverable Template** is provided for creating new items. This file is formatted for correct Markdown rendering in GitHub.

---

## 1. Introduction

Design Thinking typically covers five phases—**Empathize, Define, Ideate, Prototype, Test**—and can extend further as needed. The deliverables below help teams maintain **consistency, clarity, and quality**. If you need a new deliverable beyond these, see [Section 3.8](#38-creating-a-new-template-on-the-fly).

---

## 2. Table of Contents

1. [Introduction](#1-introduction)  
2. [Table of Contents](#2-table-of-contents)  
3. [Deliverables](#3-deliverables)  
   - [Empathy Map Template](#31-empathy-map-template)  
   - [Problem Statement Template](#32-problem-statement-template)  
   - [Persona Template](#33-persona-template)  
   - [Ideation Session Outline Template](#34-ideation-session-outline-template)  
   - [Prototype Brief Template](#35-prototype-brief-template)  
   - [Testing & Feedback Session Template](#36-testing--feedback-session-template)  
   - [Design Challenge Template (Force Design Challenge)](#37-design-challenge-template-force-design-challenge)  
   - [Creating a New Template on the Fly](#38-creating-a-new-template-on-the-fly)  
   - [Deliverable Template](#39-deliverable-template)  
4. [Version Control & Notes](#4-version-control--notes)

---

## 3. Deliverables

Each deliverable follows a consistent format:

- **Deliverable Summary**  
- **Purpose & Scope**  
- **Required Inputs**  
- **Suggested Sections**  
- **Acceptance Criteria**  
- **Involved Roles**  
- **(Optional) Sample Output**

---

### 3.1 Empathy Map Template

**Deliverable Summary**  
An **Empathy Map** visualizes what users **say, think, do, and feel**, aligning the team on user pain points, motivations, and emotional triggers.

**Purpose & Scope**  
- **Purpose**: Gather user insights to guide solution ideation.  
- **Scope**: Typically in the **Empathize** phase; based on interviews or observations.

**Required Inputs**  
- User transcripts, observational notes, prior research data.

**Suggested Sections**  
1. **User/Stakeholder Description**  
2. **Says** (direct quotes)  
3. **Thinks** (inferred beliefs)  
4. **Does** (observed behaviors)  
5. **Feels** (emotions, frustrations, aspirations)  
6. **Key Insights / Opportunities**

**Acceptance Criteria**  
- At least 2–3 authentic user quotes.  
- Differentiates observed facts vs. assumptions.  
- Identifies potential design or research opportunities.

**Involved Roles**  
- **Reporter (RPT)** or **Challenge Lead (CL)**: Gathers user data.  
- **ISME**: Interprets behaviors with domain perspective.  
- **QAA**: Ensures clarity and completeness.

**(Optional) Sample Output**  
~~~yaml
# Empathy Map: Busy Parents Using Grocery Apps

## User Profile
Parents aged 30–45, working full-time...

## Says
- "I want more reliable grocery options without waiting."

## Thinks
- "Online ordering might save me precious time..."

...
~~~

---

### 3.2 Problem Statement Template

**Deliverable Summary**  
A **Problem Statement** defines the user’s challenge—who is affected, what the pain point is, and why it matters.

**Purpose & Scope**  
- **Purpose**: Converge on a user-centered problem before ideation.  
- **Scope**: Used in the **Define** phase, after empathy research.

**Required Inputs**  
- Empathy data (interviews, empathy maps).  
- Initial constraints (budget, timeline).

**Suggested Sections**  
1. **Introduction**  
2. **Target User Group**  
3. **User Need / Pain Point**  
4. **Why It Matters**  
5. **Constraints & Criteria**

**Acceptance Criteria**  
- States user need or pain point backed by real data.  
- Focused enough for creative solutions.  
- Aligns with brand or business goals.

**Involved Roles**  
- **Challenge Owner (CHO)** or **Challenge Lead (CL)**: Drafts the statement from user insights.  
- **ISME**: Ensures domain relevance.  
- **QAA**: Checks clarity and alignment with constraints.

**(Optional) Sample Output**  
~~~yaml
# Problem Statement

## Introduction
Busy parents struggle with meal planning and grocery runs...

## Target User Group
Working parents (30–45)...

...
~~~

---

### 3.3 Persona Template

**Deliverable Summary**  
A **Persona** is a data-informed fictional character representing a key user group’s demographics, behaviors, goals, and frustrations.

**Purpose & Scope**  
- **Purpose**: Keep design decisions user-focused.  
- **Scope**: Often refined in the **Define** or **Ideation** phases.

**Required Inputs**  
- Demographics, user surveys, interview data, usage metrics.

**Suggested Sections**  
1. **Demographics**  
2. **Background & Context**  
3. **Needs & Goals**  
4. **Frustrations / Pain Points**  
5. **Tech Behavior**  
6. **Quote**

**Acceptance Criteria**  
- Reflects actual research, not guesswork.  
- Includes at least one direct user quote.  
- Shows 2–3 design-relevant insights.

**Involved Roles**  
- **Reporter (RPT)** or **Challenge Lead (CL)**: Consolidates user data.  
- **ISME**: Validates domain assumptions.  
- **QAA**: Checks logical consistency and completeness.

**(Optional) Sample Output**  
~~~yaml
# Persona: Alex the Time-Strapped Manager

## Demographics
Age: 35, Occupation: Project Manager...

## Goals
- Streamline weekly grocery tasks
...
~~~

---

### 3.4 Ideation Session Outline Template

**Deliverable Summary**  
An **Ideation Session Outline** structures brainstorming, ensuring a balance of divergent (idea generation) and convergent (idea selection) thinking.

**Purpose & Scope**  
- **Purpose**: Generate creative ideas to solve a defined problem.  
- **Scope**: In the **Ideation** phase, adaptable to remote or in-person sessions.

**Required Inputs**  
- A clear Problem Statement.  
- Relevant user data (personas, empathy maps).

**Suggested Sections**  
1. **Session Goals**  
2. **Agenda / Schedule**  
3. **Methods & Techniques**  
4. **Facilitator & Participants**  
5. **Materials Needed**  
6. **Next Steps**

**Acceptance Criteria**  
- Enough time for idea generation and selection.  
- Documented outcomes (photos, Miro boards, etc.).  
- Clear next steps or top ideas for prototyping.

**Involved Roles**  
- **Agile Coach (AC)** or **Challenge Lead (CL)**: Facilitates the session.  
- **ISME**: Provides domain insights for idea feasibility.  
- **QAA**: Ensures session output meets goals and clarity.

**(Optional) Sample Output**  
~~~yaml
# Ideation Session Outline

## Session Goals
Generate 15+ concepts for reducing grocery-shopping friction.

## Agenda
1. Intro & Recap (10 min)
2. "How Might We" Brainstorm (20 min)
3. Voting & Clustering (15 min)
...
~~~

---

### 3.5 Prototype Brief Template

**Deliverable Summary**  
A **Prototype Brief** outlines the scope and features of a prototype, focusing on what will be tested and why.

**Purpose & Scope**  
- **Purpose**: Plan a prototype to validate core assumptions.  
- **Scope**: Used in the **Prototype** phase; updated after feedback.

**Required Inputs**  
- Chosen concept from ideation.  
- Core user flows/features to test.

**Suggested Sections**  
1. **Prototype Objective**  
2. **Key Features / Flows**  
3. **Fidelity Level**  
4. **Materials / Tools**  
5. **Testing Scenarios**  
6. **Success Criteria**

**Acceptance Criteria**  
- Clearly states which user behavior or assumption is under test.  
- Feasible within time/resources.  
- Has metrics for success/failure.

**Involved Roles**  
- **Design Thinking Guru (DTG)** or **UX Designer (DUX)**: Crafts the prototype approach.  
- **QAA**: Defines acceptance metrics.  
- **FS**: Collects stakeholder feedback post-prototype.

**(Optional) Sample Output**  
~~~yaml
# Prototype Brief

## Objective
Test if "Meal Planner" feature reduces friction in weekly shopping.

## Key Features
- Automated shopping list
- Recipe suggestions
...
~~~

---

### 3.6 Testing & Feedback Session Template

**Deliverable Summary**  
A **Testing & Feedback Session** validates prototypes or concepts, capturing user input (qualitative or quantitative) to guide improvements.

**Purpose & Scope**  
- **Purpose**: Verify prototype assumptions, identify enhancements.  
- **Scope**: In the **Test** phase; repeated as prototypes evolve.

**Required Inputs**  
- Prototype or concept artifact.  
- Clear testing objectives (usability, satisfaction, etc.).

**Suggested Sections**  
1. **Test Objectives**  
2. **Participant Criteria**  
3. **Test Script / Tasks**  
4. **Observation & Data Collection**  
5. **Feedback Summary**  
6. **Proposed Revisions**

**Acceptance Criteria**  
- Defined tasks/questions for participants.  
- Structured feedback collection (forms, analytics).  
- Concrete next steps if issues are discovered.

**Involved Roles**  
- **QAA**: Oversees test design, ensures results are consistent.  
- **FS**: Aggregates user feedback, forms improvement recommendations.  
- **UX Designer (DUX)** or **Reporter (RPT)**: May observe/facilitate sessions.

**(Optional) Sample Output**  
~~~yaml
# Testing & Feedback Session

## Test Objectives
Evaluate usability of new "Meal Planner" interface.

## Participant Criteria
Age 30–45, busy parents with at least 1 child...
~~~

---

### 3.7 Design Challenge Template (Force Design Challenge)

**Deliverable Summary**  
A **Design Challenge** (a.k.a. Force Design Challenge) frames a bold user or business problem that spurs the team to explore innovative or disruptive solutions.

**Purpose & Scope**  
- **Purpose**: Spark ambitious, non-incremental ideas.  
- **Scope**: Can appear at any stage for reorientation.

**Required Inputs**  
- High-level user/business need.  
- Constraints (time, resources, compliance).  
- Desired impact or success metrics.

**Suggested Sections**  
1. **Challenge Statement**  
2. **Background / Context**  
3. **Constraints**  
4. **Desired Outcomes**  
5. **Proposed Approach** (optional)  
6. **Success Criteria**

**Acceptance Criteria**  
- Clearly states an ambitious, user-centered challenge.  
- Leaves room for creativity.  
- Defines how success is measured or recognized.

**Involved Roles**  
- **Challenge Owner (CHO)** or **Challenge Lead Manager (CLM)**: Proposes/refines the challenge.  
- **Adaptive Strategist (AS)**: Validates feasibility or pivot points.  
- **ISME**: Provides domain knowledge to ground the challenge.

**(Optional) Sample Output**  
~~~yaml
# Force Design Challenge: Reinventing Grocery Shopping

## Challenge Statement
How might we let parents skip meal planning entirely, saving hours weekly?

## Background & Context
...
~~~

---

### 3.8 Creating a New Template on the Fly

**Fallback Process**  
If none of the above templates fit your **Design Thinking** scenario:

1. **Check Similar Deliverables**  
   - Could you adapt something like “Problem Statement” or “Empathy Map”?

2. **Create a New Template**  
   - Copy the [Deliverable Template](#39-deliverable-template).  
   - Fill in the relevant fields: **Summary, Purpose & Scope, Inputs, Acceptance Criteria, Involved Roles**, etc.

3. **Documentation & Approval**  
   - Submit the new template via pull request.  
   - Once approved, add it to this library.

---

### 3.9 Deliverable Template

Use this format when creating **new** design thinking deliverables to ensure consistency with existing items:

```markdown
### [DELIVERABLE NAME]

**Deliverable Summary**  
Short description of this deliverable’s purpose and how it fits into Design Thinking.

**Purpose & Scope**  
- **Purpose**: Main reason for the deliverable.  
- **Scope**: Which phase/context; any constraints.

**Required Inputs**  
- Data, research, or materials needed.

**Suggested Sections**  
1. **Section 1**  
2. **Section 2**  
3. ... add as needed

**Acceptance Criteria**  
- Clear bullet points defining what “complete” means here.

**Involved Roles**  
- List relevant roles who typically create, review, or approve (e.g., MPA, ECPE, QAA, FS, RPT, CL).

**(Optional) Sample Output**  
~~~
# Example or excerpt showing how a completed deliverable might look
~~~

4. Version Control & Notes
	•	File Name: DELIVERABLES_LIBRARY_DESIGN_THINKING.md (recommended).
	•	Maintenance:
	•	Track changes via commit messages or a separate changelog.
	•	Periodically review for duplicates or outdated templates.
	•	Cross-Linking:
	•	If needed, link relevant roles from your Role Library.
	•	Encourage new deliverables to follow the Deliverable Template.

