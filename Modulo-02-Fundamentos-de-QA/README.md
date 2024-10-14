# Módulo 2: Fundamentos de QA

¡Bienvenido al segundo módulo del curso de QA Manual! En este módulo, abordaremos los conceptos fundamentales del aseguramiento de la calidad y los distintos tipos de pruebas que se realizan en el desarrollo de software.

## Contenido

### 1. Conceptos Clave

#### Defectos, Errores, Bugs y Fallos

- **Defecto**: Un defecto es cualquier discrepancia entre el producto real y lo que se esperaba. Por ejemplo, si un botón en una aplicación web no funciona como se esperaba, eso se considera un defecto.

- **Error**: Un error es la acción incorrecta realizada por un desarrollador que lleva a un defecto. Por ejemplo, un error en la lógica de programación que hace que un cálculo no se ejecute correctamente.

- **Bug**: Es un término informal que se utiliza para referirse a un defecto o error en el software. Por ejemplo, si una aplicación se cierra inesperadamente cuando el usuario hace clic en un botón, eso es considerado un bug.

- **Fallo**: Un fallo ocurre cuando un software no cumple con los requisitos establecidos. Por ejemplo, si una función debe retornar un valor y lo hace de manera incorrecta, esto es un fallo.

# Tipos de Pruebas en QA

El aseguramiento de la calidad (QA) abarca diferentes tipos de pruebas, cada una diseñada para evaluar aspectos específicos del software. A continuación, se presenta una clasificación detallada:

## 1. Pruebas Funcionales

Las pruebas funcionales se centran en verificar que las funciones del software cumplan con los requisitos especificados. Incluyen:

### 1.1. Pruebas de Aceptación
- **Descripción**: Verifican si el software cumple con los requisitos y expectativas del cliente.
- **Ejemplo**: Un cliente prueba una aplicación de compras en línea para asegurarse de que todos los procesos de pago funcionen correctamente.

### 1.2. Pruebas de Regresión
- **Descripción**: Aseguran que los cambios recientes en el software no afecten las funcionalidades existentes.
- **Ejemplo**: Después de una actualización de la aplicación, se prueba que las funciones anteriores sigan funcionando como se esperaba.

### 1.3. Pruebas Smoke
- **Descripción**: Pruebas básicas que verifican que las funcionalidades principales del software funcionen.
- **Ejemplo**: Un equipo realiza pruebas rápidas para verificar que la aplicación se inicie y que las funciones críticas estén accesibles.

### 1.4. Pruebas Sanity
- **Descripción**: Verifican que una funcionalidad específica funcione correctamente después de un cambio.
- **Ejemplo**: Tras corregir un error en el proceso de registro, se prueba únicamente esa función para asegurarse de que el problema se haya solucionado.

### 1.5. Pruebas Exploratorias
- **Descripción**: Se centran en explorar el software sin un conjunto de casos de prueba predefinidos.
- **Ejemplo**: Un tester utiliza su conocimiento del software para intentar encontrar defectos al interactuar con la aplicación de manera no estructurada.

## 2. Pruebas No Funcionales

Las pruebas no funcionales evalúan aspectos que no están directamente relacionados con las funciones específicas del software, como rendimiento, usabilidad y seguridad.

### 2.1. Pruebas de Usabilidad
- **Descripción**: Evalúan la facilidad de uso de la aplicación.
- **Ejemplo**: Se realiza una prueba con usuarios reales para observar si pueden navegar por el sitio web sin problemas.

### 2.2. Pruebas de Rendimiento
- **Descripción**: Miden el comportamiento del software bajo diversas condiciones de carga.
- **Ejemplo**: Se simula el acceso de múltiples usuarios a la vez para comprobar cómo se comporta la aplicación.

#### 2.2.1. Pruebas de Carga
- **Descripción**: Evalúan cómo el software se desempeña bajo una carga específica.
- **Ejemplo**: Se determina cuántos usuarios puede manejar simultáneamente un sitio web sin degradar su rendimiento.

#### 2.2.2. Pruebas de Estrés
- **Descripción**: Evalúan el software más allá de sus límites especificados para determinar su comportamiento bajo condiciones extremas.
- **Ejemplo**: Se aumenta el número de usuarios concurrentes hasta que el sistema falle, para identificar el límite máximo.

#### 2.2.3. Pruebas de Escalabilidad
- **Descripción**: Evalúan cómo se comporta el sistema a medida que aumenta la carga.
- **Ejemplo**: Se verifica si la aplicación puede manejar un incremento en el número de usuarios sin afectar su rendimiento.

### 2.3. Pruebas de Seguridad
- **Descripción**: Verifican la protección contra vulnerabilidades y ataques.
- **Ejemplo**: Se realizan pruebas para detectar posibles brechas de seguridad que podrían permitir el acceso no autorizado a datos sensibles.

### 2.4. Pruebas de Compatibilidad
- **Descripción**: Aseguran que el software funcione correctamente en diferentes entornos (navegadores, dispositivos, sistemas operativos).
- **Ejemplo**: Se prueba una aplicación web en varios navegadores para garantizar que se muestre correctamente en todos ellos.

## Resumen de Clasificación

- **Pruebas Funcionales**: Aceptación, regresión, smoke, sanity, exploratorias.
  
- **Pruebas No Funcionales**: Usabilidad, rendimiento (carga, estrés, escalabilidad), seguridad, compatibilidad.


### 3. Principios Básicos del Testing de Software

1. **El testing debe comenzar lo antes posible**: Detectar defectos en las primeras etapas del desarrollo es más eficiente.

2. **El testing es un proceso continuado**: Las pruebas deben realizarse a lo largo de todo el ciclo de vida del software, no solo al final.

3. **El testing debe ser exhaustivo**: Aunque es difícil probar todas las combinaciones posibles, se deben cubrir los escenarios más críticos.

4. **El testing es una actividad conjunta**: Todos los miembros del equipo, incluidos desarrolladores y analistas de negocio, deben estar involucrados en el proceso de pruebas.

5. **La ausencia de defectos no significa calidad**: Un software puede pasar todas las pruebas y aún así no ser de alta calidad si no cumple con las expectativas de los usuarios.

---

¡Gracias por unirte a este módulo! En el próximo módulo, exploraremos el ciclo de vida del desarrollo de software (SDLC) y cómo el QA se integra en cada modelo.
