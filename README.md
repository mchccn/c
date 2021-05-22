| [a](https://www.npmjs.com/package/@cursorsdottsx/a)
| [b](https://www.npmjs.com/package/@cursorsdottsx/b)
| **c**
| [d](https://www.npmjs.com/package/@cursorsdottsx/d)
| [e](https://www.npmjs.com/package/@cursorsdottsx/e)
| [f](https://www.npmjs.com/package/@cursorsdottsx/f)
| [g](https://www.npmjs.com/package/@cursorsdottsx/g)
| [h](https://www.npmjs.com/package/@cursorsdottsx/h)
| [i](https://www.npmjs.com/package/@cursorsdottsx/i)
| [j](https://www.npmjs.com/package/@cursorsdottsx/j)
| [k](https://www.npmjs.com/package/@cursorsdottsx/k)
| [l](https://www.npmjs.com/package/@cursorsdottsx/l)
| [m](https://www.npmjs.com/package/@cursorsdottsx/m)
| [n](https://www.npmjs.com/package/@cursorsdottsx/n)
| [o](https://www.npmjs.com/package/@cursorsdottsx/o)
| [p](https://www.npmjs.com/package/@cursorsdottsx/p)
| [q](https://www.npmjs.com/package/@cursorsdottsx/q)
| [r](https://www.npmjs.com/package/@cursorsdottsx/r)
| [s](https://www.npmjs.com/package/@cursorsdottsx/s)
| [t](https://www.npmjs.com/package/@cursorsdottsx/t)
| [u](https://www.npmjs.com/package/@cursorsdottsx/u)
| [v](https://www.npmjs.com/package/@cursorsdottsx/v)
| [w](https://www.npmjs.com/package/@cursorsdottsx/w)
| [x](https://www.npmjs.com/package/@cursorsdottsx/x)
| [y](https://www.npmjs.com/package/@cursorsdottsx/y)
| [z](https://www.npmjs.com/package/@cursorsdottsx/z)
|

**C is for Crates**

# @cursorsdottsx/c

F\*ck require and import, use crates (will still need require and import tho :C)!

Crates is very easy to install! It can be installed with either NPM or Yarn:

```bash
npm install @cursorsdottsx/c
```

```bash
yarn add @cursorsdottsx/c
```

It has a versatile API with just one function as well.

```js
const crates = require("@cursorsdottsx/c").default;

crates("add", (a, b) => {
    return a + b;
});

function add(a, b) {
    return crates("add", [a, b]);
}

crates("math", {
    add,
    subtract(a, b) {
        return a - b;
    },
});

console.log(add(1, 2)); // 3

console.log(crates("math").subtract(1, 2)); // -1
```

### Typical documentation

### `crates` – Four overloads:

`crates(name)` – Retrieve a crate.

-   `name` – The name of the crate.

`crates(name, args)` – Retrieves a crate and calls it (has to be a function).

-   `name` – The name of the crate.
-   `args` – Array of arguments to pass to the crate.

`crates(name, object)` – Defines a new crate.

-   `name` – The name of the crate.
-   `object` – The crate.

`crates(name, function)` – Defines a new crate as a function that can be called.

-   `name` – The name of the crate.
-   `object` – The crate.

[npm abc's homepage](https://codepen.io/cursorsdottsx/full/KKWNRaY)
