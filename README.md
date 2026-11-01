<div align="center">

<a href="README.md"><img src="https://img.shields.io/badge/Language-English-1A1A1A?style=for-the-badge" alt="English"></a>
<a href="README.es.md"><img src="https://img.shields.io/badge/Idioma-Espa%C3%B1ol-E65C00?style=for-the-badge" alt="Español"></a>

<br>

**[English](README.md)** | **[Español](README.es.md)**

<br><br>

# Mathematical Methods I
### Differential Geometry, Exterior Calculus, and Tensor Analysis

<p align="center">
  A rigorous and pedagogical collection of mathematical notes, analytical formulations, and geometric visualizations typeset in LaTeX.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Field-Differential_Geometry-1A1A1A?style=flat-square" alt="Field">
  <img src="https://img.shields.io/badge/Typesetting-LaTeX_%2F_TikZ-E65C00?style=flat-square" alt="LaTeX">
  <img src="https://img.shields.io/badge/Format-Source_%26_Compiled_PDF-1A1A1A?style=flat-square" alt="Format">
  <img src="https://img.shields.io/badge/Status-Active_Notes-7A746E?style=flat-square" alt="Status">
</p>

</div>

---

## Overview

This repository hosts a comprehensive, self-contained sequence of advanced lecture notes and mathematical expositions covering the foundations of **Differential Geometry**, **Exterior Calculus on Manifolds**, **Tensor Calculus**, and **Geometric Vector Analysis**.

The material bridges classical vector calculus in Euclidean space with the modern language of differential forms, moving frames, and Riemannian geometry commonly required in theoretical physics, continuum mechanics, and modern geometry.

Every thematic module includes:
* **LaTeX Source (`.tex`)**: Fully detailed mathematical derivation typeset with custom theorem blocks and vector graphics generated directly in TikZ.
* **Compiled Document (`.pdf`)**: Publication-quality document ready for reading, study, and direct reference.

---

## Pedagogical Structure

The repository is structured into four progressive stages, leading the reader from foundational affine geometry to coordinate-free tensor calculus:

```
[I. Euclidean Geometry & Symmetries]
    Euclidean Space -> Isometries and Lie Groups (O(n), SO(n), E(n))
           |
           v
[II. Tangent Bundles & Curve Theory]
    Tangent Vectors & Derivations -> Directional Derivatives -> Parametrized Curves -> Frenet-Serret Frame
           |
           v
[III. Exterior Calculus & Differential Forms]
    Dual Space & 1-Forms -> Exterior Derivative & Poincaré Lemma -> Circulation Density & Stokes' Theorem
           |
           v
[IV. Metric Geometry & Invariant Operators]
    Metric Tensor & Line Elements -> Musical Isomorphisms & Hodge Star -> Invariant Vector Calculus
```

---

## Curriculum and Repository Map

