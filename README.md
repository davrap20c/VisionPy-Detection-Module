# VisionPy-Detection-Module
Módulo de visión artificial en Python para la detección de patrones faciales en tiempo real utilizando OpenCV y procesamiento de matrices con NumPy.



# VisionPy: Módulo de Detección Biométrica en Tiempo Real 👁️

Este proyecto consiste en el desarrollo de un módulo de visión artificial capaz de procesar flujos de vídeo en vivo para la identificación de rostros. El objetivo principal es demostrar la integración de técnicas de procesamiento de imágenes y la gestión eficiente de recursos del sistema en entornos locales.

## 🌟 Funcionalidades
- **Detección en tiempo real:** Captura y análisis de frames mediante cámara web con latencia mínima.
- **Preprocesamiento Óptimo:** Implementación de filtros de escala de grises para reducir la carga computacional del procesador.
- **Identificación por Patrones:** Uso de clasificadores Haar Cascade para la detección precisa de rasgos biométricos.
- **Control de Usuario:** Gestión de eventos de teclado para el cierre seguro de procesos y liberación de hardware.

## 🛠️ Stack Tecnológico
- **Lenguaje:** Python 3.x
- **Librerías:** - `OpenCV`: Motor de visión computacional.
  - `NumPy`: Procesamiento de los frames como estructuras matriciales.

## 📥 Instalación y Uso rápido

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/davrap20c/VisionPy-Detection-Module.git](https://github.com/davrap20c/VisionPy-Detection-Module.git)
   cd VisionPy-Detection-Module


2. **Preparar el entorno e instalar dependencias:**
   python3 -m venv venv
   source venv/bin/activate
   pip install opencv-python numpy


3. **Ejecución:**
   python3 detector.py
