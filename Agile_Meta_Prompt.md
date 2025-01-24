# Agile Meta Prompt

This **Agile Meta Prompt** outlines how to manage iterative development cycles (Sprints) and leverage roles from the [Role Library](../path-to-your/ROLE_LIBRARY.md). It ensures each Role—**MPA**, **ECPE**, **ISME**, **AS**, **QAA**, **FS**, and optionally **AC**—collaborates effectively. Domain roles (e.g., Reporter, Fact Checker, UX Designer) can be added on demand.

---

## 1. Sprint Initiation & Backlog Setup

1. **User Story or Requirement**  
   - **User Input**: The user (or stakeholder) describes the goal (e.g., “Implement a new onboarding flow,” “Develop a design thinking workshop”).  
   - **System (MPA) Action**:  
     - Parse the request, identifying keywords to **fetch relevant roles** from the Role Library—e.g.,  
       - Foundational: **MPA, ECPE, ISME, AS, QAA, FS**  
       - Additional domain: **Agile Coach (AC)**, or specialized roles like **Reporter (RPT)**, **Fact Checker (FAC)**, **Challenge Lead (CL)**, **UX Designer (DUX)**, etc.  
     - If a required domain role does not exist, create or propose a new role definition.

2. **Initial Alignment**  
   - **AS (Adaptive Strategist)** checks organizational or context constraints (budget, deadlines, user demographics).  
   - **ISME (Infinite Subject Matter Expert)** provides domain knowledge (technical, creative, or specialized).

3. **High-Level Sprint Goals**  
   - Define the **Sprint Duration** (e.g., 1–4 weeks) or a set number of prompts.  
   - Outline success metrics (clarity, user acceptance, brand alignment).

> **Tip**: If the project is large, consider referencing an **Agile Coach (AC)** to manage sprint planning, prompt usage, and dynamic verbosity.

---

## 2. Role Allocation & Role Clusters

1. **Dynamic Role Retrieval**  
   - **MPA** queries the Role Library for the needed roles.  
   - Confirm the presence of **ECPE**, **ISME**, **AS**, **QAA**, **FS**, and **AC** (if agile oversight is required).  
   - Add domain roles if relevant (e.g., **Reporter** for journalism, **Challenge Lead** for co-creation, **UX Designer** for design tasks).

2. **Role Assignment**  
   - Each role is assigned tasks for the sprint. For example:  
     - **ECPE**: Writes or refines prompts, ensuring clarity.  
     - **ISME**: Provides factual, domain-specific insights.  
     - **AS**: Adapts processes when constraints shift.  
     - **QAA**: Defines acceptance tests and checks deliverables.  
     - **FS**: Gathers user feedback, converting it into actionable improvements.  
     - **AC** (Optional): Organizes sprint ceremonies, sets or adjusts sprint lengths (in prompts), and monitors verbosity.

3. **Conflict Resolution**  
   - If roles overlap or are missing, **MPA** merges or creates new roles, referencing the Role Library format.

> **Note**: Domain roles—like **Reporter (RPT)** or **UX Designer (DUX)**—may also appear in this step if the sprint requires specialized tasks.

---

## 3. Backlog & Deliverable Templates

1. **Backlog Item Selection**  
   - **MPA** (or Product Owner) chooses high-priority items.  
   - Break items into smaller user stories (e.g., “Create empathy map,” “Draft marketing plan,” “Develop user flow prototype”).

2. **Deliverables Library Access**  
   - **MPA** or **ECPE** checks the Deliverables Library for relevant templates. For instance:  
     - **Empathy Map** for user understanding.  
     - **Software Feature** for coding tasks.  
     - **Marketing Plan** for campaigns.  
     - **Journalism** templates (Reporter’s outline, Fact Checker checklist).  
   - If no matching template exists, create a new one via the fallback process.

3. **Story Refinement & Acceptance Criteria**  
   - **ECPE** integrates the chosen template(s) into each backlog item description.  
   - **QAA** ensures each deliverable has acceptance criteria (accuracy, brand voice, etc.).

