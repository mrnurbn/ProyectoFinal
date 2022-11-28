# ProyectoFinal
Este repositorio contiene el proyecto final de la materia de Estadística y Probabilidad donde hicimos uso de estadística descriptiva y después de estadística inferencial para analizar la base de datos "Top 50 canciones". Para este propósito, primero se hicieron análisis exploratorios y descriptivos de la base de datos en notebooks de Colab. Utilizamos distintas bibliotecas como pandas o seaborn. Finalmente se hizo el análisis de regresión lineal con el método de mínimos cuadrados y también se hizo un análisis con múltiples variables para encontrar el mejor modelo que se acercara lo más posible a una r de 1
###Preguntas 
##### 1) ¿Cuál fue el motivo de elegir tu base de datos? 
La razón por la que seleccionamos esta base de datos sobre las top50 canciones en spotify, se debió a que hoy en día la mayoría de la sociedad escucha múscia a través de dicha plataforma. La myoría de los usuarios son jóvenes, pero eso no quita que existan otros rangos de edades dentro de la plataforma, lo que quiere decir que la múscia que puedes encontrar y escuchar es muy amplia y dicersa. Lo que despertó cierta curiosidad en poder saber más acerca de cuáles son las canciones más escuchadas en esta plataforma, se nos hizo interesante el poder ánalizar está información con más detalle. 

##### 2) ¿Cuáles fueron tus fuentes para desarrollar el proyecto? 
La base de datos la obtuvimos de la página de Kaggle. Mientras que la demás información fueron apuntes obtenidos durante la clase. 

Anexo la referencia de donde se obtuvo la base de datos:

     Top 50 Spotify Songs - 2019. (2019, 8 agosto). Kaggle. https://www.kaggle.com/datasets/leonardopena/top50spotify2019

##### 3) ¿Cuáles fueron tus metas para tu entendimiento del proyecto? 
Cuando comenzamos el proecyto nuestro objetivo principal era ánalizar la información de está base de datos y poder tener una mejor comprensión de ella al realizar un ánalisis exploratorio. Sin embargo, conforme fueron pasando las clases y el proyecto fue progresando, nuestras metas estaban más enfocadas al descubrir diversas herramientas de como evaluar y análizar estadísticamente las bases de datos. Lo que nos llevo a querer adquirir el mejor conocimiento para en un futuro saber las diversas maneras que existen de evaluar los datos y poder seleccionar el más adecuado y correcto dependiendo de los datos e información. 

##### 4) ¿Qué elementos representativos tomaste en cuenta, esto es cuáles fueron tus varibles explicativas y cuál fue tu variable responsiva? 
Los elementos principales que tomamos en cuenta fueron: Beats per minute, Danceability y Popularity. De los cuales, Beats per minute se considero como la variable responsiva; mientras que las otras dos fueron tomadas como variables explicativas. Para poder determinar esto primero tuvimos que comprender que la responsiva tiene que ser aquella que se ve afectada, nos ayuda a estudiar a las demás variables. Por lo tanto, es el efecto esperado y responde a variables explicativas. Mientras que las variables explicativas son aquellas que se pueden considerar como "inestables" y son suceptibles a padecer una modificación.
## CONCLUSIONES
### MARIANA:
Pudimos observar que para que el uso de regresión lineal sea de utilidad y presente resultados relevantes, es necesario que las variables que seleccionemos estén relacionadas de alguna manera para que a medida que una comienza a cambiar, se tenga una respuesta de las otras que sirva de análisis y toma de decisones. De esta manera pueden revelarnos información que con un aanálisis descriptivo no obtenemos. Por ello nososotras seleccionamos las variables que creímos más convenientes que tienen efectos entre sí. Aunque nuetsra base de datos de canciones tenía muchos atributos relevantes es por esta razón que decidimos quedarnos con: Danceability, Beats per minute y Popularity. Hicimos varias pruebas para obtener el resultado más congruente en el gráfico de dispersión y la regresión lineal. Por ello pude comprender la importancia que tiene el comprender este tema e¡dentro del campo de la estadística, por su aplicación en diversas areas de estudio y para facilitar el análisis de datos variables y de grandes dimensiones. 
###CECILIA:
Pudimos comprender que la regresión lineal es una herramienta muy útil para poder sacar predicciones y comportamientos de las variables con ayuda de otras. Con este conocimiento tuvimos la oportunidad de ponerlo en práctica con la base de datos en la que habíamos estado trabajando durante el semestre. Para comenzar utilizamos la regresión lineal simple para poder modelar la relación existente entre "Danceability" y "Beats per minutes", con ello poder sacar la pendiente de regresión y poder visualizar de una mejor manera el comportamiento de estás variables, y así poder realizar un mejor ánalisis. Una vez que obtuvimos estos resultados, comenzamos a experimentar con otras varibles para poder determina la relación causa-efecto existente entre las mejores varibles, en este procedimiento requerimos de una variable dependiente y varibles independeientes. Al obtener los resultados, y quedarnos con las mejores 3 varibles (Danceability, Beats per minutes y Popularity). Nos percatamos que esta regresión lineal múltiple es de las mejores herramientas estádisitcas para poder evaluar de una mejor manera las relaciones que se presentan entre las variables y así poder obtener un ánalisis más completo. Por último, uno de los aprendizajes que adquirimos más importantes es que la regresión lineal múltiple tiene la ventaja de poder evaluar el efecto de cada predictor (variable independiente) evitando la confusión que puede generarse cuando se relacionan más de dos variables. 
