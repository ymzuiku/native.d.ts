# Typescript of native.js

## 安装

```sh
npm install --save-dev native.d.ts
```

或者

```sh
yarn add native.d.ts
```

## 使用

```ts
import 'native.d.ts';

document.addEventListener('plusready', runApp, false);

function runApp {
  // use plus.*
}
```
