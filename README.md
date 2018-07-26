# App App!

## Usage

```bash
npm i -g app-app
app-app APP_NAME [<flags>]
```

To generate your new project:

```bash
app-app cool-project-name
cd cool-project-name

atom .
npm start
```

For the `alpha` stack, you might want to install `tidy-html5`, and the [Tidy Linter](https://atom.io/packages/linter-tidy) for Atom:

```bash
brew install tidy-html5
```

#### ALPHA

* BrowserSync via `npm start`
* Deployment via `npm run deploy` to [Surge.sh](https://surge.sh)
* Linting in Atom with `stylelint` and `htmlhint`

#### BETA

* Everything in the `alpha` stack
* JavaScript (ES2015)
* Linting in Atom with `eslint` using JS Standard

### TODO

* [ ] CLI lint and warnings before deploy

## License

MIT &copy; [Jason L Perry](https://github.com/ambethia)
