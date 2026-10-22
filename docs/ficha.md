# Ficha personalizada – N.º 24

## Datos de la ficha

| Campo | Requisito |
|---|---|
| N.º de lista | 24 |
| Temática | Cafetería local |
| Campo especial del formulario | Rango numérico (`input type="range"`) |
| Breakpoint principal | 720 px |
| Restricción especial | Hoja de estilos para impresión que oculte la navegación y el formulario |

## Descripción del proyecto

La página web representa una cafetería local llamada Cafetería Esquina. Presenta información general, un menú con productos y precios, información del horario y un formulario para realizar pedidos.

## Requisitos base

### 1. Estructura HTML

Se utilizan los elementos semánticos `header`, `nav`, `main`, `section`, `aside` y `footer`. Los encabezados organizan el contenido por secciones.

### 2. Formulario

El formulario incluye campos para nombre, correo electrónico, teléfono, hora de retiro, cantidad de personas, selección de productos e intensidad del café.

Se utilizan etiquetas `label`, agrupaciones `fieldset` y `legend`, y validaciones nativas como `required`, `pattern`, `min` y `max`.

### 3. Tabla

La tabla presenta los productos, sus descripciones y sus precios. Incluye `caption`, `thead`, `tbody` y encabezados con `scope="col"` y `scope="row"`.

### 4. Diseño adaptable

Se utiliza CSS Grid para organizar el contenido principal y Flexbox para distribuir los enlaces de navegación. El diseño cambia cuando el ancho de pantalla es de 720 px o menos.

### 5. Colores

Los colores se definen mediante variables CSS, por ejemplo `--color-fondo`, `--color-texto`, `--color-principal` y `--color-borde`. Se debe comprobar que el contraste del texto normal sea de al menos 4.5:1.

### 6. Accesibilidad

Los campos del formulario tienen etiquetas asociadas. La tabla identifica sus encabezados y la imagen del logotipo incluye texto alternativo. Se debe comprobar que todos los elementos interactivos tengan un indicador de foco visible al navegar con el teclado.

### 7. Restricción especial de impresión

La regla `@media print` oculta la navegación y la sección del pedido al imprimir o guardar la página como PDF. También cambia el fondo a blanco, el texto a negro y el diseño principal a una sola columna.

### 8. Validación

- HTML: https://validator.w3.org/
- CSS: https://jigsaw.w3.org/css-validator/

Antes de entregar, se deben corregir los errores detectados por ambos validadores y comprobar que la página no tenga desplazamiento horizontal en una pantalla de 360 px.