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

------

## MINI RETO 5

- Organicé la landing con etiquetas semánticas como `header`, `main`, `section` y `footer`.
- Construí un encabezado con el nombre de la marca, enlaces de navegación y botón de inscripción.
- Conservé la sección principal de la campaña Rueda Nocturna.
- Organicé las tres tarjetas de rutas en una cuadrícula de tres columnas.
- Incorporé la sección «¿Cómo funciona?» con cuatro pasos.
- Construí una franja de inscripción para invitar a los visitantes a explorar las rutas.
- Organicé el pie de página en tres bloques de contenido.
- Utilicé enlaces internos mediante identificadores `id` para conectar las secciones.
- Reutilicé las clases de los botones y las tarjetas del kit de componentes.

### Decisiones de layout

Para distribuir las tarjetas de las rutas utilicé CSS Grid mediante Tailwind, con `grid-cols-3` y `gap-6`. Esta distribución permite presentar las tres rutas en columnas iguales y mantener una separación uniforme.

Para los cuatro pasos de «¿Cómo funciona?» también utilicé Grid, mediante `grid-cols-4` y `gap-6`, porque los elementos tienen una estructura similar y deben distribuirse de manera uniforme.

En el encabezado y el pie de página utilicé Flexbox porque necesitaba organizar los elementos horizontalmente y controlar su alineación mediante `justify-between` e `items-center`.

### nota

Aprendí a combinar Grid y Flexbox para construir diferentes distribuciones dentro de una misma página. También reforcé el uso de etiquetas semánticas, contenedores compartidos y enlaces internos para organizar la navegación.

-------

## MINI RETO 6 

### Problemas identificados en la versión de escritorio

- La distribución de tres tarjetas en una fila no era adecuada para pantallas pequeñas.
- Los cuatro pasos necesitaban una distribución más flexible.
- El encabezado requería una organización diferente en celulares.
- Los textos y espacios necesitaban ajustes para evitar que el contenido se comprimiera.
- La información de las tarjetas necesitaba reorganizarse para facilitar su lectura.

### Cambios realizados

- Adapté el encabezado para que sus elementos se apilen en celular y se organicen horizontalmente desde `md`.
- Oculté los enlaces de navegación en celulares y mantuve visible el botón «Inscríbete».
- Organicé las tarjetas de rutas con una columna por defecto, dos columnas desde `sm` y tres desde `lg`.
- Organicé los cuatro pasos con una columna por defecto, dos desde `sm` y cuatro desde `lg`.
- Ajusté tamaños de títulos, rellenos y espacios entre elementos mediante prefijos responsive.
- Organicé la franja de inscripción y el pie de página para adaptarse a diferentes anchos.

### nota

Aprendí a trabajar con el enfoque mobile-first de Tailwind CSS, estableciendo primero los estilos para celulares y utilizando los prefijos `sm:`, `md:` y `lg:` para modificar la distribución en pantallas más grandes.

--------

## MINI RETO 7

- Definí los seis colores de marca mediante variables `--color-*` dentro de `@theme`.
- Incorporé las familias tipográficas Montserrat y Open Sans desde Google Fonts.
- Reemplacé los colores genéricos de Tailwind por las utilidades personalizadas de la marca.
- Apliqué las fuentes de marca a títulos y textos.
- Incorporé variantes `dark:` para adaptar fondos, textos, tarjetas, bordes y campos de formulario.
- Utilicé la preferencia de color del sistema para activar el modo oscuro.
- Revisé las combinaciones de colores mediante criterios de contraste WCAG.

### Paleta de marca

| Color | Código |

| Verde Ruta | #1E7A4F |
| Naranja Pedal | #F39A2B |
| Azul Noche | #14213D |
| Crema | #FAF6EF |
| Gris Asfalto | #5B6470 |
| Amarillo Farol | #FFD166 |

### Decisiones de accesibilidad

Identifiqué que Verde Ruta y Gris Asfalto sobre Azul Noche no alcanzan el contraste mínimo de 4.5:1 para texto normal.

Por esta razón, utilicé Crema y Amarillo Farol como colores de texto sobre fondos oscuros y mantuve el Verde Ruta para elementos donde ofrece suficiente contraste.

### nota

Aprendí a personalizar el tema de Tailwind CSS mediante `@theme`, generar utilidades propias y utilizar Google Fonts. También comprendí cómo implementar el modo oscuro con `dark:` y la importancia de comprobar el contraste para garantizar la legibilidad.

------

## Mini Reto 8

- Revisé las clases utilizadas en los elementos de la landing para identificar estilos repetidos.
- Identifiqué los botones como elementos prioritarios para la reutilización de estilos.
- Creé las clases personalizadas `btn-primary` y `btn-highlight` mediante `@apply`, dentro de `@layer components`.
- Actualicé el HTML para utilizar estas clases en los botones, manteniendo las clases de espaciado particulares.
- Conservé la estructura de las tarjetas y las secciones para evitar crear componentes personalizados innecesarios.
- Organicé las clases siguiendo categorías: layout, espaciado, tipografía, color y estados.
- Conservé la paleta de marca, las fuentes personalizadas, el diseño responsive y las variantes de modo oscuro.

## nota
Este reto me permitió comprender la importancia de escribir código más limpio y reutilizable. Aprendí que @apply puede ayudar a reducir la repetición de clases en elementos frecuentes, como los botones, sin necesidad de convertir toda la interfaz en componentes personalizados.

También reforcé la importancia de medir el rendimiento de los recursos antes de recomendar una tecnología para un proyecto.

-----
# MINI RETO 9

Se agregó una nueva sección de inscripción a la landing, organizada en cuatro grupos mediante las etiquetas `<fieldset>` y `<legend>`:

- **Datos personales:** nombre completo, correo electrónico y celular.
- **Detalles de la ruta:** ruta seleccionada, día de salida y número de acompañantes.
- **Experiencia y equipo:** nivel de experiencia y disponibilidad de bicicleta propia.
- **Confirmación:** aceptación de las condiciones de participación.

Se utilizaron diferentes controles HTML según el tipo de información: `input`, `select`, `radio` y `checkbox`. Cada campo quedó asociado con su respectiva etiqueta mediante `label`, `for` e `id`.

### Validaciones implementadas
Se utilizaron atributos de validación nativa:

- `required`: todos los campos son obligatorios.
- `minlength="3"`: el nombre debe tener mínimo tres caracteres.
- `pattern="3[0-9]{9}"`: el celular debe tener diez dígitos y comenzar por 3.
- `maxlength="10"`: limita la longitud del celular.
- `type="email"`: comprueba el formato del correo electrónico.

También se agregó JavaScript con `checkValidity()` y `preventDefault()` para validar el formulario y mostrar un mensaje de confirmación visual.

El formulario permite validar los datos directamente en el navegador y mostrar una confirmación visual. Por ahora, no está conectado a un servidor ni almacena o transmite las inscripciones.

### nota
Durante este reto reforcé el uso de formularios semánticos en HTML, la asociación entre etiquetas y controles, y las validaciones nativas. También comprendí cómo complementar HTML con JavaScript para controlar la respuesta visual del formulario y mejorar la experiencia del usuario.

-------

