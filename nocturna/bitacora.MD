## MINI RETO 1

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
-------

## MINI RETO 2

- Instalé las dependencias `tailwindcss` y `@tailwindcss/cli` mediante npm.
- Creé la carpeta `src/` y el archivo `input.css`.
- Incorporé `@import "tailwindcss";` como punto de entrada de los estilos.
- Creé el archivo `.gitignore` para excluir la carpeta `node_modules/`.
- Ejecuté Tailwind CLI con la opción `--watch` para generar y actualizar `src/output.css`.
- Creé `index.html` y enlacé el CSS generado.
- Trasladé la sección principal de la campaña Rueda Nocturna al nuevo archivo.
- Construí tres variantes de botones: principal, secundario y de contorno.
- Incorporé estados de interacción `hover` y `focus-visible`.

### Generación de clases CSS

Al revisar `output.css`, comprobé que Tailwind genera los estilos correspondientes a las clases utilizadas en los archivos que analiza.

La clase que utilicé para comprobar la generación fue: **[escribir clase utilizada]**.

La clase que no utilicé y busqué fue: **[escribir clase no utilizada]**.

**Resultado de la comprobación:** [describir qué encontré].

Esto ocurre porque Tailwind analiza los archivos del proyecto e identifica las clases utilizadas para generar únicamente los estilos necesarios.

### Diferencias entre Play CDN y Tailwind CLI

En el ejercicio anterior utilicé Play CDN para incorporar Tailwind directamente desde un script en HTML.

En este ejercicio configuré Tailwind mediante npm y su CLI. Esto permite procesar los estilos y generar un archivo CSS que puede utilizarse en el proyecto sin depender del Play CDN.

### nota

Aprendí a configurar Tailwind CSS mediante npm y su CLI, a generar un archivo CSS de salida y a utilizar clases de utilidad para construir componentes con diferentes estados visuales.

También comprendí la importancia de mantener un indicador de foco visible para facilitar la navegación mediante el teclado.

## MINI RETO 3 

- Creé la sección «Rutas» dentro de `nocturna/index.html`.
- Construí tres tarjetas para presentar las rutas nocturnas de Rueda Libre.
- Incorporé imágenes con ancho completo y altura uniforme.
- Agregué etiquetas para identificar los niveles fácil, medio y difícil.
- Organicé la información de distancia, duración y punto de encuentro mediante elementos de lista descriptiva.
- Destaqué el precio de cada recorrido.
- Reutilicé el estilo del botón principal del Mini Reto 2.
- Apliqué efectos `hover` para modificar la sombra y el borde de las tarjetas sin desplazar su contenido.

### nota

Aprendí a construir tarjetas utilizando utilidades de bordes, sombras, espaciado, tamaños, tipografía y colores de Tailwind CSS.

También comprendí la importancia de mantener una estructura consistente entre componentes y utilizar diferencias visuales y textuales para identificar los niveles de dificultad.

------

## MINI RETO 4 
- Creé `nocturna/componentes.html`.
- Incorporé las tres variantes de botones: principal, secundario y contorno.
- Reutilicé una tarjeta de ruta del Mini Reto 3.
- Construí tres alertas: información, éxito y advertencia.
- Incorporé dos campos de formulario: correo electrónico y número de celular.
- Asocié cada campo con su etiqueta mediante los atributos `for` e `id`.
- Agregué textos de ayuda mediante `aria-describedby`.
- Incorporé estados de foco visibles mediante utilidades de Tailwind.
- Utilicé `role="status"` en la alerta de éxito para facilitar su identificación por tecnologías de asistencia.

### Reglas del kit de diseño

Para mantener la consistencia visual de los componentes establecí las siguientes reglas:

**Paleta de colores**
- Verde Ruta: `#1E7A4F`.
- Naranja Pedal: `#F39A2B`.
- Azul Noche: `#14213D`.
- Crema: `#FAF6EF`.
- Gris Asfalto: `#5B6470`.

**Bordes y formas**
- Botones e inputs: `rounded-xl`.
- Cards: `rounded-2xl`.
- Alertas: `rounded-xl`.
- Bordes definidos mediante utilidades `border`.

**Espaciado**
- Utilicé una escala consistente de espaciado mediante clases como `p-4`, `p-5`, `p-6`, `gap-4` y `space-y-5`.

**Sombras e interacción**
- Sombras iniciales con `shadow-md`.
- Efectos de interacción con `hover:shadow-xl`.
- Estados de foco visibles con `focus-visible:ring-2` y `focus:ring-2`.

### Comparación de enfoques

En Bootstrap se utilizan clases de componentes prediseñados para construir elementos de interfaz. En Tailwind CSS se combinan clases de utilidad para definir directamente los estilos de cada componente.

La configuración mediante CLI permite generar un archivo CSS de salida a partir de las clases identificadas en los archivos del proyecto, sin depender del Play CDN.

### Verificación de generación de clases

Al revisar `src/output.css`, comprobé la generación de las clases utilizadas en los archivos HTML analizados.

También busqué una clase que no estaba utilizando para comprobar que no se generara innecesariamente.

**Clase utilizada:** [completar].

**Clase no utilizada:** [completar].

**Resultado:** [registrar lo observado].

### nota

Aprendí a organizar diferentes componentes en una sola página y a establecer reglas visuales compartidas para mantener la consistencia del diseño.

También reforcé conceptos de accesibilidad mediante etiquetas asociadas, textos de ayuda, roles y estados de foco visibles.

