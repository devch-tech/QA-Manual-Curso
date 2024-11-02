# Módulo 7: Gestión de Defectos

## Introducción
La gestión de defectos es un aspecto fundamental en el aseguramiento de la calidad del software. Implica la identificación, registro, seguimiento y resolución de defectos o bugs que se presentan durante el ciclo de vida del desarrollo de software. Este módulo explorará qué es un defecto, su ciclo de vida, las herramientas para su gestión y cómo escribir reportes de defectos efectivos.

---

## 1. ¿Qué es un Defecto/Bug?
Un defecto o bug es cualquier falla en el software que provoca que no funcione de acuerdo a los requisitos o especificaciones establecidos. Estos defectos pueden surgir de varias fuentes, como errores en el código, malentendidos de los requisitos, o problemas de diseño.

### Tipos de Defectos
- **Errores de Código**: Bugs resultantes de fallos en la lógica del programa.
- **Errores de Diseño**: Problemas que surgen de un diseño inadecuado que no cumple con los requisitos del cliente.
- **Errores de Requisitos**: Defectos causados por requisitos mal definidos o incompletos.

**Ejemplo**: Si un botón de "Enviar" en un formulario no realiza ninguna acción al ser clicado, esto es un defecto que afecta la funcionalidad del sistema.

---

## 2. Ciclo de Vida de un Defecto
El ciclo de vida de un defecto describe las diferentes etapas que atraviesa desde su identificación hasta su resolución. Las etapas comunes incluyen:

1. **Nuevo**: El defecto ha sido reportado pero no ha sido revisado aún.
  
2. **Asignado**: Un desarrollador ha sido asignado para investigar y corregir el defecto.
  
3. **Corregido**: El desarrollador ha realizado los cambios necesarios en el código para resolver el defecto.
  
4. **Verificado**: El equipo de QA verifica que el defecto ha sido corregido y que el software funciona como se esperaba.
  
5. **Cerrado**: El defecto ha sido confirmado como resuelto y se cierra en el sistema de gestión.

### Ejemplo del Ciclo de Vida
- **Nuevo**: Un QA encuentra un bug y lo reporta en JIRA como "Nuevo".
- **Asignado**: Un desarrollador revisa el ticket y lo asigna a sí mismo.
- **Corregido**: El desarrollador realiza los cambios y actualiza el estado a "Corregido".
- **Verificado**: El QA realiza pruebas y confirma que el defecto está resuelto.
- **Cerrado**: El ticket se cierra y se registra como "Cerrado".

---

## 3. Herramientas para Gestión de Defectos
Existen varias herramientas que ayudan en la gestión de defectos. Algunas de las más populares son:

### 3.1 JIRA
- **Descripción**: Herramienta de gestión de proyectos ampliamente utilizada que incluye funcionalidades para la gestión de defectos.
- **Funcionalidades**: Permite crear, asignar, rastrear y cerrar tickets de defectos de manera eficiente. Los equipos pueden agregar comentarios, adjuntar archivos y establecer prioridades.

### 3.2 Bugzilla
- **Descripción**: Herramienta diseñada específicamente para la gestión de defectos en proyectos de software.
- **Funcionalidades**: Ofrece características como seguimiento de errores, asignación de tareas y generación de reportes sobre defectos.

### 3.3 Trello
- **Descripción**: Herramienta de gestión de proyectos que puede ser adaptada para la gestión de defectos.
- **Funcionalidades**: Permite crear tarjetas para cada defecto y organizarlas en columnas que representan diferentes estados del ciclo de vida.

**Ejemplo de uso de JIRA**:
1. Un QA encuentra un defecto y crea un ticket en JIRA.
2. Asigna el ticket a un desarrollador.
3. El desarrollador corrige el bug y actualiza el estado del ticket a "Corregido".
4. El QA verifica la solución y cambia el estado a "Cerrado".

---

## 4. Cómo Escribir Reportes de Defectos Efectivos
Un reporte de defecto efectivo debe contener información clara y concisa que permita al equipo de desarrollo entender y reproducir el problema. Los elementos clave incluyen:

### 4.1 Elementos de un Reporte de Defecto
- **Descripción**: Un resumen breve pero claro del defecto.
  
- **Pasos para Reproducir**: Una lista detallada de los pasos necesarios para replicar el defecto. Esto incluye acciones específicas que un usuario debe seguir.

- **Severidad**: Clasifica el impacto del defecto en el sistema (por ejemplo, crítico, mayor, menor).
  
- **Prioridad**: Indica la urgencia de resolver el defecto (alta, media, baja).

### 4.2 Ejemplo de Reporte de Defecto:

Descripción: El botón "Enviar" en la página de contacto no responde al hacer clic. Pasos para Reproducir:

Ir a la página de contacto.
Completar el formulario de contacto.
Hacer clic en el botón "Enviar". Severidad: Crítico (impide que los usuarios envíen información). Prioridad: Alta (debe ser corregido antes del lanzamiento).
