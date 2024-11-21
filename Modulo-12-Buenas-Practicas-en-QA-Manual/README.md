# Módulo 12: Buenas Prácticas en QA Manual

Las buenas prácticas en QA manual son esenciales para garantizar que el software cumpla con los estándares de calidad, se entregue a tiempo y satisfaga las necesidades del cliente. En este módulo, exploraremos las mejores estrategias para planificar y ejecutar pruebas efectivas, priorizar tareas, y mantener una comunicación clara con los equipos de desarrollo y stakeholders.

---

## 1. Cómo planificar pruebas efectivas

### **¿Por qué es importante planificar las pruebas?**
La planificación adecuada permite detectar defectos de manera eficiente, optimizar recursos y asegurar que el proceso de pruebas cubra todos los aspectos críticos del producto.

### **Pasos clave para planificar pruebas efectivas:**
1. **Entender los requisitos del proyecto:**
   - Reunirse con los stakeholders para identificar los objetivos del producto.
   - Revisar historias de usuario, criterios de aceptación y documentación técnica.
   
   **Ejemplo:**
   Si el requisito es "El usuario debe poder registrarse con su correo electrónico", define qué datos debe ingresar y qué validaciones son necesarias.

2. **Definir un alcance claro:**
   - Especificar qué partes del sistema serán probadas.
   - Identificar las exclusiones (funcionalidades no probadas en esta etapa).

   **Ejemplo de alcance:** 
   "Probar el registro de usuarios para los navegadores Chrome y Firefox en escritorio. Excluir pruebas en dispositivos móviles para esta iteración."

3. **Seleccionar tipos de pruebas necesarios:**
   - Decidir si se realizarán pruebas funcionales, de regresión, exploratorias, etc.

4. **Asignar recursos:**
   - Determinar quién ejecutará las pruebas y qué herramientas se utilizarán.

5. **Crear un cronograma:**
   - Establecer plazos para las fases de diseño, ejecución y reporte.

---

## 2. Estrategias para priorizar casos de prueba

Cuando los recursos son limitados, es crucial priorizar los casos de prueba para enfocarse en las áreas más críticas del producto.

### **Criterios para priorizar:**
1. **Impacto en el negocio:**
   - Prioriza las funcionalidades que afectan directamente al usuario final.

   **Ejemplo:** Probar el flujo de pago antes de probar cambios en el diseño de la interfaz.

2. **Probabilidad de defectos:**
   - Enfócate en áreas que históricamente han tenido más errores o que son nuevas.

   **Ejemplo:** Validar una nueva API de integración antes de probar funcionalidades existentes.

3. **Riesgos asociados:**
   - Probar funcionalidades críticas como la seguridad o el manejo de datos sensibles.

   **Ejemplo:** Validar que los usuarios solo puedan acceder a datos autorizados.

4. **Frecuencia de uso:**
   - Prioriza las funciones que los usuarios utilizan con mayor frecuencia.

   **Ejemplo:** Probar el inicio de sesión en todas las plataformas soportadas.

---

## 3. Comunicación con desarrolladores y otros stakeholders

### **Por qué es importante una comunicación efectiva**
El QA sirve como puente entre el equipo de desarrollo, el Product Owner y otros stakeholders. Una comunicación clara ayuda a resolver problemas rápidamente y asegura que todos trabajen hacia los mismos objetivos.

### **Mejores prácticas para la comunicación:**
1. **Participar activamente en reuniones:**
   - Asiste a las ceremonias ágiles (planificación, retrospectivas, etc.).
   - Expón los riesgos y problemas encontrados durante las pruebas.

2. **Usar herramientas de colaboración:**
   - Documenta y comparte hallazgos en herramientas como JIRA, Confluence o Google Docs.

3. **Proveer retroalimentación constructiva:**
   - Enfócate en describir el problema y sus implicaciones en lugar de culpar.

   **Ejemplo:** 
   "He encontrado un defecto en la funcionalidad X. Si no se corrige, podría causar problemas en el flujo de Y."

4. **Mantener una comunicación constante:**
   - Haz seguimiento a los defectos reportados y consulta a los desarrolladores cuando tengas dudas sobre la funcionalidad esperada.

---

## 4. Mejores prácticas para asegurarse de que el producto cumpla con los estándares de calidad

### **Revisión y seguimiento continuo:**
1. **Revisar criterios de aceptación:**
   - Antes de ejecutar las pruebas, asegúrate de que los criterios sean claros y verificables.

2. **Automatizar pruebas repetitivas:**
   - Implementa pruebas automatizadas para regresión y enfócate en casos más complejos manualmente.

3. **Realizar pruebas cruzadas:**
   - Ejecuta pruebas en diferentes dispositivos, navegadores y entornos.

   **Ejemplo:** 
   Probar en Chrome, Firefox y Safari, tanto en sistemas operativos Windows como macOS.

4. **Documentar todo:**
   - Registra los resultados de las pruebas, defectos encontrados y lecciones aprendidas.

5. **Realizar revisiones postmortem:**
   - Analiza el proceso de pruebas al final del proyecto para identificar áreas de mejora.

---

## Ejemplo práctico de planificación y ejecución
**Proyecto: E-commerce con funcionalidad de carrito de compras**

1. **Entender requisitos:**
   - Funcionalidad principal: El usuario puede añadir productos al carrito y realizar la compra.
   - Validaciones:
     - ¿El carrito actualiza la cantidad correctamente?
     - ¿El sistema calcula el precio total con impuestos?

2. **Definir alcance:**
   - Navegadores: Chrome y Firefox.
   - Funciones probadas:
     - Agregar producto.
     - Eliminar producto.
     - Proceder al pago.

3. **Priorizar casos de prueba:**
   - Prioridad alta: Flujo de pago.
   - Prioridad media: Actualización de cantidad.
   - Prioridad baja: Guardar carrito para después.

4. **Comunicar hallazgos:**
   - Reportar defectos con pasos detallados, severidad y prioridad.
   - Documentar los resultados en una herramienta como JIRA.

---

## Conclusión
Las buenas prácticas en QA manual son fundamentales para entregar un producto de alta calidad. Planificar cuidadosamente, priorizar casos de prueba y mantener una comunicación efectiva con el equipo no solo mejora el proceso, sino que asegura la satisfacción del cliente. 

¡Con estas estrategias, estarás listo para enfrentar cualquier desafío en QA manual!
