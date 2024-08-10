# JS Array Methods 

This section provides an overview of common JavaScript array methods, categorized by whether they return a new array, modify the original array in place, or do not modify the original array.
 - Click on each section to expand and see the relevant methods.
- Each method name is a link that can be used to quickly navigate to its detailed explanation



<details>
  <summary><h4 style="display:inline;">Methods that Return a New Array</h4></summary>
  <ol>
    <li><a href="#map">map</a></li>
    <li><a href="#filter">filter</a></li>
    <li><a href="#slice">slice</a></li>
    <li><a href="#concat">concat</a></li>
    <li><a href="#reduce">reduce</a></li>
    <li><a href="#reduceright">reduceRight</a></li>
    <li><a href="#flat">flat</a></li>
    <li><a href="#flatmap">flatMap</a></li>
   
  </ol>
</details>

<details>
  <summary><h4 style="display:inline;">Methods that Modify the Original Array (In-place)</h4></summary>
  <ol>
    <li><a href="#sort">sort</a></li>
    <li><a href="#push">push</a></li>
    <li><a href="#pop">pop</a></li>
    <li><a href="#shift">shift</a></li>
    <li><a href="#unshift">unshift</a></li>
    <li><a href="#splice">splice</a></li>
    <li><a href="#reverse">reverse</a></li>
    <li><a href="#copywithin">copyWithin</a></li>
    <li><a href="#fill">fill</a></li>
  </ol>
</details>

<details>
  <summary><h4 style="display:inline;">Methods that Do Not Modify the Original Array</h4></summary>
  <ol>
    <li><a href="#includes">includes</a></li>
    <li><a href="#indexof">indexOf</a></li>
    <li><a href="#lastindexof">lastIndexOf</a></li>
    <li><a href="#every">every</a></li>
    <li><a href="#some">some</a></li>
    <li><a href="#find">find</a></li>
    <li><a href="#findindex">findIndex</a></li>
    <li><a href="#findlast">findLast</a></li>
    <li><a href="#findlastindex">findLastIndex</a></li>
     <li><a href="#join">join</a></li>
  </ol>
</details>




<!-- - [Methods that Return a New Array](#methods-that-return-a-new-array)
  - [map](#map)
  - [filter](#filter)
  - [slice](#slice)
  - [concat](#concat)
  - [reduce](#reduce)
  - [reduceRight](#reduceright)
  - [flat](#flat)
  - [flatMap](#flatmap)
  - [slice](#slice)
  - [join](#join)
  <br/>
- [Methods that Modify the Original Array (In-place)](#methods-that-modify-the-original-array-in-place)
- [sort](#sort)
- [push](#push)
- [pop](#pop)
- [shift](#shift)
- [unshift](#unshift)
- [splice](#splice)
- [reverse](#reverse)
- [copyWithin](#copyWithin)
- [fill](#fill)
<br/>

- [Methods that Do Not Modify the Original Array ](#methods-that-do-not-modify-the-original-array)
- [includes](#includes)
- [indexOf](#indexOf)
- [lastIndexOf](#lastIndexOf)
- [every](#every)
- [some](#some)
- [find](#find)
- [findIndex](#findIndex)
- [findLast](#findLast)
- [findLastIndex](#findLastIndex) -->









## Methods that Return a New Array without change the original one
#### map()
  **Returns:** A new array
  **Description:** Applies a function to each element of the array and returns a new array with the results.
  <br/>

#### filter()
  **Returns:** A new array
  **Description:** Creates a new array with all elements that pass the test implemented by the provided function.
  <br/>

#### slice()
  **Returns:** A new array
  **Description:** Returns a shallow copy of a portion of an array into a new array object, selected from start to end (end not included).
  <br/>

#### concat()
  **Returns:** A new array
  **Description:** Merges two or more arrays and returns a new array without modifying the original arrays.
  <br/>


#### flat()
  **Returns:** A new array
  **Description:** Flattens a nested array up to a specified depth and returns a new array.
  <br/>

#### flatMap()
  **Returns:** A new array
  **Description:** First maps each element using a mapping function, then flattens the result into a new array.
  <br/>

### There is some methods that return array,obj,or other datatypes


#### reduce()
  **Returns:** Varies (could be an array, object, number, etc.)
  **Description:** Applies a function against an accumulator and each element in the array to reduce it to a single value.
  <br/>

#### reduceRight()
  **Returns:** Varies (could be an array, object, number, etc.)
  **Description:** Similar to reduce() but iterates from right to left.
<br/>








<hr/>


## Methods that Modify the Original Array (In-place)

#### sort()
  **Returns:** The sorted array (in-place)
  **Description:** Sorts the elements of an array in place and returns the sorted array.
  Methods that Modify the Original Array (In-place)
    <br/>

#### push()
  **Returns:** The new length of the array
  **Description:** Adds one or more elements to the end of an array.
    <br/>

#### pop()
  **Returns:** The removed element
  **Description:** Removes the last element from an array.
    <br/>

#### shift()
  **Returns:** The removed element
  **Description:** Removes the first element from an array.
    <br/>

#### unshift()
**Returns:** The new length of the array
**Description:** Adds one or more elements to the beginning of an array.
  <br/>

#### splice() 
**Returns:** A new array containing the deleted elements
**Description:**  Changes the contents of an array by removing or replacing existing elements and/or adding new elements in place.
  <br/>

#### reverse()
**Returns:** The reversed array (in-place)
**Description:** Reverses the order of elements in an array.
  <br/>




#### copyWithin()
**Returns:** The modified array (in-place)
**Description:** Copies part of an array to another location in the same array.
  <br/>

#### fill()
**Returns:** The modified array (in-place)
**Description:** Fills all the elements of an array from a start index to an end index with a static value.
  <br/>




## Methods that Do Not Modify the Original Array and don't return a new array 
#### includes()
**Returns:** A boolean
**Description:** Determines whether an array includes a certain element.
  <br/>

#### indexOf()
**Returns:** The first index of the element, or -1 if not found
**Description:** Returns the first index at which a given element can be found.
  <br/>

#### lastIndexOf()

**Returns:** The last index of the element, or -1 if not found
**Description:** Returns the last index at which a given element can be found.
  <br/>

#### every()

**Returns:** A boolean
**Description:** Tests whether all elements pass the provided function's test.

  <br/>


#### some()

**Returns:** A boolean
**Description:** Tests whether at least one element passes the provided function's test.
  <br/>

#### find()

**Returns:** The first element that satisfies the provided testing function
**Description:** Returns the value of the first element in the array that satisfies the provided testing function.
  <br/>


#### findIndex()

**Returns:** The index of the first element that satisfies the provided testing function
**Description:** Returns the index of the first element in the array that satisfies the provided testing function.
  <br/>

#### findLast()

**Returns:** The last element that satisfies the provided testing function
**Description:** Returns the value of the last element in the array that satisfies the provided testing function.
  <br/>

#### findLastIndex()

**Returns:** The index of the last element that satisfies the provided testing function
**Description:** Returns the index of the last element in the array that satisfies the provided testing function.
<br/>

#### join()
  **Returns:** A string
  **Description:** Joins all elements of an array into a string.













