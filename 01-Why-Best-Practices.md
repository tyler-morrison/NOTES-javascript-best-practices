# Why Best Practices?

Javascript’s syntax is a bit strange to developers from other other languages. Issues like coercion, etc. can seem strange at first pass. Furthermore, the Internet is full of resources, but often times they are competing and confusing...

## Example 1
```
var x = 10;
var y = "10";
if (x == y) {
  // This is true, but why?
  // ANSWER: Coercion of integer to string
}
```

## Example 2
```
// Why won’t this work?
function myModule() {
  return
  {
    x: 3,
    y: 4
  }
}
// ANSWER: Object literal was not defined with 'var'
```
