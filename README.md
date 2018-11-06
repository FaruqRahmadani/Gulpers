<p align="center">
  <h2 align="center">Gulper</h2>
  <p align="center">
    Powerful front-end tool for faster and easier web development.
  </p>
  <hr>
</p>

## Quick start

Several quick start, step by step:

- Clone the repo: `git clone https://github.com/syauqiahmd/Gulpers.git`
- Install base dependencies via [npm](https://www.npmjs.com/): `npm install`
- This task need gulp and webpack-cli globally, so please make sure you have install both of that with : `npm install gulp webpack-cli -g`

## What's included

Within the clone  repo you'll find the following directories and files. You'll see something like this:

```text
├── README.md
├── app
│   ├── css
│   │   └── app.css
│   ├── fonts
│   ├── img
│   │   └── fav.png
│   ├── index.html
│   └── js
│       └── app.js
├── node_modules
├── dist
│   ├── js
│   │   ├── _source
│   │   │   └── _testing.js
│   │   └── app.js
│   └── sass
│       ├── _source
│       │   └── _testing.scss
│       └── app.scss
├── gulpfile.js
├── package-lock.json
├── package.json
└── webpack.config.js
```

- you can write your sass or scss on `dist/sass/_mentah` and import in `dist/sass/app.scss`
- you can write your js on `dist/js/_mentah` and import/require in `dist/js/app.js` or you can concate from `node_modules` 

## How to run

- default task for serve and compile all resource `gulp` or `gulp serve`
- compile sass from resource to css on app using `gulp sass`
- compile js from resource to js on app using `gulp js` or `webpack -d`
