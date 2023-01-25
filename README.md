
## Instalacion

Instalamos npm en el proyecto

```bash
  npm init

```
## Modificamos el script del archivo package.json

colocamos lo siguiente 

```bash
"build-sass": " node-ass –include-path scss ./scss/style.scss ./css/style.css -w"
```

luego creamos las carpetas scss y css e instalamos lo siguiente
```bash
npm i -D node-sass

```

Finalmente corremos sass con 
```bash
npm run buil-sass

```
