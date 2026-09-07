# Contenido del curso — Análisis de Datos y Visualización de Datos para la Toma de Decisiones

Repositorio del material de clase (Esumer / Estud-IA, cohorte 20262).

## Estructura

- [`cronograma.md`](./cronograma.md) — plan semana a semana / clase por clase.
- `clases/` — una carpeta por sesión, con la fuente `.tex`, el PDF compilado
  y, cuando aplica, los cuadernos de Jupyter (`notebooks/*.ipynb`) usados en
  esa clase.

> La plantilla LaTeX (`plantilla/`) vive **fuera** de este repositorio, un
> nivel arriba (`../plantilla/`), porque es el tema reutilizable y no es
> contenido propio de una cohorte. Ver [`../plantilla/README.md`](../plantilla/README.md)
> para el flujo de compilación.

```
clases/
└── semanaNN-claseMM-slug/
    ├── semanaNN-claseMM.tex
    ├── semanaNN-claseMM.pdf
    └── notebooks/
        └── *.ipynb
```

## Qué se sube al repositorio

Por clase, **solo**: la fuente `.tex`, el `.pdf` compilado y (si aplica) los
`.ipynb` en `notebooks/`. Nada de auxiliares de compilación (`.aux`, `.log`,
`.nav`, `.out`, `.snm`, `.toc`, `.fls`, `.fdb_latexmk`, `.synctex.gz`,
`missfont.log`) ni `.ipynb_checkpoints/` — ya están excluidos en
[`.gitignore`](./.gitignore), pero conviene revisar `git status` antes de
cada commit para confirmar que no se cuele ninguno.

## Progreso

| Semana | Clase | Tema | Estado |
|---|---|---|---|
| 1 | 1 | Encuentro Inicial | ✅ listo |
| 1 | 2 | MasterClass (Nivelación) — panorama del ecosistema de datos | ✅ listo |

(Se va actualizando a medida que se preparan las demás clases —
ver el detalle completo en `cronograma.md`.)
