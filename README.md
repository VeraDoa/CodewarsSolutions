*8 kyu Reversed Strings*
* https://www.codewars.com/kata/reversed-strings/train/javascript
```javascript
function solution(str) {
  let reversed = '';
  for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
  }
  return reversed;
}
```
*8 kyu Who Is Paying*
* https://www.codewars.com/kata/who-is-going-to-pay-for-the-wall/train/javascript
```javascript
function whoIsPaying(name) {
  let arr = [name];
  if (name.length > 2) {
  let str = name.substring(0, 2);
  arr.push(str)
  }
  return arr;
}
```
*8 kyu Array Plus Array*
* https://www.codewars.com/kata/array-plus-array/train/javascript
```javascript
function arrayPlusArray(arr1, arr2) {
  let sum = 0;
  for (let i = 0; i < arr1.length; i++) {
  sum += arr1[i];
  }
  for (let i = 0; i < arr2.length; i++) {
  sum += arr2[i];
  }
  return sum;
}
```
*8 kyu Final Grade*
* https://www.codewars.com/kata/students-final-grade/train/javascript
```javascript
function finalGrade (exam, projects) {
  if(exam > 90 || projects > 10) return 100;
  if(exam > 75 && projects >= 5) return 90;
  if(exam > 50 && projects >= 2) return 75;
  return 0;
}
```
*8 kyu Personalized Message*
* https://www.codewars.com/kata/grasshopper-personalized-message/train/javascript
```javascript
function greet (name, owner) {
  if (name === owner) {
  return 'Hello boss';
  } else {
  return 'Hello guest';
  }
}
```
*8 kyu Count Sheep*
* https://www.codewars.com/kata/if-you-cant-sleep-just-count-sheep/train/javascript
```javascript
function countSheep(num) {
  let newString = '';
    for (let i = 1; i <= num; i++) {
    newString = newString + i + ' sheep...';
    }
  return newString;
}
```
*8 kyu Man In The West*
* https://www.codewars.com/kata/man-in-the-west/train/javascript
```javascript
function checkTheBucket(bucket) {
    let gold = 'gold';
    for (let i = 0; i < bucket.length; i++) {
      if (bucket[i] === 'gold') {
          return true;
        }
      }
      return false;
    }
```
*8 kyu String Repeat*
* https://www.codewars.com/kata/string-repeat/train/javascript
```javascript
function repeatStr (n, string) {
  return string.repeat(n);
}
```
*8 kyu Count of positives / sum of negatives*
* https://www.codewars.com/kata/count-of-positives-slash-sum-of-negatives/train/javascript
```javascript
function countPositivesSumNegatives(input) {
  let posCount = 0;
  let negSum = 0;
  if (input == null || input.length === 0) {
    return [];
  }
  for (let i = 0; i < input.length; i++) {
    if (input[i] > 0) {
      posCount++;
    } else {
      negSum += input[i];
    }
  }
  return [posCount, negSum];
}
```
*8 kyu Reverse List Order*
* https://www.codewars.com/kata/reverse-list-order/train/javascript
```javascript
function reverseList(list) {
  let arr = [];
  for(let i = list.length - 1; i >= 0; i--) {
  arr.push(list[i]);
  }
  return arr;
}
```
*8 kyu Even Or Odd*
* https://www.codewars.com/kata/even-or-odd/train/javascript
```javascript
function even_or_odd(number) {
  if (number % 2 === 0) return "Even";
  else return "Odd";
}
```
*8 kyu A Needle In The Haystack*
* https://www.codewars.com/kata/a-needle-in-the-haystack/train/javascript
```javascript
function findNeedle(haystack) {
  return 'found the needle at position ' + haystack.indexOf('needle');
}
```
*8 kyu Variable Assignment Debug*
* https://www.codewars.com/kata/grasshopper-variable-assignment-debug/train/javascript
```javascript
let a = 'dev';
let b ='Lab';
let name = a + b;
```
*8 kyu MakeUpperCase*
* https://www.codewars.com/kata/makeuppercase/train/javascript
```javascript
function makeUpperCase(str) {
  return str.toUpperCase();
}
```
*8 kyu Basic Variable Assignment*
* https://www.codewars.com/kata/basic-variable-assignment/train/javascript
```javascript
let a = 'code';
let b = 'wa.rs';
let name = a + b;
```
*8 kyu Opposite Number*
* https://www.codewars.com/kata/opposite-number/train/javascript
```javascript
function opposite(number) {
  return(-number);
}
```
*8 kyu Man In The West*
* https://www.codewars.com/kata/man-in-the-west/train/javascript
```javascript
function checkTheBucket(bucket) {
    let gold = 'gold';
    for (let i = 0; i < bucket.length; i++) {
      if (bucket[i] === 'gold') {
          return true;
        }
      }
      return false;
    }
```
*8 kyu Return The Day*
* https://www.codewars.com/kata/return-the-day/train/javascript
```javascript
function whatday(num) {
  switch(num) {
    case 1:
      return "Sunday";
    case 2:
      return "Monday";
    case 3:
      return "Tuesday";
    case 4:
      return "Wednesday";
    case 5:
      return "Thursday";
    case 6:
      return "Friday";
    case 7:
      return "Saturday";
    default:
      return 'Wrong, please enter a number between 1 and 7';
  }
}
```
*8 kyu Short Long Short*
* https://www.codewars.com/kata/short-long-short/train/javascript
```javascript
 function solution(a, b) {
  return a.length < b.length ? a + b + a : b + a + b;
}
```
*8 kyu Returning Strings*
* https://www.codewars.com/kata/returning-strings/train/javascript
```javascript
function greet(name) {
  return `Hello, ${name} how are you doing today?`;
}
```
*8 kyu Do I Get A Bonus?*
* https://www.codewars.com/kata/do-i-get-a-bonus/train/javascript
```javascript
function bonusTime(salary, bonus) {
  return bonus ? `£${salary * 10}` : `£${salary}`;
  }
```
*8 kyu Reversed Sequence*
* https://www.codewars.com/kata/reversed-sequence/train/javascript
```javascript
function reverseSeq(n) {
  let arr = [];
  while (n > 0) {
    arr.push(n);
    n--;
  }
  return arr;
}
```
*8 kyu Multiple Of Index*
* https://www.codewars.com/kata/multiple-of-index/train/javascript
```javascript
function multipleOfIndex(arr) {
  let arrNew = [];
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] % i === 0) {
      arrNew.push(arr[i]);
    }
  }
  return arrNew;
}
```
*8 kyu Merge Two Sorted Arrays Into One*
* https://www.codewars.com/kata/merge-two-sorted-arrays-into-one/train/javascript
```javascript
function mergeArrays(arr1, arr2) {
  let newArr = [];
  for (i = 0; i < arr1.length; i++) {
    if (!newArr.includes(arr1[i])) {
    newArr.push(arr1[i]);
    }
  }
  for (i = 0; i < arr2.length; i++) {
    if (!newArr.includes(arr2[i])) {
    newArr.push(arr2[i]);
    }
  }
  return newArr.sort((a, b) => a - b);
}
```
*8 kyu Convert a Number to a String!*
```javascript
function numberToString(num) {
  let str = num.toString();
  return str;
}
```