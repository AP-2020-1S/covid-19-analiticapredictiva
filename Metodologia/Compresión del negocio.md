## **Compresión del negocio** 
### **Objetivos del negocio**
El objetivo de este proyecto es la predicción de corto (1 mes) y mediano plazo (6 mese) de el total de casos confirmados, los nuevos casos, los casos activos, recuperados y muertes para las 5 ciudades mas pobladas de Colombia.
### **Evaluación situación actual**
#### ***Conceptos básicos***
<br>

> La siguiente informacion es tomada del curso  ***Fighting COVID-19 with Epidemiology: A Johns Hopkins Teach-Out*** impartido por la universidad Johns Hopkins, en la plataforma **COURSERA** , todas las imágenes son tomadas de los videos.

<br>

Previo a una descripción de la situación actual que esta pasando toda la humanidad es necesario introducir algunos conceptos claves para poder entender esta panadémia, empezando con la definición de brote , epidemia y pandémia.

**Brote** : Casos no esperados de una enfermedad  en un region y un tiempo  determinado (50 casos en Wuhan).

**Epidemia** : Sucede cuando el ***brote*** empieza a multiplicarse en una zona geográfica y abarca una region determinada (epidemia en China) .

**Pandemia** : Cuando esta ***epidemia*** forma ***brotes*** en otros países, ya se empieza a hablar de una pandemia .

Ya teniendo claro los anteriores conceptos, es importante mencionar que para poder determinar el comportamiento y realizar un buen seguimiento de los brotes es necesario identificar los casos que pueden ser de tres tipos:

- **Casos sospechosos** : Una persona de la cual se supone tiene la enfermedad, pero no hay evidencia fuerte que lo confirmen
- **Casos probables** : Caso sospechoso donde hay evidencia circunstancial , ejemplo estar expuesto a un caso conocido.
- **Casos confirmados** : Existe evidencia clínica o de laboratorio de que es un caso.

Teniendo en cuenta los tipos de casos se realiza una lista que tenga cada caso individual y que contenga características relevantes. con la  lista se puede caracterizar el brote realizando un curva epidemiologica, en esta curva se muestran los números de casos por la fecha de inicio de la enfermedad o otra unidad de medida de tiempo, adicionalmente se puede distinguir dependiendo de tipo de caso (sospechoso, probable o confirmado).

<p align="center">
  <img src="./img/situacion_actual/curva-epi.jpg"  alt= "curva epidemilogica"/>
</p>

La forma de la curva da una idea del tipo de brote, en el caso de la pandemia de covid-19 esta es de tipo brote propagado, donde ,se tiene una curva pequeña en forma de campana, con un crecimiento lento en el numero de casos, seguido por un lento decrecimiento en el numero de casos. Si se mira detalladamente se puede evidenciar que existen olas de infecciones.

<p align="center">
  <img src="./img/situacion_actual/curva-prop.jpg"  alt= "curva brote propagado"/>
</p>

Se puede ver de la curva, que inicialmente hay un pequeño mini-brote, luego hay un poco de tiempo entre esos casos que ocurrieron inicialmente y el desarrollo de los síntomas de los nuevos casos que ellos causaron, lo cual a su vez genera otro mini-brote. Esto sigue y sigue, y estos mini-bortes se irán uniendo hasta que se suaviza la curva.

#### ***Dinamica del brote***

Para poder comprender la dinamivca del brote se debe tener el cuanta le concepto de numero de reporudccion, este puede ser de dostipos:

- **Número de reproduccion básico R0 :** Es el número de personas infectadas por una sola persona, ***en un población sin inmunidad***
- **Número de reproduccion R :** Es el número de personas infectadas por una sola persona, ***en un población con inmunidad***, se puede definir matemáticamente como :

> R = $R_{0} \times \%susceptibles$

### Número de reproduccion y la curva epidemiologica


<p align="center">
  <img src="./img/situacion_actual/NR.jpg"  alt= "curva brote propagado"/>
</p>

Al inicio de la epidemia de una nueva enfermedad, el numero de reproducción es igual al numero de reproducción básico, ya que no se cuanta con inmunidad y sera mayor a 1, ira aumentando hasta llegar al pico de los contagios, cunado una gran porción de la población ya tiene inmunidad, luego el número de reproducción decrecerá y sera menor de 1 hasta que se produzca el final de la epidemia.


Para poder comprender completamente la dinámica del brote, es necesario tener en cuanta tres periodos de tiempo que ocurren desde que se es infectado con el virus hasta que se contagia a otra persona, esto son : 

- el **periodo de incubación** es el tiempo desde que se infecta hasta que se sienten los síntomas.
- el **periodo de latencia** es el periodo desde que se infecta hasta que la persona es capaz de contagiar a otros.
- el **tiempo de la generación** es el tiempo entre dos subsecuentes generaciones de  infectados

<p align="center">
  <img src="./img/situacion_actual/ht.jpg"  alt= "dinámica del brote"/>
</p>

### **Nota**
<br>

> - el tiempo de la generación combinado con el número de reproduccion determinan que tan rápido crece la epidemia.
>
> - los tres periodos anteriormente mencionados tienden a tener una distribución normal con una cola hacia la derecha.

<br>

En conclusión, las características mas importantes que se deben tener en cuanta en la comprensión de los datos y la modelacion son el ***numero de reducción*** y el ***tiempo de la generación***, los cuales son difíciles de definir  y varían en el tiempo, por tal motivo para el análisis se debe tener en cuanta no solo los datos de los casos, sino también las medidas implementadas por el gobierno como el distanciamiento social o las cuarentenas y como esto afecta la dinámica del brote.
