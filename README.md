Entiendo que necesitas un README completo para tu repositorio de clasificación de residuos con IA. Basándome en el código de tu sistema, te ayudo a crear un README bilingüe (inglés y español).

## Answer

Aquí tienes un README completo para tu repositorio **Clasificador_de_Residuos_IA**:

```markdown
# AI Waste Classification System / Sistema de Clasificación de Residuos con IA

A real-time waste classification system using YOLOv8 and computer vision to identify and categorize different types of waste materials.

Un sistema de clasificación de residuos en tiempo real que utiliza YOLOv8 y visión por computadora para identificar y categorizar diferentes tipos de materiales de desecho.

## 🌟 Features / Características

### English
- **Real-time Detection**: Live camera feed with instant waste classification
- **5 Waste Categories**: Metal, Glass, Plastic, Cardboard, and Medical waste
- **Visual Feedback**: Color-coded bounding boxes and category images
- **High Accuracy**: Powered by YOLOv8 deep learning model
- **User-friendly Interface**: Clean Tkinter-based GUI

### Español
- **Detección en Tiempo Real**: Transmisión de cámara en vivo con clasificación instantánea
- **5 Categorías de Residuos**: Metal, Vidrio, Plástico, Cartón y Residuos médicos
- **Retroalimentación Visual**: Cajas delimitadoras codificadas por colores e imágenes de categorías
- **Alta Precisión**: Impulsado por el modelo de aprendizaje profundo YOLOv8
- **Interfaz Amigable**: GUI limpia basada en Tkinter

## 🚀 Quick Start / Inicio Rápido

### Prerequisites / Requisitos Previos

```bash
Python 3.8+
Webcam / Cámara web
```

### Installation / Instalación

1. **Clone the repository / Clona el repositorio**
```bash
git clone https://github.com/JoseBurgoss/Clasificador_de_Residuos_IA.git
cd Clasificador_de_Residuos_IA
```

2. **Install dependencies / Instala las dependencias**
```bash
pip install ultralytics opencv-python pillow imutils tkinter numpy
```

3. **Run the application / Ejecuta la aplicación**
```bash
python PROYECTO-IA-main/main.py
```

## 📁 Project Structure / Estructura del Proyecto

```
PROYECTO-IA-main/
├── main.py                 # Main application file / Archivo principal
├── Modelos/
│   └── best.pt            # YOLOv8 trained model / Modelo YOLOv8 entrenado
└── setUp/
    ├── Canva.png          # Background image / Imagen de fondo
    ├── metal.png          # Category images / Imágenes de categorías
    ├── vidrio.png
    ├── plastico.png
    ├── carton.png
    ├── medical.png
    ├── metaltxt.png       # Category text labels / Etiquetas de texto
    ├── vidriotxt.png
    ├── plasticotxt.png
    ├── cartontxt.png
    └── medicaltxt.png
