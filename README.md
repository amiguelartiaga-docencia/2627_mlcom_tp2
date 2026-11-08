# Trabajo práctico 2 — CLIP, detección de caras y biometría facial

Álbum fotográfico **100 % sintético** (personas ficticias generadas por IA) para practicar búsqueda texto→imagen con CLIP, detección de caras y verificación/identificación facial.

## Contenido

- `img/fotos/`: las 100 fotos del álbum (JPEG con EXIF de cámara, fecha, orientación y, en algunas, GPS).
- `img/identidades/`: una imagen de enrolamiento por cada uno de los 25 personajes (`nombre_apellido.jpg`).
- `img/identidades_todos.jpg`: mosaico con los 25 personajes y su nombre.
- `notebooks/`: ejemplos de partida, listos para abrir en Google Colab.

| Cuaderno | Qué muestra | Colab |
|---|---|---|
| `ejemplo1_openclip.ipynb` | Embeddings de texto e imagen con OpenCLIP y matriz de similitud | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amiguelartiaga-docencia/2627_mlcom_tp2/blob/main/notebooks/ejemplo1_openclip.ipynb) |
| `ejemplo2_retinaface.ipynb` | Detección de caras con RetinaFace: tabla de cajas y dibujo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amiguelartiaga-docencia/2627_mlcom_tp2/blob/main/notebooks/ejemplo2_retinaface.ipynb) |
| `ejemplo3_biometria.ipynb` | Verificación facial con ArcFace: score target y non target | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amiguelartiaga-docencia/2627_mlcom_tp2/blob/main/notebooks/ejemplo3_biometria.ipynb) |

Cada cuaderno instala lo que necesita y clona este repositorio, así que funciona aunque se suba suelto a Colab.
