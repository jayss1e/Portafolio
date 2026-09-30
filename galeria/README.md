# 🎨 Galería de figuras

**215 figuras** hechas en TikZ, PGFPlots y tikz-cd, organizadas por materia. Todas son archivos `standalone`: cada `.tex` compila por sí solo y produce un `.pdf` vectorial que después se integra en las notas con `\includegraphics`.

📄 **[`catalogo.pdf`](catalogo.pdf)**: todas las figuras en un solo documento, generado con LaTeX (`catalogo.tex`).

| Materia | Figuras | Técnicas |
|---|---:|---|
| [Cálculo I](calculo-I/README.md) | 81 | PGFPlots + paquete propio `graficas.sty` |
| [Termodinámica](termodinamica/README.md) | 45 | TikZ, `patterns`, `decorations`, `\addplot3` |
| [Álgebra Lineal II](algebra-lineal-II/README.md) | 32 | TikZ 2D/3D, tikz-cd, PGFPlots |
| [Teoría analítica de números](teoria-numeros/README.md) | 21 | contornos, `\foreach`, `decorations.markings` |
| [Funciones trigonométricas e inversas](trigonometricas-inversas/README.md) | 12 | PGFPlots, ticks en π |
| [Lógica](logica/README.md) | 10 | grafos, árboles, `positioning` |
| [Álgebra Lineal I](algebra-lineal-I/README.md) | 7 | tikz-cd |
| [Variable compleja](variable-compleja/README.md) | 7 | TikZ, `angles`, `patterns` |

## Compilar una figura

```bash
cd galeria/termodinamica
pdflatex plano-S0.tex
```

Las figuras de `calculo-I/` necesitan `graficas.sty`, que está en la misma carpeta.

Para regenerar el catálogo: `cd galeria && pdflatex catalogo.tex` (dos veces, para el índice).
