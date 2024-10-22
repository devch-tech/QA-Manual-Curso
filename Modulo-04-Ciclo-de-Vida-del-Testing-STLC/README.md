# 🧪 **Ciclo de Vida del Testing (STLC)**

El **Ciclo de Vida del Testing (STLC)** es un proceso sistemático que define todas las actividades realizadas durante las fases de prueba de software. Es una parte esencial del desarrollo de software, que asegura que el producto final cumpla con los requisitos y estándares de calidad antes de ser lanzado. El STLC no solo se centra en encontrar errores, sino también en mejorar la calidad del producto desde las primeras fases del proyecto.

En este módulo, aprenderemos en detalle sobre las fases del STLC, las entradas y salidas necesarias para cada una, y cómo definir una estrategia de pruebas efectiva.

---

## 🗂️ **Fases del STLC**

### 1. **Planificación de Pruebas**
La fase de planificación es la primera en el STLC y se centra en definir el alcance, los objetivos y la estrategia de pruebas que se va a seguir durante el proyecto. Aquí se identifican los recursos necesarios (equipo, herramientas, ambientes de pruebas), se determinan los riesgos potenciales y se crean los cronogramas.

**Actividades clave:**
- Entender los requisitos del proyecto.
- Definir el alcance y los tipos de pruebas (funcionales, no funcionales, de seguridad, etc.).
- Estimar el tiempo y esfuerzo necesario para las pruebas.
- Identificar riesgos y definir un plan de mitigación.
- Seleccionar herramientas para la gestión y ejecución de pruebas.

**Entrada (Entry Criteria):**
- Requisitos del proyecto aprobados y definidos.
- Documento de diseño técnico disponible.
- Herramientas de pruebas seleccionadas.

**Salida (Exit Criteria):**
- Plan de pruebas documentado y aprobado.
- Estrategia de pruebas definida.
- Recursos asignados y cronograma de pruebas establecido.

**Ejemplo del mundo real:** Piensa en el lanzamiento de un nuevo smartphone. Antes de que llegue al mercado, la empresa debe planificar qué funciones se van a probar (llamadas, mensajes, cámara, batería), quién lo hará, cuánto tiempo tomará y qué riesgos existen (por ejemplo, problemas de rendimiento bajo ciertas condiciones).

---

### 2. **Diseño de Casos de Prueba**
En esta fase, se crean los **casos de prueba** detallados basados en los requisitos y criterios de aceptación del proyecto. Un caso de prueba es un conjunto de condiciones y pasos que se deben seguir para validar una funcionalidad específica del software.

**Actividades clave:**
- Revisar los requisitos para identificar qué funcionalidades necesitan ser probadas.
- Crear casos de prueba detallados que cubran todas las posibles situaciones, incluyendo pruebas positivas (funcionamiento esperado) y negativas (errores esperados).
- Diseñar los datos de prueba necesarios para ejecutar los casos de prueba.
- Revisar y validar los casos de prueba para asegurar que sean precisos y completos.

**Entrada (Entry Criteria):**
- Documentación de requisitos clara y aprobada.
- Plan de pruebas aprobado.
- Diseño técnico disponible.

**Salida (Exit Criteria):**
- Casos de prueba documentados, revisados y aprobados.
- Datos de prueba preparados.
- Entornos de prueba configurados para la ejecución.

**Ejemplo del mundo real:** Para una aplicación bancaria, un caso de prueba podría ser validar que un usuario pueda iniciar sesión correctamente con sus credenciales. Además, habría casos de prueba negativos para verificar qué ocurre si el usuario introduce una contraseña incorrecta o deja el campo en blanco.

---

### 3. **Ejecución de Pruebas**
Durante la fase de ejecución, se llevan a cabo los casos de prueba diseñados previamente. El equipo de QA ejecuta cada caso, registra los resultados y documenta cualquier defecto encontrado para ser corregido por el equipo de desarrollo.

**Actividades clave:**
- Ejecutar casos de prueba manualmente o mediante herramientas automatizadas.
- Comparar los resultados reales con los resultados esperados.
- Registrar cualquier desviación como defectos.
- Realizar pruebas de regresión para asegurar que las correcciones de errores no generen nuevos problemas en otras partes del sistema.

**Entrada (Entry Criteria):**
- Casos de prueba aprobados y listos.
- Ambiente de pruebas configurado.
- Datos de prueba cargados y disponibles.

**Salida (Exit Criteria):**
- Resultados de las pruebas documentados.
- Defectos registrados y comunicados al equipo de desarrollo.
- Pruebas de regresión completadas.

**Ejemplo del mundo real:** Imagina que estás probando la función de pago de una tienda en línea. Ejecutas los casos de prueba para verificar que los pagos se procesen correctamente usando diferentes métodos (tarjeta de crédito, PayPal, transferencia). Si encuentras que los pagos con tarjeta no funcionan, registras el defecto para que sea solucionado.

---

