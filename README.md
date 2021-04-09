# @devsht/tsconfig

Reusable TS config

## Installation

```bash
npm i -D @devsht/tsconfig
```

or

```
yarn add --dev @devsht/tsconfig
```

## Usage

Create a **tsconfig.json** and add this package to the extends field.

```
{
    "extends": "@devsht/tsconfig",
    "compilerOptions": {
      "outDir": "dist"
    },
    "include": ["src"]
}
```
