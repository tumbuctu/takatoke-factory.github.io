# Plantilla de app

Duplica esta carpeta y cambia el nombre por el slug de tu app, por ejemplo:

```txt
apps/mi-app/
```

Dentro de la nueva carpeta:

- Cambia los textos de `app.json`.
- Sustituye `icon.png` por el icono real de la app en 1024x1024.
- Coloca capturas con nombres simples: `01.png`, `02.png`, `03.png`.
- Si una app no existe para una plataforma, borra esa plataforma de `platforms` en `app.json`.
- Si no tienes Mac App Store, deja `"macAppStore": ""`.

Estructura esperada:

```txt
apps/mi-app/
├── app.json
├── icon.png
├── index.html
├── ios/
│   ├── es/
│   └── en/
├── ipados/
│   ├── es/
│   └── en/
└── macos/
    ├── es/
    └── en/
```

Cuando termines una app nueva, dime:

```txt
Revisa la carpeta apps y añade las apps nuevas a la web.
```

Yo leeré los `app.json`, comprobaré las imágenes y actualizaré `index.html` y las páginas individuales.
