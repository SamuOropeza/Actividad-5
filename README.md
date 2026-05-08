# Actividad 5: Memory Game - UX y Personalización Visual

Evolución del juego de memoria enfocada en la experiencia de usuario (UX), el manejo de estados de victoria y la personalización estética del entorno.

## Registro de Cambios (Version Control)

### Push 1: Interfaz y Precisión de Centrado
* **Métricas de Usuario:** Integración de un contador de clics (`taps`) dentro del diccionario de estado del juego para monitorear el desempeño.
* **Ajuste de Tipografía:** Uso de la propiedad `align="center"` y recalibración de coordenadas `goto()` para lograr el centrado geométrico de los caracteres dentro de cada celda.

### Push 2: Innovación de Contenido e Identidad Visual
* **Personalización de Imagen de Fondo:** Actualización del recurso gráfico del tablero mediante la carga de un archivo `.gif` externo, modificando la función `draw()` para integrar una identidad visual personalizada.
* **Estado:** Implementación de un validador mediante `any(hide)` para detectar el despeje total del tablero.
