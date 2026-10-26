# Ficha de respuesta a la auditoría web

**Proyecto:** Cafetería del Parque 
**Archivos revisados:** `index.html` y `css/estilos.css`

## 1. Hallazgos aceptados

### Hallazgo 1. Estructura del contenido principal
**Decisión:** Aceptado.

**Justificación:** El formulario estaba fuera de `<main>`. Se incluirá dentro del contenido principal para mejorar la estructura del HTML.

### Hallazgo 2. Agrupación de los productos
**Decisión:** Aceptado.

**Justificación:** Los productos y las preferencias estaban en el mismo grupo. Se separarán en distintos `<fieldset>` con sus respectivos `<legend>`.

### Hallazgo 3. Instrucciones del teléfono y de la intensidad
**Decisión:** Aceptado.

**Justificación:** Se agregarán instrucciones visibles para el teléfono y una descripción de la escala de intensidad, mostrando también el valor seleccionado.

### Hallazgo 5. Inconsistencia en el nombre de la cafetería
**Decisión:** Aceptado.

**Justificación:** Se unificará el nombre como «Cafetería Esquina» en el título y el pie de página. También se ajustará el texto alternativo del logo.

## 2. Hallazgos no aceptados

### Hallazgo 4. Enlace para saltar al contenido y tamaño de las áreas interactivas
**Decisión:** No aceptado.

**Justificación:** La página ya cuenta con un menú de navegación que permite dirigirse a Inicio, Menú y Pedido. Se conservarán la navegación y los tamaños actuales de los controles para mantener el diseño original.

### Hallazgo 6. Variables CSS y contraste de colores
**Decisión:** No aceptado.

**Justificación:** Se conservarán los colores y las variables actuales para mantener la apariencia visual del proyecto.

### Hallazgo 7. Enfoque mobile-first
**Decisión:** No aceptado.

**Justificación:** Se mantendrá el diseño adaptable actual, con dos columnas en pantallas grandes y una columna en pantallas de hasta 720 píxeles.

## 3. Conclusión

Se aceptan cuatro hallazgos y no se aceptan tres. Los cambios aceptados buscan mejorar la estructura del HTML, la organización del formulario, la claridad de las instrucciones y la consistencia del nombre del negocio. Los demás aspectos se mantendrán según las decisiones tomadas para esta versión del proyecto.