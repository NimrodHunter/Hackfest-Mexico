# Hackfest Blockchain México (ConsenSys + Microsoft)

[DIAS]
30 y 31 de agosto del 2017

[HORARIOS]
Miércoles: 8:30 am – 6:00 pm
Jueves: 8:30 am – 5:00 pm

[LUGAR]
Microsoft México
Av. Vasco de Quiroga 3200, Microsoft México, Ciudad de Santa Fe, México DF

# Installación de herramientas

Las herramientas, librerías y framweworks que se usarán en la hackatón son los siguientes: `nodejs`, `testrpc` y `truffle`

## Getting started

1) Instalar [nodejs](https://nodejs.org/en/download/). También se pueden usar los [gestores de paquetes](https://nodejs.org/en/download/package-manager/) de cada OS para instalar este framework.
* **Nota:** Si se tiene una versión antigua de nodejs, es posible que los paquetes npm no funcionen (TestRPC requiere node 6.9.1, por ejemplo)

2) Instalar TestRPC. Es posible que se requieran instalar [dependencias adicionales](https://github.com/ethereumjs/testrpc) según el OS en el que se esté trabajando.
Por lo general, la forma de instalarlo es la siguiente:
```
npm install -g ethereumjs-testrpc
```
El flag `-g` es para la instalación global del paquete

3) Instalar [truffle](https://truffle.readthedocs.io/en/latest/getting_started/installation/). Sólo debería bastar con el siguiente comando:
```
npm install -g truffle
```
4) Instalar [metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn). Metamask es un plugin que se agrega en el navegador web Google Chrome. Metamask provee una billetera electrónica de Ether capaz de interactuar con nuestras Đapps. Debes crear una cuenta ... listo! ya puedes enviar y recibir Ether. Ten en consideración que metamask permite cambiar la red con la que estas trabajando.


Con estas herramientas instaladas, ya estamos en condiciones de desarrollar y probar nuestras Đapps en nuestro entorno de desarrollo local.
