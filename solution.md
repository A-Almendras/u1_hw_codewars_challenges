## Return Negative

```js
function makeNegative(num) {
  // Code
  return num > 0 ? -num : num // if num > 0 is true, return the negative of the parameter num. If false, return num.
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let sum = 0

  // Loops through the array until the array length is reached
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      // if the condition of number at index i is greater than 0 is met, add it to the sum
      sum += arr[i]
    }
  }

  return sum
}

//ALTERNATE WAY USING forEach
// function positiveSum(arr) {
//   let sum = 0

//   arr.forEach((element) => {
//     if (element > 0) {
//       sum += element
//     }
//   })

//   return sum
// }
```

## Function 2

```js
// Function named square takes in argument called elem
const square = (param) => {
  return Math.pow(param, 2) // returns argument elem to the power of 2
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'

  let sumNumbs = 0

  numbers.forEach((number) => {
    sumNumbs += number
  })

  return sumNumbs
}
```

## Reversed Strings

```js
function solution(str) {
  // returns the reversed string
  return str.split('').reverse().join('') // splits into an array of strings, reverses the array in place, joins all elements of an array into a string
}
```
