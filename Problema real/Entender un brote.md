# Entender los brotes
El siguiente documento es un resumen del curso  ***Fighting COVID-19 with Epidemiology: A Johns Hopkins Teach-Out*** impartido por la universidad Johns Hopkins, en la plataforma **COURSERA** , todas las imágenes son tomadas de los videos, adicionalmente si se quiere ampliar la información de cualquier tema se puede acceder al video seleccionado el titulo de la sección deseada.

---
### [Que es un brote](https://coursera.org/share/3e15ab9608aab355ec31732473262087)
- En el caso de un brote (pequeño) o una epidemia (mas grande) ambos se refieren a un periodo de tiempo cuando hay mas casos de la enfermedad que los avitules en un lugar en particular.
- Si la enfermedad es rara se necesitaran pocos casos para que sea un brote.

- Se deben responder las 5 `W` (who , what, when, where, why)
    - Establecer la definición de los casos y su identificación
        - Who?
    - Obtener información en el tiempo, el lugar y de las personas
        - When y what
    - Identificar y caracterizar el patógeno
        - What
    - Análisis de los factores de riesgo
        - Why
    - Intervenir y reportar
        - Tomar acción
- Una buena definición de los casos, identifica a las personas que hacen parte de los brotes, por persona, lugar y tiempo.
#### Enlaces 
- [TEPHINET](https://www.tephinet.org/)
---

### [1. Identificar los casos](https://coursera.org/share/73184ec001e151235f56bd8243b5c9bd)

#### **Tipos de casos**
Existen varios tipos de casos :
- **Casos sospechosos** : Una persona de la cual se supone tiene la enfermedad, pero no hay evidencia fuerte que lo confirmen
- **Casos probables** : Caso sospechoso donde hay evidencia circunstancial , ejemplo estar expuesto a un caso conocido.
- **Casos confirmados** : Existe evidencia clínica o de laboratorio de que es un caso.
#### **Buscar casos**
Una vez se han definido las casos, los investigadores deberían de buscar los casos mediante vigilancia pasiva y activa.
- ***Vigilancia activa*** : Ir a las comunidades e identificar los casos.
- ***Vigilancia pasiva*** : Buscar casos que se han presentado en centros de salud.

---
### [2. Describir los brotes por persona, lugar y tiempo](https://coursera.org/share/08ff1da74cc1ee6fe6b4b12904b1a3ea)
Para realizar una descripción de los brotes se realiza una lista que tenga cada caso individual y que contenga características relevantes.

![lista casos](./imgs/lista.jpg)

#### **curva epidemiologica**
Con esta lista se puede caracterizar el brote realizando un **curva epidemiologica**, en esta curva se muestran los números de casos por la fecha de inicio de la enfermedad o otra unidad de medida de tiempo, adicionalmente se colorean dependiendo de tipo de caso (sospechoso, probable o confirmado).

![curva epidemilogica](imgs/curva-epi.jpg)

La forma de la curva da una idea de la causa del brote, por ejemplo la siguiente curva es característica de un ***brote de fuente puntual***, donde, todos se exponen a la enfermedad al mismo tiempo, se tiene un rápido aumento de casos, seguido por un largo y lento descenso. Generalmente estas curvas tienen un distribución log-normal.

![curva brote puntual](./imgs/curva-puntual.jpg)

Otro tipo común de brote es el ***brote de fuente común***, normalmente es causado por una exposición continua, como por ejemplo algún contaminante en el ambiente. En este tipo de brote no hay una forma distintiva. 

![curva brote puntual](./imgs/curva-comun.jpg)

El ultimo tipo de brote es el ***brote propagado***, donde las personas transmiten la enfermedad unos a otros.

![curva brote puntual](./imgs/curva-prop.jpg)

Se tiene una curva pequeña en forma de campana, con un crecimiento lento en el numero de casos, seguido por un lento decrecimiento en el numero de casos. Si se mira detalladamente se puede evidenciar que existen olas de infecciones.

Se puede ver de la curva que inicialmente hay un pequeño mini-brote, luego hay un poco de tiempo entre esos casos que ocurrieron inicialmente y el desarrollo de los síntomas de los nuevos casos que ellos causaron, lo cual a su vez genera otro mini-brote. Esto sigue y sigue, y estos mini-bortes se irán uniendo hasta que se suaviza la curva.

#### **Mapa del brote**

Por otro lado también se querrá caracterizar el brote en el espacio, se pueden hacer gráficos de puntos, donde cada caso es representado por un punto, de barras, donde el numero de casos en un area del mapa es representado por una barra, entre otros.

![curva brote puntual](./imgs/mapa-brote.jpg)

---

### [3. Identificar y caracterizar las causas](https://coursera.org/share/c4ab631253353ed6b1aa445b1a41d856)

Para caracterizar e identificar las causas del brote, hay una gran tipo de información que se puede usar, por ejemplo ***evidencia clinica***, comparando los síntomas con enfermedades conocidas.

Por otro lado se puede utilizar ***evidencia epidemiologica***, que incluye *exposición común*, donde se pregunta que tienen en común los casos. por otro lado ***evidencia epidemiologica*** tiene en cuanta la distribución de los casos por edad. ademas  también tiene en cuenta el tipo de epidemia, que se puede caracterizar con la curva epidemiologica. Y por ultima se toma en consideración el *periodo de incubación*.

#### ***Nota***
> El ***periodo de incubación*** es el tiempo entre que se infecta la persona hasta que aparecen los síntomas.
>
> El ***periodo latente*** es el periodo de tiempo le toma a la infección  para  que se vuelve infecciosa.


Por ultimo se puede usar ***evidencia de laboratorio***,esta clasificar  por  dos tipos. 
- **Organismo** , donde se realizan pruebas moleculares, de microscopio , cultivos y resistencia a las drogas.
- **Inmunológica**, donde se busca la reacción de los anticuerpos.

---

### [4.a. Estudio del factor de riesgo en una población definida](https://coursera.org/share/ba100dac75b6d68c1d78834318c8ac7a) 

Se debe identificar la exposición que esta asociado con la enfermedad, esto dará pistas del origen de la enfermedad o la actividad que lo transmite.

Para poder determinar si la transmisión de la enfermedad está altamente asociada con la exposición a un determinado factor, se puede utilizar el indice del ***riesgo relativo (RR)***.

>$RR = \frac{t_{e}}{t_{n}}$
> 
>donde:
>
> $t_{e}$ = tasas de casos expuestos
>
> $t_{n}$ = tasas de casos no expuestos

la ***tasa de casos (AR)***  se calcula como el numero de personas en el grupo que desarrollan la enfermedad dividida por el numero total de las personas en riesgo a contraer la enfermedad en ese grupo en especifico.

>$AR = \frac{G_{i}}{G}$
>
>donde :
>
>$G_{i}$ = Numero de personas que desarrollan la enfermedad en el grupo
>
>$G$ = Numero de personas en el grupo


#### ***Nota***

> Los grupos comúnmente son definidos por :
>
> - Características individuales (ejemplo edad)
>
> - Exposición (ejemplo tomar leche en el almuerzo)
>
> - Localización  

#### ***Aclaración***

> **Esta aproximación solo funciona si la población expuesta y no expuesta están identificadas debidamente.**

---

### [4.b. Estudio del factor de riesgo en una población abierta](https://coursera.org/share/59adc210eacf3a55938c9cd58035d8b3)

Cuando se detectan casos de la enfermedad, pero no se sabe exactamente cuantas personas han sido expuestas o en riesgo, es necesario utilizar otra metodología. 

En esta situación se hace un ***estudio con casos de control*** donde se debe:
- Identificar ***casos*** basados en la definición del caso.
- Identificar ***sujetos de control*** en la misma población que estaban también en riesgo pero que no se enfermaron.
- Calcular las ***probabilidades*** de exposición en los casos y los sujetos de control.
- Usar la ***tasa de probabilidad*** como una medida de asociación entre la exposición y el contagio 

La ***probabilidad de exposición*** es el porcentaje del grupo que tuvo alguna exposición, dividido por el porcentaje que no lo tuvo.

> probabilidad de exposición = $\frac{N_{e}/total}{N_{n}/total}$ = $\frac{N_{e}}{N_{n}}$
>
>donde :
>
>$N_{e}$ = Numero de personas expuestas
>
>$N_{n}$ = Numero de personas no expuestas

#### ***Nota***
>En los estudios de casos de control, se calculan las probabilidades individuales para los casos y los sujetos de control.

La ***tasa de probabilidad (TP)*** es la probabilidad relativa de tener alguna exposición en los casos y los sujetos de control.

>TP = $\frac{P_{c}}{P_{sc}}$
>
>donde:
>
>$P_{c}$ = probabilidad de exposición en los casos
>
>$P_{sc}$ = probabilidad de exposición en los sujetos de control

- **Valores por encima de 1 significan que la exposición esta asociada con la enfermedad**.

- la tasa de probabilidad solo se aproxima al riesgo relativo si la enfermedad es rara.

#### ***Aclaración***

> los sujetos de control deben ser seleccionados de la misma población que los casos.

---

### [5. Intervenir y reportar](https://coursera.org/share/190cefa6d1a1d5137bbc4a50a9bd7608)

Existen varias maneras para poder intervenir y frenar el brote como :
- Remover la fuente de exposición.
- Recomendar cambios en el comportamiento de las personas.
- Implementar tratamiento o vacunas.
