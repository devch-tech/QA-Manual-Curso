# Módulo 11: Pruebas en Entornos Ágiles

## 1. ¿Qué es Agile y cómo se diferencia de otros enfoques?
**Agile** es un marco de trabajo basado en la colaboración, la flexibilidad y la entrega rápida de valor al cliente. A diferencia de enfoques tradicionales como Waterfall, Agile se centra en:
- **Iteraciones cortas**: Desarrollo y entrega de incrementos de producto en ciclos pequeños (generalmente de 2 a 4 semanas).
- **Adaptabilidad**: Responder rápidamente a cambios en los requisitos.
- **Colaboración constante**: Comunicación cercana entre los equipos y con los clientes.

**Diferencias clave**:
- **Waterfall**: Proceso lineal y secuencial; las pruebas se realizan después del desarrollo completo.
- **Agile**: Desarrollo y pruebas se realizan de manera iterativa y continua.

---

## 2. QA en metodologías ágiles: Scrum y Kanban
### Scrum:
Scrum es un marco de trabajo ágil que organiza el desarrollo en **sprints**. Cada sprint tiene ceremonias específicas donde el QA juega un papel importante.

- **Rol del QA en Scrum**:
  - Participar en la **planificación del sprint** para revisar y entender los requerimientos.
  - Colaborar con desarrolladores para crear casos de prueba en paralelo al desarrollo.
  - Ejecutar pruebas durante el sprint y validar las historias de usuario antes de que se consideren "completas".

- **Ejemplo de tareas del QA en un sprint**:
  - Revisar criterios de aceptación.
  - Diseñar casos de prueba basados en las historias de usuario.
  - Probar funcionalidades entregadas y reportar defectos en tiempo real.

### Kanban:
Kanban utiliza un tablero visual para gestionar el flujo de trabajo. No tiene sprints definidos, pero el QA asegura la calidad en cada etapa del tablero (p. ej., "En progreso", "En revisión", "Hecho").

- **Rol del QA en Kanban**:
  - Garantizar que las tareas etiquetadas como "Listas para pruebas" se validen rápidamente.
  - Automatizar casos de prueba recurrentes para acelerar el flujo.

---

## 3. Concepto de pruebas continuas y DevOps
### Pruebas continuas:
En Agile, las pruebas no se limitan a una fase específica; se ejecutan de manera continua durante todo el ciclo de desarrollo. Esto implica:
- **Automatización de pruebas**: Ayuda a ejecutar rápidamente pruebas de regresión.
- **Validaciones frecuentes**: Los testers trabajan junto con los desarrolladores para validar pequeños cambios constantemente.

### DevOps:
DevOps combina desarrollo y operaciones para entregar software de manera más rápida y confiable. 
- **Pruebas en DevOps**:
  - Se integran en pipelines de CI/CD (Integración y Entrega Continua).
  - Aseguran que cada cambio en el código pase por pruebas automatizadas antes de llegar a producción.

**Ejemplo**:
Un pipeline de CI/CD ejecuta pruebas automatizadas en Selenium cada vez que un desarrollador realiza un commit en Git.

---

## 4. Reuniones clave en Agile y participación del QA
En un entorno ágil, el equipo participa en varias ceremonias para alinear prioridades y garantizar que el producto cumple con las expectativas. Estas reuniones son esenciales tanto para los desarrolladores como para los QAs.

### **Reuniones del marco Scrum**
1. **Sprint Planning (Planificación del Sprint)**:
   - Propósito: Planificar las tareas que se completarán durante el sprint.
   - Rol del QA:
     - Revisar las historias de usuario y sus criterios de aceptación.
     - Aportar información sobre riesgos y dependencias.
     - Estimar el esfuerzo requerido para las pruebas.

2. **Daily Stand-up (Reunión diaria)**:
   - Propósito: Compartir actualizaciones rápidas sobre el progreso del equipo.
   - Rol del QA:
     - Informar sobre el estado de las pruebas.
     - Escalar bloqueos relacionados con defectos o dependencias.

3. **Sprint Review (Revisión del Sprint)**:
   - Propósito: Demostrar el trabajo completado durante el sprint.
   - Rol del QA:
     - Presentar resultados de las pruebas realizadas.
     - Participar en la validación del producto con el cliente o stakeholders.

4. **Sprint Retrospective (Retrospectiva del Sprint)**:
   - Propósito: Identificar áreas de mejora en el proceso del equipo.
   - Rol del QA:
     - Compartir desafíos encontrados durante las pruebas.
     - Sugerir cambios para mejorar la calidad en futuros sprints.

### **Reuniones adicionales**
- **Backlog Refinement (Refinamiento del Backlog)**:
  - Propósito: Detallar y priorizar las historias de usuario.
  - Rol del QA:
    - Validar que los criterios de aceptación sean claros y probables de probar.
    - Identificar posibles escenarios negativos o riesgos.

---

## 5. ¿Qué es el backlog y cuál es su relación con el QA?
El **backlog** es una lista priorizada de requisitos, historias de usuario y tareas pendientes. Se divide en:
- **Product Backlog**: Contiene todas las funcionalidades que el producto debe tener.
- **Sprint Backlog**: Subconjunto del product backlog seleccionado para el sprint actual.

**Relación con el QA**:
- El QA revisa las historias de usuario para asegurar que los criterios de aceptación sean claros.
- Ayuda a identificar dependencias o posibles problemas antes de que se planifiquen en un sprint.

---

## 6. ¿Qué es un Product Owner y cómo interactúa con el Scrum Team?
El **Product Owner (PO)** es responsable de maximizar el valor del producto. Sus funciones incluyen:
- Crear y priorizar el product backlog.
- Definir criterios de aceptación para cada historia de usuario.
- Aclarar dudas del equipo de desarrollo y QA sobre los requisitos.

**Comunicación con el Scrum Team**:
- El PO trabaja estrechamente con el Scrum Master, desarrolladores y QA para garantizar que el equipo entienda los objetivos del producto.
- El QA consulta al PO para aclarar criterios de aceptación y validar escenarios específicos durante las pruebas.

---

## Conclusión
El QA desempeña un papel crucial en Agile al garantizar que el producto mantenga su calidad a través de colaboración, pruebas continuas y participación activa en ceremonias clave. Entender cómo se gestionan las reuniones y las responsabilidades del Product Owner mejora significativamente la integración del QA en el proceso ágil.
