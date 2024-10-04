
# Clasificación de Especies de Aves a Partir de Audio 🎶🦜

## Descripción del Proyecto 📄
Este proyecto utiliza técnicas de Machine Learning para la clasificación automática de especies de aves a partir de señales de audio. El objetivo principal es identificar las vocalizaciones de distintas especies en el Parque Natural Aiguamolls del Empordà, utilizando un enfoque basado en redes neuronales y técnicas de procesamiento de señales.

El proyecto integra modelos como Redes Neuronales Artificiales (ANN), Random Forest, Decision Tree y Redes Neuronales Convolucionales (CNN) para lograr una clasificación precisa y eficiente.

## Estructura del Proyecto 📂
1. **`Codigo_Pajaros.ipynb`:** Cuaderno Jupyter con el desarrollo del modelo de clasificación.
2. **`Informe_Clasificacion_Aves.pdf`:** Informe detallado con la metodología, resultados y análisis de las especies clasificadas.
3. **`requirements.txt`:** Archivo con las dependencias necesarias para ejecutar el proyecto.
4. **`data/`:** Carpeta opcional que puede incluir ejemplos de audios utilizados para la clasificación (no incluida en esta versión por limitaciones de espacio).

## Fuente de Datos 📁
Los audios y espectrogramas necesarios para reproducir el análisis deben descargarse desde el siguiente enlace:

- **[Dataset de audios de aves en Zenodo](https://zenodo.org/records/7505820#.Y8U4f3bMKUk)**

Asegúrate de colocar el archivo descargado en la carpeta `data/` dentro del proyecto local.

## Requisitos para Ejecutar el Proyecto 🛠️
1. Clona este repositorio en tu máquina local:
    ```bash
    git clone https://github.com/tu-usuario/Bird_Species_Classification.git
    ```
2. Instala las dependencias necesarias:
    ```bash
    pip install -r requirements.txt
    ```

3. Descarga los datos desde Zenodo y colócalos en la carpeta `data/` con la estructura correcta.
4. Ejecuta el cuaderno `Codigo_Pajaros.ipynb` para reproducir el análisis y los resultados.

## Resultados 🔍
El modelo de Redes Neuronales Artificiales (ANN) obtuvo un `88%` de precisión, superando a otros enfoques como Decision Tree y Random Forest. Se evaluaron métricas como **Recall**, **Precision** y **F1-Score**, detalladas en el informe adjunto.

## Contacto 📧
David M. López Sandoval  
Correo: [lopezsandovaldavidmauricio@gmail.com](mailto:lopezsandovaldavidmauricio@gmail.com)  
LinkedIn: [David M. López Sandoval](https://www.linkedin.com/in/ingenierodavidlopezsandoval/)
