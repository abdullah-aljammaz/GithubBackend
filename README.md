# Backend with express, And Github



# Download npm

|Download in cmd|
| --- |
|`npm i -g npm`|
|`npm i -g ts-node`|
|`npm i express`|
|`npm i @types/express`|

# Run File
| Code              | Description                                                              |
| ----------------- | ------------------------------------------------------------------------ |
| `npx tsc --init ` | Make tsconfig.json File, And Set `"rootDir":"./src"` `"ourDir":"./dist"` |
| `tsc --watch`     | Auto Compiler The Ts File To Js File                                     |

```ts

import express from 'express';

const app = express()
const PORT = 8080;
app.get('/t', function (req, res) {
    res.send('Hello World')
})
app.listen(PORT, () => {
    console.log(`server ${PORT}`)
}
)
```
