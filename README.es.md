<div align="center">

<a href="README.md"><img src="https://img.shields.io/badge/Language-English-1A1A1A?style=for-the-badge" alt="English"></a>
<a href="README.es.md"><img src="https://img.shields.io/badge/Idioma-Espa%C3%B1ol-E65C00?style=for-the-badge" alt="Español"></a>

<br>

**[English](README.md)** | **[Español](README.es.md)**

<br><br>

# Métodos Matemáticos I
### Geometría Diferencial, Cálculo Exterior y Análisis Tensorial

<p align="center">
  Colección rigurosa y pedagógica de notas matemáticas, derivaciones analíticas y visualizaciones geométricas desarrolladas en LaTeX.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Disciplina-Geometr%C3%ADa_Diferencial-1A1A1A?style=flat-square" alt="Disciplina">
  <img src="https://img.shields.io/badge/Tipograf%C3%ADa-LaTeX_%2F_TikZ-E65C00?style=flat-square" alt="LaTeX">
  <img src="https://img.shields.io/badge/Formato-C%C3%B3digo_Fuente_%26_PDF-1A1A1A?style=flat-square" alt="Formato">
  <img src="https://img.shields.io/badge/Estado-Notas_Activas-7A746E?style=flat-square" alt="Estado">
</p>

</div>

---

## Visión General

Este repositorio contiene una secuencia estructurada y autocontenida de notas de clase y exposiciones formales que cubren los fundamentos de la **Geometría Diferencial**, el **Cálculo Exterior en Variedades**, el **Análisis Tensorial** y el **Cálculo Vectorial Invariante**.

El material articula el cálculo vectorial clásico en espacios euclídeos con el formalismo moderno de formas diferenciales, sistemas de referencia móviles y geometría riemanniana, herramientas esenciales en física teórica, mecánica del continuo y geometría contemporánea.

Cada módulo temático incluye:
* **Código Fuente LaTeX (`.tex`)**: Desarrollo analítico detallado con bloques de teoremas personalizados y gráficos vectoriales generados nativamente en TikZ.
* **Documento Compilado (`.pdf`)**: Versión lista para lectura, estudio y consulta directa.

---

## Estructura Pedagógica

El plan de estudio sigue un orden de dependencia lógica estructurado en cuatro etapas:

```
[I. Geometría Euclídea y Simetrías]
    Espacio Euclídeo -> Isometrías y Grupos de Lie (O(n), SO(n), E(n))
           |
           v
[II. Fibrado Tangente y Teoría de Curvas]
    Vectores Tangentes y Derivaciones -> Derivada Direccional -> Curvas Parametrizadas -> Triedro de Frenet-Serret
           |
           v
[III. Cálculo Exterior y Formas Diferenciales]
    Espacio Dual y 1-Formas -> Derivada Exterior y Lema de Poincaré -> Densidad de Circulación y Teorema de Stokes
           |
           v
[IV. Geometría Métrica y Operadores Invariantes]
    Tensor Métrico e Intervalo ds² -> Isomorfismos Musicales y Estrella de Hodge -> Cálculo Vectorial Invariante
```

---

## Mapa Curricular y Contenido del Repositorio

