# javascript_coding_concepts
Javascript Concepts

## Table of Contents

1. [Arrays](#arrays)
2. [Scope](#scope)

## **Arrays**

### Creating Arrays

**With array literal**

```javascript
var numbers = [1, 2, 3] // with simple array literal []
console.log(numbers[0])  //1
```
**With array Constructor**

```javascript
var numbers = new Array(1,2,3) // with simple array Constructor ()
console.log(numbers[1])  //2
```

### Array Length

**Array.length**

```javascript
var numbers = [1, 2, 3]
console.log(numbers.length)  // 3

var abc = new Array('a','b','c')
console.log(abc.length) // 3

var newNumbers = new Array(1,2)
console.log(newNumbers.length) // 2

var newNumbers2 = new Array(5)
console.log(newNumbers2.length) // 5 
console.log(newNumbers2) // [ 5 empty items]

**Array constructor with a single argument specifying the length of the array**

```



