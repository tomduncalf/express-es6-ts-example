# Example demonstrating issue with Typescript + ES6 + modules such as Express

## Usage

1. `npm install`
2. `tsc`

## Expected results

Should be able to call `express()` to construct a new express app

## Actual results

```
➜  express-es6-ts-example git:(master) tsc
index.ts(1,8): error TS1192: Module '"express"' has no default export.
```