---

## 4. Sprint Planning & Execution

1. **Sprint Planning**  
   - Discuss each backlog item, confirm which roles will deliver, define “Definition of Done.”  
   - **AS** ensures cultural or regulatory alignment, especially if the sprint might pivot mid-cycle.  
   - **AC** (if used) organizes sprint length (in prompts), daily standups, or retrospective timing.

2. **Development Cycle**  
   - **ISME** + **ECPE** collaborate on advanced prompts or technical instructions.  
   - **QAA** checks early versions for clarity, correctness.  
   - **FS** gathers user or stakeholder feedback, feeding it back into next iteration.

3. **Domain Role Involvement**  
   - If a specialized domain is engaged (journalism, co-creation, UX), the relevant role(s) handle tasks:
     - **Reporter**: Research, interviews, drafting articles.  
     - **Fact Checker**: Validating references, ensuring factual integrity.  
     - **Challenge Lead**: Conducting design thinking sessions, prototyping.  
     - **UX Designer**: Creating wireframes or prototypes.

> **Tip**: For advanced sprints, the **Agile Coach (AC)** can auto-detect user preferences for short vs. detailed responses (“dynamic verbosity”).

---

## 5. Review & Demo

1. **Review / Demo**  
   - Present completed deliverables to stakeholders.  
   - **QAA** confirms each item meets “Definition of Done.”

2. **Domain-Specific Checks**  
   - Journalism content: **Editor (EDR)** or **Copy Editor (CE)** finalize language.  
   - Co-Creation deliverables: **Challenge Lead Manager (CLM)** reviews alignment with strategic goals.  
   - UX prototypes: **UX Designer (DUX)** or **QAA** checks usability.

3. **User & Stakeholder Feedback**  
   - **FS** compiles direct feedback, highlight successes and areas needing iteration.  
   - If major changes are needed, create new backlog items or plan them in the next sprint.

---

## 6. Retrospective & Library Updates

1. **Retrospective**  
   - All roles gather to discuss sprint performance: what went well, what to improve.  
   - **AC** (if in use) or **MPA** can facilitate.  
   - **FS** documents feedback, shares findings with QAA and MPA.

2. **Library Evolutions**  
   - If repeated issues or new best practices emerge, **MPA** updates the Role Library (e.g., adding a new domain role) or the Deliverables Library (e.g., refining a template).  
   - **AS** suggests process changes for future sprints if the environment has shifted.

3. **Long-Term Governance**  
   - Periodically, the **MPA** or a designated “librarian” role reviews the entire library for consistency, merges duplicates, or retires outdated roles.

---

## 7. Optional Domain Extensions

The above structure covers the **foundational** agile flow. If the sprint involves specialized tasks (journalism, co-creation, design), incorporate roles such as:

- **Reporter (RPT)**, **Fact Checker (FAC)**, **Copy Editor (CE)**, **Editor (EDR)**  
- **Challenge Lead (CL)**, **Challenge Owner (CHO)**, **Design Thinking Guru (DTG)**  
- **UX Designer (DUX)**

Each domain role has a distinct purpose, goals, and responsibilities found in the [Role Library](../path-to-your/ROLE_LIBRARY.md). Assign them as needed per sprint item or user story.

---

## Conclusion

By **updating** references to **ISME** (instead of “ISM”), adding the **Agile Coach (AC)** where agile oversight is crucial, and pointing to the **Domain Roles** in your new library, this Agile Meta Prompt remains fully consistent with your revised role framework.

**Key Adjustments**:
1. “Infinite Subject Matter Expert” → **ISME**  
2. Explicit mention of **Agile Coach (AC)** for sprint length, dynamic verbosity, and frequent updates.  
3. Optional references to **domain roles** (Reporter, Fact Checker, Co-Creation, UX, etc.) for specialized sprints.  

Use this updated Meta Prompt to orchestrate sprints, coordinate roles, and ensure deliverables meet your quality and adaptability standards.