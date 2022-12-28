# @mkropat/eslint-config

*An opinionated set of style rules*

## How to add to a new project

1. Install packages:

    ```
    npm install --save-dev eslint @mkropat/eslint-config
    ```

2. Add the following entry to your eslintrc file:

    ```javascript
    {
      "extends": "@mkropat"
    }
    ```

    <details><summary>Example <code>.eslintrc.json</code> starter file</summary>

    ```javascript
    {
      "env": {
        "browser": true,
        "node": true,
        "es2021": true
      },
      "extends": "@mkropat",
      "parserOptions": {
        "ecmaVersion": "latest",
        "sourceType": "module"
      }
    }
    ```

    </details>

## How to update the config

1. Make the change
2. Commit the change
3. Run: `npm publish --access=public`
