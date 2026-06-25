<div align="center">

# 📐 LaTeX Portfolio — DEMAT UG

**Ricardo León Martínez**  
Departamento de Matemáticas · Universidad de Guanajuato

![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![TikZ](https://img.shields.io/badge/TikZ-FF6600?style=for-the-badge)
![Beamer](https://img.shields.io/badge/Beamer-0066CC?style=for-the-badge)

</div>

---

Colección de documentos que muestran distintas capacidades de LaTeX, producidos durante mi carrera en el **DEMAT-UG**. El enfoque es técnico: cada carpeta ilustra una habilidad concreta.

---

## 🗂️ Estructura

```
DEMAT-UG-portfolio/
├── ugmath/              ← Paquete personal (.sty)
├── portadas/            ← Portadas construidas 100% en TikZ
├── presentaciones/      ← Slides con Beamer
├── notas/               ← Documentos tipo libro (multi-capítulo)
├── proyectos/           ← Solucionarios y proyectos personales
└── tareas/              ← Tareas representativas por materia
```

---

## ✨ Habilidades demostradas

### 📦 `ugmath/` — Paquete personal

`ugmath.sty` es un paquete LaTeX propio que centraliza todo el estilo de mis documentos. Incluye:

- Fuente **Libertinus** + `microtype` para tipografía refinada
- Colores institucionales UG (`#003366` azul, `#D4AF37` dorado)
- Cajas con `mdframed` + TikZ para teoremas, definiciones, soluciones y ejemplos
- Entornos `amsthm` personalizados: `theorem`, `definition`, `proof`, `solucion`
- `pgfplots`, `tikz-3dplot`, `physics`, `mathtools` preconfigurados
- Márgenes y espaciado listos para imprimir

---

### 🎨 `portadas/` — Portadas con TikZ

Portadas diseñadas completamente en TikZ, sin imágenes externas. Cada una demuestra:

| Carpeta | Técnica destacada |
|---|---|
| `algebra-lineal/` | Panel lateral + cuadrícula matemática de fondo + tipografía posicionada |
| `calculo-3/` | Bloques de color con gradiente, layout asimétrico |
| `probabilidad/` | Variación de paleta manteniendo el sistema visual |
| `teoria-numeros/` | Portada estilo libro clásico |

Todas usan `\foreach`, `\fill`, coordenadas absolutas y `current page` para control total del layout.

---

### 📊 `presentaciones/` — Beamer

**`fisica-cuerpo-rigido/`** — Dinámica del Cuerpo Rígido (Física I)

- Tema Madrid con paleta completamente redefinida (azul oscuro `#0A2850` + naranja `#FFA500`)
- Diagramas vectoriales en TikZ con `arrows.meta`, `3d`, `angles`, `quotes`
- Macros vectoriales (`\vL`, \`\vomega`, `\vtau`...) para notación limpia
- Formato widescreen `aspectratio=169`
- Fondo de portada generado íntegramente en TikZ

---

### 📚 `notas/` — Documentos tipo libro

Notas de clase en formato `book`, compilables como documento completo:

**`algebra-lineal/`**
- +170 KB de código LaTeX puro
- Tabla de contenidos, capítulos, secciones
- Diagramas conmutativos con `tikz-cd`
- Portada integrada con `pdfpages`
- Macros de notación algebraica (`\rg`, `\Tr`, `\parentesis`, `\corchetes`)

**`fisica-I/`**
- Estructura libro con capítulos por tema
- Figuras externas integradas

---

### 🧮 `tareas/` — Tareas representativas

Una o dos tareas por materia, seleccionadas por riqueza técnica:

| Carpeta | Qué muestra en LaTeX |
|---|---|
| `algebra-lineal/tarea-3` | Uso intensivo de entornos matriciales (`pmatrix`, `bmatrix`, `vmatrix`) — 46 matrices en un solo documento |
| `algebra-lineal/tarea-12` | Combinación de matrices y demostraciones largas con entornos personalizados |
| `calculo-II/tarea-5` | Demostraciones formales largas con `proof`, cajas `mdframed` |
| `calculo-II/tarea-12` | Documento de 500+ líneas, estructura con múltiples ejercicios |
| `calculo-I/tarea-10` | Gráficas con `pgfplots` + `tikzpicture` dentro de soluciones |
| `fisica-I/tarea-3` | Ecuaciones de movimiento, notación vectorial con `physics` |
| `fisica-I/tarea-6` | Tarea más extensa de Física, múltiples problemas |
| `probabilidad/tarea-10` | Tablas de distribuciones, fórmulas de probabilidad |

---

### 🔬 `proyectos/` — Proyectos personales

**`solucionario-calculo-I/`** — Solucionario personal del curso de Cálculo I  
Formato libro, iniciado en vacaciones para reforzar el material. Portada propia.

**`problemas-taller/`** — Problemas de competencia de cálculo  
Documento tipo artículo con problemas y soluciones completas.

**`teoria-analitica-numeros/`** — Notas sobre el libro de Apostol  
Proyecto independiente fuera de la currícula.

---

## 🛠️ Compilar

Todos los documentos usan `pdflatex`. Cada carpeta incluye su propia copia de `ugmath.sty`.

```bash
cd tareas/algebra-lineal/tarea-3
pdflatex tarea3.tex
```

---

## 📬 Contacto

## 📬 Contacto

**GitHub:** [@jayss1e](https://github.com/jayss1e)  
**Instagram:** [@anillo_conmutativo](https://www.instagram.com/anillo_conmutativo)  
**Correo:** ricardoleonmartinez623 [at] gmail.com

---

<div align="center">
  <sub>Hecho con ❤️ y muchas horas de <code>Overfull \hbox</code></sub>
</div>
