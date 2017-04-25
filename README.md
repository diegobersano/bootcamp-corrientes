# Azure Bootcamp 2017 en Corrientes
En el Azure Bootcamp 2017 en Corrientes tuve el gusto de dar una charla con [Sebastián Henzenn](https://twitter.com/sebis) sobre Azure Functions.

Los temas que expusimos son los siguientes:

- Definición de **Azure Functions**
- Ejemplo de aplicación
- Debug en Visual Studio 2017
- Deployment continuo

En las siguientes diapositivas podrán ver la parte teórica que comentamos en la introducción de dicha demo:

<iframe src="//www.slideshare.net/slideshow/embed_code/key/4jPGhfIHNuJeBw" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/dbersano/azure-bootcamp-2017-azure-functions" title="Azure Bootcamp 2017 - Azure functions" target="_blank">Azure Bootcamp 2017 - Azure functions</a> </strong> de <strong><a target="_blank" href="https://www.slideshare.net/dbersano">Diego Bersano</a></strong> </div>

En la carpeta [DemoFunctions](DemoFunctions) podrán encontrar la solución presentada para que ante un comentario en una issue de GitHub se realice un comentario en un canal de Slack.
Para dar algo de variedad en el ejemplo, hay dos funciones:

- **_GithubWebhookJS:_** Función que recibe por un POST el contenido del comentario realizado en la issue de GitHUb.
- **_GenericWebhookCSharp:_** Función que recibe por un POST de la anterior el contenido y lo envía al Webhook expuesto poe Slack, logrando de esta forma la realización de un comentario.

A continuación les dejo los siguientes enlaces al detalle de las explicaciones para los puntos restantes:

- Cómo hacer debug de nuestras Azure Functions en C#?
- Configurando deployment continuo en las Azure Functions