____________________________________________________________________________________

# Sistema automatizado para la detección de actividades de corrida anómalas mediante técnicas de aprendizaje no supervisado
This project is a part of the  **Proyecto 1 de Innovación Tecnológica** course in the Applied Artificial Intelligence Master, Universidad Icesi, Cali Colombia. 

#### -- Project Status: Active

## Contributing Members

|Name     |  Email   | 
|---------|-----------------|
|[Laura Isabel Chaparro Navia](https://github.com/lauraich)| @lauraich        |
|[Fabian Ortiz](https://github.com/FabOrCo) |     @FabOrCo    |
|[Ricardo Chicangana](https://github.com/rchicangana) |     @rchicangana   |

## Contact
* Feel free to contact the team leader or the instructor with any questions or if you are interested in contributing!


## Project Intro/Objective
El propósito del proyecto es desarrollar un sistema automatizado para la detección de actividades de corrida anómalas mediante técnicas de aprendizaje no supervisado utilizando datos de los últimos 5 meses (10/2024 - 02/2025) y empleando métricas cómo velocidad, distancia, elevación, tiempo y frecuencia cardiaca.

### Methods Used
* Machine Learning
* Data Visualization
* Clustering Algorithms

### Technologies
* Python

## Project Description
Swetro es una aplicación en la que los usuarios se registran para competir en retos deportivos de running, ciclismo y caminata, ya sea para ganar premios o simplemente por el espíritu de competencia. Para participar, los usuarios registran sus actividades mediante relojes inteligentes de marcas como Garmin, Suunto, Wahoo, IgpSport, Polar y Apple Watch, o a través de las apps móviles oficiales de estas marcas desde un dispositivo móvil.

Uno de los desafíos recurrentes que enfrenta Swetro es la detección de actividades sospechosas o incoherentes, las cuales pueden surgir por diversas razones, tales como:

* Errores en los sensores de los dispositivos, lo que genera registros
incorrectos en métricas cómo la velocidad, distancia o ritmo cardíaco.

* Registros humanamente imposibles, como velocidades extremas o distancias cubiertas en tiempos irrealistas.

* Uso inadecuado del dispositivo, por ejemplo, dejarlo encendido todo el día sin realizar actividad física real.

* Intento de fraude, donde un usuario registra una actividad pero en realidad realizó otra (ejemplo: marcar una caminata como un trote).

* Aprovechamiento de medios externos, como subirse a un vehículo o utilizar una bicicleta eléctrica para obtener mejores tiempos y distancias.

Por lo tanto, para evitar que estas irregularidades afecten la competencia justa y la validez de los premios, es necesario desarrollar un sistema de detección de actividades atípicas o sospechosas.

Para este estudio, se utilizará un dataset de los últimos 5 meses (octubre 2024 - febrero 2025) con registros de actividades deportivas:

* Cada fila representa una actividad registrada por un usuario.
* Cada columna corresponde a una variable o característica de la actividad, como distancia, tiempo, velocidad promedio, ritmo cardíaco promedio, elevación ganada, etc.
  
Dado que las irregularidades pueden variar según la disciplina deportiva, este análisis se centrará exclusivamente en los registros de running, buscando patrones que indiquen posibles fraudes o datos erróneos.

## Getting Started
Instructions for contributors
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how contributors may obtain the data )*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [https://github.com/lauraich/running_anomalies_detection_data_analysis/blob/main/Primera%20entrega%20-%20Reporte%20de%20la%20primera%20etapa.pdf](link)
* [https://github.com/lauraich/running_anomalies_detection_data_analysis/blob/main/Proyecto_final_analisis_de_datos_I.ipynb](link)


