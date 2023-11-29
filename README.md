# Backend with express, And Github

| Code              | Description                                                              |
| ----------------- | ------------------------------------------------------------------------ |
| `npx tsc --init ` | Make tsconfig.json File, And Set `"rootDir":"./src"` `"ourDir":"./dist"` |
| `tsc --watch`     | Auto Compiler The Ts File To Js File                                     |

# How Run The Server

First Download Express From npm
|Download in cmd|
| --- |
|`npm i express`|
|`npm i @types/express`|
```ts
ffdasfadsf
> [!WARNING]\
> We use caching to decrease the load on our servers (see <https://github.com/anuraghazra/github-readme-stats/issues/1471#issuecomment-1271551425>). Our cards have a default cache of 6 hours (21600 seconds). Also, note that the cache is clamped to a minimum of 6 hours and a maximum of 24 hours. If you want the data on your statistics card to be updated more often you can [deploy your own instance](#deploy-on-your-own) and set [environment variable](#disable-rate-limit-protections) `CACHE_SECONDS` to a value of your choosing.

import express from "express";

const app = express();
const PORT = 21;
app.get("/t", function (req, res) {
  res.send("Hello World");
});
app.listen(PORT, () => {
  console.log(`server ${PORT}`);
});
```