| Module | Core Topics and Mathematical Concepts | Source (`.tex`) | Compiled (`.pdf`) | Document Language |
| :--- | :--- | :--- | :--- | :--- |
| **Euclidean Space** | Affine $E^n$, canonical inner product, induced norm, metric distances, Cauchy-Schwarz and triangle inequalities, orthogonality, and angles. | [`Euclidean_Space.tex`](Euclidean_Space/Euclidean_Space.tex) | [`Euclidean_Space.pdf`](Euclidean_Space/Euclidean_Space.pdf) | English |
| **Groups and Euclidean Geometry** | Rigid motions, isometry group $E(n)$, orthogonal group $O(n)$ and rotation group $SO(n)$, Rodrigues' rotation formula, active vs. passive transformations, infinitesimal differentials. | [`Mathematical_Methods_1_Groups_and_Euclidean_Geometry.tex`](Groups_and_Eucliden_Geometry/Mathematical_Methods_1_Groups_and_Euclidean_Geometry.tex) | [`Euclidean_Geometry_and_Simetric_Groups.pdf`](Groups_and_Eucliden_Geometry/Euclidean_Geometry_and_Simetric_Groups.pdf) | Spanish |
| **Tangent Space** | Topological open sets in $E^3$, smooth mappings, tangent vectors as geometric derivations, tangent space $T_p(E^3)$, smooth vector fields, natural coordinate frame $\{U_i\}$. | [`Tangent_Space.tex`](Tangent_Space/Tangent_Space.tex) | [`Tangent_Space.pdf`](Tangent_Space/Tangent_Space.pdf) | English |
| **Directional Derivative** | Derivation along tangent vectors $v_p[f]$, Cartesian calculation, algebraic properties, Leibniz rule, vector fields as linear differential operators, coordinate basis connections. | [`Directional_Derivative.tex`](Directional_Derivative/Directional_Derivative.tex) | [`Directional_Derivative.pdf`](Directional_Derivative/Directional_Derivative.pdf) | English |
| **Curves in Euclidean Space** | Parametrized curves $\alpha(t)$, velocity vector $\alpha'(t)$ as derivation, instantaneous velocity, representation in natural frame, reparametrizations, regularity criteria. | [`Curves.tex`](Curves_in_Euclidean_Space/Curves.tex) | [`Curves_in_E3.pdf`](Curves_in_Euclidean_Space/Curves_in_E3.pdf) | English |
| **Curves and Frenet-Serret Frame** | Moving frame $\{T, N, B\}$, curvature $\kappa$ and torsion $\tau$, Frenet-Serret equations, Darboux vector, arbitrary parameter formulas, osculating planes, Fundamental Theorem of Space Curves. | [`Mathematical_Methods_1_Curves_and_Frenet.tex`](Curves_and_Frenet_S/Mathematical_Methods_1_Curves_and_Frenet.tex) | [`Curves_and_Frenet.pdf`](Curves_and_Frenet_S/Curves_and_Frenet.pdf) | Spanish |
| **Differential 1-Forms** | Dual vector space $T_p^*$, covectors, coordinate differentials $dx^i$ as dual basis, evaluation $\omega(V)$, hyperplane visualization, exact forms, differential $df$, coordinate transformation laws. | [`1_Forms.tex`](1_Forms/1_Forms.tex) | [`Mathematical_Methods_1_Forms.pdf`](1_Forms/Mathematical_Methods_1_Forms.pdf) | English |
| **Exterior Derivative** | Differential $k$-forms, exterior wedge product $\wedge$, antisymmetry, Jacobian determinants, graded Leibniz rule, nilpotency $d^2 = 0$, Poincaré lemma, closed vs. exact forms. | [`Exterior_Derivative.tex`](Exterior_Derivative/Exterior_Derivative.tex) | [`Exterior_Derivative.pdf`](Exterior_Derivative/Exterior_Derivative.pdf) | English |
| **Circulation Density & Orientation** | Closed-loop line integrals, infinitesimal rectangular loops, circulation density, oriented area elements, geometric Stokes' Theorem, oriented volume forms $dx \wedge dy \wedge dz$. | [`Mathematical_Methods_1_Circulation_density_Orientation.tex`](Circulation_density_Orientation/Mathematical_Methods_1_Circulation_density_Orientation.tex) | [`Mathematical_Methods_1_Circulation_density_Orientation.pdf`](Circulation_density_Orientation/Mathematical_Methods_1_Circulation_density_Orientation.pdf) | English |
| **The Metric and Tensors** | Multilinear algebra, tensor components, Riemannian metric tensor $g_{ij}$, line element $ds^2$, index lowering, metric in orthogonal coordinates, semi-Riemannian / pseudo-Riemannian geometries. | [`The_metric_and_Tensors.tex`](The_metric_and_Tensors/The_metric_and_Tensors.tex) | [`Mathematical_Methods_1_Metric_and_Tensors.pdf`](The_metric_and_Tensors/Mathematical_Methods_1_Metric_and_Tensors.pdf) | English |
| **Differential Operators** | Musical isomorphisms ($\flat, \sharp$), scale factors $h_i$, invariant gradient, Hodge star operator $\star$, invariant divergence, Laplace-Beltrami operator, invariant curl in curvilinear frames. | [`Differential_Operators.tex`](Diiferential_Operators/Differential_Operators.tex) | [`Differential_Operators.pdf`](Diiferential_Operators/Differential_Operators.pdf) | English |
| **Sheet Problems** | Supplementary problem sheets, analytical exercises, and applied problems in differential geometry. | [`README.md`](Sheet_Problems/README.md) | N/A | Bilingual |

---

## Module Summaries

### 1. Euclidean Space and Symmetries
* **Euclidean Space**: Formulates $\mathbb{R}^n$ as a metric space equipped with the standard dot product, establishing Cauchy-Schwarz and triangle inequalities as prerequisites for Riemannian metrics.
* **Groups and Euclidean Geometry**: Analyzes rigid motions as affine mappings $F(x) = Rx + p$. Covers the Lie group $SO(3)$, derivation of Rodrigues' rotation formula, and the distinction between active rotations of physical vectors and passive coordinate transformations.

