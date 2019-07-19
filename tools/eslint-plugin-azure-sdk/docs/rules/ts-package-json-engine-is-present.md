# ts-package-json-engine-is-present

Requires support for all Node LTS version.

Currently, this requires `engine` in `package.json` to be set to `">=8.0.0"`.

## Examples

### Good

```json
{
  "engine": ">=8.0.0"
}
```

### Bad

````json
{
    "engine": ">=6.0.0"
}
```'

```json
{
    "engine": ">=10.0.0"
}
````

```json
{}
```

## [Source](https://azuresdkspecs.z5.web.core.windows.net/TypeScriptSpec.html#ts-package-json-engine-is-present)

Also encompasses [ts-node-support](https://azuresdkspecs.z5.web.core.windows.net/TypeScriptSpec.html#ts-node-support), as the rules are similar enough to not exist separately for linting purposes.