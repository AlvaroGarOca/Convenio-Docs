# Trabajar con Skaffold
Si ahora hiciesemos un cambio en la imagen, el contenido del HTML o lo que sea, entonces tendríamos que parar los pods manualmente, relanzarlos, etc. Con Skaffold, si hacemos un cambio en un archivo y lo guardamos, automáticamente se aplicará el cambio en local y podremos ver lo que hemos hecho sin tener que hacer nada más manualmente. 

Para eso vamos a hacer un cambio en nuestro proyecto. Antes lo hicimos con un configmap, pero esta vez vamos a montar el index en la imagen que usaremos para el pod. Esto es algo que realmente no es tan óptimo como lo hemos hecho antes, pero será más sencillo para hacerlo en local, ya que se aplicará lo que hace a Skaffold, ya que un cambio manual en el configmap no hace que se relance el pod como tal. Además, es rápido.

Estos son 