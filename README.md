# GAD-2401 · Tema 1: Datos y su preprocesamiento

Sitio didáctico de la asignatura **Análisis y visualización de datos** (clave **GAD-2401**), carrera de Ingeniería Informática · TecNM / TESCHA.

Es un sitio **estático** (HTML + CSS). No requiere Node ni base de datos: se abre en el navegador o se publica en GitHub Pages.

## Contenido

| Página | Tema |
|--------|------|
| [index.html](index.html) | Portada, objetivos y mapa del tema |
| [conjuntos.html](conjuntos.html) | 1.1 Conjunto de datos (volumen, variedad, velocidad) |
| [relaciones.html](relaciones.html) | 1.2 Relaciones, matrices y medidas de similitud (fórmulas con KaTeX) |
| [preprocesamiento.html](preprocesamiento.html) | 1.3 Preprocesamiento |
| [caso-practico.html](caso-practico.html) | 1.4 Caso práctico con Python / Pandas |
| [ventas_raw.csv](ventas_raw.csv) | Dataset sucio para el ejercicio de limpieza |

## Cómo verlo en tu computadora

1. Descarga o clona este repositorio.
2. Abre `index.html` con el navegador (doble clic).

O, si tienes Python:

```bash
python3 -m http.server 8080
```

Luego visita `http://localhost:8080`.

## Cómo subirlo a GitHub

En la carpeta del proyecto:

```bash
git init
git add .
git commit -m "Tema 1: Datos y preprocesamiento — GAD-2401"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/gad2401-tema1.git
git push -u origin main
```

Crea antes el repositorio vacío en GitHub (sin README, para evitar conflictos).

## Publicar en GitHub Pages (sitio web público)

1. En el repositorio: **Settings → Pages**.
2. **Build and deployment → Source:** Deploy from a branch.
3. **Branch:** `main` / carpeta `/ (root)`.
4. Guarda. En uno o dos minutos el sitio queda en:

`https://TU_USUARIO.github.io/gad2401-tema1/`

## Estructura

```
gad2401-tema1/
├── README.md
├── LICENSE
├── .gitignore
├── index.html
├── conjuntos.html
├── relaciones.html
├── preprocesamiento.html
├── caso-practico.html
└── assets/
    ├── styles.css
    └── favicon.svg
```

Las fórmulas de 1.2 se renderizan con [KaTeX](https://katex.org/) (CDN).

## Licencia

MIT. El contenido académico se basa en el programa de la asignatura GAD-2401 (TecNM).
