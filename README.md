# Node Front End Build Process
>  *Build process to design front end web interfaces using NPM scripts or maybe gulp*
>
> *A rebuild of [Puddletown Bootstrap](https://github.com/PuddletownDesign/puddletown-bootstrap)*

---

## Puddletown Bootstrap Features

### Modes

- `Dev` - Normal development process started using `npm start`
- `Build` - Creates a `deploy` directory when `npm run build` is run.

### Gulp (due to speed) for the following features:

- HTML Minification
- Image Minification
- SVG Minification
- SASS Conversion
- CSS Autoprefixing
- SASS / JS Source Maps

## Using Webpack Puddletown Bootstrap:

- Converted ES6 to ES5
- Treeshaking
- Hot Reloading

## For Testing 

- Mocha
- Chai

## Puddletown Bootstrap `package.json` devDependencies

- "babel-core": "^6.26.3" - for ES6 conversion
- "babel-loader": "^6.4.1" - for running babel
- "babel-preset-env": "^1.7.0" - babel preset
- "chai": "^4.2.0" - mocha testing framework
-  "gulp": "^3.9.1" - script runner
-  "gulp-autoprefixer": "^5.0.0" - css autoprefixing
- "gulp-connect": "^5.7.0" - hot reloading
- "gulp-htmlmin": "^5.0.1" - html minification
- "gulp-imagemin": "^6.2.0" - image minification
- "gulp-sass": "^4.0.2 - SASS conversion
- "gulp-sourcemaps": "^2.6.5" - sourcemaps creation for SASS / JS
- "gulp-svgmin": "^2.2.0" SVG MInification
- "mocha": "^6.2.2" - Testing framework
- "rimraf": "^3.0.0" - Directory deletion
- "webpack": "^3.12.0" - JS Builder
- "webpack-stream": "^3.2.0" - Webpack hot reloading

---

**🤍2025 [Brenton Holiday](https://github.com/8rents?tab=repositories)**
