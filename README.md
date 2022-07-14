# MONITORIZACION DE COBERTURAS DE AGUA SUPERFICIAL
El Cambio Climático está provocando temperaturas más cálidas que aumentan la evaporación del suelo, haciendo que los períodos con bajas precipitaciones sean  más  secos  que  en  condiciones  más  frías,  contribuyendo  al  fortalecimiento  de  un problema  ya  conocido  la  sequía.  La  sequía  a  pesar  de  la  pandemia  del  Covid-19,  sigue 
afectando a varias regiones de Bolivia (Oruro, Potosí, Cochabamba, Sucre, Tarija, Santa Cruz y La Paz), provocados por fenómenos climáticos. Las temporadas de lluvia en todo el territorio de Bolivia, provocan según la morfología y la composición del suelo cambios en la cobertura de suelo,   este  elemento  vital generalmente  se  desperdicia  en  épocas  de  sequía  por  lo  cual  mediante  una  correcta monitorización permitiria la creación de atajados artificiales (geomembranas), que brinden agua para el consumo  humano  y  productivo  de  comunidades  alejadas  de  centros  urbanos o brinden datos útiles para reorientar las politicas públicas de cambio climatico 

## Titulo del Repositorio
Modelo de segmentación de superficies de agua del proyecto HackCities desarrollado con Google Earth Engine y TensorFlow. 

## Motivación
El proyecto busca monitorear la cobertura de agua en una región especifica, para desarrollar mejores politicas ambientales en pro de preservar y/o utilizar de manera mas eficiente nuestras fuentes de agua naturales.

## Capturas de pantalla
Imagenes de la región objetivo para las pruebas del modelo: Laguna Alalay

Región objetivo de la imagen en formato RGB 

![image](https://user-images.githubusercontent.com/1416275/178981759-fc469836-6b14-407e-8e77-d7331348d104.png)

Aplicación de la conversion de bandas de tipo de clasificación a la Region objetivo para obtener los tipos de cobertura.

![image](https://user-images.githubusercontent.com/1416275/178982849-8f5ca1ef-9f87-41fa-8fac-fac405e02e82.png)

Modelo Convolucional aplicado

![image](https://user-images.githubusercontent.com/1416275/178983246-ad6a2cd2-d4e0-4f70-aea2-30784201566f.png)

Gráficos de entrenamiento y validación

![image](https://user-images.githubusercontent.com/1416275/178983895-6f25cbd6-6b57-4477-bf18-4bac3eacd6d5.png)

Resultados del modelo, observamos los cambios en el terreno.

Obtenemos imagenes y sus predicciones, en nuestro caso un terreno ubicado en el departamento de Cochabamba cerca a Coari.

![img](https://user-images.githubusercontent.com/1416275/178984453-41965a1e-66ee-4c3d-902e-4eb7a0001de0.png)

![image](https://user-images.githubusercontent.com/1416275/178984937-be50e1b0-e5fc-4e07-9573-281ee1c310c0.png)


## Tecnologías/Frameworks utilizados
- Google Colab (Colaboratory)
- Google Earth Engine
- TensorFlow
- Keras
- Apache Beam
- Numpy
- Matplotlib

## Funcionalidades mas importantes

El proyecto permite una consulta a imagenes de GEE y da claridad sobre como aplicar modelos deredes neuronales sobre esas imagenes.

## Instalación
El cuaderno de Colab presente en el repositorio muestra cómo crear el proyecto, entrenarlo con datos de Earth Engine, hacer predicciones sobre imágenes.

1° escargue el archivo en formato zip. 

![image](https://user-images.githubusercontent.com/1416275/178988982-bfd83430-0e45-4c42-9a1e-b36fb30e4e04.png)

2° Despues descomprima la carpeta 

3° Suba el archivo .ipynb a su entorno colab.

![image](https://user-images.githubusercontent.com/1416275/178992636-7fc00267-a2de-4c44-8929-73da2f488add.png)

Y eso es todo luego puede ejecutar el proyecto en su entorno colab.

## Creditos
* Elmer Efrain Alanoca Condori
* Federico Ortega Chura
* Juan Carlos Sanchez Calle
* Delma Dafné Torrico Flores

## Recursos Utilizados
* Catalog Sentinel-2 MSI: MultiSpectral Instrument, Level-1C

https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2#bands

* Catalog ESA WorldCover 10m v100 

https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v100

* Measuring climate and land changes with AI

https://cloud.google.com/blog/topics/developers-practitioners/measuring-climate-and-land-changes-ai?utm_source=youtube&utm_medium=unpaidsoc&utm_campaign=CDR_ret_gcp_yfuxjwamepw_PeopleAndPlanetAI_061422&utm_content=description

* DeepGlobe Land Cover Classification Challenge

https://competitions.codalab.org/competitions/18468

* Kaggle

https://www.kaggle.com/balraj98/deepglobe-land-cover-classification-dataset

* Recursos adicionales para FCNs and Segmentation:

[Fully Convolutional Network](https://www.mygreatlearning.com/blog/fcn-fully-convolutional-network-semantic-segmentation/)

[Guide to Semantic Segmentation](https://nanonets.com/blog/semantic-image-segmentation-2020/)

[Understanding and Implementing a Fully Convolutional Network](https://towardsdatascience.com/implementing-a-fully-convolutional-network-fcn-in-tensorflow-2-3c46fb61de3b)

[An Overview of Image Segmentation](https://www.jeremyjordan.me/semantic-segmentation/)

[FCN vs U-Net](https://stackoverflow.com/questions/50239795/intuition-behind-u-net-vs-fcn-for-semantic-segmentation)

[Simple Example of Semantic Segmentation](https://awaywithideas.com/a-simple-example-of-semantic-segmentation-with-tensorflow-keras/)

[Metrics to Evaluate Semantic Segmentation Model](https://towardsdatascience.com/metrics-to-evaluate-your-semantic-segmentation-model-6bcb99639aa2)

## Licencia

The MIT License

Copyright (c) 2020 [OurEyesAI]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

<!--
**OurEyesAI/OurEyesAI** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
