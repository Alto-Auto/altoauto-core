#  AltoAuto FEA Automation
**Modern, transparent FEA automation built on open tools.**

---

## Overview
**AltoAuto** is a next-generation structural simulation pipeline that stitches together:
- **Gmsh** for advanced meshing (with optional Netgen fallback),
- **calculix** for linear static solution
- **code aster** for nonlinear solutions,
- **PyVista** for interactive visualization, validation, and mesh quality checks.

---

##  Pipeline Architecture
| 🔧 Feature | 🚀 Description |
|------------|----------------|
| **Mesh Plan Panel** | Fully explicit global/local sizing, curvature growth, min elem size, optional optimization flags. |
| **Loads & BCs Panel** | Interactive face selector to paint forces, fixed constraints, pressures. |
| **Material Panel** | Dropdown for typical isotropic materials (steel, aluminum), plus custom input. |
| **Solution Settings** | Static structural primary, with multi-mesh convergence option. |
| **Study Control** | Overview panel showing entire study plan (mesh levels, BC summary, solver settings), editable for power users. |
| **Results Panel** | Displacement, von Mises stress plots, automatic convergence plots, negative Jacobian highlighting. |

---

## Our mission is to build a transparent, controllable alternative to black-box CAE platforms, focusing on:
- Explicit mesh control & multi-mesh convergence  
- Direct JSON-driven face grouping for reusability  
- Postprocessing that highlights real engineering trust metrics: negative Jacobians, reaction checks, displacement vs load, energy convergence.
- Loop through design to very best quality

---

## Contributing
If you’re a fellow mechanical rebel tired of the black-box CAE model, we welcome:
More quality metrics (dihedral angles, aspect ratios)
Python auto-tuning loops for mesh refinement
Even simple doc improvements
Open a PR or reach out at contact@altoauto.net.
