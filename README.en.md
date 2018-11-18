# [Interna] Script to change the current directory to the internal memory directory in Termux (Android)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/natanvilchis) <br>

Simple script to change from the current directory to the internal memory <br>

*Read in other languages: [Spanish](README.md), [English](README.en.md)*

![Alt text](images/interna.jpg "Interna")
 
 
## Tabla de contenido
  - [Pre-requirements](#pre-requirements)
    - [Enable write permissions](#Enable-write-permissions)
    - [Install Git](#Install-Git)
      - [1) Install Git:](#1-Install-Git)
      - [2) Accept the installation of Git:](#2-Accept-the-installation-of-Git)
      - [3) Wait until the installation finishes: ](#3-Wait-until-the-installation-finishes)
  - [Installation](#Installation)
    - [1) Get interna](#1-Get-interna)
    - [2) Open folder interna](#2-Open-folder-interna)
    - [3) Run script interna.sh](#3-run-script-interna)
  - [Example](#example)
 
	
## Pre-requirements

### Enable write permissions
Have the Termux write permissions enabled (Settings => Apps => Termux => Permissions => Storage)
<img src="images/permisos_1.jpg" width="25%" alt="Enable write permissions">
<img src="images/permisos_2.jpg" width="25%" alt="Enable write permissions">
<img src="images/permisos_3.jpg" width="25%" alt="Enable write permissions">

### Install Git
Install Git in Termux:  
#### 1) Install Git:
Execute the following command in termux: <br> 
```
pkg install git
```

<img src="images/git_1.jpg" width="75%" alt="pkg install git"> <br>
#### 2) Accept the installation of Git:
<img src="images/git_2.jpg" width="75%" alt="Accept installation"> <br>
#### 3) Wait until the installation finishes:
<img src="images/git_3.jpg" width="75%" alt="Installation finishes"> <br>

## Installation
### 1) Get Interna
In Termux execute the following command:
````
git clone https://github.com/NatanVilchis/interna
````
<img src="images/interna_1.jpg" width="75%" alt="Interna Installation"> <br>
Wait until you finish getting the entire repository: <br>
<img src="images/interna_2.jpg" width="75%" alt="Interna Installation"> <br>
### 2) Open the internal folder
In Termux execute the following command:
````
cd interna/interna
````
<img src="images/interna_3.jpg" width="75%" alt="Interna Installation"> <br>

### 3) Run script interna
In Termux execute the following command:
````
bash interna.sh
````
<img src="images/interna_4.jpg" width="75%" alt="Interna Installation"> <br>

## Example
From any current directory you can write the following:
### Ejecución de interna
````
. interna
````
<img src="images/example_1.jpg" width="75%" alt="Example"> <br>
You can verify that you are in the folder of the internal memory with the command ls in Termux
````
ls
````
<img src="images/example_2.jpg" width="75%" alt="Example"> <br>



## Made by
[Natan Vilchis](https://natanvilchis.org) <br>

## License
This project is licensed under the MIT license, see [LICENSE](LICENSE) to see the details.
