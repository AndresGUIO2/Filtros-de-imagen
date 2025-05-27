# Filtros de Procesamiento de Imágenes con OpenCV

Este proyecto contiene un análisis práctico de diferentes filtros espaciales usados en procesamiento digital de imágenes. Todo se desarrolla en un Jupyter Notebook usando Python, NumPy y OpenCV.

## 🧪 Contenido del notebook

El notebook guía paso a paso la aplicación de los siguientes filtros:

- 📊 **Filtro de Media** – suavizado lineal
- 📈 **Filtro de Mediana** – eliminación de ruido tipo sal y pimienta
- 🌙 **Filtro Logarítmico** – realce en zonas oscuras
- 🔳 **Filtro de Cuadro Normalizado** – suavizado uniforme
- 🌫️ **Filtro Gaussiano** – suavizado suave con conservación de bordes
- 🌀 **Filtro de Laplace** – detección de bordes por segunda derivada
- 🔀 **Filtro de Sobel** – detección de bordes por gradiente
- 🎯 **Filtro de Canny** – detección avanzada de contornos con umbral doble

Cada filtro incluye:

- Descripción matemática
- Ejemplo conceptual
- Implementación en código Python con OpenCV
- Comparación visual de resultados

---

## ⚙️ Requisitos

Este proyecto utiliza Python y se recomienda trabajar en un entorno virtual con Conda.

### 📁 Instalar el entorno Conda

```bash
conda env create -f environment.yml
conda activate filtros-imagenes
