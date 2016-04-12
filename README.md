# ember-addon-snippets

Ember addon snippets for [Atom](http://atom.io/) and [VS Code](http://code.visualstudio.com/).

## ember-addon-snippets-atom
* View atom package [source](https://github.com/ciena-blueplanet/ember-addon-snippets-atom).
* [Installation](https://github.com/ciena-blueplanet/ember-addon-snippets-atom#consuming-ember-addon-snippets-in-atom)
* View package on [apm](https://atom.io/packages/ember-addon-snippets).

## ember-addon-snippets-vsc
* View vsc extension [source](https://github.com/ciena-blueplanet/ember-addon-snippets-vsc).
* [Installation](https://github.com/ciena-blueplanet/ember-addon-snippets-vsc#consuming-ember-addon-snippets-in-vsc)

### Adding snippets to your ember addons

Follow these instructions to add snippets to your ember addons. It will ensure that they can be consumed by [ember-addon-snippets-atom](https://github.com/ciena-blueplanet/ember-addon-snippets-atom) and [ember-addon-snippets-vsc](https://github.com/ciena-blueplanet/ember-addon-snippets-vsc).

1. Create a `snippets` folder at the root of your ember project.
2. Create a `snippets.json` file inside the `snippets` folder.
3. Fill `snippets.json` with snippets. Your file should have the following format.

```json
{
    ".source.hbs": {
        "ember-frost-button": {
            "prefix": "frost-button",
            "body": "{{frost-button}} $1"
        },
        ...
    },
    ".source.js": {
        "Console log": {
            "prefix": "log",
            "body": "console.log $1"
        },
        ...
    },
    ...
}
```


