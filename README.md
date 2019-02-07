# Desafio Frontend Zeroq

Zeroq esta en busca de un desarrollador frontend para unirse a su equipo de desarrollo, este desafío tiene la finalidad de poner a prueba los conocimientos minimos que requerimos para este puesto.

El desafío consiste en consimir una API Restful, luego listar, ordenar y agrupar las oficinas proporcionadas según algunos atributos.

Se proporcionará, un mockup de como debe quedar el prototipo y de las interacciones que debería tener.

## Restricciones

1. Se debe realizar usando el framework react.js ( Esto es excluyente ya que es el framework que usamos en todos nuestros front y es de gran importancia )

## Lo que necesitaras

#### Endpoint

El unico endpoint a consultar será:


 GET: https://dev.zeroq.cl/desafio-frontend/

#### Assets

En la carpeta assets de este proyecto estaran las imagenes de guía y logotipo.

## Lo que debes realizar

#### 1. Listar las oficinas proporcionadas en el endpoint.
#### 2. Agregar un campo de texto para filtrar oficinas por su nombre.
El nombre se obtiene en el tributo `name` de cada oficina

#### 3. Agregar un campo select para ordenar oficinas por personas en fila y tiempo promedio de atención.

Cada oficina tiene un atributo `lines` y a su vez cada una de ellas tienen atributos `waiting` que son personas en fila y `elapsed` que es el tiempo promedio de atención de esa fila en segundos.

- Para obtener el total de personas en fila hay que sumar los `waiting` de las filas de una oficina.
- Para obtener a atención promedio hay que promediar los `elapsed` de las filas de las oficinas y mostrarlas en formato `HH:mm:ss`.

#### 4. Filtrar oficinas por estado de conexión

El Estado se obtiene en el tributo `online` de cada oficina, que es un booleano.

#### 5. Maquetar segun diseño entregado

Se evalua que el prototipo se parezca lo mas posible a los screens proporcionados.



