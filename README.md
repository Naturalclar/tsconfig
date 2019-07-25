# tsconfig

Base Typescript config for my projects

## Usage

First, install the package

```
yarn add -D @naturalclar/tsconfig
```

Then, in your project directory, make a new `tsconfig.json`

```json
{
  "extends": "@naturalclar/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "rootDir": "src"
  }
}
```

## License

MIT
