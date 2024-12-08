Autores:
  Diego Arbeloa
  Diego Guerrero

Preguntas
1) Url del proyecto
  https://github.com/GesProDiego2024-25/GESPRO_Practica_3_Curso_2024_2025

2)
 - Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local. (25%)
    * posicionarte en el commit para subir cambios
     En el repositorio de go-bees te posiciones en la lista de commits en el deseado, puedes buscarlo mediante el mensaje del commit o por
    el id. Cuando ya lo tengas posicionado pulsas en "reset master to this commit">"hard-discard all changes".
   <img width="860" alt="foto 7" src="https://github.com/user-attachments/assets/9d4cd90e-17d6-4c65-a33e-5c4d30972974">

    * tener master al dia y estar posicionado en master
      Tienes que estar posicionado en la rama master en gitkraken, para comprobar si hay cambios pulsas "fech all", esta herramienta nos dirá si hay
      cambios con respecto a la rama remota. Si hubiera cambios pulsamos push para sincronizar ambas ramas.
      <img width="767" alt="foto 10" src="https://github.com/user-attachments/assets/67f1b0d9-24f0-499a-89fa-7078c7b92351">

    * Crear rama a partir de tarea con nombre = a Gobees
    en github nos situamos en Issues, pulsamos sobre el Issue que vamos a crear la rama y creamos la rama con el nombre del Issue.
    ![Imagen de WhatsApp 2024-12-08 a las 23 00 26_0c3ff7a3](https://github.com/user-attachments/assets/8b14aeca-5718-48bd-b7d1-f74422c4ff4a)
    ![Imagen de WhatsApp 2024-12-08 a las 23 00 44_245901dd](https://github.com/user-attachments/assets/883116b5-f56c-4877-b8ac-4f19ca27262f)
    ![Imagen de WhatsApp 2024-12-08 a las 23 01 20_528cde2b](https://github.com/user-attachments/assets/63a6f03c-32d5-4411-a601-68f9c1ffdc82)


    * posicionarse en rama en local
      <img width="452" alt="foto 1" src="https://github.com/user-attachments/assets/f5d98c80-bcd1-46f0-a73a-7390ca297cdc">

    Una vez creada la rama en el github, hacemos fetch en gitkraken para ver la rama, nos aparecerá en el cuadro de "remote",
    tendremos que pulsar dos veces sobre esa rama y nos aparecerá en el cuadro de local, ahí es cuando tendremos la rama en el
    repositorio local y podremos subir los cambios.

    * Añadir cambios de carpeta gobees a la carpeta P3
      Copias todos los archivos del repositorio de go-bees al repositorio local de la práctica 3.
    (no hay que copiar la carpta .git)
   ![Imagen de WhatsApp 2024-12-08 a las 22 30 44_02c5783f](https://github.com/user-attachments/assets/21c74338-0ea4-4606-a3c4-1b340738e44e)


    * Git Stage all * Git commit
      <img width="302" alt="foto 2" src="https://github.com/user-attachments/assets/945623cf-fdd0-4e56-893d-ca3ff4d55f8c">

    Cuando guardemos los cambios en algún fichero del proyecto en atom, dicho fichero aparecerá	sobresaltado en naranja, esto querrá decir
    que no se ha sincronizado con el repositorio local, para ellos vamos a gitkraken y hacemos fetch para comprobar si ha habido cambios.
    Nos saldrá a la derecha que ha habido cambios entonces añadimos los cambios y hacemos el commit.
   
    * Create PRQ (de nuestro proyecto a nuestro proyecto) master
    Cuando ya tienes todos los commits de la rama hechos, subes todos los cambios de tu rama a github y alli creas la pull request para sincronizar tu rama con la rama master, estonces la pull request necesita la aprovacion de otras     
    personas,y se debe de confirmar por al menos un miembro.
    <img width="964" alt="foto 3" src="https://github.com/user-attachments/assets/dee7c4fc-b874-4804-81cd-303ebb346fa1">

    <img width="1056" alt="foto  4" src="https://github.com/user-attachments/assets/34ac6c88-8a50-4947-a3fc-296fda5ce40a">

    <img width="1010" alt="foto 5" src="https://github.com/user-attachments/assets/5b185583-31d3-4a08-89c7-e352e315bd39">


    * Merge PRQ y actualizar Master en local
    Una vez creada la pull request, otro miembro del equipo la confirmara, por lo que se sincronizara automaticamente la rama creada y la rama master. Para actualizar la master en local primero se hace un fetch, y luego pulsas pull para   
    traer los cambios del repositorio remoto al local.
    IMPORTANTE: Cuando hagas el pull para sincronizar ambas ramas master(local y remoto) en gitkraken tienes que tener la rama master seleccionada.
    
    <img width="767" alt="image" src="https://github.com/user-attachments/assets/81d133fa-8871-4c92-a6b8-7326096e2780">

    <img width="483" alt="foto 6" src="https://github.com/user-attachments/assets/687ead0c-68a0-410f-9e46-c2cdb291251c">



