# Control de Movimiento

El control de movimiento consiste en gestionar el movimiento mecánico de una carga. 

## Industrias de aplicación
- Empaque
- Ensamblaje
- Impresión
- Productos de madera
- Maquinaria
- Electrónica y semiconductores

## Ejes de movimiento
Eje (axis): Movimiento realizado por un actuador. 
Se pueden tener varios ejes de control para realizar una tarea.

## Variables a controlar
- Posición
- Velocidad
- Torque
- Aceleración

## Ejemplo CNC
Los sistemas de control de movimiento son fundamentales en máquinas CNC para realizar cortes y movimientos de precisión. Anteriormente, se usaba un único motor con un eje largo y diferentes engranajes para cambiar trayectorias y velocidades. Este método es menos flexible y más costoso en mantenimiento.
![Figura de prueba](imagenes/torno)
### Ejemplo
- Máquina Dobladora
- Máquina Etiquetadora

## Componentes del control de movimiento
- **Human-Machine Interface (HMI)**
- **Control de movimiento**
- **Drivers (potencia)**
- **Actuadores**
- **Mecanismos de transmisión**
- **Retroalimentación (sensores)**

## Características del control
- La fuerza negativa provocada por el movimiento debe ser compensada.
- Se debe controlar el torque para reducir el offset de velocidad.
- La dinámica de la velocidad debe ser rápida para garantizar trayectorias precisas.

## Esquema de control
### Lazo en cascada
Este esquema mejora la precisión y respuesta del sistema de control de movimiento.

## Aplicaciones prácticas
- **Transporte**: Cadenas de suministro automatizadas.
- **Maquinaria de bobinado**: Cortadoras y laminadoras.
- **Productos alimenticios**: Procesos automatizados.
- **Fabricación de semiconductores**: Aplicaciones fotográficas en wafers.
- **Ensamble de componentes electrónicos**.

## Ejemplos adicionales
1. **Brazo robótico**: Un robot de ensamblaje usa control de movimiento para posicionar piezas con precisión.
2. **Sistema de riego automatizado**: Un mecanismo controla el desplazamiento de los rociadores en una plantación.

## Ecuaciones
La ecuación básica del movimiento controlado:
\[ F = m \cdot a \]
Donde:
- \( F \) es la fuerza aplicada,
- \( m \) es la masa de la carga,
- \( a \) es la aceleración resultante.

## Figuras
1. Esquema de un sistema de control de movimiento.
2. Diagrama de un controlador PID en lazo cerrado.

## Tablas
| Componente | Función |
|------------|---------|
| HMI | Interfaz de usuario |
| Controlador | Gestiona el movimiento |
| Driver | Proporciona potencia |
| Actuadores | Ejecutan el movimiento |
| Sensores | Retroalimentación |

## Ejercicios
1. ¿Cuál es la diferencia entre un sistema de control de movimiento con lazo abierto y uno con lazo cerrado?
2. Diseña un sistema de control de movimiento para una banda transportadora en una fábrica.

## Conclusiones
- El control de movimiento es clave en la automatización industrial.
- Permite mejorar la precisión, eficiencia y flexibilidad de los sistemas mecánicos.
- La implementación de lazos de control mejora la estabilidad y el rendimiento.

## Referencias
- Ogata, K. *Ingeniería de control moderna*.
- Chen. *Diseño de sistemas de control analógicos y digitales*.
- Astrom, K. *Controladores PID: Teoría, diseño y sintonización*.
