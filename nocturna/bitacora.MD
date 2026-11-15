## MINI RETO — Prototipo de campaña con Tailwind CSS

**Objetivo:** crear una sección principal para la campaña «Rueda Nocturna» utilizando Tailwind CSS Play CDN y únicamente clases de utilidad.

### Actividades realizadas

- Creé la carpeta `nocturna/` y el archivo `prototipo.html`.
- Incorporé el Play CDN de Tailwind CSS en el documento.
- Construí la sección principal con la etiqueta de campaña «Nuevo · Jueves a sábado».
- Agregué el título principal «Rueda Nocturna» y el subtítulo «Descubre Medellín en bici cuando se encienden las luces».
- Incorporé los dos datos destacados: «3 rutas» y «Desde $55.000».
- Construí el enlace «Inscríbete» con apariencia de botón utilizando clases de Tailwind.
- Apliqué utilidades de espaciado, tamaños, colores y tipografía directamente en las clases del HTML.
- Utilicé la paleta de colores de Rueda Libre para conservar la identidad visual de la marca.
- No utilicé etiquetas `<style>`, atributos `style=""` ni clases de Bootstrap.

### Comparación con Bootstrap (semana 2)

En el ejercicio realizado con Bootstrap construí el botón utilizando clases de componentes prediseñados, por ejemplo `btn btn-primary`. Estas clases permiten aplicar rápidamente una apariencia de botón mediante los estilos que ofrece el framework.

En este ejercicio utilicé Tailwind CSS para construir el enlace «Inscríbete» combinando diferentes clases de utilidad:

- `bg-[#F39A2B]`: establece el color de fondo naranja.
- `text-[#14213D]`: establece el color del texto.
- `px-8`: agrega espacio horizontal.
- `py-4`: agrega espacio vertical.
- `rounded-xl`: redondea las esquinas.
- `font-bold`: aplica negrita al texto.

### Diferencia clave entre Bootstrap y Tailwind

Bootstrap es un framework orientado a componentes prediseñados, mientras que Tailwind utiliza un enfoque *utility