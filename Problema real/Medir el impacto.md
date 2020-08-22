# Medir el impacto
El siguiente documento es un resumen del curso  ***Fighting COVID-19 with Epidemiology: A Johns Hopkins Teach-Out*** impartido por la universidad Johns Hopkins, en la plataforma **COURSERA** , todas las imágenes son tomadas de los videos, adicionalmente si se quiere ampliar la información de cualquier tema se puede acceder al video seleccionado el titulo de la sección deseada.

---
## [Tasa de ataque](https://coursera.org/share/b2deb8be1a6e3a9f95fe982de7a66b28) 
Se pude medir la tasa de transmisión de diferentes manera, entre ellas están:
### - Tasa básica de ataque
Es una simple medida entre las personas que están en riesgo contra las personas que están infectadas.

> TA = $\frac{casos}{población}$

### - tasa de ataque secundario doméstico
Ya que es en la practica es casi imposible acceder a la información de toda la población, existen otros tipo de métodos que ayudan a dar una idea de la tasa de transmisión, entre ellos esta la ***tasa de ataque secundario domestico***.

Esta tasa se define como la proporción de casos en un hogar, dado ue el hogar ha sido expuesto. Usualmente se asume que al inicio solo hay un caso.

![](./imgs/TBA.jpg)

>TAS = $\frac{I-1}{N-1}$
>
>donde:
>
>$I$ son los infectados
>
>$N$ es la población total en el hogar 

### - Tasa de ataque expuesta susceptible

Del modelo anterior, aunque es una buena aproximación del problema, no refleja la realidad de la situación, ya que la mayoría de las veces la persona que se contagian, contagian a su vez a otras personas, por ese motivo se implementa ***Tasa de ataque expuesta susceptible***, que tiene en cuanta las generaciones del contacto.

![](./imgs/TS.jpg)

En este ejemplo, en la generación *T=1* solo esta infectada una persona (de cuatro posibles), la cual infecta a una persona. en la generación *T=2* la persona infectada infecta a otra, como se puede evidenciar, en esta generación ya no se tiene en cuenta a la persona infecta de la generación *T=1* ya que ha adquirido inmunidad y no se tendrá en cuenta en el numero total de posible infectados para esa generación y las posteriores, sucede exactamente lo mismo en la generación *T=3* y *T=4*.

Luego de recopilar los resultados se calcula la tasa con la formula:

> TAS = $\frac{\sum I}{\sum N}$
>
>donde:
>
>$I$ son los infectados
>
>$N$ es la población para cada generación

---

## [Número de reproduccion](https://coursera.org/share/85c153e1cea28c3fd3450a4582ff7e5c)
- **Número de reproduccion básico R0 :** Es el número de personas infectadas por una sola persona, ***en un población sin inmunidad***
- **Número de reproduccion R :** Es el número de personas infectadas por una sola persona, ***en un población con inmunidad***, se puede definir matemáticamente como :

> R = $R_{0} \times \%susceptibles$

### Número de reproduccion y la curva epidemiologica

![](./imgs/NR.jpg)

Al inicio de la epidemia de una nueva enfermedad, el numero de reproduccion es igual al numero de reproduccion básico, ya que no se cuanta con inmunidad y sera mayor a 1, ira aumentando hasta llegar al pico de los contagios, cunado una gran porción de la población ya tiene inmunidad, luego el número de reproduccion decrecerá y sera menor de 1 hasta que se produzca el final de la epidemia.

---

## [Historia de las enfermedades infecciosas](https://coursera.org/share/915e203cadda417181689649978a3269)

- el **periodo de incubación** es el tiempo desde que se infecta hasta que se sienten los síntomas.
- el **periodo de latencia** es el periodo desde que se infecta hasta que la persona es capaz de contagiar a otros.
- el **tiempo de la generación** es el tiempo entre dos subsecuentes generaciones de  infectados

![](./imgs/ht.jpg)


### **Nota**

> - el tiempo de la generación combinado con el número de reproduccion determinan que tan rápido crece la epidemia.
>
> - los tres periodos anteriormente mencionados tienden a tener una distribución normal con una cola hacia la derecha.