<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
     
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) Curso de Nest para Microservicios

## Installation

```bash

#### Clonar el repositorio
git clone

#### Reconstruir submódulos
git submodule update --init --recursive

#### Creat .env
cp env.template .env

#### Ejecutar Docker
docker-compose up --build
 



```
 


 ### Pasos para crear los Git Submodules


1. Crear un nuevo repositorio en GitHub
2. Clonar el repositorio en la máquina local
3. Añadir el submodule, donde `repository_url` es la url del repositorio y `directory_name` es el nombre de la carpeta donde quieres que se guarde el sub-módulo (no debe de existir en el proyecto)
```
git submodule add <repository_url> <directory_name>
```
4. Añadir los cambios al repositorio (git add, git commit, git push)
Ej:
```
git add .
git commit -m "Add submodule"
git push
```
5. Inicializar y actualizar Sub-módulos, cuando alguien clona el repositorio por primera vez, debe de ejecutar el siguiente comando para inicializar y actualizar los sub-módulos
```
git submodule update --init --recursive
```
6. Para actualizar las referencias de los sub-módulos
```
git submodule update --remote
```


## Importante
Si se trabaja en el repositorio que tiene los sub-módulos, **primero actualizar y hacer push** en el sub-módulo y **después** en el repositorio principal. 

Si se hace al revés, se perderán las referencias de los sub-módulos en el repositorio principal y tendremos que resolver conflictos.