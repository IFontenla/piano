# Empaquetado web

- Tengo ofuscación
- Tengo mimificacion
- Tree shaking
- Preprocesadores de CSS
- Frameworks de css
- Frameworks web
- Uso de lenguajes no javascript
- Mecanismos de optimizacion

# Empaquetadores famosos

- webpack
- rollup
- wmr
- esbuilt
- parcel
- snowpack
- vite

# Pasos

## Crear un proyecto node a partir de npm
npm init --yes

## Añadir la dependencia tonejs (dependencia de producción)
npm install tone

## Añadir el empaquetador parcel (dependencia de desarrollo)
npm install --save-dev parcel

## Construimos y arrancamos la aplicación
npx parcel src/index.html
npx parcel build src/index.html

# Añadimos la librería react
npm install react react-dom