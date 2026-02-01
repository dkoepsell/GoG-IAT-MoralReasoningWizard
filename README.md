# GoG Moral Reasoner
*A structural diagnostic tool for moral agency, obligation, contradiction, and repair*

## Overview

The **GoG Moral Reasoner** is an interactive, browser-based diagnostic tool developed alongside  
**_The Geometry of the Good_** (David R. Koepsell).

It operationalizes a **relational ontology of ethics** by making moral structure *inspectable* rather than verdict-driven. The tool does **not** calculate moral answers or rank outcomes. Instead, it reveals where moral agency, obligation, contradiction, and repair arise or fail to arise within a given situation.

This repository exists to support **methodological clarity, teaching, and empirical stress-testing** of the framework.

---

## What This Tool Is (and Is Not)

### This tool **is**
- A **structural diagnostic instrument**
- A formalization of **moral agency** via the *Irreversible Accountability Test (IAT)*
- A way to surface **obligations** arising from relational directedness and vulnerability
- A mechanism for detecting **structural gaps and contradictions**
- A framework that treats **repair** as a first-class moral phenomenon

### This tool **is not**
- A moral decision engine
- A scoring or ranking system
- A normative rulebook
- An optimizer or AI alignment system
- A substitute for moral judgment or deliberation

Contradictions flagged by the tool are **diagnostic signals**, not errors.

---

## Core Concepts

### Moral Agency (Irreversible Accountability Test)

An entity qualifies as a **moral agent** only if:

1. It is an intelligible addressee of normative claims  
2. It can breach those claims in an attributable way  
3. Such breaches generate **non-resettable normative residue**  
4. That residue is borne by the entity itself across time  
5. The entity could have done otherwise under the relevant constraints  

If these conditions fail, the entity is not a moral agent.  
Importantly, this does **not** eliminate obligation. It re-routes it.

---

### Obligation

Obligations arise structurally when relations exhibit:

- **Directedness** (contact, recognition, dependence, representation)
- **Vulnerability** (exposure, dependence, exclusion, harmability)

Obligation is not grounded in consent, rules, or preferences.  
It is a feature of relational structure.

---

### Contradiction and Repair

The tool explicitly tracks situations such as:

- Charged relations with no articulated duties
- Breaches without enduring residue
- Enduring residue without repair pathways
- Duties assigned to entities that cannot bear them

These are treated as **structural incoherences**, not logical errors.  
They indicate where moral explanation, institutional redesign, or repair is required.

Repair restores relational coherence after failure. It is not optional or merely remedial.

---

## Ontological Hygiene (BFO-Aligned, Minimal)

The tool includes a **minimal ontological typing layer** inspired by Basic Formal Ontology (BFO).

This layer is used only to detect **category mistakes**, such as:
- Assigning obligations to roles rather than bearers
- Treating events as agents
- Treating instruments as accountable systems

BFO typing does **not** determine moral outcomes.  
It serves only as structural guardrails.

---

## Relationship to Other Projects

### The Geometry of the Good (GoG)

This tool operationalizes the core ontology developed in *The Geometry of the Good* by making its claims testable and inspectable in concrete cases.

### SOoL (Structural Ontology of Law)

The GoG Moral Reasoner operates at the **pre-legal moral diagnostic layer**.  
SOoL models how responsibility, roles, and contradictions are instantiated and repaired within legal systems.

In short:
- GoG diagnoses **where accountability must arise**
- SOoL models **how law carries, misattributes, or repairs it**

The two frameworks are complementary but not merged.

---

## Repository Contents

```
/moral-reasoner
  moral-reasoner.html     # Single-file interactive tool
  README.md               # This document
  /examples
    contradictory-case.json
    repaired-case.json
```

The tool runs entirely in the browser. No build step. No backend.

---

## Usage

1. Open `moral-reasoner.html` in a modern browser  
2. Create a case or load one via JSON import  
3. Define entities, relations, events, and repair paths  
4. Inspect agency classifications, obligation routing, and diagnostics  

JSON export/import is supported for teaching, analysis, and extension.

---

## Status and Scope

This project is **experimental and exploratory**.

- APIs are not stable
- The UI may change
- The purpose is diagnostic clarity, not completeness

Contributions that improve clarity, extensibility, or pedagogical usefulness are welcome.  
Normative verdicts are out of scope.

---

## License

MIT License.  
Free to use, adapt, and extend with attribution.

---

## Citation

If you reference this tool in academic work, please cite:

Koepsell, D. R. *The Geometry of the Good*. EthicsPress.  
GoG Moral Reasoner (GitHub repository).

---

## Contact

David R. Koepsell  
https://davidkoepsell.com
