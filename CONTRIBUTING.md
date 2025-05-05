# Contributing to AltoAuto

Thanks for your interest in improving AltoAuto!  
We're building a long-term automation platform — your contributions help move the entire engineering workflow forward.

---

## What You Can Contribute

We welcome:
- Feature suggestions
- Bug reports
- Testing feedback (especially with real-world STEP or CDB files)
- Clean pull requests with working code or documentation

---

## Code Guidelines

- Write clear, readable Python
- Keep functions small and focused
- Add docstrings where needed
- Use comments to explain logic, especially mesh or FEA-specific steps
- Before submitting a PR, test your code on at least 1 real model

---

## Repo Structure (WIP)

- `step_to_msh/` → STEP → GMSH logic
- `msh_to_cdb/` → `.msh` → `.cdb` conversion logic
- `face_extractor/` → Tagging or mapping mesh faces to loads
- `pressure_mapper/` → Pressure logic (element/nodal based)

---

## Legal Note (Important)

By contributing to this project:
- You agree to assign all IP rights in your contributions to AltoAuto
- You agree not to reuse or resell any parts of this codebase for commercial purposes
- You agree to the [LICENSE](LICENSE) (CC BY-NC-ND 4.0)

---

## How to Start

1. Fork the repo
2. Open an Issue with what you want to do (bug, feature, idea)
3. Discuss if needed — we’ll reply fast
4. Submit a Pull Request (PR)
5. We’ll review, test, and merge if it fits

---

## Respect the Project

This is not a product. It's a work in progress.  
We welcome help — but we keep quality high and the mission focused.

---

For deeper questions, email: [contact@altoauto.net](mailto:contact@altoauto.net)
