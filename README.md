![header](imagenes/header.png)

## TP5 Testing - IOT (UBA)

Autor:
* Iván Cruz Flores

Docentes:

* Esp. Ing. Estevan Volentini.
* Esp. Ing. Alejandro Permingeat.
* Carlos Pantelides.

## TEMA: Aplicación de técnicas de testing web 

Dentro del Master Test Plan se planificó aplicar la técnica de "State Transition Testing". 


## State Transition Testing:
es un tipo de prueba de software que se realiza para verificar el cambio en el estado de la aplicación con una entrada variable. Se cambia la condición de entrada pasada y se observa el cambio de estado.

State Transition Testing es básicamente una técnica de prueba de "caja negra" que se lleva a cabo para observar el comportamiento del sistema o aplicación para diferentes condiciones de entrada pasadas en una secuencia.

<p align="center">
    <img src="imagenes/State_transition.jpg">
</p>

## Práctica de estudio: 

Modificación al Master Test Plan

Agregar una característica a determinar al master test plan y desarrollar una acción de test de un test case sencillo de esta característica.

Se solicita entregar:

* Documento Master Test Plan modificado.
* Documento con el desarrollo de la acción de test.

Desarrollo:

* La presente práctica se enfoca en aplicar un ejemplo de test de caja negra para la función de Login del sistema del TP final.
* La estrutura funcional de las capas usadas en la aplicación de prueba, se aprecia en la siguiente imagen.

<p align="center">
    <img src="imagenes/capas-funcional.jpg">
</p>

# Herramienta usada: Wapiti 

Es ana herramienta que realiza pruebas de caja negra al escanear páginas web e inyectar datos. Intenta inyectar cargas y ver si un script es vulnerable. Es compatible con los ataques GET y POSTHTTP y detecta múltiples vulnerabilidades.

<p align="center">
    <img src="imagenes/herramienta.jpg"><br>
    Enlace oficial: https://wapiti.sourceforge.io/
</p>

Módulo funcional a usar:

<p align="center">
    <img src="imagenes/aplicacion.jpg">
</p>

En el siguiente video se muestra el Funcionamiento de lo aplicado durante la práctica:
<p align="center">
    <img src="imagenes/play.png"> https://youtu.be/UMlD7U_ij_w
 </p>

## Dependencias:
```
* Python 3.7
* Python pip.
* Wapiti Scanner.
```
