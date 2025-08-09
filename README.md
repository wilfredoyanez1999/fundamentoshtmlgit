# Proyecto: Blog de Gatos y Perros

Este proyecto es un blog sencillo que contiene artículos sobre curiosidades de los gatos y los perros. Está estructurado en HTML y utiliza imágenes para ilustrar los artículos.

## Estructura del Proyecto

```
fundamentos_html_git/
├── .gitignore
├── home.html
├── style.css
├── imgenes/
│   └── _SNI2031.avif
```

### Archivos y Carpetas

1. **home.html**  
   Archivo principal del proyecto que contiene el código HTML del blog. Incluye un encabezado, una sección con artículos, y un pie de página.

2. **style.css**  
   Archivo de estilos CSS que define los colores y estilos de los elementos del blog.

3. **imgenes/**  
   Carpeta que contiene las imágenes utilizadas en el blog. Actualmente incluye:
   - `_SNI2031.avif`: Imagen de un gato utilizada en los artículos.

4. **.gitignore**  
   Archivo para ignorar archivos y carpetas específicas en el control de versiones.

## Contenido del Blog

### Artículos
El blog contiene varios artículos sobre curiosidades de los gatos y los perros. Cada artículo incluye:
- Un título.
- Un párrafo introductorio.
- Una imagen ilustrativa.
- Un párrafo adicional con información.

### Imágenes
Las imágenes están ubicadas en la carpeta `imgenes/`. Asegúrate de que las rutas de las imágenes sean correctas para que se muestren adecuadamente en el navegador.

### Estilos
El archivo `style.css` define los estilos del blog:
- Los encabezados (`header` y `h2`) tienen colores específicos.
- Los párrafos con la clase `.texto1` tienen color rojo.
- Los elementos con el ID `#texto2` tienen color púrpura.

## Cómo Visualizar el Proyecto

1. Abre el archivo `home.html` en cualquier navegador web.
2. Asegúrate de que la carpeta `imgenes/` esté en el mismo directorio que el archivo `home.html`.
3. Verifica que el archivo `style.css` esté correctamente enlazado en el `<head>` del documento HTML.

## Notas

- Algunas imágenes tienen rutas incompletas (`imgenes/`). Corrige las rutas si deseas que se muestren correctamente.
- El enlace en el pie de página (`www.infogatos.com`) no incluye el protocolo `http://` o `https://`. Esto puede causar problemas al intentar acceder al enlace.

## Créditos

Proyecto creado por el usuario en el contexto de aprendizaje de fundamentos de HTML
