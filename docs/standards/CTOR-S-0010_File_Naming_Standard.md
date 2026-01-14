# CTOR‑S‑0010: File Naming Standard
**Status:** Active  
**Version:** 1.1  
**Approved by:** CTOR Federation Standards Committee  
**Scope:** All CTOR software repositories and digital assets  

---

## 1. Purpose

This standard defines the official naming convention for all CTOR source files, engine modules, AI agents, prototypes, and related digital assets.  
The goal is to ensure consistency, traceability, and clarity across all CTOR‑Federation repositories, including H2H, H2AI, AIAI, and TEAM platforms.

---

## 2. General Format

All CTOR engine and module files must follow the naming pattern:

CTOR_<PLATFORM><AUTHOR><RULESET>_<VERSION>


This structure ensures that every file is self‑describing and can be uniquely identified within the ecosystem.

---

## 3. Component Definitions

### 3.1 PLATFORM  
Indicates the CTOR subsystem or gameplay mode.

| Code  | Description              |
|-------|--------------------------|
| H2H   | Human vs Human           |
| H2AI  | Human vs AI              |
| AIAI  | AI vs AI                 |
| TEAM  | Team vs Team             |
| CORE  | Shared or cross‑platform modules |

---

### 3.2 AUTHOR  
Identifies the creator or responsible entity for the file.

| Code       | Description                                |
|------------|--------------------------------------------|
| CTO        | Original author of CTOR engine prototypes  |
| FED        | Official CTOR Federation implementation    |
| LAB        | Experimental or research version           |
| COMMUNITY  | Community‑contributed module               |

---

### 3.3 RULESET  
Defines the operational capabilities or rule subset implemented in the file.

Two formats are permitted:

---

#### A. **Descriptive format**  
For broad categories:

- `BASE` — basic rule set  
- `ADV` — advanced rule set  
- `FULL` — complete CTOR rules  

---

#### B. **Explicit operation format (recommended)**  
Encodes the number of operations supported:

P#M#R#G#


Where:

- **P** — number of Put operations  
- **M** — number of Move operations  
- **R** — number of Replace operations (max 1 per turn)  
- **G** — number of Migration operations (max 1 per turn)  

Example:
P2M2R1G1

Meaning:
- Put 2  
- Move 2  
- Replace 1 (only once per turn)  
- Migration 1 (only once per turn)  

This format is preferred for engine modules and AI agents.

---

### 3.4 VERSION  
Indicates the version of the file.

Format:
V#
V#_#


Where:

- Major version — breaking changes  
- Minor version — incremental improvements  

Examples:

- `V1` — initial stable version  
- `V1_1` — minor update  
- `V2` — major revision  

---

## 4. Full Example

Using the recommended explicit ruleset format:

CTOR_H2AI_CTO_P2M2R1G1_V1


Meaning:

- CTOR engine  
- Human‑vs‑AI platform  
- Authored by DRBRONN  
- Supports Put 2, Move 2, Replace 1, Migration 1  
- Version 1  

This is the canonical naming format for the current CTOR‑H2AI engine file.

---

## 5. Additional Guidelines

1. File names must use **uppercase letters** and **underscores only**.  
2. No spaces, hyphens, or special characters are allowed.  
3. File extensions (e.g., `.html`, `.js`, `.py`) are appended normally and are not part of the naming standard.  
4. Each repository must include a `/docs/standards` directory containing this document.  
5. All future CTOR engines, AI agents, and modules must comply with this standard.

---

## 6. Version History

- **1.1** — Added Migration operation (G#), clarified Replace and Migration limits  
- **1.0** — Initial release of CTOR‑S‑0010


