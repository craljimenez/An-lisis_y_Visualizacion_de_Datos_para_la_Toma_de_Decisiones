# Contenido del curso — Análisis de Datos y Visualización de Datos para la Toma de Decisiones

Repositorio del material de clase (Esumer / Estud-IA, cohorte 20262).

## Estructura

- [`cronograma.md`](./cronograma.md) — plan semana a semana / clase por clase.
- `clases/` — una carpeta por sesión, con la fuente `.tex` de las
  diapositivas, el PDF compilado y, según la clase, el material de la hora
  de práctica: cuadernos de Jupyter (`notebooks/*.ipynb`) o un taller en PDF
  (`taller-*.tex`/`.pdf`, con sus datos en `datos/*.csv`).

> La plantilla LaTeX (`plantilla/`) vive **fuera** de este repositorio, un
> nivel arriba (`../plantilla/`), porque es el tema reutilizable y no es
> contenido propio de una cohorte. Ver [`../plantilla/README.md`](../plantilla/README.md)
> para el flujo de compilación.

```
clases/
└── semanaNN-claseMM-slug/
    ├── semanaNN-claseMM.tex
    ├── semanaNN-claseMM.pdf
    ├── notebooks/        (si la práctica es un cuaderno Jupyter)
    │   └── *.ipynb
    ├── taller-*.tex       (si la práctica es un taller en PDF)
    ├── taller-*.pdf
    └── datos/
        └── *.csv
```

## Qué se sube al repositorio

Por clase, **solo**: la fuente `.tex` (de las diapositivas y del taller, si
lo hay), los `.pdf` compilados, los `.ipynb` en `notebooks/` (si aplica) y
los `.csv` en `datos/` (si aplica). Nada de auxiliares de compilación
(`.aux`, `.log`, `.nav`, `.out`, `.snm`, `.toc`, `.fls`, `.fdb_latexmk`,
`.synctex.gz`, `missfont.log`) ni `.ipynb_checkpoints/` — ya están excluidos
en [`.gitignore`](./.gitignore), pero conviene revisar `git status` antes de
cada commit para confirmar que no se cuele ninguno.

## Progreso

| Semana | Clase | Tema | Estado |
|---|---|---|---|
| 1 | 1 | Encuentro Inicial (incluye panorama del ecosistema de datos) | ✅ listo |
| 1 | 2 | Fundamentos de estadística descriptiva | ✅ listo |

(Se va actualizando a medida que se preparan las demás clases —
ver el detalle completo en `cronograma.md`.)
