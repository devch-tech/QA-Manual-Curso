# Módulo 9: Documentación de Pruebas

## Introducción
La documentación de pruebas es una parte esencial del proceso de QA, ya que garantiza que todo el proceso de pruebas esté bien planificado, estructurado y documentado para que otros miembros del equipo puedan entenderlo y seguirlo. Este módulo te enseñará cómo crear y gestionar documentos clave de pruebas, desde el plan de pruebas hasta los reportes de ejecución.

---

## 1. Plan de Pruebas
### ¿Qué es un Plan de Pruebas?
Un plan de pruebas es un documento detallado que describe el enfoque, los objetivos, los recursos y el cronograma de las actividades de prueba para un proyecto. Actúa como una guía para el equipo de pruebas y asegura que todos estén alineados.

### ¿Cómo crear un Plan de Pruebas?
1. **Objetivos de la prueba**: Define claramente qué se espera lograr con las pruebas (por ejemplo, validar la funcionalidad principal de una aplicación web).
2. **Alcance de las pruebas**: Detalla qué funcionalidades se van a probar y cuáles están fuera del alcance.
3. **Recursos y roles**: Especifica quién estará a cargo de cada tarea (QA, desarrolladores, analistas).
4. **Cronograma**: Indica las fechas clave para la planificación, ejecución y finalización de las pruebas.
5. **Criterios de aceptación**: Define cuándo una prueba se considera exitosa.

**Ejemplo de un objetivo de plan de pruebas**:
> Verificar que la funcionalidad de inicio de sesión cumpla con los requisitos de seguridad y usabilidad.

---

## 2. Estrategia de Pruebas
### ¿Qué es una Estrategia de Pruebas?
Es un enfoque de alto nivel que describe cómo se llevarán a cabo las pruebas en el proyecto. La estrategia de pruebas define el tipo de pruebas, los métodos y las herramientas que se usarán.

### Componentes de una Estrategia de Pruebas
- **Objetivos de la estrategia**: Qué se pretende lograr con la estrategia de pruebas (e.g., asegurar la cobertura de pruebas en componentes críticos).
- **Alcance y cobertura**: Áreas de la aplicación que se probarán.
- **Tipos de pruebas a realizar**: Funcionales, no funcionales, de regresión, etc.
- **Criterios de aceptación y salida**: Define cuándo se puede proceder al siguiente paso o finalizar el proceso de pruebas.

**Ejemplo de un criterio de salida**:
> Todos los casos de prueba críticos deben pasar con éxito y no debe haber defectos de alta severidad.

---

## 3. Casos de Prueba
### ¿Cómo escribir casos de prueba claros y efectivos?
Un caso de prueba es un conjunto de condiciones o acciones que se ejecutan para verificar una funcionalidad específica del software.

### Estructura de un caso de prueba:
1. **ID del caso de prueba**: Un identificador único (e.g., TC001).
2. **Título**: Breve descripción de lo que se va a probar (e.g., "Verificar la funcionalidad de inicio de sesión").
3. **Precondiciones**: Los requisitos previos antes de ejecutar el caso (e.g., "El usuario debe estar registrado").
4. **Pasos de prueba**:
   - Ingresar el nombre de usuario.
   - Ingresar la contraseña.
   - Hacer clic en "Iniciar sesión".
5. **Resultado esperado**: Qué debe ocurrir después de ejecutar los pasos (e.g., "El usuario es redirigido a su panel de control").
6. **Resultado real**: Documentar lo que ocurrió realmente al ejecutar el caso.
7. **Estado**: Aprobado o fallido.

**Ejemplo de caso de prueba**:
| ID     | TC001                                    |
|--------|-------------------------------------------|
| Título | Verificar inicio de sesión con datos válidos |
| Precondiciones | El usuario está registrado          |
| Pasos  | 1. Ir a la página de inicio de sesión <br> 2. Ingresar usuario <br> 3. Ingresar contraseña <br> 4. Clic en "Iniciar sesión" |
| Resultado esperado | El usuario accede al panel de control |
| Resultado real | [Completar tras ejecución]        |
| Estado  | [Aprobado/Fallido]                     |

---

## 4. Reportes de Ejecución de Pruebas
### ¿Cómo documentar los resultados de la ejecución?
La documentación de los resultados es fundamental para analizar el estado de las pruebas y tomar decisiones informadas.

### Componentes de un reporte de ejecución:
- **Resumen de la prueba**: Breve resumen de lo que se probó y los resultados generales.
- **Casos de prueba ejecutados**: Lista de casos de prueba con sus resultados.
- **Defectos encontrados**: Un resumen de los defectos identificados durante la ejecución.
- **Recomendaciones**: Pasos a seguir basados en los resultados (e.g., "Repetir pruebas después de corregir defectos").

**Ejemplo de reporte de ejecución**:

