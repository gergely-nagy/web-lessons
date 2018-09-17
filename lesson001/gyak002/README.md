<h1 align="center" style="border-bottom: none;"> Gyakorlat-002</h1>
<h3 align="center">Böngésző kompatibilitás (Babel js)</h3>

## ES6 újdonságok

Próbáljuk ki a következő ES6-os kódrészleteket [Babel js](https://babeljs.io/repl) online fordítóban.

### Arrow function

```javascript
const materials = [
  'Hydrogen',
  'Helium',
  'Lithium',
  'Beryllium'
];

let result = materials.map(material => material.length);

// console.log(result);
```

### Osztályok

```javascript
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
  
   get calcArea() {
    return this.width*this.height;
   }
}
```

### Template Strings

```javascript
// Basic literal string creation
`In JavaScript '\n' is a line-feed.`

// Multiline strings
`In JavaScript this is
 not legal.`

// String interpolation
var name = "Bob", time = "today";
`Hello ${name}, how are you ${time}?`

```

És még sok más ... :)