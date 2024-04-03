# What is new Date in JavaScript ?
 
avaScript Date objects represent a single moment in time in a platform-independent format. Date objects encapsulate an integral number that represents milliseconds since the midnight at the beginning of January 1, 1970, UTC
____
 ``` JavaScript
 new Date()
new Date(date string)
new Date(year,month,day,hours,minutes,seconds,ms)
new Date(milliseconds)
```
___

new Date(string)- creates a date object from a date string:
___
![](https://www.oreilly.com/api/v2/epubs/9780133410877/files/graphics/02tab05.jpg)
___
![](https://image.slidesharecdn.com/domdateandobjectsandeventhandling-220306134224/85/dom-date-and-objects-and-event-handling-71-320.jpg?cb=1668028314)
___

# What is new Map in JavaScript ?

Map objects are collections of key-value pairs. A key in the Map may only occur once; it is unique in the Map's collection. A Map object is iterated by key-value pairs — a for...of loop returns a 2-member array of [key, value] for each iteration. Iteration happens in insertion order, which corresponds to the order in which each key-value pair was first inserted into the map by the set() method (that is, there wasn't a key with the same value already in the map when set() was called).
___
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR-904Mu63_Khsv6oFAytiCcxYnBiuJhir180_74FEEig&s)
___
``` JavaScript
const map1 = new Map();

map1.set('a', 1);
map1.set('b', 2);
map1.set('c', 3);

console.log(map1.get('a'));
// Expected output: 1

map1.set('a', 97);

console.log(map1.get('a'));
// Expected output: 97

console.log(map1.size);
// Expected output: 3

map1.delete('b');

console.log(map1.size);
// Expected output: 2
```
___

# What is new Set in JavaScript ?

A JavaScript Set is a collection of unique values. Each value can only occur once in a Set. A Set can hold any value of any data type.

![](https://miro.medium.com/v2/resize:fit:1016/1*VZ7dOZJ9Ac4puGUzc0QluQ.png)
___

``` JavaScript
const a = new Set([1, 2, 3]);
const b = new Map([
  [1, "one"],
  [2, "two"],
  [4, "four"],
]);
console.log(a.union(b)); // Set(4) {1, 2, 3, 4}
```