# Módulo 13: Preparación para Entrevistas de QA Manual

Este módulo está diseñado para ayudarte a destacar en entrevistas de QA manual. Cubriremos las preguntas más comunes, ejercicios prácticos que suelen solicitar, y cómo abordar problemas típicos que se presentan durante estas evaluaciones.

---

## 1. Preguntas comunes en entrevistas de QA Manual

Las entrevistas para roles de QA Manual suelen centrarse en evaluar tu conocimiento técnico, tu enfoque para resolver problemas y tu habilidad para comunicarte de manera efectiva. Aquí tienes una lista de preguntas frecuentes y consejos para responderlas:

### **Preguntas sobre conceptos básicos de QA:**
1. **¿Qué es QA y cuál es su importancia?**
   - **Respuesta sugerida:** 
     QA (Quality Assurance) es el proceso de garantizar que un producto cumpla con los estándares de calidad antes de ser lanzado. Es importante porque reduce riesgos, mejora la experiencia del usuario y asegura que el producto cumpla con los requisitos.

2. **¿Cuál es la diferencia entre QA, QC y Testing?**
   - **QA (Aseguramiento de la calidad):** Se enfoca en prevenir defectos.
   - **QC (Control de calidad):** Se enfoca en identificar defectos.
   - **Testing:** Es el proceso práctico de encontrar defectos mediante la ejecución de pruebas.

3. **¿Qué tipos de pruebas has realizado?**
   - Aquí puedes mencionar pruebas funcionales, de regresión, exploratorias, de compatibilidad, entre otras.

4. **¿Realizabas pruebas funcionales y no funcionales? Si realizabas no funcionales, ¿qué herramientas utilizabas?**
   - **Respuesta:** 
     - **Pruebas funcionales:** Validar que el sistema cumple con los requisitos funcionales, como la verificación de formularios o botones.
     - **Pruebas no funcionales:** Validar aspectos como rendimiento, seguridad y usabilidad. 
       - Ejemplos de herramientas:
         - **Rendimiento:** JMeter, LoadRunner.
         - **Seguridad:** OWASP ZAP, Burp Suite.
         - **Usabilidad:** Encuestas a usuarios, pruebas A/B.

### **Preguntas sobre técnicas de diseño de pruebas:**
5. **¿Cómo diseñarías casos de prueba para un botón de inicio de sesión?**
   - Respuesta sugerida: Diseñaría casos para validar:
     - Credenciales válidas e inválidas.
     - Campo vacío.
     - Límites en el tamaño del texto.
     - Seguridad (intentos de fuerza bruta).
     - Compatibilidad en distintos navegadores.

6. **¿Qué es una prueba de caja negra y cuándo la usarías?**
   - **Respuesta:** Es una técnica donde no se considera la lógica interna del código. Se usa para validar funcionalidades basadas en entradas y salidas esperadas.

### **Preguntas situacionales:**
7. **¿Qué harías si encuentras un defecto crítico en la víspera del lanzamiento?**
   - **Respuesta:** Informaría de inmediato al equipo, explicando el impacto del defecto y propondría posibles soluciones (como un parche post-lanzamiento o un cambio en la fecha).

8. **¿Cómo manejas conflictos con desarrolladores sobre un defecto?**
   - **Respuesta:** Me enfocaría en los datos y la evidencia, demostrando el problema con capturas de pantalla, pasos para reproducirlo y su impacto en el sistema.

---

## 2. Preguntas sobre tu experiencia diaria como QA

Estas preguntas buscan evaluar cómo gestionas tu tiempo y te relacionas con otros equipos.

### **1. ¿Cómo es tu día como QA?**
   - **Respuesta sugerida:** 
     Mi día como QA empieza con la **daily**, donde el equipo discute qué se hizo, qué se hará y si hay problemas o bloqueos. 
     Luego, dependiendo del día, puedo participar en:
     - **Planning:** Ayudamos a definir qué tareas o historias de usuario entrarán en el sprint, revisando criterios de aceptación y posibles riesgos.
     - **Ejecución de pruebas:** Diseño, ejecución y documentación de casos de prueba.
     - **Revisiones:** Validación de defectos corregidos o revisión de historias de usuario completadas.
     - **Retrospectiva:** Analizamos cómo mejorar procesos o identificar áreas de mejora en el equipo.

---

## 3. Ejercicios prácticos de diseño de casos de prueba

Es común que durante la entrevista te pidan diseñar casos de prueba para una funcionalidad sencilla. Aquí tienes ejemplos prácticos:

### **Ejemplo 1: Diseñar casos de prueba para un campo de búsqueda en una página web.**

| **ID** | **Caso de prueba**                                       | **Pasos**                                     | **Resultado esperado**                         |
|--------|----------------------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| 1      | Buscar una palabra válida                                | 1. Ingresar "QA". <br> 2. Presionar Enter.    | Mostrar resultados relevantes con "QA".       |
| 2      | Buscar palabra con caracteres especiales                | 1. Ingresar "$QA". <br> 2. Presionar Enter.   | Mostrar resultados relevantes o mensaje "No hay resultados". |
| 3      | Buscar dejando el campo vacío                           | 1. Dejar el campo en blanco. <br> 2. Presionar Enter. | Mostrar mensaje "Por favor, ingrese una palabra para buscar". |
| 4      | Probar límite máximo de caracteres en el campo de búsqueda | 1. Ingresar 256 caracteres. <br> 2. Presionar Enter. | Mostrar error o truncar texto al máximo permitido (e.g., 255 caracteres). |

---

### **Ejemplo 2: Diseñar casos de prueba para un carrito de compras.**

| **ID** | **Caso de prueba**                                        | **Pasos**                                     | **Resultado esperado**                         |
|--------|-----------------------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| 1      | Añadir un producto al carrito                             | 1. Seleccionar un producto. <br> 2. Clic en "Añadir al carrito". | Producto aparece en el carrito con el precio correcto. |
| 2      | Remover un producto del carrito                           | 1. Añadir un producto. <br> 2. Clic en "Eliminar". | El carrito queda vacío y se muestra mensaje "Tu carrito está vacío". |
| 3      | Validar cantidad máxima de un producto en el carrito      | 1. Seleccionar 100 unidades del mismo producto. | Mostrar mensaje de límite si excede (e.g., "Máximo permitido: 50 unidades"). |
| 4      | Probar la funcionalidad de "Pagar ahora" con carrito vacío | 1. No añadir productos. <br> 2. Clic en "Pagar ahora". | Mostrar mensaje "No hay productos en el carrito". |

---

## Conclusión

La clave para destacar en una entrevista de QA manual es demostrar tu conocimiento técnico, tu capacidad de análisis y tus habilidades de comunicación. Practica diseñar casos de prueba y resolver problemas típicos para estar preparado. ¡Recuerda que la práctica constante te dará confianza!
