# Checklist de tareas para el desarrollo de proyectos y tareas

Este checklist establece una serie de pasos estructurados para llevar a cabo tareas y proyectos de desarrollo web de manera eficiente y consistente. Está diseñado para ayudar al equipo a asegurar que cada solicitud o proyecto sea abordado con claridad, siguiendo buenas prácticas de codificación, optimización y asegurando la calidad del código en cada etapa. Fomenta el uso de herramientas colaborativas como GitHub y la revisión entre compañeros, lo que facilita la homologación del proceso y mejora la legibilidad, funcionalidad y tiempos de entrega.

1. **Analizar la petición**

   - Revisa el requerimiento con atención para comprender el objetivo del proyecto y/o solicitud.  
     **Ejemplo**: Si se solicita un nuevo formulario, verifica las especificaciones de diseño y funcionalidad.

2. **Consultar al equipo que realizó la solicitud en caso de dudas**

   - Si algo no está claro, pide más detalles al equipo que hizo la solicitud antes de comenzar.  
     **Ejemplo**: ¿Qué funcionalidad específica debe tener el botón de “Ver más”?

3. **Verificar con el equipo de desarrollo si ya se ha trabajado en algo similar**

   - Si el desarrollo es complejo, pregunta al equipo si existe algún trabajo previo que puedas reutilizar o mejorar.  
     **Ejemplo**: Antes de crear un 360 de un vehículo, verifica si ya hay una implementación previa en otro proyecto que se pueda adaptar.

4. **Buscar información de forma autónoma**

   - Investiga soluciones por tu cuenta antes de depender del equipo, ya que mayormente el equipo se encuentra generando soluciones para otros proyectos.
   - Utiliza herramientas de IA como ChatGPT para acelerar la resolución de problemas.  
     **Ejemplo**: "¿Cómo puedo hacer que un modal en Bootstrap sea accesible?"

5. **Verificar si existe una página de pruebas en el CMS**

   - Antes de realizar cambios, asegúrate de que existe una página de pruebas en el CMS. Si no, crea una como 'sitemap only' o 'disabled'. Esto te permitirá hacer pruebas directamente en el CMS sin afectar el sitio en producción.  
     **Ejemplo**: Si vas a modificar la página `/modelos`, crea una página `/modelos-pruebas` para realizar las pruebas.

6. **Verificar que el desarrollo es responsive**

   - Asegúrate de que el sitio sea totalmente funcional en diferentes dispositivos y tamaños de pantalla.  
     **Ejemplo**: Revisa el diseño en pantallas de móvil, tablet y escritorio, usando herramientas como Chrome DevTools.

7. **Para formularios: Verificar el envío correcto de leads**

   - Si implementas un formulario, asegúrate de que los datos se envíen correctamente al servidor o CRM.  
     **Ejemplo**: Usa una cuenta de prueba para comprobar que los leads se registran sin errores.

8. **Limpiar y optimizar el código para mejorar la legibilidad**

   - Elimina código redundante o innecesario, asegúrate de seguir las mejores prácticas de codificación.  
     **Ejemplo**: Organiza el CSS de forma modular, elimina líneas de código no usadas o comentarios innecesarios.

9. **Dejar comentarios en el código**

   - Comenta secciones clave del código para que otros desarrolladores sepan su función y sea más fácil localizarlas.  
     **Ejemplo**: `<!-- Este div contiene los enlaces al footer dinámico -->`

10. **Si trabajas en una página existente, verificar que no se han producido modificaciones no deseadas**

- Revisa que no se alteraron elementos no relacionados con la nueva funcionalidad.  
  **Ejemplo**: Verifica que el menú de navegación sigue funcionando después de agregar un nuevo dropdown.

11. **Verificar la ubicación correcta de scripts y estilos en el CMS**

- Asegúrate de que los scripts y estilos están ubicados en la sección correcta del CMS. Los elementos que afectan solo a una página específica deben colocarse en esa página, mientras que los estilos y scripts globales deben ir en secciones como 'Sitewide Footer Content (Displays Before Footer)'.  
  **Ejemplo**: Si modificas el home, coloca los scripts específicos en la página de home y los globales en la sección general del sitio.

12. **Revisar el proyecto en GitHub**

    - Verifica que todos los cambios están correctamente subidos, pero solo después de haber confirmado que las pruebas en el CMS son exitosas. Utiliza GitHub para control de versiones y, una vez probado, continúa con la revisión y aprobación.  
      **Ejemplo**: Usa `git status` para revisar tu rama y confirmar que estás actualizado.

13. **Realizar un Pull Request y solicitar aprobación**

    - Una vez que los cambios funcionen en el CMS, solicita una revisión a tus compañeros de equipo para validar calidad y funcionalidad.
    - Crea un Pull Request y asigna revisores para la aprobación. Revisa los comentarios y ajusta en caso de ser necesario.  
      **Ejemplo**: Detalla en el Pull Request las tareas realizadas y asigna compañeros del equipo para su aprobación.

14. **Integrar los cambios en el CMS**

    - Una vez aprobado el Pull Request, realiza la integración en el CMS siguiendo los procedimientos establecidos.  
      **Ejemplo**: Actualiza la versión en el CMS y comprueba que los cambios funcionan correctamente en producción.
