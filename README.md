# Electron 笔记
## 介绍
- github 开发的开源框架
- 用 web 前端技术 开发桌面应用
- Electron = chromium(提供UI能力) + node.js(底层能力:文件读写等; 可以使用npm包) + native API(桌面端跨平台原生的能力)

## 使用 node 的 fs 模块
```js
fs = require('fs')
fs.readFile('text.txt', 'utf8', (err, data) => {
    console.log(data)
})
```
