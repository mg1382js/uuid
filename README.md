# UUID Generator

This is a simple UUID generator class implemented in JavaScript. It generates a version 4 UUID (random UUID) without using any external packages.

## Installation

Since this is a standalone class, you don't need to install any packages. Just include the `uuid.js` file in your project.

## Usage

To use the `uuid` class to generate a UUID, follow the example below:

```js

import { uuid } from '@mahdi.golzar/uuid';

const uuidGenerator = new uuid();
const newUUID = uuidGenerator.generateUUID();

console.log(newUUID); // Example output: 'e8a5b86c-0f47-4db2-9b2e-95b61e0dfb69'
```
