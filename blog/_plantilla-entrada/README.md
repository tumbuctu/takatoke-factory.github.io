# Plantilla de entrada de blog

Duplica esta carpeta cuando quieras crear una entrada nueva:

```txt
blog/nombre-de-la-entrada/
```

Dentro de la nueva carpeta:

- Edita `entry.json`.
- Cambia `slug` para que coincida con el nombre de la carpeta.
- Pon `published` en `true` cuando quieras que aparezca en la web.
- Si la entrada tiene imagenes, colocalas en `images/` y anadelas en `images` dentro del JSON.
- Si no tiene imagenes, deja `"images": []`.

Cuando termines, dime:

```txt
Actualiza la pagina de blog con los json de entradas de blog nuevos.
```

Yo revisare las carpetas publicadas, validare rutas e integrare las entradas en `blog.html`.
