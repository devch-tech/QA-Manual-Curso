# Módulo 10: Automatización de Pruebas - Introducción para QA Manual

## Introducción
La automatización de pruebas es el uso de herramientas y scripts para realizar pruebas de software de manera automática, con el objetivo de aumentar la eficiencia y cobertura del proceso de pruebas. En este módulo, exploraremos los fundamentos de la automatización de pruebas, sus ventajas y desventajas, y cuándo es recomendable aplicarla.

---

## 1. ¿Cuándo automatizar y cuándo no?
### Casos ideales para automatizar:
- **Pruebas repetitivas**: Aquellas que necesitan ser ejecutadas frecuentemente, como pruebas de regresión.
- **Pruebas de alto riesgo**: Escenarios críticos que requieren validación constante.
- **Pruebas que requieren grandes volúmenes de datos**: Automatizar permite realizar pruebas con diferentes conjuntos de datos rápidamente.
- **Pruebas que necesitan ser ejecutadas en múltiples entornos**: Asegura que la aplicación funcione de manera consistente en diferentes plataformas.

### Casos donde NO es ideal automatizar:
- **Pruebas de usabilidad**: Requieren la evaluación subjetiva de un humano.
- **Pruebas ad hoc/exploratorias**: Necesitan de la intuición y análisis humano.
- **Pruebas que se ejecutan solo una vez**: No es eficiente invertir tiempo en automatizar algo que no se repetirá.

---

## 2. Diferencias entre QA Manual y Automatizado
### QA Manual:
- **Proceso**: Implica la ejecución manual de casos de prueba por parte de un tester.
- **Flexibilidad**: Permite al tester observar aspectos subjetivos como la experiencia del usuario.
- **Costo**: Generalmente menor al inicio, pero se vuelve más costoso en pruebas repetitivas.

### QA Automatizado:
- **Proceso**: Usa scripts y herramientas para ejecutar pruebas sin intervención humana.
- **Eficiencia**: Reduce el tiempo de ejecución de pruebas masivas y repetitivas.
- **Mantenimiento**: Puede requerir un alto costo de mantenimiento de scripts y frameworks.

**Ejemplo**:
- *QA Manual*: Un tester verifica manualmente que los botones de una aplicación respondan correctamente.
- *QA Automatizado*: Un script de Selenium verifica automáticamente el comportamiento de los botones en múltiples navegadores.

---

## 3. Ventajas y Desventajas de la Automatización
### Ventajas:
- **Ahorro de tiempo**: Las pruebas que se ejecutan automáticamente son mucho más rápidas que las manuales.
- **Mayor cobertura de pruebas**: Permite validar más escenarios y casos de prueba.
- **Repetibilidad**: Las pruebas pueden ejecutarse tantas veces como se necesite con los mismos resultados.
- **Detección temprana de defectos**: La ejecución regular de pruebas automatizadas ayuda a identificar problemas en etapas tempranas del desarrollo.

### Desventajas:
- **Alto costo inicial**: Se necesita tiempo y recursos para desarrollar scripts y configurar herramientas.
- **Mantenimiento de scripts**: Los cambios en la aplicación pueden requerir actualizaciones frecuentes en los scripts de prueba.
- **No apto para pruebas subjetivas**: La automatización no puede evaluar la experiencia del usuario o aspectos creativos.

---

## 4. Herramientas Populares de Automatización (Introducción)
### 1. **Selenium**:
- **Descripción**: Una de las herramientas más populares para la automatización de pruebas web.
- **Características**: Permite escribir scripts en múltiples lenguajes como Java, Python y C#.
- **Uso**: Ideal para pruebas de regresión y pruebas funcionales en aplicaciones web.

### 2. **Appium**:
- **Descripción**: Herramienta de código abierto para pruebas de aplicaciones móviles (iOS y Android).
- **Características**: Soporta múltiples lenguajes y plataformas, ideal para proyectos móviles.
- **Ejemplo de uso**: Automatizar la prueba de inicio de sesión en una app móvil.

### 3. **Cypress**:
- **Descripción**: Herramienta moderna para la automatización de pruebas web, con enfoque en aplicaciones de una sola página (SPA).
- **Características**: Ofrece una experiencia de prueba rápida y fácil de configurar.
- **Ventajas**: Integración directa con el código y pruebas en tiempo real.

**Ejemplo de script en Selenium (Java)**:
```java
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class TestLogin {
    public static void main(String[] args) {
        System.setProperty("webdriver.chrome.driver", "ruta/al/driver/chromedriver");
        WebDriver driver = new ChromeDriver();
        driver.get("https://ejemplo.com/login");

        // Pasos para automatizar la prueba de inicio de sesión
        // (Buscar elementos, interactuar y verificar resultados)
        
        driver.quit();
    }
}
