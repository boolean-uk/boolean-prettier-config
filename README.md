# boolean-prettier-config

Source: https://dev.to/matthias/sharing-prettier-configuration-files-gba

## Usage

If you want to use your shared Prettier configuration in other projects, you need to reference it in your project's `package.json` manifest by adding the `prettier` property:

```json
{
  "name": "my-cool-library",
  // ...
  "prettier": "@boolean-uk/boolean-prettier-config"
  // ...
}
```
