<h1 align="center">Examen Parcial IA</h1>

<h2>Repositorio:</h2>

Este es el link del [repositorio](https://github.com/albabernal03/Parcial2/tree/main)

-------------------------------------------------

<h2>Antes de comenzar:</h2>

Para instalar todas las dependencias del proyecto, simplemente ejecuta el siguiente comando en tu terminal estando en el directorio del proyecto y con tu entorno virtual activado:

```
pip install -r requirements.txt
```
---------------------------------
<h2>Resolución:</h2>

En este proyecto, hemos abordado un desafío en ingeniería digital propuesto por la Universidad Alfonso X "El Sabio". Nos hemos centrado en la aplicación del Método de Elementos Finitos (MEF) 3D, combinando Python y herramientas como Paraview para el análisis y visualización de estructuras.

Nuestro trabajo comenzó con la generación de un arreglo tridimensional que representa un dominio estructural básico utilizando Python, seguido por la exportación de resultados de análisis estructural a formatos compatibles con Paraview. Para esto, hemos utilizado bibliotecas estándar como NumPy y Pandas, garantizando la precisión y legibilidad de nuestros datos.

Además, implementamos funciones auxiliares en Python para calcular el tensor de deformaciones para elementos finitos tetraédricos, lo que nos permitió comprender mejor el comportamiento estructural en diferentes condiciones.

En el pre-procesamiento de datos, generamos un mallado de tetraedros a partir de geometría básica proporcionada, mientras que la implementación de funciones de forma nos permitió realizar análisis más detallados en puntos específicos del dominio.

El ensamblaje de matrices de rigidez global se realizó con éxito, asegurando la validez y eficiencia de nuestros modelos. Finalmente, desarrollamos un solver para el sistema de ecuaciones resultante del MEF y generamos visualizaciones impactantes de tensiones y deformaciones en la estructura analizada utilizando Paraview, descargado de su página oficial para garantizar su integridad y fiabilidad.

-----------------------------------------------------
<h2>Visualizaciones:</h2>

![parcial2](https://github.com/albabernal03/Parcial2/assets/91721875/a6eb427e-2a2c-439e-98eb-94f5224f4ab8)

![parcial2 1](https://github.com/albabernal03/Parcial2/assets/91721875/0abb0270-7259-4703-9c7f-dc9d5a36cd92)

![parcial2 2](https://github.com/albabernal03/Parcial2/assets/91721875/b4472417-e26e-4816-afe6-e6eaa14bcc78)

![parcial2 3](https://github.com/albabernal03/Parcial2/assets/91721875/be3e5897-2f38-4fde-8086-6d2da1b71cd6)

