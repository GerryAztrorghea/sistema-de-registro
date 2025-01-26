<h1> Sistema de Registro </h1>

- Estado del proyecto en construccion 

Para ejecutar el sistema, debes poner:
``` npm install react```

<h3>Clonar un repositorio</h3><br>
  ```git clone + (url)```

<h3>Mostrar los cambios dentro del repositorio</h3><br>
  ```git log``` <p> Muestra los cambios con mucha informacion</p>
  ```git log --oneline``` <p> Muestra los cambios en una forma mas resumida </p>
  ```git push``` <p>Saber si existe algo que se tiene que bajar</p>

<h4> Saber el estado en el que se encuentra el repositorio</h4>
    ``` git status``` en que momento esta el repositorio
    
<h4> U en vscode</h4>
  <p> Es el estado de los cambios que no se han realizado </p>
  ```git add . ``` todos los archivos
  ```git add + nombreArchivo``` solo lo va a mandar el cambio

<h4>Realizar un commit</h4>
  ```git commit -m "texto"``` mandar los cambios con el commit

<h4> Enviar al repositorio remoto</h4>
  ```git push```

<h4> Ver los cambios que se han realizado dentro de git y github </h4>
   ``` git diff + nombreArchivo ``` muestra los cambios 

<h4> Mover a versiones anterior</h4>
    ``` git restore --source + hash + nombreArchivo``` la version anterior muestra 

<h4> Muestra las ramas que tiene el proyecto</h4>
    ``` git branch```

  <h5> Creacion de una rama</h5>
    ```git checkout -b desarrollo``` creacion de la rama 

  <h5> Mover a la rama </h5>
    ```git switch + nombre de rama```

  <h5> Mandar o subir al repositorio con otra rama</h5>
    ``` git push origin + nombreRama```

  