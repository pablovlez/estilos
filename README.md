
**Instalacion en Ubuntu**

**Instalar NodeJs**

Node.js v10.x:

```sh
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
```

**Clonar el repositorio**
```sh
git clone origin https://github.com/pablovlez/estilos.git
```

**Instalacion de la aplicacion y dependencias**

Situarse en el directorio del proyecto y ejecutar los siguientes comandos

```sh
npm install 
```

**Archivos de desarrollo**

En el directorio ./scss se encuentra el archivo custom.scss donde se definirán los nuevos estilos o estilos a heredar.

**Compilando los archivos sass**

Para compilar el archivo se ejecuta el siguiente comando:

```sh
npm run build:prod 
```

El archivo generado en el directorio ./build/custom.css es el que se incluye en la aplicación web

