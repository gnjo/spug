# spug
spug 

# usage
spug(layout,retType); //retType default html
```js
let layout=`
body
 .cls2 aaabbccc
head
 .cls(data-x="xyz" onclick="x()") xxxyyyzz
`
let html=spug(layout) //default html
let fr=spug(layout,'fr') //fragment
let el=spug('.cls(data-x="xyz")','el') //need top element
```
