## Lab 2 – Modelación y Simulación

Este laboratorio explora tres tipos de sistemas dinámicos usando Python:

1. **Retardos de primer orden:**
   Se simula un sistema con entrada constante y salida proporcional al stock dividido entre el retardo. Se visualiza cómo el sistema alcanza el equilibrio de forma exponencial.

2. **Retroalimentación con retardo:**
   Se modela un sistema donde las decisiones se basan en información percibida con retraso. Se observa cómo esto puede generar oscilaciones y sobrecorrecciones.

3. **Modelo SIR (Sistemas no lineales):**
   Se implementa el modelo epidemiológico SIR y se simula su comportamiento en el tiempo, identificando el pico de infección y el umbral de inmunidad de grupo.

El código fue implementado usando `matplotlib`, `numpy` y `solve_ivp` de `scipy`.
