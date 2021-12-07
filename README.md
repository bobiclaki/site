### A good example is ` 3x+1 `

```js
let n = text = 7;

while(n !== 1) {
    text += ` -> ${!(n % 2) ? n /= 2 : (n = 3 * n + 1)}`;
    if (n === 1) console.log(text);
}
```

###### :D
