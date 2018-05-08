# generator-parcel
> Parcel based web app where everything just works

The goal of this generator is to provide a quick way to scaffold a front-end project using the latest technologies, powered by Parcel for an easy zero configuration setup. It has optional TypeScript and Sass support, and comes with babel and postcss with autoprefixer installed and setup.

## Quick Start
Install Yeoman first, then the generator:
```
npm i -g yo
npm i -g generator-parcel
```

Generate your project:
```
yo parcel
```

Run it:
```
npm start
```

## Sample output
Here's an example of what the project structure might look like after generation:
```
.
├── .babelrc
├── .gitignore
├── .postcssrc
├── .yo-rc.json
├── package-lock.json
├── package.json
├── node_modules
└── src
    ├── assets
    │   ├── scripts
    │   │   ├── app.ts
    │   │   └── index.ts
    │   └── styles
    │       └── index.scss
    └── index.html
```

## License
MIT © [Chris Anselmo](https://chrisanselmo.com/)
