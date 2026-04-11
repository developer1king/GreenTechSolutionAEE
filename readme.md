Aquí tienes el contenido listo en formato Markdown limpio:

```md
# GreenTech Solutions - Auditoría y Optimización de Software Verde

Este documento explica cómo se transformó el código original en una aplicación de Software Verde (*Green Software*), optimizada para reducir su impacto ambiental. Para lograrlo, se aplicaron principios clave de eficiencia energética, de carbono y de uso de hardware.

## Filosofía de optimización

La reestructuración parte de los principios que siguen los profesionales del software sostenible: reducir emisiones de carbono sin importar el lenguaje o el framework que se utilice. Más que cambiar herramientas, se trata de optimizar decisiones.

## 1. Eliminación de “software inflado” (*bloatware*)

Desde el punto de vista energético, lo ideal es evitar cualquier procesamiento innecesario.

- **Qué se hizo:** Se eliminaron librerías como jQuery y Moment.js.  
- **Impacto:** Usar scripts pesados para tareas simples (por ejemplo, mostrar un año) consume recursos de más. Al quitarlos, se reduce la carga de trabajo en la CPU del usuario y, con ello, la Intensidad de Carbono del Software (SCI), ya que se evitan cálculos que realmente no aportan valor.

## 2. Eficiencia de carbono: menos transferencia, menos emisiones

Gran parte del impacto ambiental del software viene del movimiento de datos en la red.

- **Qué se hizo:** Se eliminaron enlaces externos como Bootstrap, FontAwesome y Google Fonts.  
- **Impacto:** Cada petición HTTP adicional implica consumo energético en servidores, redes y dispositivos. Con esta optimización, la aplicación funciona con una sola petición (el HTML), logrando un nivel muy alto de eficiencia en este aspecto.

## 3. Eficiencia de hardware: uso inteligente de recursos gráficos

El software verde también busca sacar el máximo provecho del hardware existente.

- **Imágenes:** Se reemplazó una imagen de alta resolución de Unsplash por un degradado hecho con CSS. Esto evita cargas pesadas y reduce el trabajo de la GPU al procesar imágenes.  
- **Fuentes:** Se dejó de usar la fuente “Montserrat” y se optó por `system-ui`. Así se eliminan tiempos de carga, bloqueos de renderizado y dependencias externas.

## 4. Evaluación en “tiempo de creación” (inspirado en WGSL)

Se tomó como referencia la lógica de optimización de WGSL (WebGPU Shading Language), donde ciertas operaciones se resuelven antes de ejecutarse.

- **Constantes vs variables:** En WGSL, lo que se define como constante no se calcula en tiempo de ejecución.  
- **Aplicación práctica:** El año del footer se dejó como texto fijo. De esta forma, se evita que el navegador ejecute scripts innecesarios cada vez que carga la página, similar a cómo un shader optimizado evita cálculos en la GPU.

Este proyecto demuestra que es posible reducir el impacto ambiental del software desde el diseño y la implementación, alineándose con los compromisos climáticos mediante una ingeniería más consciente y eficiente.
```
