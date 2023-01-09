# a-treeshakable-pkg

## Introduction

This package is only designed for treeshaking test, and it contains 3 functions named as 'a' 'b' and 'c'

## Installation

```bash
npm install a-treeshakable-pkg --save
```

## Usage

```js
import { a } from "a-treeshakable-pkg";
a();
export { a };
```

Test your build to see if only function `a` is bundled.
