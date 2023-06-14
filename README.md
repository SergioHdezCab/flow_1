# flow_1
 Flow 1 de node red

## Introducción


Este es el primer ejercicio realizado en NodeRed, el cual consiste en conectar un Nodo Inject con uno de Debug para generar TimeStamp.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [Docker Engine](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- [NodeRed](https://nodered.org/docs/getting-started/local)

## Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realizar las configuraciones necesarias

- [Instalación de Virutal Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Introducción a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Aplicacion multicontenedor de servidor IoT con Docker compose](https://edu.codigoiot.com/mod/lesson/view.php?id=3889&pageid=3804&startlastseen=no)
- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

## Instrucciones

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. Tener instalado Docker Engine.
2. Tener instaldo nodeRed por Docker Compose
3. Tener el contenedor de NodeRed con el volumen de data activado

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar el contenedor de NodeRed con el comando
        
        docker start $(docker ps -a -q)

2. Dirigirse a [localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resutlado de este flow, sólo es necesario abrir la pestaña Debug.

## Resultados

A continuación puede verse una vista previa del resultado de este flow.

![](https://github.com/hugoescalpelo/flow1-g12/blob/main/imagenes/Screenshot%20from%202023-05-23%2023-26-20.png?raw=true)


# Créditos

Desarrollado por Nadia Yamile