# eslintrc

## Usage

### Config ESLint

create `.eslintrc.js` at your project root and write the following.

#### React Project

```javascript:.eslintrc.js
module.exports = {
  extends: ['./node_modules/@okatechnology/eslint-config/eslintrc/eslintrc-react'],
}
```

#### React Native Project

```javascript:.eslintrc.js
module.exports = {
  extends: ['./node_modules/@okatechnology/eslint-config/eslintrc/eslintrc-react-native'],
}
```

#### Next.js Project

```javascript:.eslintrc.js
module.exports = {
  extends: ['./node_modules/@okatechnology/eslint-config/eslintrc/eslintrc-react-next'],
}
```

#### Node.js Project

```javascript:.eslintrc.js
module.exports = {
  extends: ['./node_modules/@okatechnology/eslint-config/eslintrc/eslintrc-node'],
}
```

### Config Prettier

create `.prettierrc.js` at your project root and write the following.

```javascript:.prettierrc.js
module.exports = {
  ...require('@okatechnology/eslint-config/prettierrc/prettierrc'),
}
```

### Config TypeScript

create `tsconfig.json` at your project root and write the following.

#### React Project

```json:tsconfig.json
{
  "extends": "@okatechnology/eslint-config/tsconfig/tsconfig.react.json",
  "include": [...],
  "compilerOptions": {
    "baseUrl": "./"
  }
}
```

#### React Native Project

```json:tsconfig.json
{
  "extends": "@okatechnology/eslint-config/tsconfig/tsconfig.react-native.json",
  "include": [...],
  "compilerOptions": {
    "baseUrl": "./"
  }
}
```

#### Node.js Project

```json:tsconfig.json
{
  "extends": "@okatechnology/eslint-config/tsconfig/tsconfig.node.json",
  "include": [...],
  "compilerOptions": {
    "baseUrl": "./"
  }
}
```
