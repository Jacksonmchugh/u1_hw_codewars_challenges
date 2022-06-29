## Return Negative

````js
const num =[2]
function makeNegative(num) {
  return -num

}

## Sum of Positive

```js
const arr =[-1, 2, -3, 4, -5]
function positiveSum(arr) {
  let sum = 0;
  for(let i =0; i <arr.length; i++){
    if(arr[i] > 0) sum += arr[i]
  }
  return sum

}


````

## Function 2

```js
const num = [2]
function square(num) {
  return num * num
}
```

## Sum Arrays

```js
function sum(numbers) {
  let sum = 0
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i]
  }
  return sum
}
```

## Reversed Strings

```js
const str = [1, 2, 3, 4]
function solution(str) {
  return str.split('').reverse().join('')
}
```
