# spug
spug 

# usage
spug(layout,fragmentflg); //fragmentflg default false
```js
let layout=`
body
 .cls2 aaabbccc
head
 .cls(data-x="xyz" onclick="x()") xxxyyyzz
`
let el=spug(layout)
;//return el
let fr=spug(layout,true)
;//return fragment
```
