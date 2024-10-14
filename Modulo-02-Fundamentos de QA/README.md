# Módulo 2: Fundamentos de QA

¡Bienvenido al segundo módulo del curso de QA Manual! En este módulo, abordaremos los conceptos fundamentales del aseguramiento de la calidad y los distintos tipos de pruebas que se realizan en el desarrollo de software.

## Contenido

### 1. Conceptos Clave

#### Defectos, Errores, Bugs y Fallos

- **Defecto**: Un defecto es cualquier discrepancia entre el producto real y lo que se esperaba. Por ejemplo, si un botón en una aplicación web no funciona como se esperaba, eso se considera un defecto.

- **Error**: Un error es la acción incorrecta realizada por un desarrollador que lleva a un defecto. Por ejemplo, un error en la lógica de programación que hace que un cálculo no se ejecute correctamente.

- **Bug**: Es un término informal que se utiliza para referirse a un defecto o error en el software. Por ejemplo, si una aplicación se cierra inesperadamente cuando el usuario hace clic en un botón, eso es considerado un bug.

- **Fallo**: Un fallo ocurre cuando un software no cumple con los requisitos establecidos. Por ejemplo, si una función debe retornar un valor y lo hace de manera incorrecta, esto es un fallo.

### 2. Tipos de Pruebas

#### Pruebas Funcionales

Las pruebas funcionales se centran en verificar que cada función del software opere de acuerdo con los requisitos especificados. Un ejemplo de prueba funcional podría ser verificar que un usuario pueda iniciar sesión en una aplicación con credenciales válidas.

#### Pruebas No Funcionales

Estas pruebas evalúan aspectos que no están relacionados con el comportamiento específico del software, como la usabilidad, el rendimiento y la seguridad. Algunos tipos de pruebas no funcionales incluyen:

- **Pruebas de Usabilidad**: Evalúan la facilidad de uso de una aplicación. Por ejemplo, se puede observar cómo los usuarios navegan en una interfaz y si pueden completar tareas sin frustraciones.

- **Pruebas de Rendimiento**: Miden cómo responde el software bajo diferentes condiciones de carga. Esto incluye pruebas de carga, pruebas de estrés y pruebas de volumen. Por ejemplo, probar una aplicación para ver cuántos usuarios pueden usarla simultáneamente sin que se degrade el rendimiento.

- **Pruebas de Seguridad**: Se enfocan en identificar vulnerabilidades y asegurar que los datos estén protegidos. Esto incluye pruebas de penetración para simular ataques y evaluar la seguridad de una aplicación.

- **Pruebas de Compatibilidad**: Verifican que el software funcione correctamente en diferentes navegadores, sistemas operativos y dispositivos. Por ejemplo, asegurar que una aplicación web se vea y funcione bien en Chrome, Firefox y Safari.

- **Pruebas de Aceptación**: Determinan si el software cumple con los requisitos y expectativas del cliente. Esto se puede realizar mediante pruebas de aceptación del usuario (UAT), donde los usuarios finales prueban el software en un entorno real antes de su lanzamiento.

#### Pruebas de Regresión

Las pruebas de regresión se realizan para asegurar que nuevas actualizaciones o cambios en el software no afecten negativamente a las funciones existentes. Por ejemplo, después de corregir un bug en el proceso de pago, se deben realizar pruebas de regresión para asegurarse de que la funcionalidad de compra siga funcionando.

#### Pruebas Smoke

Las pruebas smoke son un conjunto básico de pruebas que se realizan para verificar que las funciones principales del software están operativas. Se ejecutan generalmente después de una nueva compilación. Por ejemplo, si se lanza una nueva versión de una aplicación, las pruebas smoke podrían verificar que la aplicación se inicia y que los principales botones funcionan.

#### Pruebas Sanity

Las pruebas sanity son un tipo específico de pruebas de regresión que se llevan a cabo para comprobar que una función específica o un conjunto de funciones está trabajando correctamente después de un cambio. Por ejemplo, si se corrige un bug en la funcionalidad de búsqueda, se realizan pruebas sanity para verificar que esta funcionalidad no tenga problemas.

#### Pruebas Exploratorias

Las pruebas exploratorias son un enfoque menos estructurado donde el tester explora el software sin un conjunto predefinido de pruebas. Esto permite identificar defectos inesperados. Por ejemplo, un tester podría navegar por la aplicación y utilizarla de manera creativa para descubrir errores que no se habrían encontrado con pruebas tradicionales.

### 3. Principios Básicos del Testing de Software

1. **El testing debe comenzar lo antes posible**: Detectar defectos en las primeras etapas del desarrollo es más eficiente.

2. **El testing es un proceso continuado**: Las pruebas deben realizarse a lo largo de todo el ciclo de vida del software, no solo al final.

3. **El testing debe ser exhaustivo**: Aunque es difícil probar todas las combinaciones posibles, se deben cubrir los escenarios más críticos.

4. **El testing es una actividad conjunta**: Todos los miembros del equipo, incluidos desarrolladores y analistas de negocio, deben estar involucrados en el proceso de pruebas.

5. **La ausencia de defectos no significa calidad**: Un software puede pasar todas las pruebas y aún así no ser de alta calidad si no cumple con las expectativas de los usuarios.

---

¡Gracias por unirte a este módulo! En el próximo módulo, exploraremos el ciclo de vida del desarrollo de software (SDLC) y cómo el QA se integra en cada modelo.
