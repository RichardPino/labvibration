# LabVibration — Laboratorio Virtual de Vibraciones Estructurales

Aplicación web interactiva diseñada para analizar el movimiento armónico amortiguado y la frecuencia natural de oscilación de una estructura mediante el acelerómetro de un smartphone o el modo de simulación integrado.

## Cómo usar la aplicación
1. Abre la web app desde el enlace activo de GitHub Pages en tu teléfono o computador.
2. Selecciona **Modo Simulación** (ajusta masa, rigidez y amortiguamiento) o **Sensor Real** (activa el acelerómetro del dispositivo).
3. Presiona **Iniciar Captura** para visualizar en tiempo real el gráfico de aceleración ($\text{m/s}^2$) versus tiempo ($\text{s}$) y los indicadores calculados.
4. Registra al menos 5 repeticiones en la tabla de validación para revisar promedios, dispersión y error respecto al valor de referencia.

## Estructura del proyecto
- `index.html`: Interfaz web responsiva, motor de simulación/lectura de sensores y visualización gráfica con Chart.js.
- `README.md`: Documentación general, instrucciones de uso y trazabilidad del repositorio.
