# [DragonToy-Tetrahedral-Sim]

Simulate Tetrahedral FEM Models in your browser in real-time using the GPU!

![Gif of DragonToy-Tetrahedral-Sim in action](./DragonToy-Tetrahedral-SimDemo.gif)



 # Building

This demo can either be run without building (in Chrome/Edge/Opera since raw three.js examples need [Import Maps](https://caniuse.com/import-maps)), or built with:
```
npm install
npm run build
```
After building, make sure to edit the index .html to point from `"./src/main.js"` to `"./build/main.js"`.

 # Dependencies
 - [three.js](https://github.com/mrdoob/three.js/) (3D Rendering Engine)
 - [esbuild](https://github.com/evanw/esbuild/) (Bundler)
