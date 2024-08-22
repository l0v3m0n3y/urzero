# urzero
JavaScript library for ur0.cc
# main
```js
async function main(){
    const {urzero} = require('./urzero');
    const url= new urzero();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
