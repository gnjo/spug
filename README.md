# spug
spug simple pattern pug
```
depth single space->" " only.
```

# usage
spug(layout,retType); //retType default html
```js
let layout=`
body
 .cls2 aaabbccc
  .cmd1 cmd1
  .cmd2 cmd2
  .cmd3 cmd3
 .cls3 uuuuuuu
  .cmd100 cmd100
  .cmd200 cmd200
  .cmd300 cmd300
head
 .cls(data-x="xyz" onclick="x()") xxxyyyzz
`
let html=spug(layout) //default html
let fr=spug(layout,'fr') //fragment
let el=spug('.cls(data-x="xyz")','el') //need top element
```

```
tree0
[depth][tag(param)] [text]
```
