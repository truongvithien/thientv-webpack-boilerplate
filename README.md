# 🚀 ThienTV's custom boilerplate

This is my custom boilerplate for web development. It includes some of my favorite frameworks and libraries. You can use it for your own project or just for learning purpose.

## Includes

There are some features that are included in this boilerplate. You can choose to use them or not by removing them from `package.json` file or remove them by `yarn remove ...` or `npm uninstall ...` command.

|Framework   | Available |
|------------|-----------|
| Webpack 5  | ✅        |
| Sass/SCSS  | ✅        | 
| Twig       | ✅        |
| JQuery     | ✅        |
| ThreeJS    | ✅        |
| GSAP       | ✅        |
| BarbaJS    | ✅        |
| ... | ... |

Output willl be in `dist/` folder. You can use `dist/` folder as your root folder for your web server or web static hosting.


## Development

### Initial setup
Run one of the following commands to install all dependencies.

```
npm install
```
```
yarn install
```

### Start watching development
Run one of the following commands to start watching your files for changes and automatically recompile them to `dist/` folder.
```
npm run dev
```
```
yarn dev
```

### Build for production
Run one of the following commands to build your application for production. This will minify your code and optimize it for production.

```
npm run build
```
```
yarn build
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

