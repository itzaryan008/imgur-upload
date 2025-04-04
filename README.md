<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -aryan Imgur Upload-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>




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
