# Conceptos básicos

## Repositorio

Un **repositorio** es como una carpeta en la que se encuentran archivados los ficheros de tu proyecto:

- Código
- Documentación
- Ejemplos

### Tipos de repositorios

- **Público:** visible para todos.
- **Privado:** acceso restringido para usuarios específicos.

## Archivo README

El archivo **README** contiene instrucciones básicas para conocer y moverse por el repositorio.

Puede contener:

- Nombre del proyecto
- Descripción y créditos
- Índice de contenidos
- Uso del proyecto
- Licencia

## Rama

Una **rama (branch)** es una copia del contenido de un proyecto que permite trabajar en cambios sin modificar directamente la rama principal.

### Rama master

La rama **master** contiene el proyecto original o principal.

> Actualmente, muchos proyectos utilizan `main` como nombre de la rama principal.

### Rama remota

Es una rama que se encuentra en el repositorio remoto y permite trabajar de forma paralela.

También podemos tener una **rama local**, que es una copia en nuestro ordenador donde podemos trabajar sin afectar al proyecto original.

## Clone y Fork

### Clone

**Clone** es una copia del proyecto original que descargamos en nuestro ordenador para trabajar de forma local y offline.

### Fork

**Fork** es una copia del proyecto original que se crea en nuestro perfil de GitHub para poder trabajar con él de forma independiente y online.

## Commit

Un **commit** es un registro de los cambios que vamos realizando en un proyecto.

A medida que vamos haciendo cambios, modificando ficheros, añadiendo nuevas líneas o borrando las existentes, vamos guardando esos cambios en forma de **commits**.

Un commit se puede entender como una **foto o versión del proyecto en un momento determinado**.

Los commits se guardan en la rama local en la que estamos trabajando.

## Push y Pull Request

### Push

El **push** sirve para enviar nuestros cambios desde el repositorio local al repositorio remoto.

Es decir, enviamos nuestros cambios hacia el repositorio remoto.

```bash
git push
```
## Pull Request

Un **Pull Request** es una solicitud para integrar nuestros cambios en la rama principal.

Es como una solicitud de **revisión o aportación** para que nuestros cambios sean revisados antes de integrarlos.

Normalmente se realiza desde la interfaz gráfica de GitHub.

## Merge

El **merge** sirve para integrar los cambios de una rama en otra.

Por ejemplo, podemos integrar los cambios de una rama de trabajo en la rama principal.

Cuando se realiza el **merge**, los cambios de las dos ramas quedan integrados.

En GitHub, los cambios pueden ser revisados mediante un **Pull Request** antes de realizar el merge.

# Las 3 áreas de Git

Git trabaja con tres áreas diferentes:

## 1. Working Area (Área de trabajo)

Es el directorio en el que estamos trabajando.

Aquí realizamos los cambios en los archivos del proyecto.

## 2. Staging Area (Área de preparación)

Es donde colocamos los archivos o cambios que queremos guardar en el próximo commit.

Por ejemplo:

    git add archivo.txt

## 3. Repository (Repositorio)

Es donde se almacenan los datos, los commits y todos los cambios realizados en el proyecto.

# Git

**Git** es un software de control de versiones distribuido que permite colaborar y trabajar con otras personas en la creación de un proyecto.

Git permite:

- Guardar diferentes versiones de un proyecto.
- Registrar los cambios realizados.
- Trabajar con diferentes ramas.
- Recuperar versiones anteriores.
- Colaborar con otras personas.

# Markdown

**Markdown** es un lenguaje de marcas que facilita la aplicación de formato a un texto para publicarlo en una página web.

Permite crear fácilmente:

- Títulos
- Listas
- Texto en **negrita**
- Texto en *cursiva*
- Enlaces
- Código
- Tablas

# GitHub

**GitHub** es una plataforma web para alojar proyectos que utiliza **Git** como herramienta de control de versiones.

En GitHub se pueden almacenar:

- Código
- Documentación
- Software
- Ejemplos

Además, permite trabajar y colaborar con otras personas en un mismo proyecto.
