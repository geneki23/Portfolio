# Portfolio

# Guía de Estilos del Proyecto

## 1. **Colores utilizados**

A continuación, se muestran los códigos de los colores que se utilizan en la web:

- **Color de fondo**: `#ffffff` (Blanco)
- **Color del texto**: `#000000` (Negro)
- **Color de los bordes**: `#000000` (Negro)
- **Color de enlaces**: `#000000` (Negro)
- **Color de enlaces hover**: `#555555` (Gris oscuro)

## 2. **Tipografías**

Las tipografías utilizadas en el proyecto son las siguientes:

- **Tipografía principal**: "Helvetica Neue", Helvetica, Arial, sans-serif
- **Tipografía para los títulos**: "Helvetica Neue", Helvetica, Arial, sans-serif

Estas fuentes se emplean para todos los textos, con un enfoque en mantener la simplicidad y legibilidad del contenido.

## 3. **Logo Personal**



![Logo Personal](icons/logo.png)



## 4. **Librerías Utilizadas**

Para este proyecto se han utilizado las siguientes librerías:

- **Google Fonts**: Para cargar las fuentes "Helvetica Neue" y otras fuentes personalizadas.
- **Normalize.css**: Para garantizar que el diseño se vea consistente en todos los navegadores.

**Enlaces:**
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Normalize.css](https://necolas.github.io/normalize.css/)
- [jQuery](https://jquery.com/) (Si es necesario)

## 5. **Enlaces de Referencia Utilizados**

A continuación, se incluyen los enlaces a los sitios web que se utilizaron para obtener recursos y ejemplos de código que se implementaron en este proyecto:

- [Canva](https://www.canva.com/) - Herramienta de diseño para crear el logo.
- [Unsplash](https://unsplash.com/) - Para encontrar imágenes de alta calidad.
- [Font Awesome Icons](https://fontawesome.com/) - Para íconos utilizados en la página.

## 6. **Problemas Técnicos y Soluciones**

### Problema 1: **No se muestra el favicon en algunos navegadores**
- **Descripción**: Después de agregar el favicon, no se reflejaba en algunos navegadores.
- **Solución**: Se solucionó asegurando que el archivo favicon tenga el formato adecuado `.ico` o `.png`, y añadiendo el enlace correcto en la sección `<head>` del archivo HTML.
  
## Problema 2: La línea de borde no se extiende hasta el final de la pantalla
**Descripción**: En algunas secciones, la línea de borde no llegaba al final de la pantalla.

**Solución**: Aseguramos que el contenedor tuviera un width: 100% y que el border-bottom estuviera aplicado correctamente al elemento deseado. También se ajustó el margin para garantizar que ocupe todo el ancho.