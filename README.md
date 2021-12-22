# Git

## ¿Qué es git?

git es un sotware de control de versiones

## ¿Qué es github?

Github es un servicio web que arroja código y trabaja con git.

## git init

Este comando permite iniciar las modificaciones que se le realicen a un repositorio.

## git clone

Clona un repositorio remoto (que vive por ejemplo en GitHub) de manera local.

## git status

Describe el estado del repositorio actual, cambios a agregar, cambios agregados a commitear y commits a pushear si los hubiera. Además especifica información como la branch actual.

## git add

Agrega los cambios realizados en archivos/directorios del proyecto para formar parte del potencial próximo commit.

## git commit

Crea un hito o punto de control con todos los cambios agregados desde el último commit, permite añadirle un mensaje descriptivo (recomendado).

### good commits messages

- Capitalizados
- En inglés
- En infinitivo
- En presente simple

ej: "Add good commits messages tips"

## git log

Muestra el historial de commits del repositorio y branch actuales, el hash de cada uno, así como fecha y hora, autor y mensaje.

## git checkout

Permite desplazarse entre ramas git checkout nombre-de-la-rama así como crear nuevas ramas git checkout -b "nombre-de-la-rama".

## git push

Publica los commits los repositorios locales en un repositorio remoto.

## git pull

Actualiza el repositorio local con los commits que estén en el repositorio remoto y que sean faltantes.

## git merge

Permite mezclar o unir la rama de trabajo actual con una especificada.

## .gitignore

Es un archivo que permite especificar todos aquellos archivos y directorios que no son necesarios seguir, agregar, commitear, ni pushear.
Ejemplos: - Archivos con la extensión .pyc (archivos de Python)
	  - Directorios con la extensión /tmp (directorios) 

## Tutorial interactivo

[learngitbranching](https://learngitbranching.js.org/)
