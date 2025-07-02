# AltoAuto: CAD + FEA Automation Reimagined

> What if engineering workflows were as automated as modern code?  
> What if you could simulate anything from STEP file to stress plot without ever touching the GUI?

---

## Our Vision

AltoAuto is here to automate what the big guys never dared to touch:

- Import geometry → auto-mesh → tag faces → run FEA → export results  
- Replace hours of clicking with clean, API-driven pipelines  
- Make simulation as scriptable and repeatable as real software builds

We are **engineers building for engineers** — not GUI babysitters.

---

## 🔧 What We're Building (Phase 1)

### FEA Automation Tools:
- Shell/Solid Element Switching
- FaceSelectorLite (Area ID → Load Mapping)
- Mesh Convergence Tester
- STEP → Gmsh → CDB → MAPDL pipeline
- Full GUI-driven FEA setup with PyMAPDL backend

---

## This Repo: The FEA Import Pipeline

This repository is the foundation for importing and processing geometry:

- `step_to_msh/` → STEP to GMSH mesh
- `msh_to_cdb/` → Mesh to valid Ansys CDB
- `face_extractor/` → Match mesh faces to element IDs (WIP)
- `pressure_mapper/` → Pressure logic via element or nodal targeting

**Goal:**  
Enable full-scale simulation from imported CAD files

---

## What We Believe

- Automation should be default, not luxury
- Engineers should write logic, not click boxes
- Simulation should scale like code
- You shouldn't need 10 licenses to run 1 model

---

## 👥 Community & Collaboration

This project is open to:
- Engineers experimenting with FEA workflows
- Developers curious about automation
- Anyone who wants to explore what's possible with CAD/FEA pipelines

We're early in this project and welcome technical discussion, code contributions, bug reports, and feature ideas.  

All contributions are reviewed before merge, and the project is governed under AltoAuto’s license and ownership terms.

---

## 🤝 How to Contribute

We welcome:
- Pull requests
- Feature suggestions
- Pressure application experiments
- Real-world part testing

Before contributing:
- Read [`LICENSE`](LICENSE)
- Check [`CONTRIBUTING.md`](CONTRIBUTING.md)
- Submit clean PRs with context

All contributions are owned by AltoAuto. No commercial forks allowed.

---

## License

Licensed under **CC BY-NC-ND 4.0**  
Use for non-commercial, academic, or personal development.  
For commercial licensing: [contact@altoauto.net](mailto:contact@altoauto.net)

---

## Who We Are

Built by [AltoAuto](https://altoauto.net) — Build for engineers By engineers With purpose

> If you’ve ever said "Why the hell do I have to click this 20 times?" — you're one of us.

- Email: [contact@altoauto.net](mailto:contact@altoauto.net)
- LinkedIn: [@AltoAuto](https://www.linkedin.com/company/altoauto)
- Website: https://altoauto.net
