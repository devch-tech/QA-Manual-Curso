# Módulo 14: Talleres Prácticos y Ejercicios

Este módulo está enfocado en ejercicios prácticos que te ayudarán a aplicar los conceptos aprendidos en situaciones reales. Cubriremos cómo diseñar casos de prueba, realizar pruebas exploratorias y reportar defectos, además de crear un plan de pruebas.

---

## 1. Diseñar casos de prueba para una aplicación web sencilla

Vamos a diseñar casos de prueba para una funcionalidad básica: un formulario de registro de usuario. Imagina que el formulario tiene los siguientes campos:
- Nombre de usuario (alfanumérico, obligatorio).
- Correo electrónico (obligatorio, con validación de formato).
- Contraseña (mínimo 8 caracteres, obligatorio).
- Botón de registro.

### **Casos de prueba sugeridos:**

| **ID** | **Caso de prueba**                                                   | **Pasos**                                                                                       | **Resultado esperado**                                                                            |
|--------|----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| 1      | Registrar usuario con datos válidos                                  | 1. Completar todos los campos con datos válidos. <br> 2. Clic en "Registrar".                  | Registro exitoso. Mostrar mensaje "Registro completado" y redirigir al usuario a la página principal. |
| 2      | Registrar usuario con un correo inválido                             | 1. Ingresar un correo sin `@` o dominio (e.g., "correo.com"). <br> 2. Clic en "Registrar".     | Mostrar mensaje de error: "Por favor, ingrese un correo válido".                                  |
| 3      | Dejar el campo de contraseña vacío                                   | 1. Completar todos los campos excepto "Contraseña". <br> 2. Clic en "Registrar".               | Mostrar mensaje de error: "La contraseña es obligatoria".                                        |
| 4      | Ingresar una contraseña con menos de 8 caracteres                    | 1. Ingresar "12345" como contraseña. <br> 2. Clic en "Registrar".                              | Mostrar mensaje de error: "La contraseña debe tener al menos 8 caracteres".                      |
| 5      | Probar con un nombre de usuario que contenga caracteres especiales   | 1. Ingresar "Usuario@123". <br> 2. Completar el resto de los campos. <br> 3. Clic en "Registrar". | Mostrar mensaje de error: "El nombre de usuario solo puede contener caracteres alfanuméricos".   |

---

## 2. Pruebas exploratorias en una aplicación móvil

### **¿Qué son las pruebas exploratorias?**
Son un enfoque dinámico donde el QA explora la aplicación en busca de defectos sin seguir un conjunto estricto de casos de prueba. Este tipo de pruebas es ideal para descubrir problemas inesperados o validar funcionalidades no documentadas.

### **Ejercicio práctico: Exploración de una aplicación de notas**
Supongamos que tienes una aplicación de notas con las siguientes funcionalidades:
- Crear una nueva nota.
- Editar una nota existente.
- Eliminar una nota.
- Buscar notas por título.

### **Pasos sugeridos para realizar pruebas exploratorias:**
1. **Navegación básica:** 
   - Abrir la aplicación y explorar las opciones disponibles en el menú principal.
   - Verificar que la interfaz sea intuitiva y que no haya errores de diseño.
2. **Crear notas:**
   - Crear una nota con un título y contenido.
   - Probar límites en el tamaño del título (e.g., ingresar más de 100 caracteres).
   - Crear una nota sin contenido y verificar el comportamiento.
3. **Editar y eliminar notas:**
   - Modificar el contenido de una nota existente y guardar los cambios.
   - Intentar eliminar una nota y confirmar que desaparezca de la lista.
   - Verificar si hay opción para recuperar notas eliminadas.
4. **Buscar notas:**
   - Buscar notas con palabras clave exactas y parcialmente coincidentes.
   - Probar búsquedas con mayúsculas/minúsculas o caracteres especiales.

### **Reporte de resultados exploratorios:**
Registra tus hallazgos de manera clara. Por ejemplo:
- **Problema:** Al intentar buscar notas con caracteres especiales (&, %, $), la aplicación se cierra inesperadamente.
- **Pasos para reproducir:** Abrir la función de búsqueda, ingresar "&nota", presionar "Buscar".
- **Impacto:** La funcionalidad de búsqueda es inusable si el usuario emplea ciertos caracteres.

---

## 3. Ejercicios de identificación y reporte de defectos en un proyecto de ejemplo

### **Ejercicio práctico: Reportar un defecto en un sistema de gestión de tareas**
Imagina que estás probando un sistema de gestión de tareas. Descubres el siguiente problema: **el sistema permite crear tareas duplicadas con el mismo nombre y fecha límite**.

#### **Pasos para reportar el defecto:**
1. **Título:** Permite la creación de tareas duplicadas.
2. **Descripción:**
   - El sistema permite al usuario agregar múltiples tareas con el mismo nombre y fecha límite sin ningún mensaje de error.
3. **Pasos para reproducir:**
   1. Abrir el sistema de gestión de tareas.
   2. Crear una tarea con el nombre "Proyecto A" y fecha límite "2024-11-21".
   3. Crear otra tarea con el mismo nombre y fecha límite.
   4. Observar que ambas tareas son aceptadas.
4. **Resultado esperado:** Mostrar un mensaje de error como "La tarea ya existe" o permitir duplicados solo si tienen diferentes fechas límite.
5. **Impacto:** Alta. Puede causar confusión y errores al gestionar tareas.

---

## 4. Creación de un plan de pruebas para un proyecto real

### **¿Qué es un plan de pruebas?**
Un plan de pruebas es un documento que describe el enfoque, el alcance y las actividades necesarias para realizar pruebas en un proyecto.

### **Ejercicio práctico: Plan de pruebas para una tienda en línea**
#### **Secciones clave del plan:**
1. **Objetivo:**
   - Garantizar que las funcionalidades principales de la tienda en línea (registro, búsqueda de productos, carrito de compras, pagos) funcionen correctamente.
2. **Alcance:**
   - Funcionalidades incluidas: Registro, inicio de sesión, búsqueda de productos, pago.
   - Funcionalidades excluidas: Integración con redes sociales.
3. **Criterios de aceptación:**
   - Todos los casos de prueba funcionales deben pasar.
   - No se permiten defectos críticos ni mayores en el lanzamiento.
4. **Recursos:**
   - Herramientas: TestRail para gestión de pruebas, Jira para reporte de defectos.
   - Equipo: 2 QA manuales y 1 líder de QA.
5. **Cronograma:**
   - Fase de pruebas: 2 semanas.
6. **Riesgos:**
   - Riesgo de no tener suficiente tiempo para pruebas exploratorias si los casos funcionales toman más de lo esperado.

---

## Conclusión

Los talleres prácticos son esenciales para consolidar los conocimientos de QA. Al realizar estos ejercicios, te familiarizarás con los desafíos reales de esta profesión y estarás mejor preparado para resolverlos en un entorno laboral.

