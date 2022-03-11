# Instalaciones recomendadas - Curso de Angular

## Instalaciones Necesarias
* [Google Chrome](https://www.google.com/chrome/)

* [Visual Studio Code](https://code.visualstudio.com/)

* [Postman](https://www.postman.com/downloads/)

* [Mongo Compass](https://www.mongodb.com/try/download/compass)

* [Git](https://git-scm.com/)

* [Crear cuenta en GitHub](https://github.com/)

```
git config --global user.name "Tu nombre"
git config --global user.email "Tu correo"
```

* [Cliente GitHub](https://desktop.github.com/)

* [Node](https://nodejs.org/es/)


## Extensiones de VSCode
[Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)

### Configuración del Bracket Pair Colorizer 2

[Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
```
"bracket-pair-colorizer-2.colors": [
    "#fafafa",
    "#9F51B6",
    "#F7C244",
    "#F07850",
    "#9CDD29",
    "#C497D4"
],
```
### Tema que estoy usando en VSCode:

* [Monokai Night](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-monokai-night)

* [Iconos](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

### Instalaciones recomendadas sobre Angular
* [Angular Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)

* [Angular Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

* [TypeScript importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)

* [Markdown](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

### Instalación de Angular y flujo de trabajo
* [Angular/Cli](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)

```
    npm install -g @angular/cli
    ng --version
```

### Typescript
* [Editor online] https://stackblitz.com/edit/typescript-vxnz8z)

* [Proyecto base](https://att-c.udemycdn.com/2020-11-26_22-16-40-1c57137749af2bcf444a011b338f78ac/original.zip?response-content-disposition=attachment%3B+filename%3Dcurso-angular-intro-typescript-ecmascript.zip&Expires=1645294749&Signature=Q1PCdY8PoyFlPNwuvThoNPjSu780C-I7mRi3j0USdzihUFATWrWOBII29D-iB7kSSXP7oL8Z3sBKzceKxhMdOWRUGTsAD1EXiUh6~P3ww48JCvB1uPBmAw462biUs5Ke4pUUFeYVJNfh3H9xv~xBMnhvBV7EsLYizrISrcDkg2~IQJn6nZ-7mL~Xc9qaITwt~3jy01RXwp6-qmvBwbn-PSLcyJeD57oGIcmC111n5d1AqKxvHxmkoQMK9RRpQj2ni6oy4uKiZYXHdhP99BR0biy-4gxWFIIZEWljm6iHbR2do7Es1Yjn6CViJPd-ANcvCYgZORoOi50voZ5wWR18og__&Key-Pair-Id=APKAITJV77WS5ZT7262A)

* [Instalar las dependencias] 
```
npm install
```

* [Ejecutar tu proyecto de Typescript] 
```
npm start
```

### Angular

* [Crear Proyecto]
```
    ng new project_name             Para crear el proyecto project_name
    ng serve -o                     Para correr el proyecto en el navegador
```

### Utilerías
* [Estilos](https://gist.github.com/Klerith/3ddee04a27c09be05e888d5d4ac1d09f)


### Errores comunes
* [Al crear el proyecto]
```
https://registry.npmjs.org/
```
Solución
```
npm config set registry="http://registry.npmjs.org/"
npm install source-map-resolve
```
* [Otro error al crear el proyecto]
```
npm WARN deprecated source-map-resolve@0.6.0: See https://github.com/lydell/source-map-resolve#deprecated
npm ERR! Cannot read properties of null (reading 'pickAlgorithm')
```
Solución
```
npm cache clear --force
```
