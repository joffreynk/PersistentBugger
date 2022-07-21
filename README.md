# PersistentBugger
Write a function that takes a positive number num and returns its multiplicative persistence, which is the number of steps it takes to multiply all the digits of num by each other, and repeating with the product until a single digit is obtained.
```
const persistence = num => {
  // Your solution
};

console.log(persistence(999)); // 4
// because 9*9*9=729, 7*2*9=126, 1*2*6=12, and finally 1*2=2

console.log(persistence(93)); // 3
// because 9*3=27, 2*7=14, 1*4=4 and 4 has only one digit

console.log(persistence(5)); // 0
// because 5 is already a single-digit number
```