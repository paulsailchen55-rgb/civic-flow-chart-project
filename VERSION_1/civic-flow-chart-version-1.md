# Civic Flow Chart — Version 1 Working Specification

**Status:** Public working specification  
**Scope:** Framework definition and testable design principles  
**Initial test environment:** Santa Cruz County, California  

## 1. Purpose

The Civic Flow Chart is an explanatory and navigation framework for complicated civic processes.

Its purpose is to make existing public systems easier to understand without replacing the institutions that have authority over those systems.

The framework should help a person see:

- where they are;
- what they are trying to accomplish;
- what happens at the current node;
- why a requirement exists, when that is knowable;
- who has authority;
- who is responsible for the next action;
- what information or action is required;
- how long the step may take;
- what it costs;
- what happens if the person cannot complete it;
- what happens next;
- whether there is a way to pause, go back, appeal, correct, or exit; and
- where the information can be verified.

## 2. Core routing

**WHERE ARE YOU?**  
↓  
**WHAT ARE YOU TRYING TO DO?**  
↓  
**WHO HAS AUTHORITY?**  
↓  
**WHO IS RESPONSIBLE FOR THE NEXT ACTION?**

This is the basic routing logic.

## 3. Child Test

A person should be able to answer:

1. What is happening?
2. What am I trying to do?
3. Where am I in the process?
4. Who decides?
5. Who is responsible for the next step?
6. What do I need to do?
7. Why is this required?
8. What does it cost?
9. How long should it take?
10. What if I cannot do it?
11. What happens next?
12. Can I go back, pause, appeal, or exit?
13. Where can I verify this?

The Child Test tests the explanation, not the complexity of the underlying system.

## 4. Node schema

A node can contain:

**SPACE · TIME/CLOCK · PRIORITY · AUDIENCE · AUTHORITY · RESPONSIBILITY · INPUT · ACTION · STATUS · MONEY · NEXT · BACKTRACK · EXIT**

A minimal node should identify the current state and the next meaningful action. Additional fields are added when they improve navigation or accountability.

Unknown information should be explicitly labeled **UNKNOWN / NOT YET MAPPED**.

## 5. Clock model

One process may contain several different clocks.

### Legal clock

A period established by law, regulation, court order, or another authoritative rule.

### Administrative target

An agency or organization target, service standard, or expected processing period.

### Observed duration

Measured or reported time from actual cases.

### Resident elapsed time

The time experienced by the person moving through the process, including waiting, travel, preparation, repeated contacts, and delays.

### Financial clock

A deadline or time pressure created by billing, financing, penalties, rent, taxes, fees, or other economic conditions.

A mapped clock should identify its source, start point, type, expected duration or deadline, and known consequences of delay.

## 6. Friction model

The first question about friction is:

> **What is this friction doing?**

Only then:

> **What do I need to do?**

Possible legitimate functions include safety, environmental protection, participation, rights protection, accessibility, verification, and accountability.

Possible burdens include duplicate information, unclear instructions, unnecessary handoffs, waiting, cost, distance, technology requirements, uncertainty, and repeated work.

The framework does not assume that friction is either good or bad. It makes the function and burden inspectable.

## 7. Backtrack and reversibility

The map must distinguish:

- navigation backtracking;
- administrative correction;
- appeal or review;
- legal reversibility;
- physical reversibility; and
- irreversible consequences.

A map can always provide a navigation path backward even when the underlying process cannot legally or physically be reversed.

## 8. Current process vs. proposed alternative

These must remain separate.

### CURRENT PROCESS

What authoritative sources say happens now.

### PROPOSED ALTERNATIVE

A possible redesign, policy proposal, experiment, or community idea.

A proposal must not be displayed as if it were an existing rule.

## 9. Evidence model

The framework distinguishes:

**FACT → MODEL → ESTIMATE → OPINION**

A source record should identify:

- source type;
- source owner;
- authority type;
- date;
- purpose;
- scope;
- current status;
- evidence or basis;
- review status.

Examples of distinctions:

- A statute can establish legal authority.
- A court decision can establish or interpret legal authority.
- A scientific paper can provide evidence without itself being government authority.
- A historical source can document the past without being current authority.
- A government webpage can explain a process without necessarily being the underlying legal source.

## 10. Three views

The same underlying process can be viewed as:

### Resident Map

**What am I trying to do?**

### Government Map

**Who is responsible?**

### Flow Map

**How does it move?**

The views should remain connected to the same underlying nodes and relationships.

## 11. Twelve master doors

The initial interface can use twelve broad doors:

1. Home, Land & Building
2. Money, Taxes & Economic Security
3. Health & Human Services
4. Roads, Transportation & Public Space
5. Water, Waste & Environment
6. Safety & Emergencies
7. Animals & Agriculture
8. Records, Information & Identity
9. Civic Participation
10. Justice, Rights & Accountability
11. Work, Business & Procurement
12. Government IT & Digital Access

These are navigation categories, not a claim that government has only twelve components.

## 12. Emergency mode

Emergency mode is a different presentation of the same underlying map.

First questions:

**WHAT IS HAPPENING? → WHERE? → IS ANYONE IN IMMEDIATE DANGER? → WHAT NEEDS TO HAPPEN NOW?**

Possible operational sequence:

**LIFE/SAFETY → IMMEDIATE HAZARD → CRITICAL INFRASTRUCTURE → ESSENTIAL SERVICES → RECOVERY → NORMAL CIVIC BUSINESS**

This is an operational sequencing model, not a moral ranking.

## 13. Ledger / Lab / Archive

### Ledger

A lightweight record of:

- friction;
- observed clocks;
- evidence;
- failed handoffs;
- stakeholder costs;
- verification questions;
- proposed changes.

The correction mechanism should remain simple. A useful basic signal is:

