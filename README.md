# eslint-plugin-edudoc

edudoc

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-edudoc`:

```
$ npm install eslint-plugin-edudoc --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-edudoc` globally.

## Usage

Add `edudoc` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "edudoc"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "edudoc/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





