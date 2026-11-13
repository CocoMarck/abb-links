Crea una página web de reclutamiento tipo "menú de enlaces" (formato vertical, optimizado para móvil) para la empresa ABB en México.

### Reglas de desarrollo:
- Usa **full Bootstrap 5** como base para toda la estructura, distribución, espaciados y tipografía responsiva.
- Mantén el CSS personalizado al mínimo indispensable (únicamente para los colores corporativos, efectos al pasar el cursor y elementos fijos que Bootstrap no resuelva de forma nativa).
- **Regla obligatoria:** Si incluyes cualquier recurso o estilo externo adicional a Bootstrap (por ejemplo, fuentes de Google Fonts), debes documentarlo explícitamente con un comentario en el código explicando qué es y para qué se usa.

### Diseño y experiencia visual:
- Fondo gris muy claro con todo el contenido centrado en pantalla dentro de un contenedor estrecho tipo tarjeta móvil.
- En la esquina superior derecha debe ir fijo el logotipo en SVG de ABB (`./icons/abb-logo.svg`), discreto y adaptable a pantallas pequeñas.
- Encabezado principal llamativo con el texto **"RECLUTAMIENTO ABB"** en color rojo corporativo.
- Paleta limpia: tarjetas y botones blancos con bordes sutiles, esquinas redondeadas y sombra ligera. Al pasar el cursor sobre los botones, deben iluminarse en rojo corporativo con texto blanco y una ligera elevación.

### Contenido y datos reales a incluir:
1. **Sección "Vacantes Disponibles":** Una caja blanca con la lista de los siguientes puestos (marcados con palomita verde):
   - Ayudante General
   - Ayudante General (Fin de semana)
   - Materialista
   - Inspector de Calidad
   - Coordinador de Almacén
   - Entrenador
   - Facilities
   - Técnico Eléctrico

2. **Sección de Contacto:** El llamado a la acción *"¡Contáctenos y agenda tu entrevista!"* seguido de botones independientes que abran en una pestaña nueva con el ícono de WhatsApp (`./icons/whatsapp-logo-bold-svgrepo-com.svg`):
   - **RECLUTAMIENTO Y VACANTES APODACA:** +52 81 8254 7528 (enlace directo a WhatsApp)
   - **RECLUTAMIENTO JUÁREZ:** +52 81 1690 3357 (enlace directo a WhatsApp)
   - **VACANTES JUÁREZ:** +52 81 1801 6792 (enlace directo a WhatsApp)
   - **Visitar Página Web:** Enlace directo a `https://new.abb.com/mx`

3. **Pie de página:** Aviso discreto de derechos con el año 2026 y "Enlaces de Contacto".

Encárgate tú de toda la arquitectura, clases, estilos y entrega los archivos listos para usar.