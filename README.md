# Map, Filter, Reduce
[![Status overview badge](../../blob/badges/.github/badges/autograding/badge.svg)](#-results)


* Work from the `index.js` file provided in this repository.

#### 1. Get Total Amount of Orders
* Create a function which returns the total amount of the `orders` array, and store the value(sum) in a variable named `totalAmount`. 

```javascript
const orders = [
  { amount: 250 },
  { amount: 400 },
  { amount: 100 },
  { amount: 325 }
];
```

#### 2. Increment by 1
* Create a function named `mappedArray` that accepts an array of numbers as argument and increments each element by 1. Return the new array of modified elements.

#### 3. Filter Evens
* Create a function called `filterEvens` that filters an array of numbers and only returns even numbers only. The function should take an array of numbers as an argument and should not use a loop.

* Examples:
```javascript
filterEvens([1,2,3,11,12,13]); //returns [2,12]
filterEvens([22,2,31,110,6,13]); //returns [22,2,110,6]
```

#### 4. Filter Friends
* Given an array, create a function named `filterFriends` which accepts two arguments: an array and a string. It filters an array based on a search string and returns elements that contain the search string.

* Examples

```javascript
const friends = ["rika", "jenna", "bleda", "oliver", "itamar"];
console.log(filterItems(friends, 'ka')); // ["Rika"];
console.log(filterItems(friends, 'e')); // ["Jenna", "Bleda", "Oliver"];
```

#### 5. Sum Up
* Write a function called `sumUp` that uses the reduce method to sum up an array of numbers. 

* Examples:
```javascript
sum([1,2,3,4,5]); //returns 15
sum([6,7,7]); //returns 20
```

#### 6. Square Root
* Write a function named `getSquareRoot`, which maps an array of numbers and returns the square root of each element in the array.

[//]: # (autograding info start)
# <img src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" alt="" data-canonical-src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" height="31" /> Results
> ⌛ Give it a minute. As long as you see the orange dot ![processing](https://raw.githubusercontent.com/DCI-EdTech/autograding-setup/main/assets/processing.svg) on top, CodeBuddy is still processing. Refresh this page to see it's current status.
>
> This is what CodeBuddy found when running your code. It is to show you what you have achieved and to give you hints on how to complete the exercise.


### 1. Total Amount

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status0.svg) | should return total amount |

###  2. ArrayOfNumbers

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status1.svg) | Should increment each element by 1, and return a new Array |

### 3. Filter Evens

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status2.svg) | Should return filtered Array of only Even Numbers |

### 4. Friends

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status3.svg) | Excepts an Array and Filters based on a search query |

###  5. Sum Up

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status4.svg) | Should Return the sum of an Array of Numbers |

### 6. Square Root

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/autograding/status5.svg) | Should return the Square root of each element in the Array |



[🔬 Results Details](../../actions)
[🐞 Tips on Debugging](https://github.com/DCI-EdTech/autograding-setup/wiki/How-to-work-with-CodeBuddy)
[📢 Report Problem](https://docs.google.com/forms/d/e/1FAIpQLSfS8wPh6bCMTLF2wmjiE5_UhPiOEnubEwwPLN_M8zTCjx5qbg/viewform?usp=pp_url&entry.652569746=PB-datastructure-advarray)


[//]: # (autograding info end)