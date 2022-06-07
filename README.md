<div style="width: 100%; clear: both;">
  <div style="float: left; width: 50%;">
    <img src="http://www.uoc.edu/portal/_resources/common/imatges/marca_UOC/UOC_Masterbrand.jpg" align="left">
  </div>
  <div style="float: right; width: 50%;">
    <p style="margin: 0; padding-top: 22px; text-align:right;">M2.851 · Tipología y ciclo de vida de los datos · Práctica 1</p>
    <p style="margin: 0; text-align:right; padding-button: 100px;">Estudios de Informática, Multimedia y Telecomunicación</p>
    <p style='color: #105269; font-size: 18px; text-align:right; font-family: verdana'><b>  Máster Ciencia de Datos</b></p>
  </div>
</div>
<div style="width:100%;">&nbsp;</div>

<p style='font-size:16px;'>
  Autor: <br>
  CGD <br> </p>
<p style='font-size:12px;'>      
  Junio 2022 </p>
<hr>

# <b><u> Práctica 2. LIMPIEZA Y ANÁLISIS DE DATOS </b></u>

## <b> Introducción </b>

En este proyecto se elabora un caso práctico de limpieza y análisis de datos orientado al ámbito de las geociencias para la clasificación de facies donde se pretende identificar los datos relevantes para el estudio y usar las herramientas de integración, limpieza y validación y análisis de las mismas. 


### Objetivo

El objetivo analítico consiste en comprender los datos disponible de los 9 pozos del campo de gas más grande de Estados Unidos, Hugoton y Panama field al suroeste de Kansas y analizar la relevancia de sus variables para la clasificación y predicción de las facies a partir del análisis de modelos supervisados y no supervisados.Para los modelos predictivos se evaluará qué tan bueno es el modelo, mientras que en modelos descriptivos se evalú es qué tan bien se ajusta al dominio descrito.
Para los modelos predictivos se evalúa qué tan bueno es el modeloa la hora de hacer la predicción, mientras que en modelos descriptivos se evalúa qué tan bien se ajusta el modelo al dominio descrito.

## Descripción de los datasets:  

<b><u>facies_data.csv:</b></u>

El conjunto de datos se ha tomado de [Kaggle](https://www.kaggle.com/datasets/imeintanis/well-log-facies-dataset)

El origen de los datos procede de un ejercicio de clase de la [Universidad de Kansas (Dubois et. al, 2007) sobre Neural Networks y Fuzzy Systems](http://www.people.ku.edu/~gbohling/EECS833/). Los datos están recogidos de 9 pozos del campo de gas más grande de Estados Unidos, Hugoton y Panama field al suroeste de Kansas. 

Para más información sobre el origen de los datos se puede consultar la siguiente información: [ Bohling and Dubois (2003)](https://www.kgs.ku.edu/PRS/publication/2003/ofr2003-50.pdf) y [Dubois et al. (2007)](https://www.sciencedirect.com/science/article/pii/S0098300406001956?via%3Dihub)

## Descripción de las variables del dataset:

+ **Facies**: Unidad litoestatrigráfica característica (target)
+ **Formation**:	factor - categórica. Nombre de las formaciones geológicas divididas en 7 unidades estratigráficas C, B5, B4, B3, B2, B1, A1 cada una con un intervalo no marino (SH) sustentado por uno marino (LM).
+ **Well_Name**: Nombre de los pozos.
+ **Depth**: Profundidad de las mediciones (feet)
+ **GR**:	numeric. Registro Gamma ray [0,150 gAPI]
+ **ILD_log10**: Registro de resistividad [0,100 ohm.m]
+ **DeltaPHI**:	 Transformación Delta Phi,  diferencia de porosidad de densidad de neutrones (netron - density porosity) [0.2,-0.6]
+ **PHIND**: Registro de porosidad media de densidad de neutrones. [0.3,-0.1]
+ **PE**:	Efecto fotoeléctrico. [0,20]
+ **NM_M**:	Indicador no marino (NM) - marino (M)
+ **RELPOS**: numeric. Posición relativa. [3,-1]

## Package content

El proyecto consta de los siguientes archivos:

- `facies_data.csv`: dataset 
- `README.md`: contiene información del proyecto
- `PRA2.rmd`: contiene el código y comentarios de la práctica
- `PRA2.pdf`: contiene el código y el desarrollo del proyecto
- `PRA2.html`: contiene el código y el desarrollo del proyecto en formato html


## Licencia:

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/CGD2401/Hotels_reviews.git">Limpieza y análisis de datos aplicado a las geociencias</a> por <span property="cc:attributionName">CGD </span> Licencia: <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>

Esta licencia permite el uso compartido de los datos. No se permite el uso comercial. 

