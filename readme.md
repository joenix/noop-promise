# noop-promise

## 1. Install

```sh
npm i noop-promise
# or
yarn add noop-promise
# or
pnpm i noop-promise
```

## 2. Import

```js
import noopPromise from 'noop-promise';
// or
import { noopPromise } from 'noop-promise';
```

## 3. Use

```js
import { noopPromise } from 'noop.js';

const fn = async (callback = noopPromise) => {
  await callback();
};
```
