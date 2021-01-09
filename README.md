# @pcode-at/tsconfig

A shared TypeScript configuration for pcode projects based on [@seancroach/tsconfig](https://github.com/seancroach/tsconfig).

## Highlights

- Enables strict options which enforce type safety
- Enables linting options which enforce a higher quality of code
- Enables importing `.json` files directly within TypeScript
- Targets Node v10 to ensure compatibility with all active LTS Node versions

Of course, you _could_ write all the configurations yourself, but why do that when
it's already right here to use!

## Installation

Install `@pcode-at/tsconfig` through `npm`:

```
$ npm install --save-dev @pcode-at/tsconfig
```

## Usage

In your `tsconfig.json` file, extend `@pcode-at/tsconfig` using the `extends` field:

```jsonc
{
  "extends": "@pcode-at/tsconfig"
  // ...
}
```

## License

This package is available as open source under the terms of the [MIT License](https://github.com/pcode-at/tsconfig/blob/latest/LICENSE.md).
