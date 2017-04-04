# CSShortcut App

> Projeto Descolado <3

## Stack

- Task Runner: [Gulp](http://gulpjs.com/)
- Html Template Engine: [Pug](https://pugjs.org/api/getting-started.html)
- Css Preprocessor: [Stylus](http://stylus-lang.com)

## Run the project locally

1 - Prepare the evironment:

```sh
npm install -g gulp-cli
```

2 - Clone the project and install the dependecies

```sh
git clone https://github.com/Bilusca/csshortcut-app.git
cd csshortcut-app
npm install
``` 

3 - Run static server and livereload

```sh
gulp server
```

## Folders Structure

	.
	├── README.md
	├── LICENSE.md
	├── CONTRIBUTING.md
	├── out/
	├── src/
	|   ├── assets/
	|   |   ├── img/
	|   |   ├── scripts/
	|   |   |   └── script.js
	|   |   └── styles/
	|   |       └── style.styl
	|   ├── partials/
	|   |   ├── footer.pug
	|   |   └── header.pug
	|   ├── layouts/
	|   |   └── default.pug
	|   └── index.pug
	├── gulpfile.js
	├── package.json
	├── .editorconfig
	└── .gitignore


[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](https://github.com/Bilusca/csshortcut-app/blob/master/LICENSE.md)

> Projeto sussa pra aprender umas paradas ai.

## Automatic Tasks

- `$ gulp build`: Compile, concat and minify all files
- `$ gulp server`: Watch the files and start a static server

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing
Find on our [roadmap](https://github.com/Bilusca/csshortcut-app/issues/1) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/Bilusca/csshortcut-app/blob/master/CONTRIBUTING.md).

## License
[MIT License](https://github.com/Bilusca/csshortcut-app/blob/master/LICENSE.md)