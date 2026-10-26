# website_analysis_about_ia
El impacto de la Inteligencia Artificial
Sitio web informativo sobre la Inteligencia Artificial (IA), sus principales aplicaciones, ventajas y desafíos. Incluye una segunda página con un formulario para que las personas compartan su opinión sobre el futuro de la IA.
Contenido del proyecto
- index.html: página principal con una introducción a la IA, sus aplicaciones y sus ventajas y desafíos.
- formulario.html: formulario para ingresar nombre, correo electrónico, percepción sobre el futuro de la IA y comentarios.
- noticias.html: pagina con recoleccion de noticias relevantes de analisis sobre la IA y su impacto.
- README.md: documentación del proyecto.
Si guardaste los archivos con los nombres index_semantico.html y formulario_semantico.html, actualizá los enlaces entre páginas o renombrá los archivos para que coincidan con los nombres indicados arriba.

Tecnologías utilizadas
- HTML5: estructura y contenido de las páginas.
- CSS: estilos visuales integrados dentro de los documentos HTML.
- HTML semántico: uso de elementos como header, main, section, nav y footer para describir las regiones y la organización del contenido.
No se necesita instalar dependencias para abrir el sitio localmente.
Cómo ejecutar el sitio
1. Descargá o cloná este repositorio.
2. Comprobá que index.html y formulario.html estén en la misma carpeta.
3. Abrí index.html en un navegador.
4. Usá el enlace de la página principal para entrar al formulario y el enlace del formulario para volver al inicio.
También podés publicar el proyecto con GitHub Pages desde la configuración del repositorio, si los archivos están en la ubicación que GitHub Pages utiliza para publicar el sitio.
¿Qué aporta el HTML semántico a la usabilidad?
El HTML semántico utiliza elementos que describen el propósito de cada región del documento, en lugar de depender únicamente de contenedores genéricos como div.

En este proyecto:
- header identifica el encabezado de cada página.
- main delimita el contenido principal.
- section agrupa contenido relacionado por tema.
- nav identifica los enlaces de navegación entre páginas.
- footer contiene la información del pie de página.
- Los encabezados (h1, h2) organizan el contenido por niveles.
- Las etiquetas label asociadas a los campos del formulario ayudan a identificar qué información debe ingresar la persona.
- Los atributos required permiten que el navegador compruebe que ciertos campos estén completos antes de enviar el formulario.
Estas decisiones pueden mejorar la usabilidad y la accesibilidad, porque hacen que la estructura sea más clara para las personas, los lectores de pantalla y otras herramientas. También facilitan el mantenimiento del código.

El HTML semántico no cambia automáticamente la apariencia visual ni garantiza mejores posiciones en buscadores. La experiencia final también depende del CSS, de la claridad del contenido, de la navegación y de que los controles funcionen correctamente.
Accesibilidad y alcance
- Se declara el idioma del documento mediante lang="es".
- Se incluye la configuración de caracteres UTF-8 y la etiqueta viewport para adaptar la página al ancho del dispositivo.
- Los campos del formulario tienen etiquetas asociadas.
- Los enlaces permiten moverse entre la página principal y el formulario.
- El formulario usa action="#" como marcador de posición: por sí solo, no guarda ni envía los datos a una base de datos o a un servicio externo. Para recibir respuestas reales, hace falta configurar un servidor o integrar un servicio de formularios.
Posibles mejoras futuras
- Separar los estilos CSS en un archivo independiente, por ejemplo styles.css.
- Añadir pruebas de accesibilidad y verificar el contraste de colores.
- Configurar un destino real para el formulario y definir cómo se protegerán los datos personales.
- Revisar el sitio en distintos tamaños de pantalla y navegadores.
- Validar el HTML con un validador de estándares web.
Estado del proyecto
Proyecto estático de carácter informativo y educativo. No requiere un proceso de compilación.
