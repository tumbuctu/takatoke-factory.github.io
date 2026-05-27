# Blog de Takatoke Factory

Cada entrada vive en su propia carpeta:

```txt
blog/
├── _plantilla-entrada/
│   ├── entry.json
│   └── images/
└── mi-entrada/
    ├── entry.json
    └── images/
```

Campos principales de `entry.json`:

- `slug`: nombre tecnico de la entrada y de la carpeta.
- `type`: categoria visible, traducida a espanol e ingles.
- `date`: fecha en formato `YYYY-MM-DD`.
- `title`: titulo en espanol e ingles.
- `summary`: resumen corto para la tarjeta del blog.
- `content`: texto completo para una futura pagina individual o modal.
- `apps`: apps relacionadas.
- `tags`: etiquetas en espanol e ingles.
- `images`: lista de imagenes opcionales.
- `published`: `true` para publicar, `false` para mantener como borrador.

Las imagenes se guardan dentro de la carpeta de cada entrada, por ejemplo:

```txt
blog/mi-entrada/images/01.png
```
