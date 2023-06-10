<b>Rest / Spread Operator Exercises</b><br><br>
<i>In this exercise, you’ll refactor some ES5 code into ES2015.</i>
<p>
Given this function:<br>
function filterOutOdds() {<br>
  var nums = Array.prototype.slice.call(arguments);<br>
  return nums.filter(function(num) {<br>
    return num % 2 === 0<br>
  });<br>
}
</p>
 Refactor it to use the rest operator & an arrow function:
/* Write an ES2015 Version */
<p>
<p>
  <b>findMin</b><br>
</p>
Write a function called findMin that accepts a variable number of arguments and returns the smallest argument.

<p>Make sure to do this using the rest and spread operator.</p>

findMin(1,4,12,-3) // -3<br>
findMin(1,-1) // -1<br>
findMin(3,1) // 1<br>
<br>
  <b>mergeObjects</b>
<br>
<p>Write a function called mergeObjects that accepts two objects and returns a new object which contains all the keys and values of the first object and second object.</p>

mergeObjects({a:1, b:2}, {c:3, d:4}) // {a:1, b:2, c:3, d:4}
</p>
<p>
<b>doubleAndReturnArgs</b></p>
Write a function called doubleAndReturnArgs which accepts an array and a variable number of arguments. The function should return a new array with the original array values and all of additional arguments doubled.</p>
doubleAndReturnArgs([1,2,3],4,4) // [1,2,3,8,8]<br>
doubleAndReturnArgs([2],10,4) // [2, 20, 8]<br>
<br>
<p>
  <b>Slice and Dice!</b>
</p>
For this section, write the following functions using rest, spread and refactor these functions to be arrow functions!

Make sure that you are always returning a new array or object and not modifying the existing inputs.

/** remove a random element in the items array
and return a new array without that item. */

function removeRandom(items) {

}

/** Return a new array with every item in array1 and array2. */

function extend(array1, array2) {

}

/** Return a new object with all the keys and values
from obj and a new key/value pair */

function addKeyVal(obj, key, val) {

}


/** Return a new object with a key removed. */

function removeKey(obj, key) {

}


/** Combine two objects and return a new object. */

function combine(obj1, obj2) {

}


/** Return a new object with a modified key and value. */

function update(obj, key, val) {

}