### 4. **Reporte de Pruebas**
La fase de reporte se centra en recopilar todos los resultados de las pruebas y generar informes detallados. Estos informes se utilizan para analizar el estado del proyecto, identificar posibles áreas problemáticas y decidir si el software está listo para el lanzamiento.

**Actividades clave:**
- Crear informes detallados sobre los resultados de las pruebas (cuántos casos de prueba se pasaron, cuántos fallaron, cuántos defectos se encontraron).
- Realizar un análisis para identificar tendencias (por ejemplo, si una funcionalidad específica tiene muchos errores recurrentes).
- Recomendar si el software está listo para avanzar a la siguiente fase o si se necesitan más pruebas.

**Entrada (Entry Criteria):**
- Ejecución de pruebas completada.
- Defectos registrados.

**Salida (Exit Criteria):**
- Informe de pruebas generado y compartido con las partes interesadas.
- Decisión tomada sobre la liberación del software o la necesidad de más pruebas.

**Ejemplo del mundo real:** Después de probar un sistema de reservas de vuelos, el equipo de QA prepara un informe que muestra cuántos casos de prueba se ejecutaron, cuántos pasaron y fallaron, y si los problemas encontrados afectan funciones críticas. Si se encuentran errores en la selección de asientos, se recomienda volver a probar después de las correcciones.

---

### 5. **Cierre de Pruebas**
El cierre de pruebas es la fase final del STLC, en la que el equipo verifica que todas las pruebas planificadas se hayan completado y que todos los defectos importantes se hayan resuelto. También se realiza una retrospectiva para identificar qué funcionó bien y qué podría mejorarse en futuros proyectos.

**Actividades clave:**
- Verificar que todos los casos de prueba planificados se hayan ejecutado.
- Asegurarse de que todos los defectos críticos se hayan solucionado.
- Realizar una retrospectiva del proyecto para documentar lecciones aprendidas.
- Archivar todos los artefactos de pruebas para referencia futura.

**Entrada (Entry Criteria):**
- Ejecución de pruebas completada.
- Todos los defectos críticos resueltos y verificados.

**Salida (Exit Criteria):**
- Informe final de cierre de pruebas.
- Documentación archivada.
- Retrospectiva completada y lecciones aprendidas documentadas.

**Ejemplo del mundo real:** Imagina que un equipo de QA ha terminado de probar una nueva actualización de software para un sistema de ventas minorista. Después de asegurarse de que todos los casos de prueba planificados se completaron y de que los errores críticos se resolvieron, realizan una reunión para discutir qué se podría mejorar en el futuro (por ejemplo, automatizar ciertas pruebas repetitivas para ahorrar tiempo).

---

## 🛠️ **Entrada y Salida (Entry & Exit Criteria) para cada Fase del STLC**

- **Planificación de Pruebas:**
  - *Entrada:* Requisitos claros y aprobados.
  - *Salida:* Plan de pruebas y estrategia definidos.
  
- **Diseño de Casos de Prueba:**
  - *Entrada:* Plan de pruebas aprobado.
  - *Salida:* Casos de prueba detallados y validados.
  
- **Ejecución de Pruebas:**
  - *Entrada:* Casos de prueba listos y ambiente de pruebas configurado.
  - *Salida:* Resultados de pruebas y reporte de defectos.
  
- **Reporte de Pruebas:**
  - *Entrada:* Resultados de la ejecución de pruebas.
  - *Salida:* Informe de pruebas y recomendaciones.
  
- **Cierre de Pruebas:**
  - *Entrada:* Todos los defectos críticos resueltos.
  - *Salida:* Informe de cierre y lecciones aprendidas.

---

## 📊 **Cómo Definir la Estrategia de Pruebas**

Definir una estrategia de pruebas es crucial para asegurar que las actividades de QA se alineen con los objetivos del proyecto. Una buena estrategia de pruebas debe incluir:

1. **Objetivos de Pruebas:** ¿Qué se busca lograr con las pruebas? (Ej.: asegurar la estabilidad, detectar errores en la funcionalidad clave, validar la experiencia del usuario).

2. **Tipos de Pruebas:** Determinar qué tipos de pruebas se van a realizar (funcionales, de rendimiento, de seguridad, pruebas automatizadas, etc.).

3. **Enfoque y Metodología:** ¿Se usará un enfoque ágil, cascada o DevOps? ¿Qué herramientas se utilizarán?

4. **Planificación del Ambiente de Pruebas:** Asegurar que los entornos sean similares a producción para que las pruebas sean realistas.

5. **Gestión de Riesgos:** Identificar posibles riesgos y establecer cómo se manejarán.

**Ejemplo:** En un proyecto ágil para una app de mensajería, la estrategia de pruebas podría incluir pruebas automatizadas para las funciones básicas (enviar y recibir mensajes), pruebas de rendimiento para asegurarse de que la app maneje miles de mensajes simultáneamente y pruebas de seguridad para proteger los datos de los usuarios.

---

Siguiendo estas fases y aplicando una estrategia bien definida, te aseguras de que tu proceso de testing sea eficiente, completo y contribuya a un producto final de alta calidad.

