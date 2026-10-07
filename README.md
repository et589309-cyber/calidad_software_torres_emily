# Calidad del Software

Este repositorio está orientado a la materia de Calidad del Software y reúne conceptos básicos sobre cómo asegurar que un sistema sea útil, confiable y mantenible.

## ¿Qué es la calidad del software?

La calidad del software hace referencia a qué tan bien un sistema cumple con los requisitos funcionales y no funcionales esperados por los usuarios y la organización. Un software de calidad no solo funciona, sino que también es:

- Confiable: realiza tareas sin fallas inesperadas.
- Mantenible: es fácil de entender, modificar y extender.
- Seguro: protege datos y evita vulnerabilidades.
- Usable: permite una experiencia clara para el usuario.
- Eficiente: usa recursos de forma adecuada.
- Escalable: puede crecer sin perder rendimiento ni estabilidad.

## Conceptos básicos

### Requisitos
Los requisitos describen lo que debe hacer el sistema y las condiciones que debe cumplir. Pueden ser funcionales (qué debe hacer) y no funcionales (rendimiento, seguridad, usabilidad, disponibilidad, etc.).

### Verificabilidad
Un sistema es más fácil de validar cuando sus resultados pueden medirse o comprobarse de forma objetiva. Esto permite detectar errores antes de que lleguen al usuario final.

### Mantenimiento
El mantenimiento incluye correcciones, mejoras y adaptaciones del software a lo largo de su ciclo de vida. Un código limpio y bien documentado facilita este proceso.

### Riesgo
El riesgo aparece cuando un defecto, falta de seguridad o mala decisión de diseño puede afectar la operación, la calidad o la confianza del producto.

### Mejora continua
La calidad del software no se logra solo al final del proyecto; debe cuidarse durante todo el ciclo de desarrollo con revisión, pruebas y ajustes constantes.

## Pruebas de software

Las pruebas permiten verificar que el sistema se comporte como se espera y ayudar a detectar errores antes de producción.

### Pruebas unitarias
Las pruebas unitarias validan unidades pequeñas de código, como funciones o métodos, de forma aislada. Su objetivo es comprobar que cada parte del software haga lo que se espera.

Beneficios:
- Detectan errores tempranamente.
- Facilitan la refactorización.
- Mejoran la confianza en el código.
- Son rápidas de ejecutar.

Ejemplo:
- Verificar que una función de suma retorne el resultado correcto.
- Probar validaciones de entrada en una función de registro.

### Pruebas E2E (End-to-End)
Las pruebas E2E simulan escenarios reales del usuario final, verificando que el sistema funcione de extremo a extremo. Evalúan la interacción entre módulos, interfaces, backend y flujo completo de negocio.

Beneficios:
- Validan el comportamiento real del sistema.
- Detectan fallos entre componentes.
- Ayudan a asegurar una experiencia de usuario correcta.

Ejemplo:
- Iniciar sesión en una aplicación web.
- Completar un formulario y confirmar que la información se guarda correctamente.
- Comprar un producto desde la interfaz hasta la confirmación final.

## Diferencia entre pruebas unitarias y E2E

Las pruebas unitarias se enfocan en piezas pequeñas y aisladas del código; las pruebas E2E se enfocan en el sistema completo como lo usa un usuario real.

En general:
- Unitarias: rápidas, gran cobertura de lógica interna.
- E2E: más lentas, pero validan flujos completos y experiencia de usuario.

Lo ideal es combinar ambas: pruebas unitarias para lógica y E2E para validar escenarios críticos del producto.

## Buenas prácticas en calidad de software

- Escribir código claro y mantenible.
- Realizar pruebas frecuentes durante el desarrollo.
- Documentar funciones, decisiones y flujos.
- Revisar código y aplicar estándares del equipo.
- Automatizar pruebas en procesos de integración continua.
- Usar métricas simples para evaluar calidad, como cobertura de pruebas y cantidad de defectos detectados.

## Conclusión

La calidad del software se logra mediante una combinación de buenas prácticas, diseño sólido y pruebas adecuadas. Las pruebas unitarias y las pruebas E2E son herramientas clave para asegurar que el software no solo funcione, sino que también sea confiable, útil y sostenible a lo largo del tiempo.
