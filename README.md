# randomJs
No, It's not a JS library or an npm package

----

### Iterating over an array
```javascript
array.forEach(function(value) {
    console.log("[" + value + "]");
});
```
```javascript
for (let i = 0; i < array.length; i++) {
    console.log("[" + array[i] + "]");
}
```
```javascript
while (array.length) {
    console.log("[" + array.shift() + "]");
}
```

