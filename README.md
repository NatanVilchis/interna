# [Interna] Script para cambiar el directorio actual al directorio de la memoria interna en Termux (Android)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/natanvilchis) <br>

Script simple para cambiar del directorio actual a la memoria interna <br>

*Leer en otros lenguajes: [Español](README.md), [Inglés](README.en.md)*

![Alt text](images/interna.jpg "Interna")
 
 
## Tabla de contenido
  - [Pre-requisitos](#pre-requisitos)
    - [Activar permisos de escritura](#activar-permisos-de-escritura)
    - [Instalar Git](#instalar-git)
      - [1) Instalar Git:](#1-instalar-git)
      - [2) Aceptar la instalación de Git:](#2-Aceptar-la-instalación-de-Git)
      - [3) Esperar hasta que la instalación termine: ](#3-Esperar-hasta-que-la-instalación-termine)
  - [Instalación](#instalacion)
    - [1) Obtener interna](#1-Obtener-interna)
    - [2) Abrir la carpeta interna](#2-Abrir-la-carpeta-interna)
    - [3) Ejecutar el script interna.sh](#3-Ejecutar-el-script-interna.sh)
  - [Ejemplo](#ejemplo)
 
	
## Pre-requisitos

### Activar permisos de escritura
Tener activados los permisos de escritura de Termux (Ajustes => Apps => Termux => Permisos => Almacenamiento)
<img src="images/permisos_1.jpg" width="25%" alt="Activar permisos en Termux">
<img src="images/permisos_2.jpg" width="25%" alt="Activar permisos en Termux">
<img src="images/permisos_3.jpg" width="25%" alt="Activar permisos en Termux">

### Instalar Git
Instalar git en Termux:  
#### 1) Instalar Git:
Ejecutar en termux el siguiente comando: <br> 
```
pkg install git
```


<img src="images/git_1.jpg" width="75%" alt="pkg install git"> <br>
#### 2) Aceptar la instalación de Git:
<img src="images/git_2.jpg" width="75%" alt="Aceptamos instalación"> <br>
#### 3) Esperar hasta que la instalación termine: 
<img src="images/git_3.jpg" width="75%" alt="Instalación terminada"> <br>

## Instalación
### 1) Obtener Interna
En Termux ejecutar el siguiente comando:
````
git clone https://github.com/NatanVilchis/interna
````
<img src="images/interna_1.jpg" width="75%" alt="Instalación de Interna"> <br>
Esperar a que termine de obtener todo el repositorio: <br>
<img src="images/interna_2.jpg" width="75%" alt="Instalación de Interna"> <br>
### 2) Abrir la carpeta interna
En Termux ejecutar el siguiente comando:
````
cd interna/interna
````
<img src="images/interna_3.jpg" width="75%" alt="Ejemplo"> <br>

### 3) Ejecutar el script interna.sh
En Termux ejecutar el siguiente comando:
````
bash interna.sh
````
<img src="images/interna_4.jpg" width="75%" alt="Ejemplo"> <br>

## Ejemplo
Desde cualquier directorio actual se puede escribir lo siguiente 
### Ejecución de interna
````
. interna
````
<img src="images/example_1.jpg" width="75%" alt="Ejemplo"> <br>
Se puede verificar que se encuentra en la carpeta de la memoria interna con el comando ls en Termux
````
ls
````
<img src="images/example_2.jpg" width="75%" alt="Ejemplo"> <br>



## Hecho por 
[Natan Vilchis](https://natanvilchis.org) <br>

## Licencia
Este proyecto está licenciado bajo la licencia MIT, ver  [LICENSE](LICENSE) para ver los detalles.
