# Example demonstrating issue with Typescript + ES6 + modules such as Express

## Usage

1. `npm install`
2. `tsc`

## Expected results

Should be able to call `express()` to construct a new express app

## Actual results

```
➜  express-es6-ts-example git:(master) tsc
typings/serve-static/serve-static.d.ts(76,36): error TS2305: Module '"express"' has no exported member 'Response'.
typings/serve-static/serve-static.d.ts(77,17): error TS2305: Module '"express"' has no exported member 'Handler'.
```
