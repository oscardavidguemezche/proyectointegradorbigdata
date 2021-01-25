### Greeplace

### Descripción general

``` 
El proyecto Gree Peace suerge de la necesidad de los trabajadores agricolas
de tener un sistema de monitoreo automatizado, este estara conformado un 
dispositivo conformado por sensores que realizen la tarea de recibir la 
informacion y enviarla a la base de datos, asi como de interpretarlos para 
hacer funcionar un sistema de riego, ademas se contara con una plataforma 
para revisar la informacion. Esto le permitira al usuario, automatizar sus 
labores, tener de manera mas rapida y precisa la informacion y asi reaccionar 
en base a esta.
```
## Diagrama general de flujo de datos
```
  https://embed.creately.com/b3b6by7aru8?type=svg
```
### 5v's del big data

```sh
$ volumen:
$ es dificil saber hasta que punto se considera una gran volumen de datos ya que pueden ser por ejemplo 10G
$ 1TB etc, pero se dice que tiene un gran volumen de datos cuando tu maquina no puede 
$ procesar la informacion es decir se queda lenta y no puedes acceder de forma rapida
$ greeplace maneja maquinas en la nube para procesar sus datos

$ valor:
$ el valor se refiere a como vamos a conocer esos datos, es decir el contexto, la informacion y no hay un flujo
$ greeplace recolecta informacion del compo, es decir monitorea el estado de la planta 

$ veracidad:
$ se refiera a que los datos sean lo que este buscando, en este caso usamos sensores que nos garantizan el recabado de datos como
$ temperatura, humedad, calidad del aire 

$ visualizacion:
$ como su nombre indica es como vamos a visualizar la informacion, greeplace tiene una pagina web
$ donde se puede ver el contenido recabo por los sensores en forma de grafica y en foma de tablas


$ variedad:
$ se refiere a como vamos a manejar los datos en si hay muchas forma, greeplace maneja una api publica donde se puede consultar los datos de los sensores por usuario
$ ademas contamos con una base de datos asi que hay varidad de formas en la que podemos analizar los datos


$ velocidad:
$ como indica esto es la velocidad en que se mueven los datos para ello contamos con maquinas virtuales la cuales nos ayudan a manupular
$ los datos es decir extraer los datos del json y base de datos


$ viscocidad :
$ para tomar mejores deciciones de negocio para realizar tratos con los datos

$ viralidad:
$ que tan fuerte son los datos que tan importante es que tenga guardado los datos

```


### Diagrama de flujo

``` 
https://embed.creately.com/b3b6by7aru8?type=svg 
```

### Diagrama ETL 
```
**Extracción** 
La informacion es almacenada y extraida de una Base de datos.

**Transformación** 
Los datos son solicitados por la pagina web a travez de una API, estos son
entregados a traves de un formato JSON el cual es traducido por la pagina
para ser presentados finalmente al usuario

**Load**
Una vez que la informacion solicitada a la API es traducioda del JSON le
es presentada al usuario por medio de una tabla y una grafica.

```
