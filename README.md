# eslint-pre-commit

#### copy from 3rdeden
```js
{
  "scripts": {
    "lint": "eslint"
  },
  "pre-commit": ["lint"]
}
```



for .eslintrc.js demo

```js
{
    "env": {
        "browser": true,
        "commonjs": true,
        "es6": true
    },
    "extends": "eslint:recommended",
    "parserOptions": {
        "ecmaFeatures": {
            "jsx": true
        },
        "sourceType": "module"
    },
    "globals": {
	"_": true,
        "$": true


    },

    "rules": {
        "indent": [
            "error",
            "tab"
        ],
        "linebreak-style": [
            "error",
            "unix"
        ],
        "quotes": [
            "error",
            "single"
        ],
        "semi": [
            "error",
            "always"
        ]
    }
}



```



### License

MIT
