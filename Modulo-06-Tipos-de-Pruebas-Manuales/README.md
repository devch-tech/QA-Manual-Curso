# Módulo 6: Tipos de Pruebas Manuales

## Introducción
En este módulo, abordaremos los diferentes tipos de pruebas manuales esenciales en el proceso de aseguramiento de calidad (QA). Cada tipo de prueba cumple un rol específico y nos ayuda a garantizar que el software cumpla con los requisitos funcionales y no funcionales.

---

## 1. Pruebas Funcionales
Estas pruebas verifican que el sistema cumple con los requisitos y especificaciones definidas. Se centran en probar lo que hace el sistema desde el punto de vista del usuario, asegurando que las funcionalidades respondan correctamente.

- **Casos de Uso**: Prueban escenarios específicos de interacción entre el usuario y el sistema, asegurando que las funcionalidades se comporten según lo esperado.
  
  **Ejemplo**: En una aplicación de banco, un caso de uso puede ser verificar que un usuario pueda realizar una transferencia correctamente.

- **Escenarios**: Describen situaciones en las que los usuarios interactúan con el sistema. Los escenarios ayudan a estructurar las pruebas funcionales y guían los casos de prueba.

  **Ejemplo**: Probar un proceso de registro, donde el usuario introduce sus datos y recibe un mensaje de confirmación.

- **Validación de Requerimientos**: Verifica que cada requerimiento funcional se cumpla.

  **Ejemplo**: Si el sistema requiere autenticación, las pruebas funcionales verificarán que sólo los usuarios autorizados puedan acceder.

---

## 2. Pruebas de Regresión
Aseguran que nuevas funcionalidades o correcciones no afecten las partes ya implementadas. Estas pruebas vuelven a ejecutar casos previamente aprobados para validar que todo sigue funcionando correctamente.

- **Cómo identificar y seleccionar casos para regresión**: Al implementar un cambio en el sistema, se identifican los módulos y funcionalidades impactados para seleccionar casos de prueba relevantes.

  **Ejemplo**: Después de actualizar el módulo de pago de una app de e-commerce, las pruebas de regresión comprueban que el carrito de compras y el proceso de checkout aún funcionan correctamente.

---

## 3. Pruebas Exploratorias
Consisten en explorar el sistema de forma libre y sin guías predefinidas, buscando errores y comportamientos inusuales. En estas pruebas, el tester se basa en su experiencia e intuición.

- **Técnicas y enfoques**: Las pruebas exploratorias no siguen un guion estricto; se exploran diferentes funcionalidades, interacciones y combinaciones de acciones.

- **Documentación de resultados**: Aunque no se planifican previamente, es esencial documentar cualquier error encontrado o comportamiento inesperado.

  **Ejemplo**: En una app móvil, el tester explora la navegación entre pantallas de perfil y configuración, documentando cualquier problema de interfaz o funcionalidad.

---

## 4. Pruebas de Usabilidad
Evalúan qué tan fácil es para el usuario interactuar con el sistema, identificando problemas de diseño e interfaz.

- **Criterios de Evaluación**: La usabilidad se evalúa según la facilidad de uso, eficiencia, accesibilidad y satisfacción del usuario.

- **Herramientas de seguimiento**: Herramientas como Hotjar o Google Analytics pueden ayudar a observar la interacción del usuario y detectar puntos problemáticos.

  **Ejemplo**: En una app de salud, se realiza una prueba de usabilidad para asegurar que los usuarios puedan ingresar datos de manera rápida y sin confusión.

---

## 5. Pruebas de Compatibilidad
Verifican que el software funcione correctamente en distintos dispositivos, navegadores y sistemas operativos.

- **Dispositivos**: Prueban el funcionamiento en una variedad de dispositivos, como móviles, tablets y computadoras.

- **Navegadores**: Aseguran que la aplicación se vea y funcione bien en Chrome, Firefox, Safari, entre otros.

- **Sistemas Operativos**: Verifican que el software funcione correctamente en Windows, macOS, iOS, Android, etc.

  **Ejemplo**: En una web de e-commerce, se prueba que el proceso de pago funcione igual de bien en Android e iOS.

---

## 6. Pruebas de Seguridad (básicas)
Validan que el sistema esté protegido contra accesos no autorizados, garantizando la confidencialidad, integridad y disponibilidad de los datos.

- **Validaciones de autenticación y autorización**: Aseguran que sólo usuarios autorizados tengan acceso a funcionalidades y datos específicos.

- **Manejo de errores**: Verifican que los mensajes de error no revelen información sensible.

  **Ejemplo**: En una plataforma bancaria, las pruebas de seguridad comprueban que los usuarios no puedan acceder a cuentas ajenas.

---

## Otros Tipos de Pruebas Manuales

### Pruebas de Integración
Verifican la correcta interacción entre los distintos módulos del sistema, asegurando que los componentes trabajen juntos sin problemas.

- **Ejemplo**: En un sistema de reserva de vuelos, las pruebas de integración comprueban que el sistema de pagos se comunique correctamente con el sistema de reservas.

### Pruebas de Aceptación del Usuario (UAT)
Aseguran que el sistema cumple con las expectativas del usuario final y esté listo para su implementación. Se realizan en un entorno similar al de producción.

- **Ejemplo**: En una aplicación bancaria, las pruebas UAT validan que los usuarios puedan realizar transferencias y pagos sin problemas.

### Pruebas de Carga
Evalúan el rendimiento del sistema bajo condiciones específicas de carga.

- **Ejemplo**: En un portal de e-commerce, las pruebas de carga verificarían que el sistema pueda manejar múltiples usuarios simultáneos durante una campaña de descuentos.

### Pruebas de Instalación y Desinstalación
Aseguran que el software se instale y desinstale correctamente sin afectar el sistema.

- **Ejemplo**: Al instalar una aplicación en Windows, se verifica que los archivos necesarios se instalen correctamente y que la desinstalación los elimine sin dejar residuos.

---

Este módulo ofrece una visión completa de los diferentes tipos de pruebas manuales fundamentales en QA, asegurando que el software no sólo funcione según los requisitos, sino que también sea robusto, seguro, y amigable para el usuario.
