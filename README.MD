Detector de Objetos especificamente la deteccion de camguros, es una clase aparte entrenada y preexistente.

Todo se resuelve en el archivo app.js

La idea es escalarlo para poder integrarse a pps o webs con modales de foto en tiempo real.

#### Levantarlo Localmente
Para correr la app de manera local es necesario intalar las dependencias:

```
npm install
```

And start:

```
npm start
```

La app correra en el pto 3000 `[http://localhost:3000](http://localhost:3000)`


El modelo toma de 1 a 2 segundos en cargar, después de eso, muestra las imágenes de los objetos a la cámara y la aplicación dibujará cuadros delimitadores a su alrededor. Obteniendo sus coordenadas.
