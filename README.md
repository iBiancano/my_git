# GIT PRACTICA 1

## Conceptos básicos de Git
* Git se basa en snapshots (instantáneas) del código en un estado determinado, que viene dado por el autor y la fecha
* Un Commit es un conjunto de cambios guardados en el repositorio de Git y tiene un identificador SHA1 único
* Las ramas (branches) se pueden pensar como una línea de tiempo a partir de los commit. Hay siempre como mínimo una rama principal o predefinida llamada Master
* Head es el puntero al último commit en la rama activa
* Remote se refiere a sitios que hospedan repositorios remotos como GitHub, BitBucket o GitLab

## Conectarse a una sesión de GitPod
1) Crear un nuevo repositorio en nuestro GitHub llamado "my_git" e inicializarlo con el archivo README de forma automática
* Se puede hacer un fork de https://github.com/Juli-BCN/my_git
2) Abrir una sesión en GitPod con el nuevo respositorio, que seria una URL parecida a esta:
```
https://gitpod.io#https://github.com/Juli-BCN/my_git
```

## Ayuda de Git
Con `git help` en el terminal obtenemos ayuda. Vamos a mirar la ayuda de configuración con:
> git help config


## Configuración de Git
Como mínimo debemos configurar el nombre y el email en la aplicación con el comando `git config`:
> git config --global user.name "Nombre Apellido"

> git config --global user.email "tu_email_aqui@ejemplo.com"

Para comprobar podemos usar:
> git config -–global –list
