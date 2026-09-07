# Plantilla LaTeX — Análisis y Visualización de Datos (Esumer / Estud-IA)

Tema de Beamer con la identidad visual tomada de
`../../Plantilla presentación Estud-IA y ESUMER.pptx`: azul institucional
(`#262E66`), bloque geométrico teal/azul cielo y acento naranja de Estud-IA.

## Archivos

- `beamerthemeesumer.sty` — el tema (colores, tipografía, portada, encabezado
  de diapositiva, pie de página). No se edita por clase.
- `clase-template.tex` — plantilla de una sesión. Se copia una vez por clase.
- `assets/esumer-logo.png` / `assets/esumer-logo-white.png` — logo institucional
  (versión oscura y versión blanca para fondos navy).

## Convención de carpetas (ver [`../cronograma.md`](../cronograma.md))

Cada clase vive en su propia carpeta dentro de `../clases/`, con el PDF, la
fuente `.tex` y (si aplica) los cuadernos de Jupyter que se usan en esa
sesión:

```
Contenido_Curso/
├── plantilla/                 (este tema, no se toca por clase)
├── cronograma.md
└── clases/
    └── semanaNN-claseMM-slug/
        ├── semanaNN-claseMM.tex
        ├── semanaNN-claseMM.pdf
        └── notebooks/          (solo si la sesión usa Google Colab/Jupyter)
            └── *.ipynb
```

## Flujo de trabajo por clase

1. Crear la carpeta de la clase y copiar la plantilla:

   ```bash
   mkdir -p clases/semanaNN-claseMM-slug
   cp plantilla/clase-template.tex clases/semanaNN-claseMM-slug/semanaNN-claseMM.tex
   ```

2. Editar en ese archivo el bloque **DATOS DE LA CLASE**
   (`\title`, `\subtitle`, `\author`, `\date`, `\setmodulo`, `\setsemana`,
   `\setclase`, `\setfechaclase`, `\setmodalidad`) usando la fila
   correspondiente de [`../cronograma.md`](../cronograma.md).

3. Compilar **siempre con `xelatex` (o `lualatex`)**, nunca `pdflatex`, porque
   el tema usa `fontspec`. Compilar **dos veces**: la primera pasada calcula
   las posiciones de los elementos de fondo (portada, franja del título) y la
   segunda las coloca correctamente.

   Desde la raíz de `Contenido_Curso/` (para que `plantilla/assets/...` se
   resuelva bien), guardando la salida en la propia carpeta de la clase:

   ```bash
   TEXINPUTS=".:plantilla:$TEXINPUTS" xelatex -output-directory=clases/semanaNN-claseMM-slug clases/semanaNN-claseMM-slug/semanaNN-claseMM.tex
   TEXINPUTS=".:plantilla:$TEXINPUTS" xelatex -output-directory=clases/semanaNN-claseMM-slug clases/semanaNN-claseMM-slug/semanaNN-claseMM.tex
   ```

4. Si la sesión tiene laboratorio/taller en Python, agregar el o los
   cuadernos en `clases/semanaNN-claseMM-slug/notebooks/*.ipynb`.

## Fuente

El tema intenta usar la tipografía oficial (`Aptos` / `Aptos Display`). Si no
está instalada en el equipo, usa automáticamente `Lato` como alternativa de
aspecto similar. Para usar Aptos, instalar las fuentes (p. ej. desde un
paquete de Office) en `~/.local/share/fonts` y volver a compilar.

## Personalización rápida

- Colores: editar las líneas `\definecolor{esumer...}` en
  `beamerthemeesumer.sty`.
- Motivo geométrico de la portada: bloque `\setbeamertemplate{title page}` en
  el mismo archivo (usa coordenadas relativas a la esquina superior derecha).
- Para una diapositiva separadora de sección dentro de una clase:

  ```latex
  \begin{frame}[plain]
    \sectionpage
  \end{frame}
  ```