| Módulo | Conceptos Clave y Desarrollo Matemático | Código Fuente (`.tex`) | Documento (`.pdf`) | Idioma del Documento |
| :--- | :--- | :--- | :--- | :--- |
| **Euclidean Space** | Espacio afín $E^n$, producto interno canónico, norma inducida, distancias métricas, desigualdades de Cauchy-Schwarz y triangular, ortogonalidad y ángulos. | [`Euclidean_Space.tex`](Euclidean_Space/Euclidean_Space.tex) | [`Euclidean_Space.pdf`](Euclidean_Space/Euclidean_Space.pdf) | Inglés |
| **Groups and Euclidean Geometry** | Movimientos rígidos, grupo euclídeo $E(n)$, grupos ortogonal $O(n)$ y de rotaciones $SO(n)$, fórmula de rotación de Rodrigues, transformaciones activas y pasivas, diferencial infinitesimal. | [`Mathematical_Methods_1_Groups_and_Euclidean_Geometry.tex`](Groups_and_Eucliden_Geometry/Mathematical_Methods_1_Groups_and_Euclidean_Geometry.tex) | [`Euclidean_Geometry_and_Simetric_Groups.pdf`](Groups_and_Eucliden_Geometry/Euclidean_Geometry_and_Simetric_Groups.pdf) | Español |
| **Tangent Space** | Conjuntos abiertos en $E^3$, funciones diferenciables, vectores tangentes como derivaciones, espacio tangente $T_p(E^3)$, campos vectoriales y referencia natural $\{U_i\}$. | [`Tangent_Space.tex`](Tangent_Space/Tangent_Space.tex) | [`Tangent_Space.pdf`](Tangent_Space/Tangent_Space.pdf) | Inglés |
| **Directional Derivative** | Derivada en la dirección de un vector tangente $v_p[f]$, cálculo en coordenadas cartesianas, propiedades algebraicas, regla de Leibniz, campos vectoriales como operadores diferenciales. | [`Directional_Derivative.tex`](Directional_Derivative/Directional_Derivative.tex) | [`Directional_Derivative.pdf`](Directional_Derivative/Directional_Derivative.pdf) | Inglés |
| **Curves in Euclidean Space** | Curvas parametrizadas $\alpha(t)$, vector velocidad $\alpha'(t)$ como derivación, paso al límite de la secante, componentes en la referencia natural, reparametrización y condiciones de regularidad. | [`Curves.tex`](Curves_in_Euclidean_Space/Curves.tex) | [`Curves_in_E3.pdf`](Curves_in_Euclidean_Space/Curves_in_E3.pdf) | Inglés |
| **Curves and Frenet-Serret Frame** | Triedro móvil $\{T, N, B\}$, curvatura $\kappa$ y torsión $\tau$, ecuaciones de Frenet-Serret, vector de Darboux, fórmulas para parámetro arbitrario, planos osculador y normal, Teorema Fundamental de Curvas. | [`Mathematical_Methods_1_Curves_and_Frenet.tex`](Curves_and_Frenet_S/Mathematical_Methods_1_Curves_and_Frenet.tex) | [`Curves_and_Frenet.pdf`](Curves_and_Frenet_S/Curves_and_Frenet.pdf) | Español |
| **Differential 1-Forms** | Espacio dual $T_p^*$, covectores, diferenciales de coordenadas $dx^i$ como base dual, evaluación $\omega(V)$, interpretación geométrica de foliaciones, formas exactas, diferencial $df$ y cambios de base. | [`1_Forms.tex`](1_Forms/1_Forms.tex) | [`Mathematical_Methods_1_Forms.pdf`](1_Forms/Mathematical_Methods_1_Forms.pdf) | Inglés |
| **Exterior Derivative** | $k$-formas diferenciales, producto exterior (wedge) $\wedge$, antisimetría, determinantes jacobianos, regla graduada de Leibniz, propiedad de nilpotencia $d^2 = 0$, Lema de Poincaré, formas cerradas y exactas. | [`Exterior_Derivative.tex`](Exterior_Derivative/Exterior_Derivative.tex) | [`Exterior_Derivative.pdf`](Exterior_Derivative/Exterior_Derivative.pdf) | Inglés |
| **Circulation Density & Orientation** | Integrales de línea en lazos cerrados, circulación en lazos rectangulares infinitesimales, densidad de circulación, elementos de área orientada, Teorema de Stokes geométrico, formas de volumen $dx \wedge dy \wedge dz$. | [`Mathematical_Methods_1_Circulation_density_Orientation.tex`](Circulation_density_Orientation/Mathematical_Methods_1_Circulation_density_Orientation.tex) | [`Mathematical_Methods_1_Circulation_density_Orientation.pdf`](Circulation_density_Orientation/Mathematical_Methods_1_Circulation_density_Orientation.pdf) | Inglés |
| **The Metric and Tensors** | Álgebra multilineal, componentes tensoriales, tensor métrico riemanniano $g_{ij}$, elemento de línea $ds^2$, descenso de índices, métrica en coordenadas curvilíneas, geometrías semiriemannianas y pseudoriemannianas. | [`The_metric_and_Tensors.tex`](The_metric_and_Tensors/The_metric_and_Tensors.tex) | [`Mathematical_Methods_1_Metric_and_Tensors.pdf`](The_metric_and_Tensors/Mathematical_Methods_1_Metric_and_Tensors.pdf) | Inglés |
| **Differential Operators** | Isomorfismos musicales ($\flat, \sharp$), factores de escala $h_i$, gradiente invariante, operador estrella de Hodge $\star$, divergencia invariante, operador de Laplace-Beltrami, rotacional invariante en sistemas curvilíneos. | [`Differential_Operators.tex`](Diiferential_Operators/Differential_Operators.tex) | [`Differential_Operators.pdf`](Diiferential_Operators/Differential_Operators.pdf) | Inglés |
| **Sheet Problems** | Cuadernos de ejercicios, problemas analíticos y aplicaciones prácticas en geometría diferencial. | [`README.md`](Sheet_Problems/README.md) | N/A | Bilingüe |

---

## Resumen de Módulos

### 1. Espacio Euclídeo y Simetrías
* **Espacio Euclídeo**: Formalización de $\mathbb{R}^n$ como espacio afín dotado de producto escalar canónico, demostrando las desigualdades de Cauchy-Schwarz y triangular como base indispensable para la geometría métrica.
* **Grupos y Geometría Euclídea**: Análisis de movimientos rígidos como transformaciones afines $F(x) = Rx + p$. Estudio del grupo de Lie $SO(3)$, derivación de la fórmula de rotación de Rodrigues y distinción formal entre rotaciones activas del vector físico y transformaciones pasivas de coordenadas.

