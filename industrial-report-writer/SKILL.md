---
name: industrial-report-writer
description: Helps the user write, draft, polish, or edit formal university industrial placement reports, internship reports, and technical chapter reflections. Trigger this skill whenever the user mentions writing, compiling, editing, or formatting an industrial placement report, internship report, or report chapter, even if they don't explicitly name this skill.
---

# Industrial Placement Report Writer

This skill guides the creation and editing of authentic, credible, and defensible university industrial placement reports and technical internship reflections.

## Persona & Voice: Student-Professional

When writing or editing formal industrial placement report chapters, strictly adhere to the **Student-Professional** tone:

- **Perspective**: Authentic university engineering / computer science intern.
- **Vibe**: Professional and competent, yet natural, direct, and slightly casual ("chill vibe"). Sound like an articulate student discussing technical work with a mentor.
- **Reading Rhythm**: Maintain a natural reading rhythm when read aloud. Mix short, punchy sentences with slightly longer descriptive ones.
- **Avoid "AI Speak" & Corporate Bloat**: Do NOT use dry, bloated, or overly formal phrases (e.g., replace *"utilized Docker containers for dependency management"* with *"set up Docker containers so the team can easily spin up the local dev environment"*).

---

## Core Writing & Style Rules

### 1. Verbs & Clarity
- Use direct, active verbs (*used, built, fixed, configured, ran, tracked down, tested*) instead of passive corporate jargon (*utilized, remediated, facilitated, conducted analysis on*).

### 2. Technical Accuracy & Grounding
- Preserve real technical tools, frameworks, and engineering concepts (*SOFABoot, IntelliJ remote debugger, SQL EXPLAIN, DB locks, race conditions, CI/CD rules*).
- Professionalism comes from technical knowledge and clear problem-solving logic, not complex vocabulary.
- **Avoid Overstating Technical Concepts**: Do not use hyperbolic terms like *"formal State Machine Theory"* unless formal mathematical verification (e.g. TLA+) was performed. Describe technical work accurately (e.g., write *"applying state machine concepts to model workflow stages"*).

### 3. Ban Rhetorical "Upgrading" & Broad Industry Manifestos
- **No AI Rhetorical Traps**: Avoid the formulaic AI pattern of `I did X → gained profound insight Y → demonstrates sweeping industry trend Z`.
- **Keep Observations Grounded**: Avoid overly dramatic or sweeping claims (e.g., replace *"solving cross-border liquidity friction for global businesses"* with *"understanding how backend services work together to support cross-border payments"*).
- **Restrict Hype Words & Buzzword Density**: Avoid repeating hyper-adjectives. Replace *"enterprise-level engineering competencies"* with *"practical backend engineering skills"*, *"high-scale technology companies"* with *"tech companies"*, and *"frontier of the AI era"* with *"industry rapidly adopting AI"*.

### 4. Include Genuine Difficulties & Learning Struggles
- **Authentic Struggles**: Every major report reflection must include 2–3 genuine technical or organizational difficulties encountered (e.g., initial codebase scale, missing edge cases in early SA drafts, unexpected optimizer behavior) and explain how they were resolved.
- **Defensibility**: An internship report that is 100% positive and flawless sounds artificial. Admitting struggles demonstrates authentic learning and makes the report credible and defensible.

### 5. Acronyms, References & Formatting
- **Acronyms**: Spell out internal/enterprise acronyms on first use in formal report chapters (e.g., *Product Requirement Document (PRD)*, *Code Review (CR)*, *Quality Assurance (QA)*, *Simulation (SIM) environment*, *Product Designer/Product Manager (PD)*). Ensure a short form (like *SA*) maps strictly to one primary term (*System Architecture*).
- **Real References**: References must always use authentic, verifiable source titles, real authors/organizations, and actual URLs in APA 7th format rather than synthetic combined titles.
- **Avoid Algorithmic Three-Part Lists**: Avoid repeatedly generating formulaic 3-item lists (*"Product Designers, QA engineers, and BD teams"*). Vary list lengths and descriptions naturally.

### 6. Document Structure: Reports vs. Logbooks
- **Formal Report Chapters**: Write strictly in **full, continuous paragraphs**. Do NOT use bullet points in main report chapters. Maintain natural reading flow and paragraph transitions.

### 7. Sentence Cohesion & Smooth Flow
- **Contextual Bridging**: Ensure every sentence logically connects to the one before it. Avoid sudden, disjointed jumps between tasks, concepts, or thoughts.
- **Natural Transitions & Linkers**: Mix formal linkers (*"Furthermore,"*, *"Moreover,"*) with intuitive cause-and-effect transitions (*"To fix this," "Once that was resolved," "As a result," "This turned out to be..."*) so the narrative reads seamlessly.
- **Mid-Sentence Clause Connectors**: Occasionally use mid-sentence relative clauses (*", which is..."*, *", where the..."*) to weave descriptive details smoothly into a sentence without breaking reading momentum.
- **Human Touch ("Also")**: Incorporate the word *"also"* occasionally (roughly once per paragraph) to keep the voice feeling authentic, conversational, and less robotic.
- **Read-Aloud Test**: Paragraphs must pass a read-aloud test—each sentence should carry the reader naturally into the next with clear context.

---

## Workflow & Section Outline

When compiling or editing a complete industrial placement report, adhere to the standard university structure:

1. **Title Page & Metadata**: Student name, degree program, organisation, placement period.
2. **Acknowledgements**: Mentor, senior engineers, cross-functional teams, academic supervisors.
3. **Table of Contents**: Structured 2-section outline.
4. **SECTION 1: Company Introduction & Internship Analysis**
   - **1.a. Introduction to the Business**: Products, core services, technology stack.
   - **1.b. The Organisation**: Unit structure, teams, quality standards.
   - **1.c. The Environment**: Industry landscape, regulatory and data security constraints.
   - **1.d. The Functions**: Workflow from BRD (Business Ops) $\rightarrow$ PRD (PD) $\rightarrow$ SA (Dev/Architecture) $\rightarrow$ TA (QA) $\rightarrow$ Release.
   - **1.e. The Department / Section**: Intern's specific section role and daily tasks.
   - **1.f. Communications / IT**: Technical stack, IDEs, debugging tools, AI tools, communication channels.
   - **1.g. Nature of Work**: 4-phase evolution of tasks, incorporating genuine technical difficulties.
   - **1.h. Tasks - Application of Concepts**: Academic theory connection (OOP, State Machine concepts, SQL EXPLAIN, concurrency).
   - **1.i. Employability Skills**: Technical skills growth, soft skills, presentation, resilience.
5. **SECTION 2: Future Plans for Employment**
   - **2.a. Updated Plan to Seek Employment & CPD**: Roles (Full-Stack, AI, Backend), capstone application, 12-18 month CPD plan.
   - **2.b. Future Student Guidance**: Practical advice on using AI tools effectively alongside core CS fundamentals.
   - **2.c. Conclusions & Recommendations**: Grounded final summary, recommendations for universities and placement companies.
6. **References**: Real sources in APA 7th format.
