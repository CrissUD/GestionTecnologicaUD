# GestionTecnologicaUD
## Descripcion

Este Repositorio da un seguimiento a la gestion de tecnologias para realizar la automatizacion de procesos relacionados con el desarrollo de un producto de software.

## Integrantes
Cristian Felipe Patiño Caceres - 20141020079

Maycol Hernandez Garcia- 20141020078

Javier Castañeda Castañeda - 20141020049 

## Instrucciones Docker compose

#### Primero debe clonar el repositorio, esto lo hacemos con la direccion del repositorio

git clone https://github.com/CrissUD/GestionTecnologicaUD.git

#### Entramos a la carpeta que contiene el repositorio en concreto

cd GestionTecnologicaUD/

#### Se ejecuta el archivo Docker-compose

sudo docker-compose up -d

#### En caso de sacar error por version se debe editar el archivo para cambiar la version de docker-compose

nano docker-compose.yml

#### Se ingresa al servicio desde el navegador wev

localhost:8080

#### El usuario y contraseña para el ingreso por defecto es "admin", "admin" 

#### Para bajar el servicio basta con 

sudo docker-compose down