**THIS LOOKS WRONG.**

### Lab

A testing space for alternatives and simulations. Assumptions can be changed and results compared without pretending that the alternative is current government practice.

### Archive

A record of prior maps, source versions, plans, decisions, assumptions, and superseded pathways.

The shorthand is:

**LIVING MAP → LEDGER → ARCHIVE → FUTURE**

## 14. Civic memory / continuity / renewal

### Civic Memory

Preserve what existed, what was attempted, what happened, and what was learned.

### Civic Continuity

Carry useful knowledge, relationships, resources, and accomplishments through periods of change.

### Civic Renewal

Review inherited systems and determine what should continue, change, be replaced, be retired, or be remembered.

Lifecycle:

**ALPHA → LIFE → OMEGA → REVIEW → RENEWAL → ALPHA′**

Secular public-language equivalent: **Lifecycle Review / Renewal Cycle**.

Core principle:

> The purpose survives the version. The version does not become the purpose.

The framework must be capable of its own review, replacement, and retirement.

## 15. Completion and contribution

The project distinguishes:

- Official Record;
- Process Record;
- Experience Record;
- Outcome Record;
- Archive.

Key question:

> **Completion according to whom, for what purpose, and by what evidence?**

A formal endpoint is not necessarily the same thing as a human outcome or the end of all consequences.

Useful distinctions:

**ENDPOINT ≠ COMPLETION ≠ CLOSURE**

The framework should not turn dignity or human worth into a bureaucratic score.

## 16. System gravity

System gravity is a working design metaphor for resistance to movement between civic states or nodes.

Possible components include:

- time;
- money;
- distance;
- knowledge;
- physical access;
- technology;
- uncertainty;
- authority;
- risk.

It is a model for analysis, not a claim about a physical force.

## 17. Maintenance and staleness

Time-sensitive nodes should identify:

- source owner;
- source location;
- date last verified;
- effective date or version;
- review trigger;
- reviewer or responsible organization, when known.

The framework should permit a node to become:

**UNKNOWN / NOT YET MAPPED**

rather than silently presenting stale information as current.

## 18. Disagreement

A node can be marked **DISPUTED** when relevant sources or participants disagree.

The framework does not need to settle every disagreement.

> **The map does not have to settle every disagreement. It has to make the disagreement inspectable.**

## 19. Civic memory without stagnation

Preserving everything can become stagnation. Replacing everything can destroy memory.

The archive therefore preserves provenance rather than automatically deciding what deserves permanent significance.

A useful historical record answers:

- This existed.
- This is when it existed.
- This is what it was for.
- This is what changed.
- This is what evidence remains.
- This is what replaced it, if anything.

Future users can then make their own judgments about significance.

## 20. Institutional placement

The Civic Flow Chart should be placed as an explanatory layer alongside authoritative institutions rather than presented as a new authority.

Potential placement includes:

- public libraries;
- city and county information systems;
- planning and community development resources;
- emergency-management information;
- state-agency information;
- community organizations;
- printable public reference materials;
- basic HTML and other open formats.

The framework should work without AI, social media, or a user account.

## 21. Santa Cruz test environment

Santa Cruz County is the initial test environment.

The test environment is useful because a resident may encounter overlapping responsibilities involving a city, county, special district, regional body, state agency, federal agency, or combinations of these.

The Santa Cruz examples are tests of the framework. They are not intended to define the framework or establish official facts without verification.

## 22. Self-audit / hostile-user test

The framework must be tested against the possibility that it creates the problem it is intended to solve.

Potential failure modes:

- explanation becomes authority;
- maintenance becomes bureaucracy;
- simplification hides important complexity;
- an estimate becomes mistaken for a deadline;
- an archive becomes unusable;
- transparency creates a gatekeeper;
- a correction process creates more friction;
- the map creates false confidence that government is fully coherent;
- visible choices appear to be decisions made by the map;
- sophisticated users benefit more than people with fewer resources;
- the project itself becomes an institution that resists replacement.

Primary hostile-user questions:

> **Who gets to decide that the Civic Flow Chart is correct?**

> **What happens if the Civic Flow Chart itself becomes friction?**

## 23. Success criteria

A useful implementation should allow an ordinary resident to:

- identify a starting point;
- identify the next responsible actor;
- distinguish authority from explanation;
- distinguish a legal deadline from an estimate;
- see known costs and consequences;
- locate review, appeal, correction, backtrack, or exit paths;
- verify important information at its source;
- recognize uncertainty instead of being given false certainty.

A useful implementation should allow staff or institutions to:

- see handoffs;
- identify unclear responsibility;
- identify repeated work and friction;
- correct mapped information;
- preserve historical versions;
- understand how a resident experiences the process.

The framework should remain usable in print and basic HTML.

## 24. Development sequence

The intended development sequence is:

**RESEARCH → MAP → CHILD TEST → SUBSTANTIVE REVIEW → STRUCTURAL REVIEW → RENDERING REVIEW → RECIPIENT REVIEW → RELEASE → OBSERVE → REVISE → ARCHIVE**

Working rule:

**Fast production. Slow release.**

## 25. Future technical layer

Once the conceptual model is sufficiently tested, the project may add:

- machine-readable node and edge schemas;
- JSON or other open data structures;
- HTML rendering;
- printable rendering;
- interactive maps;
- source-verification records;
- lightweight ledger functions;
- archive/version comparison;
- emergency views;
- APIs;
- software implementations.

Technology should implement the model, not silently redefine it.

## 26. Version boundary

Version 1 is intentionally a framework specification rather than a finished software product.

It establishes the vocabulary, distinctions, routing logic, self-audit principles, and initial test environment needed for later implementation.

Future versions may change the model. Changes should be documented rather than silently overwriting the history of the project.
