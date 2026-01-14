# CTOR-H2AI
# CTOR‑H2H — Official Human‑vs‑Human Reference Implementation

CTOR‑H2H is the canonical reference implementation of CTOR for human‑versus‑human play.  
This repository defines the official ruleset, move‑validation engine, match structure, and baseline tools used for competitive CTOR sessions across the CTOR‑Federation ecosystem.

## Development Background

The initial version of CTOR‑H2H was originally implemented as a local two‑player game using HTML, CSS, and JavaScript.  
It was tested directly on the author’s computer and included three core operations from the official CTOR ruleset:

- **Put** — placing two new chips  
- **Move** — moving two an existing chips  
- **Replace** — replacing two own chips to one own chip  

## Long‑Term Vision

The ultimate goal of CTOR‑H2H is to evolve into a full online platform comparable to established Go and Chess servers, enabling both amateur and professional CTOR players to compete, study games, and participate in official tournaments.

## Repository Structure

/src            — core implementation (H2H_Comet_Base)
/tests          — validation and correctness tests
/docs           — specifications, diagrams, and protocol descriptions
/examples       — sample matches and usage examples
/roadmap        — development plans and release notes

## Standards Alignment

This implementation follows the official CTOR Standards:
- **CTOR‑S‑0001** — Core Rules  
- **CTOR‑S‑0002** — Digital Move Protocol  
- **CTOR‑S‑0003** — Tournament Rules  

All updates to this repository must remain compliant with federation‑approved specifications.

## Development Goals

- Maintain architectural purity and reproducibility  
- Provide a stable foundation for competitive CTOR events  
- Support integration with future CTOR platforms  
- Enable academic and research use  

## License and Trademark

This project is released under the **MIT License**.  
CTOR is a registered trademark; see the **NOTICE** file for details.

## Status

Version: **v1.0.0 (in preparation)**  
This release will include the complete H2H_Comet_Base implementation and full documentation.
