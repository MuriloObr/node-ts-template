# Node TS Template
Boilerplate starter for node and typescript projects.
### Steps

```shell
# Start npm
npm init
```
>Remember to change in package.json `"type": "commonjs"` to `"type": "module"` 
```shell
# Install dev deps for ts and linting
npm i -D typescript tsx eslint prettier eslint-config-prettier @types/node
```
> Find the recommended tsconfig file in this [link](https://github.com/tsconfig/bases) based on your envinronment
```shell
# Init eslint
npm init @eslint/config@latest
```
```js
# Add this to your eslint.config.js
// Other imports...
import prettierConfig from 'eslint-config-prettier'

export default tseslint.config(
  // Other configs...
  prettierConfig
)
```
```shell
# Install deps for logging and env variables
npm i pino pino-pretty dotenv
```
