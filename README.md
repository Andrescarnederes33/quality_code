# Quality Code
En este proyecto se utilizaron las siguientes tecnologías:

- [ReactJs](https://es.reactjs.org/) - Diseño de interfaz
- [Material UI](https://material-ui.com/) - Libreria de componentes UI
- [Prettier](https://prettier.io/) - Formato para codigo

##¿Como funciona?

- src/containers -> Secciones de las paginas, compuestas por componentes.
- src/components -> Componentes globales de la aplicación.
- src/components -> Componentes globales de la aplicación.
- src/hooks -> Almacena todos los `Hooks` en las nuevas caracteristicas de ReactJs.
- src/utils -> Utilidades extras (JWT, Theme, StatusMessages).


##Metodologías
- BEM (Css)

##Development
```sh
npm install --save
npm run dev
```

##Production
```sh
npm run build
npm install serve --save-dev
npm serve -S ./build -p 3001
```