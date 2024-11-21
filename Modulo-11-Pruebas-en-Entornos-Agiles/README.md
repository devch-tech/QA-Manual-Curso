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

## 4. Rol del QA en las ceremonias ágiles
1. **Planificación del sprint**:
   - Revisar historias de usuario y criterios de aceptación.
   - Identificar riesgos y dependencias.

2. **Daily stand-up**:
   - Compartir el progreso de las pruebas.
   - Reportar bloqueos que puedan retrasar la validación.

3. **Revisión del sprint**:
   - Validar junto con el equipo que las historias cumplan con los requerimientos.
   - Proporcionar feedback sobre los resultados de las pruebas.

4. **Retrospectiva del sprint**:
   - Discutir problemas encontrados durante las pruebas.
   - Proponer mejoras para optimizar el proceso de testing.

---

## Conclusión
El QA en Agile no solo valida el producto; también asegura que el equipo esté alineado en cuanto a calidad y objetivos. La colaboración, adaptabilidad y pruebas continuas son esenciales para garantizar entregas rápidas y confiables.
