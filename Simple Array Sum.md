PROBLEM: Given an array of integers, find the sum of its elements.

```javascript
function simpleArraySum(ar) {
return ar.reduce(function(a,b) {return a+b})
}
//I use reduce here for code elegance and performance
