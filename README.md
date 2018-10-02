{{- /* **NOTE: This  template comment will be removed by [`tmpl`].**
# gitbook.tmpl

Template of [GitBook](https://github.com/GitbookIO/gitbook)

## How to use this template

```bash
# Install tmpl
go get -u github.com/nwtgck/tmpl

# Create a project from this template
tmpl new https://github.com/nwtgck/gitbook.tmpl.git mygitbook
```

Then, you will have `mygitbook/` directory.

## What should you do after [`tmpl`] run?

Modify files in [./docs](docs).

[`tmpl`]: https://github.com/nwtgck/tmpl

<!-- The following section is a template of README.md-->
*/ -}}
# {{.project_name}}

{{.description}}

## How to build

```sh
cd {{.DirName}}
npm install
npm run build
```

Then you can `./_book/index.html` in your browser

## How to develop GitBook

```sh
cd {{.DirName}}
npm install
npm start
```

Then a server for developing will run on http://localhost:4000/ .
If you edit some .md files, the server automatically rebuild!

## How to deploy to GitHub pages

```sh
$ cd {{.DirName}}
$ npm install
$ npm run deploy
```

## Helpful sites
* https://developer.gitbook.com/ - Latest-GitBook-used website
