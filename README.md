# Introduction: eslint-config-andrmoel

This library contains the global eslint config for all andrmoel projects.

# Getting started

## Installing

1. Add the development dependency
    ```
    yarn add git+ssh://git@github.com/andrmoel/eslint-config-andrmoel -D
    ```
2. Add config to your `.eslintrc.json` file
    ```
    {
      "extends": [
        "eslint-config-andrmoel/default",
        "eslint-config-andrmoel/react"
      ]
    }
    ```

## Configuration files

### default config

This configuration contains general JavaScript/ES6 formatting rules.

Example usage:
```
{
  "extends": [
    "eslint-config-andrmoel/default"
  ]
}
```

### react config

This configuration contains general JSX/react formatting rules.

Example usage:
```
{
  "extends": [
    "eslint-config-andrmoel/react"
  ]
}
```
