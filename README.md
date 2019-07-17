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
* https://www.codewars.com/kata/convert-a-number-to-a-string/train/javascript
```javascript
function numberToString(num) {
  let str = num.toString();
  return str;
}
```
*8 kyu Count Odd Numbers Below N*
* https://www.codewars.com/kata/count-odd-numbers-below-n/train/javascript
```javascript
const oddCount = n => Math.floor(n / 2);
```
*8 kyu Sum Without Highest And Lowest Number*
* https://www.codewars.com/kata/sum-without-highest-and-lowest-number/train/javascript
```javascript
function sumArray(arr) {
  if (!arr || !arr.length || arr.length <= 1) return 0;
  let min = arr[0];
  let max = arr[0];
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    sum += arr[i];
  }
  for (let i = 1; i < arr.length; i++) {
    if (max < arr[i]) {
      max = arr[i];
    }
    if (min > arr[i]) {
      min = arr[i];
    }
  }
  return sum - max - min;
}
```
*8 kyu 101 Dalmatians - squash the bugs, not the dogs!*
* https://www.codewars.com/kata/101-dalmatians-squash-the-bugs-not-the-dogs/train/javascript
```javascript
const howManyDalmatians = number => {
  if (number <= 10) return 'Hardly any';
  if (number <= 50) return 'More than a handful!';
  if (number === 101) return '101 DALMATIANS!!!';
  return "Woah that's a lot of dogs!";
}
```
*8 kyu Online RPG: player to qualifying stage?*
* https://www.codewars.com/kata/online-rpg-player-to-qualifying-stage/train/javascript
```javascript
const playerRankUp = points =>
  points >= 100 ? 'Well done! You have advanced to the qualifying stage. Win 2 out of your next 3 games to rank up.' : false;
```
*8 kyu Fix the Bugs (Syntax) - My First Kata*
* https://www.codewars.com/kata/fix-the-bugs-syntax-my-first-kata/train/javascript
```javascript
const myFirstKata = (a, b) =>
  typeof a !== 'number' || typeof b !== 'number' ? false : a % b + b % a;
```
*8 kyu L1: Set Alarm*
* https://www.codewars.com/kata/l1-set-alarm/train/javascript
```javascript
const setAlarm = (employed, vacation) => employed && !vacation;
```
*8 kyu Convert boolean values to strings 'Yes' or 'No'*
* https://www.codewars.com/kata/convert-boolean-values-to-strings-yes-or-no/train/javascript
```javascript
function boolToWord(bool) {
  return bool ? 'Yes' : 'No';
}
```
*8 kyu Sentence Smash*
* https://www.codewars.com/kata/sentence-smash/train/javascript
```javascript
function smash (words) {
  return words.join(' ');
}
```
*8 kyu Remove String Spaces*
* https://www.codewars.com/kata/remove-string-spaces/train/javascript
```javascript
function noSpace(x) {
  return x.replace(/ /g, '');
}
```
*8 kyu Find the Remainder*
* https://www.codewars.com/kata/find-the-remainder/train/javascript
```javascript
function remainder(a, b) {
  return (a > b ? a % b : b % a)
}
```
*8 kyu Filter Coffee*
* https://www.codewars.com/kata/filter-coffee/train/javascript
```javascript
function search(budget, prices) {
return prices.filter((el) => el <= budget).sort((a,b) => a-b).join();
}
```
*8 kyu Removing Elements*
* https://www.codewars.com/kata/removing-elements/train/javascript
```javascript
function removeEveryOther(arr) {
  let newArr = [];
  for (let i = 0; i < arr.length; i = i + 2) {
    newArr.push(arr[i]);
  }
  return newArr;
}
```
```javascript
function removeEveryOther(arr) {
  return arr.filter(function(a, b) {
  return b % 2 === 0;
  });
}
```
*8 kyu Calculate average*
* https://www.codewars.com/kata/calculate-average/train/javascript
```javascript
function find_average(array) {
  let sum = 0;
  let count = 0;
  for (let i = 0; i < array.length; i++) {
    sum += array[i];
    count++;
  }
  return (sum / count);
}
```
*8 kyu Miles per gallon to kilometers per liter*
* https://www.codewars.com/kata/miles-per-gallon-to-kilometers-per-liter/train/javascript
```javascript
function converter (mpg) {
  return +(mpg * 0.3540060435382138).toFixed(2)
}
```
*8 kyu Sum of differences in array*
* https://www.codewars.com/kata/sum-of-differences-in-array/train/javascript
```javascript
function sumOfDifferences(arr) {
  let sum = 0;
  arr.sort((a, b) => b - a);
  for (let i = 0; i < arr.length - 1; i++) {
    sum += (arr[i] - arr[i + 1]);
  }
  return sum;
}
```
*8 kyu Add Length*
* https://www.codewars.com/kata/add-length/train/javascript
```javascript
function addLength(str) {
  let arr = [];
  let arr2 = str.split(' ');
  for (let i = 0; i < arr2.length; i++){
    arr.push(arr2[i] + ' ' + arr2[i].length);
  }
  return arr;
}
```
*8 kyu Return Negative*
* https://www.codewars.com/kata/return-negative/train/javascript
```javascript
function makeNegative(num) {
  if (num > 0) {
    return -num;
  } else {
    return num;
  }
}
```
*8 kyu Third Angle of a Triangle*
* https://www.codewars.com/kata/third-angle-of-a-triangle/train/javascript
```javascript
function otherAngle(a, b) {
  return 180 - (a + b);
}
```
*8 kyu Power*
* https://www.codewars.com/kata/power/train/javascript
```javascript
function numberToPower(number, power) {
  let result = 1;
  for (let i = 1; i <= power; i++) {
    result = number * result;
  }
  return result;
}
```
*8 kyu Transportation on vacation*
* https://www.codewars.com/kata/transportation-on-vacation/train/javascript
```javascript
function rentalCarCost(d) {
 if (d >= 7) return d * 40 - 50;
 if (d >= 3) return d * 40 - 20;
 return d * 40;
 }
 ```
 *8 kyu Summation*
 * https://www.codewars.com/kata/grasshopper-summation/train/javascript
 ```javascript
 function summation(num) {
   let sum = 0;
   for (let i = 0; i <= num; i++)
     sum += i;
   return sum;
 }
 ```
 *8 kyu Welcome!*
 * https://www.codewars.com/kata/welcome/train/javascript
 ```javascript
 function greet(language) {
   let lang = {
     english: 'Welcome',
     czech: 'Vitejte',
     danish: 'Velkomst',
     dutch: 'Welkom',
     estonian: 'Tere tulemast',
     finnish: 'Tervetuloa',
     flemish: 'Welgekomen',
     french: 'Bienvenue',
     german: 'Willkommen',
     irish: 'Failte',
     italian: 'Benvenuto',
     latvian: 'Gaidits',
     lithuanian: 'Laukiamas',
     polish: 'Witamy',
     spanish: 'Bienvenido',
     swedish: 'Valkommen',
     welsh: 'Croeso'
   }
   if (!lang[language]) {
     return 'Welcome';
   }
   return lang[language];
 }
 ```
*8 kyu Leonardo Dicaprio and Oscars*
* https://www.codewars.com/kata/leonardo-dicaprio-and-oscars/train/javascript
```javascript
function leo(oscar) {
if (oscar === 88) return ('Leo finally won the oscar! Leo is happy');
if (oscar === 86) return ('Not even for Wolf of wallstreet?!');
if (oscar < 88) return ('When will you give Leo an Oscar?');
if (oscar > 88) return ('Leo got one already!');
}
```


