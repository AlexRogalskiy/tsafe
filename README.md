<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/117557564-572a0a80-b074-11eb-9d54-4ecfb5fb208f.png">  
</p>
<p align="center">
    <i>A collection of utilities for stepping up your TypeScript game</i>
    <br>
    <br>
    <a href="https://github.com/garronej/tsafe/actions">
      <img src="https://github.com/garronej/tsafe/workflows/ci/badge.svg?branch=main">
    </a>
    <a href="https://bundlephobia.com/package/tsafe">
      <img src="https://img.shields.io/bundlephobia/minzip/tsafe">
    </a>
    <a href="https://www.npmjs.com/package/tsafe">
      <img src="https://img.shields.io/npm/dw/tsafe">
    </a>
    <a href="https://github.com/garronej/tsafe/blob/main/LICENSE">
      <img src="https://img.shields.io/npm/l/tsafe">
    </a>
</p>
<p align="center">
  <a href="https://www.tsafe.dev">Home</a>
   - 
  <a href="https://docs.tsafe.dev">Documentation</a>
</p>

## Three GIFs to convince you that you need `tsafe` in your life

<p align="center">
    <br>
    <i>Assert things you know are true, get runtime errors where you were wrong:</i>
    <br>
    <br>
    <img src="https://user-images.githubusercontent.com/6702424/134988258-9d3d4097-628b-4b8f-b00b-d256f7c2361c.gif">
</p>
<p align="center">
    <i>Implement compile time unit testing (<a href="https://github.com/garronej/tsafe/blob/main/src/test/exclude.types.ts">example</a>):</i>
    <br>
    <br>
    <img src="https://user-images.githubusercontent.com/6702424/134994250-29f1b5c3-2193-49ba-ad75-e3c981723724.gif">
</p>
<p align="center">
    <i>Make TypeScript believe whatever you say:</i>
    <br>
    <br>
    <img src="https://user-images.githubusercontent.com/6702424/134994590-f01b8aee-a94a-4b4c-8f43-ee5ce8911443.gif">
</p>

## Motivations

Powerful TypeScript features like [assertion functions](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html#assertion-functions) or [user-defined type guards](https://www.typescriptlang.org/docs/handbook/advanced-types.html#user-defined-type-guards) are only useful if paired with utility functions.

TypeScript, however, only exports type helpers \(e.g. `Record`, `ReturnType`, etc.\).

This module provides _«the missing builtins»_ such as [the assert function](https://docs.tsafe.dev/assert)
and corrects frustrating aspects of default utility types such as [`ReturnType`](https://docs.tsafe.dev/returntype).

[**Documentation website**](https://docs.tsafe.dev)

## Installation

`tsafe` is both an [NPM](https://www.npmjs.com/package/tsafe) and a [Deno](https://deno.land/x/tsafe) module.
(Achieved with [denoify](https://github.com/garronej/denoify))

## Import in deno:

```typescript
import { assert, typeGuard, ... } from "https://deno.land/x/tsafe/mod.ts";
```

## Install elsewhere:

```bash
$ npm install --save tsafe
#OR
$ yarn add tsafe
```
