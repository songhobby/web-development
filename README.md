# web-development

Minimal `Webpack` setup for `React` project with `Typescript`, `Sass`, `Babel` and `Material UI`.

## Hightlights:

0. From Scratch, contrary to `create-react-app`

1. Automatical `html tag` injection with hashed file name. (etc. `<link href="styles.[contenthash].css" />`, `<script ...`)

2. Pipelined processing of `Sass`, `ts`, `tsx` files with `Babel`

3. Seperate `Webpack` configuration for development and production

## Typical `npm` setup steps

```
npm start (for development)
npm build (for production)
```
