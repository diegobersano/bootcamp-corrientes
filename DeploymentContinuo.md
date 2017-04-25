# Configurando deployment continuo en las Azure Functions

Una de las opciones interesantes dentro de lo que son las Azure Functions es la posibilidad de aplicar integraci�n continua. Esto implica que ante cada *push* que se haga sobre nuestro repositorio Azure capture dichos cambios, los compile y si todo funciona de forma correcta los publique.

Las alternativas disponibles que tenemos son las siguientes:

#### Usar un repositorio git interno dentro de la misma Azure Function
Esta alternativa es realmente interesante, ya que est� todo integrado dentro de la misma aplicaci�n.

#### Usar un repositorio externo, el cual se puede integrar en el portal
Lo que deberemos hacer en este caso es inicializar el repositorio bajando el c�digo generado en Azure por FTP y luego subirlo al repositorio que decidamos usar. Una vez finalizado eso iremos al portal de Azure y configuraremos en la opci�n de **_Deployment source_** el repositorio en cuesti�n.

![Opciones deployment continuo](images/OpcionesDeploymentContinuo.png "Opciones deployment continuo")