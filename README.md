<h2 align="center">Backend with express, And Github</h2>

# npm Download <!-- omit in toc -->

- [npm Web](#https://www.npmjs.com/)
    - [ts-node](#https://www.npmjs.com/package/ts-node)
    - [express](#https://www.npmjs.com/package/express)
    - [@types/express](#https://www.npmjs.com/package/@types/express)
| Download in cmd        |
| ---------------------- |
| `npm i -g npm`         |
| `npm i -g ts-node`     |
| `npm i express`        |
| `npm i @types/express` |

# Run File

| Code              | Description                                                              |
| ----------------- | ------------------------------------------------------------------------ |
| `npx tsc --init ` | Make tsconfig.json File, And Set `"rootDir":"./src"` `"ourDir":"./dist"` |
| `tsc --watch`     | Auto Compiler The Ts File To Js File                                     |

# Test Code

```ts
import express from "express";

const app = express();
const PORT = 8080;
app.get("/test", function (req, res) {
  res.send("Hello World");
});
app.listen(PORT, () => {
  console.log(`server ${PORT}`);
});
```
