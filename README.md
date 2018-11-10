This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Why use this rather than the official create-react-app:

- This project just uses the official CRA to bootstrap.
- NO eject. Everything is original.
- Just add few more features to make developer life easier.

## How to use it?

- Clone or fork this repo instead of `create-react-app blahBlah`
- Then start coding.

## Added the following features:

In the project directory, you can run:

#### 1. Enable the in-IDE ESLint tips

Just add `eslintConfig` to `package.json`

#### 2. Use `normalize.css`

A better version `reset.css`, already installed and imported in `index.js`.

#### 3. `yarn update` or `npm run update`

It will interactively check the latest version for your packages and let you choose whether to update or not.

It you use `npm` over `yarn`, please run the following command:

```bash
npm uninstall syncyarnlock
npm install --dev npm-check
```

Then replace the `update` script in `package.json` to this: `npm-check -u`

#### 4. `yarn inspectBundle` or `npm run inspectBundle`

It will build your production build and analysis your bundle file in a nice way.

#### 5. `yarn formatAllCode` or `npm run formatAllCode`

It will format all your JavaScript code with `prettier`.

If you use `TypeScript`, change the `formatAllCode` script to `./node_modules/.bin/prettier --parser typescript --write './src/**/*.ts' './src/**/*.tsx'`

#### 6. Added a simple hot module reloading

Warning: Just for faster static editing. Component state won't be HMRed.