### 2. Cálculo Diferencial y Teoría Local de Curvas
* **Espacio Tangente**: Tratamiento de los vectores tangentes como derivaciones que operan sobre campos escalares $C^\infty$, introduciendo la base natural $\{U_1, U_2, U_3\}$ y la estructura del fibrado tangente.
* **Derivada Direccional**: Interpretación y equivalencia de los campos vectoriales como operadores diferenciales de primer orden.
* **Curvas y Cinemática**: Definición del vector velocidad, noción de regularidad ($\alpha' \neq 0$) e invariancia bajo reparametrizaciones.
* **Triedro de Frenet-Serret**: Construcción del sistema ortonormal móvil $\{T, N, B\}$ para curvas parametrizadas por longitud de arco, deduciendo las relaciones dinámicas regidas por la curvatura $\kappa$ y la torsión $\tau$, junto con el vector de Darboux y la expansión canónica local.

### 3. Formas Diferenciales y Cálculo Exterior
* **1-Formas Diferenciales**: Construcción del espacio cotangente $T_p^*$ y definición de formas diferenciales como funcionales lineales sobre vectores tangentes, complementada con su interpretación geométrica como foliación de planos.
* **Álgebra Exterior**: Formalización del producto alternante $\wedge$, el operador derivada exterior $d$, la identidad de nilpotencia $d^2 = 0$ y la exactitud local de formas cerradas a través del Lema de Poincaré.
* **Densidad de Circulación y Stokes**: Definición de la densidad de circulación como el límite microscópico de integrales de línea, estableciendo cómo la derivada exterior representa la circulación por unidad de área orientada.

### 4. Análisis Tensorial y Operadores Diferenciales Invariantes
* **Métrica y Tensores**: Generalización del producto interno a tensores métricos $g = g_{ij} dx^i \otimes dx^j$, leyes de transformación tensorial bajo cambios de coordenadas y cálculo del elemento de línea cuadrático $ds^2$ en espacios euclídeos y variedades semiriemannianas.
* **Operadores Diferenciales Invariantes**: Unificación del cálculo vectorial mediante los isomorfismos musicales ($\flat, \sharp$) y el operador dual de Hodge $\star$:
  $$\operatorname{grad}(f) = (df)^\sharp$$
  $$\operatorname{div}(V) = \star d \star (V^\flat)$$
  $$\operatorname{rot}(V) = (\star d (V^\flat))^\sharp$$
  $$\Delta f = \star d \star d f$$

---

## Especificaciones Tipográficas y de Diseño

Todos los documentos comparten un sistema homogéneo de maquetación y jerarquía visual en LaTeX:

* **Paleta de Color**:
  * Texto Principal / Títulos: `blackmain` (`#1A1A1A`)
  * Color de Acento: `orangeacc` (`#E65C00`)
  * Fondo de Bloques Principales: `creambg` (`#FBF8F1`)
  * Fondo de Cajas de Acento: `orangebg` (`#FFF4EB`)
  * Texto Secundario / Atenuado: `graymuted` (`#7A746E`)
* **Tipografía**: Familia tipográfica Latin Modern (`lmodern`) complementada con optimizaciones microtipográficas (`microtype`).
* **Gráficos**: Diagramas vectoriales de alta precisión generados directamente con TikZ y PGF (`tikz-3dplot`, `angles`, `quotes`).
* **Cajas Estructurales**: Entornos para definiciones, teoremas y ejemplos implementados mediante `tcolorbox`.

---

## Instrucciones de Compilación

### Requisitos Previos
Para compilar los documentos localmente se requiere una distribución de TeX:
* **Linux**: TeX Live (`texlive-latex-extra`, `texlive-science`, `texlive-pictures`)
* **macOS**: MacTeX
* **Windows**: MiKTeX o TeX Live

Paquetes requeridos en la instalación:
`amsmath`, `amssymb`, `tcolorbox`, `tikz`, `tikz-3dplot`, `fancyhdr`, `geometry`, `microtype`, `enumitem`, `babel`.

### Compilación Individual
Ingrese al directorio del módulo correspondiente y ejecute `pdflatex`:

```bash
pdflatex -interaction=nonstopmode <archivo>.tex
pdflatex -interaction=nonstopmode <archivo>.tex
```
*(Se recomiendan dos pasadas para resolver de manera adecuada referencias cruzadas y numeración).*

### Compilación Completa (Batch)
Para compilar la totalidad de los archivos `.tex` de todos los módulos desde la raíz del repositorio:

```bash
find . -mindepth 2 -name "*.tex" -execdir pdflatex -interaction=nonstopmode {} \;
```

---

## Referencias Bibliográficas Recomendadas

1. **Barrett O'Neill**, *Elementary Differential Geometry*, Academic Press.
2. **Theodore Frankel**, *The Geometry of Physics: An Introduction*, Cambridge University Press.
3. **Bernard F. Schutz**, *Geometrical Methods of Mathematical Physics*, Cambridge University Press.
4. **Manfredo P. do Carmo**, *Differential Geometry of Curves and Surfaces*, Prentice-Hall.
5. **John M. Lee**, *Introduction to Smooth Manifolds*, Springer Graduate Texts in Mathematics.

---

## Licencia y Uso Académico

Estos materiales están desarrollados con propósitos académicos, docentes y de autoaprendizaje. La consulta, clonación y compilación de las notas es libre. En caso de utilizar las plantillas LaTeX o los diagramas TikZ en obras educativas derivadas, se agradece citar este repositorio como referencia de origen.
