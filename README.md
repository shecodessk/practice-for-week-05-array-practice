# Array practice

Identify the time complexity of each of these functions with a 1 sentence
justification for your answer. Assume `arr` is an array of length _n_.

## `arr.push()`

Time complexity: O(1) 
Space complexity: O(n)
Justification: time complexity is constant because no matter how many elements are push(), you don't have to go through/modify the whole array. Space complexity would be O(n) as we are modifying the memory by adding slots in the array.


[push on MDN][push]


## `arr.pop()`

Time complexity: O(1)
Space complexity: O(1)
Justification: time complexity is constant because no matter how many elements are pop(), you don't have to go through/modify the whole array. Space complexity would be O(n) as we are modifying the memory by removing slots in the array.

[pop on MDN][pop]

## `arr.shift()`

Time complexity: O(n)
Space complexity: O(n)
Justification: time complexity is O(n) you have to go through/modify every following index in the array. Space complexity would be O(n) as we are modifying the memory by adding slots in the array.


[shift on MDN][shift]

## `arr.unshift()`

Time complexity: O(n)
Space complexity: O(n)
Justification: time complexity is O(n) you have to go through/modify every following index in the array. Space complexity would be O(n) as we are modifying the memory by removing slots in the array.

[unshift on MDN][unshift]

## `arr.splice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: time complexity is O(n) you have to go search through every index in the array. Space complexity would be O(n) as we are modifying the number slots needed altering the memory required by adding/replacing/removing elements in the array.

[splice on MDN][splice]

## `arr.slice()`

Time complexity: O(n)
Space complexity: O(n)
Justification: time complexity is O(n) you have to go search through indexes in the array. Space complexity would be O(n) as we are getting a shallow copy besides from our original array. 

[slice on MDN][slice]

## `arr.indexOf()`

Time complexity: O(n)
Space complexity: O(1)
Justification: time complexity is O(n) you have to go search through every value in the array to match the indexOf argument. Space complexity would be O(1) as we are not altering anything requiring more memory.

[indexOf on MDN][indexOf]

## `arr.map()`

Time complexity: O(n)
Space complexity: O(n)
Justification: Linear time complexity because you have to search through each element in the array. Creates a new array so it expands the space needed.

[map on MDN][map]

## `arr.filter()`

Time complexity: O(n)
Space complexity: O(1)
Justification: Linear time complexity because you have to search through each element in the array. Space complexity stays constant, we are searching through the array and returning part of it in a new array.

[filter on MDN][filter]

## `arr.reduce()`

Time complexity: O(n)
Space complexity: O(n)
Justification: Linear time complexity because you have to go through each element in the array. Space complexity is also linear. Even though the final result of passing the reducer callback into the constant variable is a single value, you require multiple variables.

[reduce on MDN][reduce]

## `arr.reverse()`

Time complexity: O(n)
Space complexity: O(1)
Justification: Linear time complexity because you have to search through each element in the array. It doesn't create a new array, it modifies existing one so space complexity stays constant.

[reverse on MDN][reverse]

## `[...arr]`

Time complexity: O(1)
Space complexity: O(n)
Justification: spread helps the array to pass endless arguments into becoming individual elements in the array. This doesn't change time complexity as it could be passing 1 or 1000000. Space complexity changes as the more elements into your array, the more slots of memory you need for each one, therefore having a linear space complexity.

[spread on MDN][spread]

[push]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push
[pop]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop
[shift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift
[unshift]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/unshift
[splice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice
[slice]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice
[indexOf]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf
[map]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
[filter]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
[reduce]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
[reverse]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse
[spread]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax