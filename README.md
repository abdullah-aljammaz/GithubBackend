<h2 align="center">Backend with express, And Github</h2>

# npm Download <!-- omit in toc -->
| Download in cmd        |
| ---------------------- |
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

# Git Phase

| number | Phase |
|-|-------|
|1|Track|
|2|Stage|
|3|commit|

# Sign In With Github
```cmd
$ git config --global user.email "Email"
$ git config --global user.name "User_name"
$ git config user.email #Check Email
$ git config user.name # Check Name
```
# Download The File Project From Github
```cmd
$ git clone "URL"
```
# Upload The File
```cmd
$ git add .
$ git commit -m"your message"
$ git push
```
# Need To Download
* [git scm](https://git-scm.com/)
* [Node.js](https://nodejs.org/en/download)
