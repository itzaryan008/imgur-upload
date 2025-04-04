<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -aryan Imgur Upload-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>


<a href="https://www.npmjs.com/package/aryan-imgur-upload"><img alt="npm version" src="https://img.shields.io/npm/v/aryan-imgur-upload.svg?style=flat-square"></a>
<img alt="version" src="https://img.shields.io/github/package-json/v/itzaryan008/aryan-imgur-upload?label=github&style=flat-square">
<a href="https://www.npmjs.com/package/aryan-imgur-upload"><img src="https://img.shields.io/npm/dm/aryan-imgur-upload.svg?style=flat-square" alt="npm downloads"></a>
[![js dilvr](https://data.jsdelivr.com/v1/package/npm/aryan-imgur-upload/badge)](https://www.jsdelivr.com/package/npm/aryan-imgur-upload)

## Instalation :
```bash
> npm i aryan-imgur-upload
```



```js
const {imgur} = require("aryan-imgur-upload")

async function upload(url){
  const response = await imgur(url)
  console.log(response)
  
}

upload(url)
```
