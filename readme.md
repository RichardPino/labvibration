# LabVibration — Laboratorio Virtual de Vibraciones Estructurales

**Asignatura:** Proyecto de Innovación Tecnológica · Universidad Mayor  
**Autor:** Richard Pino (Modalidad Individual — Ingeniería Civil Industrial)  
**Docente:** Prof. Ana G. E. Jorquera F.

---

## Descripción del Proyecto
**LabVibration** es una aplicación web responsiva diseñada como un laboratorio móvil de bajo costo que permite a estudiantes analizar experimentalmente la vibración libre amortiguada de estructuras flexibles utilizando el acelerómetro integrado de un smartphone o un motor de simulación dinámica en tiempo real.

## Características Principales
* **Modo Dual de Captura:**
  * **Sensor Real:** Lectura directa del acelerómetro del teléfono mediante `DeviceMotionEvent` (eje Z).
  * **Simulación Paramétrica:** Ajuste interactivo de masa ($m$), rigidez ($k$) y razón de amortiguamiento ($\xi$).
* **Visualización Científica:** Gráfico cartesiano dinámico de *Aceleración ($m/s^2$) vs. Tiempo ($s$)* construido con **Chart.js**.
* **Cálculo Automático:** Obtención instantánea de frecuencia natural ($f_n$) y amplitud máxima ($A_0$).
* **Protocolo de Validación Experimental:** Tabla de registro para las 5 repeticiones obligatorias con cálculo automático de promedio y desviación estándar ($\sigma$).

## Instrucciones de Uso y Ejecución
1. **Ejecución en línea (GitHub Pages):** Abrir directamente la URL pública del proyecto desde el navegador de un teléfono inteligente o computador.
2. **Ejecución local:** Descargar el archivo `index.html` y abrirlo con doble clic en cualquier navegador moderno (Chrome, Safari, Edge o Firefox).
3. **Uso con Sensor Real:** Seleccionar **Sensor Real**, presionar **Solicitar Permiso de Sensores**, fijar el teléfono a la estructura flexible y presionar **Iniciar Ensayo**.

## Estructura del Repositorio
```text
labvibration/
├── index.html                        # Interfaz web principal (MVP integrado)
├── README.md                         # Documentación técnica e instrucciones de uso
└── docs/
    ├── guia_laboratorio_v1.pdf       # Guía de laboratorio del estudiante (Puntos 1 al 17)
    └── informe_tecnico_gate4.pdf     # Informe Técnico de Avance Gate 4
```