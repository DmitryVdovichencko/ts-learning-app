# <img height=100px width=auto src='https://pbs.twimg.com/profile_images/1149708719178993664/3Hb8W4aX.png' /> TypeScript Learning App

## Install TS

* Install TypeScript globally, so we can use it everywhere

```
yarn global add typescript
```
* And check version

```
tsc --v
```
* In project folder we'll create `tsconfig.json` file

``` javascript
{
  "compilerOptions": {
    "target": "es6",
    "jsx": "react",
    "module": "commonjs"
  },
  "exclude": [
    "node_modules"
  ]
}
```
__Here we:__
1. Add options for TS compiler
    1. JS engine target is ES6
    2. Modules in CommonJS 
    3. `.jsx` files set to `react`
2. Ignore `node_modules`

