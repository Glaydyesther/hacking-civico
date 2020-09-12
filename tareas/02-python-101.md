## Tarea2
![p](https://user-images.githubusercontent.com/68880854/92984111-82b90e80-f46d-11ea-9145-9ec66ab7ce38.jpg)

***
**Densidad poblacional**
*Ciudad-Mérida: 940.3803486529318
Estado-Yucatán: 53.06079850217589
País- México:60.84925383391664*
~~~
def densidad_poblacional(poblacion, area_ciudad):
print(poblacion/area_ciudad)

densidad_poblacional(830732,883.4)
densidad_poblacional(2097175,39524)
densidad_poblacional(119530753,1964375)

940.3803486529318
53.06079850217589
60.84925383391664
~~~


**¿Qué pasa comparar varios estados o ciudades?**
Compararlos nos indica que entre mayor población haya en un espacio pequeño de superficie territorial la densidad poblacional será lo suficientemente grande.
***
***
**Gasto per cápita Sector Salud**
*Año 2019: 1039.6225406193166
Año 2020: 1077.7679479104427*
~~~
def gasto_percapita(gasto_publico, poblacion):
  print(gasto_publico/poblacion)

gasto_percapita(124266865116, 119530753)
gasto_percapita(128826414373,119530753 )

1039.6225406193166
1077.7679479104427
~~~
Aumentó  3.66% se debe a la contingencia presentada (COVID) aunque siendo sinceros debió aumentar aún más el porcentaje ya que la contingencia al ser sanitaria se debe invertir más en el sector salud.
***
La información nos es útil para conocer las inversiones que el gobierno realiza en la población y más que nada la densidad poblacional con la que cuenta nuestro país influye en el gasto público que está invertido.

El gobierno define la cantidad necesaria que la población necesita para el gasto público en cada uno de los sectores ya que cuenta con la información acerca de qué sector es el más importante dependiendo la situación social, económica, política en la que nos encontremos.

<https://www.infobae.com/america/mexico/2020/03/13/gobierno-de-amlo-aumento-presupuesto-para-el-sector-salud-pero-lo-redujo-para-vigilancia-epidemiologica/>
