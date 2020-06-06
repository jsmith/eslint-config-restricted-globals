# eslint-config-restricted-globals
Restrict global variables to prevent accidental global access. Based on this TypeScript [issue](https://github.com/microsoft/TypeScript/issues/14306).

## Installation
```
npm install --save-dev eslint-config-restricted-globals
```

## Usage
Place this config inside the `extends` section of your `eslint` config file.
```json
{
  "extends": [
    ...
    # alternatively you can omit eslint-config- and just place "restricted-globals"
    "eslint-config-restricted-globals",
    ...
  ]
}
```

## References
Based on [this comment](https://github.com/microsoft/TypeScript/issues/14306#issuecomment-552890299) from @jahooma.
