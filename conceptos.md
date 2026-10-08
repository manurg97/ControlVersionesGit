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