### 2. Differential Calculus and Local Curve Theory
* **Tangent Space**: Treats tangent vectors rigorously as derivations acting on $C^\infty$ scalar fields, introducing the natural basis $\{U_1, U_2, U_3\}$ and the tangent bundle of $\mathbb{R}^3$.
* **Directional Derivative**: Connects vector fields with first-order linear differential operators.
* **Curves and Kinematics**: Establishes velocity vectors, regularity conditions ($\alpha' \neq 0$), and reparametrization invariants.
* **Frenet-Serret Apparatus**: Constructs the moving frame $\{T, N, B\}$ along unit-speed space curves, deriving the kinematic evolution system governed by curvature $\kappa$ and torsion $\tau$, with Darboux vector formulations and local canonical expansions.

### 3. Differential Forms and Exterior Calculus
* **Differential 1-Forms**: Constructs the cotangent space $T_p^*$ and defines 1-forms as linear functionals on tangent vectors, illustrated via dual level surfaces.
* **Exterior Algebra**: Formalizes the alternating wedge product $\wedge$, graded exterior differentiation $d$, the nilpotency identity $d^2 = 0$, and the local exactness of closed forms via the Poincaré Lemma.
* **Circulation and Stokes**: Formulates circulation density as the infinitesimal limit of line integrals, showing how the exterior derivative geometrically represents boundary circulation per unit oriented area.

### 4. Tensor Analysis and Invariant Differential Operators
* **The Metric and Tensors**: Generalizes inner products to metric tensors $g = g_{ij} dx^i \otimes dx^j$, computing coordinate transformation laws and quadratic line elements $ds^2$ in curvilinear and pseudo-Riemannian manifolds.
* **Invariant Differential Operators**: Unifies vector calculus via differential geometry using musical isomorphisms ($\flat$ and $\sharp$) and the Hodge star $\star$:
  $$\operatorname{grad}(f) = (df)^\sharp$$
  $$\operatorname{div}(V) = \star d \star (V^\flat)$$
  $$\operatorname{curl}(V) = (\star d (V^\flat))^\sharp$$
  $$\Delta f = \star d \star d f$$

---

## Typography and Design Specifications

All documents share a unified typography and visual hierarchy engineered in LaTeX:

* **Color Palette**:
  * Primary Text / Headings: `blackmain` (`#1A1A1A`)
  * Accent Highlight: `orangeacc` (`#E65C00`)
  * Primary Box Background: `creambg` (`#FBF8F1`)
  * Accent Box Background: `orangebg` (`#FFF4EB`)
  * Secondary / Muted Text: `graymuted` (`#7A746E`)
* **Typography**: Latin Modern font family (`lmodern`) with microtypographic adjustments (`microtype`).
* **Graphics**: Clean vector diagrams natively rendered using TikZ and PGF (`tikz-3dplot`, `angles`, `quotes`).
* **Structural Containers**: Custom callout frames implemented with `tcolorbox`.

---

## Compilation Instructions

### Prerequisites
To compile the documents locally, a standard TeX distribution is required:
* **Linux**: TeX Live (`texlive-latex-extra`, `texlive-science`, `texlive-pictures`)
* **macOS**: MacTeX
* **Windows**: MiKTeX or TeX Live

Ensure the following packages are present in your TeX tree:
`amsmath`, `amssymb`, `tcolorbox`, `tikz`, `tikz-3dplot`, `fancyhdr`, `geometry`, `microtype`, `enumitem`, `babel`.

### Building a Single Document
Navigate to any module folder and compile using `pdflatex`:

```bash
pdflatex -interaction=nonstopmode <filename>.tex
pdflatex -interaction=nonstopmode <filename>.tex
```
*(Two compilation passes are recommended to correctly resolve references and page numbers).*

### Batch Compilation
To compile all `.tex` files across all subdirectories from the repository root:

```bash
find . -mindepth 2 -name "*.tex" -execdir pdflatex -interaction=nonstopmode {} \;
```

---

## Recommended References

1. **Barrett O'Neill**, *Elementary Differential Geometry*, Academic Press.
2. **Theodore Frankel**, *The Geometry of Physics: An Introduction*, Cambridge University Press.
3. **Bernard F. Schutz**, *Geometrical Methods of Mathematical Physics*, Cambridge University Press.
4. **Manfredo P. do Carmo**, *Differential Geometry of Curves and Surfaces*, Prentice-Hall.
5. **John M. Lee**, *Introduction to Smooth Manifolds*, Springer Graduate Texts in Mathematics.

---

## License and Academic Usage

These materials are organized for academic, self-study, and research purposes. Feel free to clone, study, and compile the notes. If utilizing the LaTeX templates or figures in derivative educational work, citation of this repository is appreciated.
