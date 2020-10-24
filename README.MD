# Manuel Chichi CV

Este repositorio contiene el Curriculum Vitae de Manuel Chichi en formato JSON. Para visualizarlo se utilizo la herramienta *resume-cli*.

## Requisitos previos.

[NodeJs](https://nodejs.org/es/download/) que utilizaremos para servir el JSON en una web local.

## Comandos de uso.

Primero debemos instalar los paquetes necesarios.
```
npm install

En el caso de que se requiera visualizar el curriculum en una web debemos ejecutar el siguiente comando.
```
npm run resume serve
```

En caso de que sea requerido exportar el Curriculum como PDF, podemos ejecutar el siguiente comando.
```
npm run resume export resume.pdf
```