# 5. Diseño de Casos de Prueba

El diseño de casos de prueba es fundamental en el proceso de QA, ya que permite definir y documentar cómo se verificará que el software cumple con los requisitos establecidos. Un caso de prueba describe las condiciones, los datos de entrada, los pasos a seguir y los resultados esperados necesarios para validar una funcionalidad específica de la aplicación.

## ¿Qué es un Caso de Prueba?

Un **caso de prueba** es una especificación detallada que define las condiciones y los pasos que se deben seguir para probar una característica particular del software. Cada caso de prueba incluye entradas, resultados esperados y, en algunos casos, los datos necesarios para validar su correcto funcionamiento. Los casos de prueba son útiles no solo para validar la funcionalidad, sino también para documentar el proceso y servir como guía en pruebas futuras.

### Estructura de un Caso de Prueba

1. **Identificador**: Un código único para referenciar el caso de prueba.
2. **Título**: Un nombre claro que describa brevemente el objetivo del caso de prueba.
3. **Precondiciones**: Cualquier condición previa que deba cumplirse antes de ejecutar el caso de prueba (ej., usuario registrado).
4. **Pasos**: Las acciones que se deben realizar en el sistema para llevar a cabo el caso de prueba.
5. **Datos de Prueba**: Valores específicos de entrada para cada paso del caso de prueba.
6. **Resultado Esperado por Paso**: El resultado esperado en cada paso si la aplicación funciona correctamente.
7. **Resultado Real**: El resultado obtenido tras la ejecución del caso de prueba (solo se completa después de la prueba).
8. **Estado**: Indica si el caso de prueba fue exitoso o fallido.

#### Ejemplo de Caso de Prueba para una Función de Login:

- **Identificador**: TC001
- **Título**: Validar el inicio de sesión con credenciales correctas.
- **Precondiciones**: El usuario debe estar registrado con un nombre de usuario y contraseña válidos.
- **Pasos y Resultados Esperados**:

  1. **Paso 1**: Navegar a la página de inicio de sesión de la aplicación.
      - **Resultado Esperado**: La página de inicio de sesión se carga correctamente, mostrando los campos de usuario, contraseña y el botón "Iniciar sesión".
      
  2. **Paso 2**: Ingresar el nombre de usuario válido (`usuario_prueba`) en el campo "Usuario".
      - **Resultado Esperado**: El campo acepta el nombre de usuario sin errores ni advertencias.
      
  3. **Paso 3**: Ingresar la contraseña válida (`ContraseñaSegura123`) en el campo "Contraseña".
      - **Resultado Esperado**: El campo oculta los caracteres de la contraseña (por seguridad) y no muestra mensajes de error.
      
  4. **Paso 4**: Hacer clic en el botón "Iniciar sesión".
      - **Resultado Esperado**: El sistema valida las credenciales, y el usuario es redirigido a la página de inicio, mostrando un mensaje de bienvenida.

- **Datos de Prueba**:
  - Nombre de usuario: `usuario_prueba`
  - Contraseña: `ContraseñaSegura123`

- **Resultado Real**: *(a completar después de la prueba)*.
- **Estado**: *(Éxito/Fallo)*

Este nivel de detalle en cada paso permite identificar con precisión dónde ocurre un fallo, lo cual es esencial en pruebas manuales detalladas.

## Diferencia entre Casos de Prueba y Scripts de Prueba

- **Casos de Prueba**: Documentación detallada que especifica pasos, datos y resultados esperados para verificar una funcionalidad.
- **Scripts de Prueba**: Instrucciones de código en pruebas automatizadas para validar funcionalidades sin intervención manual. Requieren conocimientos de programación y suelen estar destinados a tareas repetitivas o con gran volumen de datos.

## Técnicas de Diseño de Pruebas

### Pruebas de Caja Negra

En las pruebas de caja negra, el tester no necesita conocer el código ni la lógica interna del sistema. Se enfoca en verificar la funcionalidad desde la perspectiva del usuario.

1. **Equivalencia de Partición**:
   - Agrupa los datos de entrada en particiones que representan valores equivalentes.
   - Ejemplo: En un campo de "edad" (que acepta entre 18 y 99), los valores se dividen en tres particiones: valores válidos (18-99), valores menores a 18 y valores mayores a 99. Se elige al menos un valor de cada partición para probar cómo responde el sistema.

2. **Análisis de Valores Límite**:
   - Enfoca la prueba en los valores extremos de los rangos de entrada.
   - Ejemplo: Para un campo que acepta edades entre 18 y 99, los límites a probar serían 18, 99 y valores cercanos como 17 y 100, ya que los errores suelen ocurrir en estos límites.

3. **Tablas de Decisión**:
   - Organiza y documenta las combinaciones de condiciones y sus resultados esperados en una tabla.
   - Ejemplo: En una aplicación de préstamos, la tabla incluiría variables como el "historial crediticio" y "salario mensual" para verificar si el préstamo se aprueba o rechaza. Cada combinación de condiciones lleva a un resultado específico, útil para asegurar que todas las combinaciones posibles se hayan probado.

4. **Transición de Estados**:
   - Se basa en cómo el sistema cambia de un estado a otro según diferentes acciones.
   - Ejemplo: En un sistema de cajero automático, los estados pueden incluir "Tarjeta Insertada", "PIN Verificado", "Retiro Procesado" y "Tarjeta Eyectada". Cada acción debe llevar al siguiente estado previsto.

### Pruebas de Caja Blanca

En las pruebas de caja blanca, el tester debe tener conocimientos sobre la estructura interna del sistema. Son más comunes en pruebas de desarrollo o automatización, pero en QA Manual es útil conocer los conceptos básicos.

1. **Cobertura de Código**:
   - Evalúa qué porcentaje del código se ejecuta durante las pruebas.
   - Ejemplo: En una función de cálculo que tiene varias condiciones, se prueban todas las rutas posibles de ejecución (caminos) para asegurarse de que se cubre completamente el código.

2. **Flujo de Datos**:
   - Analiza cómo se manipulan y se transfieren los datos en el sistema.
   - Ejemplo: En una función que procesa y almacena la información de un formulario de registro, se verifica que cada dato ingresado (nombre, email, etc.) pase correctamente por el proceso y se almacene de forma correcta y segura en la base de datos.

Estas técnicas de diseño de pruebas aseguran una cobertura adecuada y ayudan a detectar fallos potenciales en el sistema. Es fundamental documentar cada técnica y caso de prueba de forma clara, ya que sirve como referencia en pruebas futuras y garantiza que el sistema cumpla con los requisitos esperados.
