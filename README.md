<h2 align="center">Backend with express, And Github</h2>

# npm Download <!-- omit in toc -->
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
<hr>

# git, github

# Git Phase

| phase|
|------|
|Track|
|Stage|
|commit|

```bash
git add .
git commit -m"your message"
git push
```

> [!WARNING]  
> You need To download Git Bash
