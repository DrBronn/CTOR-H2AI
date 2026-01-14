## Development Background

The initial Human‑vs‑AI prototype was implemented in HTML, CSS, and JavaScript, tested locally by the author, and later uploaded to the official CTOR GAME Inc. website: https://ctorgame.com/ai.

The first AI‑ready version supported three core CTOR operations:

### For the human player:
- **Put** — placing two new chips  
- **Move** — moving two existing chips  
- **Replace** — replacing two own chips with one own chip  

### For the AI agent (first version):
- **Put** — placing two new chips  

The limitation to a single AI operation reflects the complexity of building a fully playable AI opponent. As the project evolves, more advanced AI techniques will be introduced, including:

- Strong player heuristics  
- Minimax search  
- Monte Carlo methods  
- Learning from examples  
- Self‑learning based on neural networks  

## Purpose

CTOR‑H2AI is designed to:

- Provide a clean, standardized API for integrating AI agents  
- Support multiple difficulty levels and adaptive training modes  
- Enable research in decision‑making, heuristics, and reinforcement learning  
- Serve as the foundation for CTOR mobile and desktop applications  
- Prepare the ecosystem for large‑scale Human‑vs‑AI competitions  

## Long‑Term Vision

The long‑term goal of CTOR‑H2AI is to power a full‑scale online platform where players can train against AI opponents of varying strength, similar to modern Go and Chess servers.

The platform will support:
- Ranked Human‑vs‑AI matches  
- AI tutors and training modes  
- Opening libraries and strategy modules  
- Integration with mobile CTOR applications  
- Federation‑approved competitive formats  

## Repository Structure
/src            — core Human‑vs‑AI engine and integration modules
/ai             — baseline AI agents and evaluation tools
/tests          — validation and correctness tests
/docs           — specifications, API descriptions, and diagrams
/examples       — sample AI matches and training scenarios
/roadmap        — development plans and release notes

## Standards Alignment

This implementation follows the official CTOR Standards:
- **CTOR‑S‑0001** — Core Rules  
- **CTOR‑S‑0002** — Digital Move Protocol  
- **CTOR‑S‑0003** — Tournament Rules  
- **CTOR‑S‑0005** — Human‑vs‑AI Integration Guidelines (in development)  

All updates must remain compliant with federation‑approved specifications.

## Development Goals

- Provide a robust, extensible AI integration layer  
- Maintain compatibility with CTOR‑H2H and CTOR‑AI‑AI  
- Support research in AI strategy and evaluation  
- Enable commercial‑grade mobile and desktop applications  
- Ensure reproducibility and transparency for academic use  

## License and Trademark

This project is released under the **MIT License**.  
CTOR is a registered trademark; see the **NOTICE** file for details.

## Status

Version: **v0.1.0 (in preparation)**  
This release will include the baseline AI agent, integration API, and initial training tools.
