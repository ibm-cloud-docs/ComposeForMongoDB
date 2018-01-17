---

Copyright:
  Years: 2017
lastupdated: "2017-10-23"
---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Visión general del servicio

La página _Visión general_ muestra información sobre la base de datos de {{site.data.keyword.cloud}} Compose. La visión general incluye información de identificación esencial y el uso actual de recursos. También encontrará una sección correspondiente a las series de conexión que puede utilizar con las herramientas o las herramientas que puede usar para conectarse a la base de datos.

## Detalles de despliegue

El panel _Detalles de despliegue_ muestra detalles del servicio.

![Detalles de despliegue](./images/mongodb-deployment-details.png "Una vista del panel Detalles de despliegue")

### Tipo

El tipo de base de datos que ofrece el servicio y la versión de la base de datos que utiliza el servicio.

### Nombre

Un identificador interno para el servicio.

### Uso

El tamaño de la base de datos y la cantidad de almacenamiento que proporciona su plan de servicio.


## Series de conexión

Encontrará series de conexión adicionales para el servicio en un conjunto de separadores en el panel _Series de conexión_. Encontrará información sobre cómo utilizar series de conexión para conectar al servicio en el apartado [Conexión de una aplicación externa](./connecting-external.html).

### HTTPS

Algunas bibliotecas de cliente pueden utilizar la serie de conexión **HTTPS**, que contiene toda la información necesaria para que se conecten otras bibliotecas.

### Serie de conexión

Puede utilizar su serie de conexión directamente en una aplicación para conectarse a {{site.data.keyword.composeForMongoDB}} o puede establecerla como variable de entorno. Para ello, ejecute el siguiente mandato en el shell:

```
export MONGODB_URL="<CONNECTION STRING>"
```

### Línea de mandatos

La **línea de mandatos** es un mandato preformateado que invocará `mongo` con los parámetros correctos. Para poderla utilizar, deberá tener las herramientas mongo instaladas en el sistema local. Encontrará información sobre cómo hacerlo en el apartado [Conexión de una aplicación externa](./connecting-external.html).

### Certificado SSL

El servicio Compose {{site.data.keyword.cloud_notm}} le ofrece un certificado SSL que puede utilizar para conectar con la base de datos.