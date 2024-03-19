Generador de Dominios y Detectores

Este repositorio contiene varias herramientas para trabajar con nombres de dominios. A continuación, se describen los principales componentes:
Generador de Nombres de Dominios

El objetivo principal de este trabajo es el Generador de Nombres de Dominios. El modelo generador se encuentra implementado en el notebook Generador_DGA_Modelo.ipynb.
Generación de Dominios

El notebook Generador_Dominios.ipynb utiliza el modelo generador para generar un conjunto de dominios. El número de dominios generados se puede modificar cambiando el valor del último ciclo for en el notebook. La cantidad de dominios generados será el resultado de dividir ese valor por 45.
Detectores de Dominios AGD

En la carpeta, se encuentran detectores de Dominios AGD (Algorithms for Generating Domains) que se utilizan para comprobar la calidad de los dominios generados. Los detectores se encuentran implementados en los notebooks Detec_Harpo_SetData.ipynb y Detec_Mío_SetData.ipynb. Puedes probar cualquier set de dominios modificando el nombre del archivo "4kdomain.csv" en los notebooks.
Conjunto de Datos 4kdomains.csv

El conjunto de datos 4kdomains.csv es el resultado de la generación de dominios utilizando el modelo generador. Este conjunto de datos es objeto de estudio y puede ser utilizado para evaluar y probar los detectores de dominios.

Siéntete libre de explorar, utilizar y modificar las herramientas en este repositorio para tus propios proyectos y experimentos. Cualquier contribución o sugerencia es bienvenida.

¡Gracias por visitar este repositorio y esperamos que te sea útil para tus investigaciones y trabajos relacionados con nombres de dominios!



Domain Generator and Detectors

This repository contains several tools for working with domain names. Below are the main components described:
Domain Name Generator

The main objective of this work is the Domain Name Generator. The generator model is implemented in the notebook Generador_DGA_Modelo.ipynb.
Domain Generation

The notebook Generador_Dominios.ipynb uses the generator model to generate a set of domains. The number of generated domains can be modified by changing the value of the last for loop in the notebook. The amount of generated domains will be the result of dividing that value by 45.
AGD Domain Detectors

In the folder, there are AGD (Algorithms for Generating Domains) Domain Detectors used to check the quality of the generated domains. The detectors are implemented in the notebooks Detec_Harpo_SetData.ipynb and Detec_Mío_SetData.ipynb. You can test any set of domains by modifying the name of the file "4kdomain.csv" in the notebooks.
Dataset 4kdomains.csv

The dataset 4kdomains.csv is the result of domain generation using the generator model. This dataset is the object of study and can be used to evaluate and test domain detectors.

Feel free to explore, use, and modify the tools in this repository for your own projects and experiments. Any contribution or suggestion is welcome.

Thank you for visiting this repository, and we hope it is useful for your research and work related to domain names!
