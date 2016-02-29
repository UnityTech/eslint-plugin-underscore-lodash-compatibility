# eslint-plugin-underscore-lodash-compatibility

Ensures your javascript can use underscore or lodash interchangeably as a dependency.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-underscore-lodash-compatibility`:

```
$ npm install eslint-plugin-underscore-lodash-compatibility --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-underscore-lodash-compatibility` globally.

## Usage

Add `underscore-lodash-compatibility` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "underscore-lodash-compatibility"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "underscore-lodash-compatibility/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here


## License and Copyright

Copyright 2016 Afnan Fahim. All rights reserved.

[MIT License](http://en.wikipedia.org/wiki/MIT_License)