```

## 🎯 How It Works / Cómo Funciona

### English
1. **Camera Initialization**: The system captures live video from your webcam [1](#0-0) 
2. **AI Processing**: Each frame is processed by the YOLOv8 model for object detection [2](#0-1) 
3. **Classification**: Detected objects are classified into 5 categories [3](#0-2) 
4. **Visual Feedback**: Results are displayed with colored bounding boxes and category images [4](#0-3) 

### Español
1. **Inicialización de Cámara**: El sistema captura video en vivo desde tu cámara web
2. **Procesamiento IA**: Cada frame es procesado por el modelo YOLOv8 para detección de objetos
3. **Clasificación**: Los objetos detectados se clasifican en 5 categorías
4. **Retroalimentación Visual**: Los resultados se muestran con cajas delimitadoras coloreadas e imágenes de categorías

## 🗂️ Waste Categories / Categorías de Residuos

| Category/Categoría | Color | RGB Value |
|-------------------|-------|-----------|
| Metal | Yellow/Amarillo | (255, 255, 0) |
| Glass/Vidrio | White/Blanco | (255, 255, 255) |
| Plastic/Plástico | Red/Rojo | (0, 0, 255) |
| Cardboard/Cartón | Gray/Gris | (150, 150, 150) |
| Medical/Médico | Blue/Azul | (255, 0, 0) |

## 🔧 Technical Details / Detalles Técnicos

### Core Components / Componentes Principales

- **Main Application**: `ventana_principal()` - Initializes GUI and starts detection loop [5](#0-4) 
- **Detection Loop**: `Scanning()` - Processes camera frames and performs classification [6](#0-5) 
- **Image Display**: `images()` - Updates GUI with category-specific visuals [7](#0-6) 

### Dependencies / Dependencias

- `ultralytics` - YOLOv8 implementation
- `opencv-python` - Computer vision operations
- `tkinter` - GUI framework
- `PIL` - Image processing
- `numpy` - Numerical operations

## 🎮 Usage / Uso

### English
1. Ensure your webcam is connected and working
2. Run the application using `python PROYECTO-IA-main/main.py`
3. Point objects at the camera to see real-time classification
4. The system will display bounding boxes around detected objects
5. Category images and labels will appear on the interface

### Español
1. Asegúrate de que tu cámara web esté conectada y funcionando
2. Ejecuta la aplicación usando `python PROYECTO-IA-main/main.py`
3. Apunta objetos hacia la cámara para ver la clasificación en tiempo real
4. El sistema mostrará cajas delimitadoras alrededor de los objetos detectados
5. Las imágenes y etiquetas de categorías aparecerán en la interfaz

## 🛠️ Troubleshooting / Solución de Problemas

### English
- **Camera not detected**: Ensure webcam drivers are installed and no other application is using the camera
- **Model not loading**: Verify that `best.pt` exists in the `Modelos/` directory
- **Missing images**: Check that all image files exist in the `setUp/` directory

### Español
- **Cámara no detectada**: Asegúrate de que los drivers de la cámara web estén instalados y ninguna otra aplicación esté usando la cámara
- **Modelo no carga**: Verifica que `best.pt` existe en el directorio `Modelos/`
- **Imágenes faltantes**: Verifica que todos los archivos de imagen existan en el directorio `setUp/`

## 📄 License / Licencia

This project is open source. Feel free to contribute and improve the system.

Este proyecto es de código abierto. Siéntete libre de contribuir y mejorar el sistema.

## 👨‍💻 Author / Autor

Jose Burgos - [GitHub](https://github.com/JoseBurgoss)
```

![Canva](https://github.com/user-attachments/assets/9c29a457-b6c8-4091-8576-8f19bee6ae6f)
![carton](https://github.com/user-attachments/assets/a0a76199-24ba-437b-be8b-c86eb2f20eb3)
![cartontxt](https://github.com/user-attachments/assets/3544e4f9-2420-4d48-814e-2bb41492cc1e)
![medical](https://github.com/user-attachments/assets/93f50cde-ed59-4dc6-a4f4-4b07672de6fd)
![medicaltxt](https://github.com/user-attachments/assets/36d1e2ce-3cc7-4e6a-8b41-3ab3666fe704)
![metal](https://github.com/user-attachments/assets/45cda1d9-9de2-472d-9c5c-ec811c9706a8)
![metaltxt](https://github.com/user-attachments/assets/670d0f64-8c39-4427-9643-a7c87b6b0ea7)
![plastico](https://github.com/user-attachments/assets/890e3fe4-03bb-40af-bfbc-34226c2b071f)
![plasticotxt](https://github.com/user-attachments/assets/cdbd2f13-dbca-4e47-b7e1-d95d3e599243)
![vidrio](https://github.com/user-attachments/assets/fc0040c0-b5fc-460f-8f4e-cfe1b11ac0e2)
![vidriotxt](https://github.com/user-attachments/assets/68f05855-b01a-4f6c-8aa2-0328371f17bc)
