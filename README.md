# prettier-config-mrdgh2821

Prettier Config for MRDGH2821's projects

## Install

Install using this command.

```bash
npm i prettier-config-mrdgh2821 --save-dev
```

## Usage

To use this config:

Edit your `package.json` file and add a field `"prettier": "prettier-config-mrdgh2821"`

```json
{
  "name": "my-cool-library",
  "version": "9000.0.1",
  "prettier": "prettier-config-mrdgh2821"
}
```

Or refer [this](https://prettier.io/docs/en/configuration.html#sharing-configurations)

## Rules

```json
{
  "printWidth": 100, // https://github.com/airbnb/javascript#19.13
  "tabWidth": 2, // https://github.com/airbnb/javascript#19.1
  "useTabs": false, // https://github.com/airbnb/javascript#19.1
  "semi": true, // https://github.com/airbnb/javascript#21.1
  "singleQuote": true, // https://github.com/airbnb/javascript#6.1
  "quoteProps": "as-needed", // https://github.com/airbnb/javascript#3.6
  "jsxSingleQuote": false, // https://github.com/airbnb/javascript/tree/master/react#quotes
  "trailingComma": "all", // https://github.com/airbnb/javascript#20.2
  "bracketSpacing": true, // https://github.com/airbnb/javascript#19.12
  "bracketSameLine": true,
  "jsxBracketSameLine": false, // https://github.com/airbnb/javascript/tree/master/react#alignment
  "arrowParens": "always", // https://github.com/airbnb/javascript/tree/master/react#alignment
  "requirePragma": false,
  "insertPragma": false,
  "proseWrap": "preserve",
  "htmlWhitespaceSensitivity": "css",
  "endOfLine": "lf",
  "embeddedLanguageFormatting": "auto",
  // Some settings automatically inherited from .editorconfig
  "overrides": [
    {
      "files": ".editorconfig",
      "options": {
        "parser": "yaml"
      }
    }
  ]
}
```
