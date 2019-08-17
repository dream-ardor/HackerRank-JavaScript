## Objective

In this challenge, we practice using arrow functions.

Complete the function in the editor. It has one parameter: an array. It must iterate through the array performing one of the following actions on each element:

If the element is even, multiply the element by 2.
If the element is odd, multiply the element by 3.

### :stars: My Code
```js
const modifyArray = nums =>
    nums.map(x => x % 2 == 0 ? x * 2 : x * 3);

```
