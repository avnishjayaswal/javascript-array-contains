# javascript-array-contains

The includes() method determines whether a javascript array contains a specified element.

This method returns true if the array contains the element, and false if element not exist in array.

```javascript

var list = ["A", "B", "C", "D", "E"];

console.log(list.includes("A")); // true

 console.log(list.includes("A",1)); //returns false, as "A" is not present at index 1. 

console.log(list.includes("B",1)); //returns True , as "B" is present at index 1. 

console.log(list.indexOf("A") !== -1 ); // true

```

<h2>Array indexOf function</h2>

how to check exact position of element using indexOf JS method

indexOf(element) method, which search for element in the specified array and returns the index of its first occurrence, and -1 if the array does not contain element

```javascript

var JSArr = ["A", "B", "C", "D"];

console.log(JSArr.indexOf("A")) // 0  found at postion 0 
console.log(JSArr.indexOf("B")) // 1  found at postion 1 
console.log(JSArr.indexOf("F")) // -1  not found

```

Example 2 using function 

```javascript

      var JSArr = ["A", "B", "C", "D"];

      if (JSArr.indexOf("A") !== -1) {
        alert("Value exists");
      } else {
        alert("Value does not exists");
      }

```
