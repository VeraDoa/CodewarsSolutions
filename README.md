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
*8 kyu Is It Even?*
* https://www.codewars.com/kata/is-it-even/train/javascript
```javascript
function testEven(n) {
   return n % 2 === 0;
}
```
*8 kyu Bin to Decimal*
* https://www.codewars.com/kata/bin-to-decimal/train/javascript
```javascript
function binToDec(bin) {
  return parseInt(bin, 2);
}
```
*8 kyu Count by X*
* https://www.codewars.com/kata/count-by-x/train/javascript
```javascript
function countBy(x, n) {
  let z = [];
  for (let i = 1; i <= n * x; i++)
    if (i % x === 0) {
      z.push(i)
    }
  return z;
}
```
*8 kyu A function within a function*
* https://www.codewars.com/kata/53844152aa6fc137d8000589
```javascript
function always (n) {
  return function() {
  return n;
  }
}
```
*8 kyu Unfinished Loop - Bug Fixing #1*
* https://www.codewars.com/kata/unfinished-loop-bug-fixing-number-1/train/javascript
```javascript
function createArray(number) {
  let newArray = [];
  for (let i = 1; i <= number; i++) {
    newArray.push(i);
  }
  return newArray;
}
```
*8 kyu Simple Calculator*
* https://www.codewars.com/kata/simple-calculator/train/javascript
```javascript
function calculator(a, b, sign) {
  if (typeof a !== 'number' || typeof b !== 'number') {
    return 'unknown value';
    }
  switch (sign) {
    case ('+'):
      return a + b;
    case ('-'):
      return a - b;
    case ('*'):
      return a * b;
    case ('/'):
      return a / b;
    default:
      return 'unknown value';
  }
}
```
*8 kyu You Can't Code Under Pressure #1*
* https://www.codewars.com/kata/you-cant-code-under-pressure-number-1/train/javascript
```javascript
function doubleInteger(i) {
  return i * 2;
}
```
*8 kyu Sort and Star*
* https://www.codewars.com/kata/sort-and-star/train/javascript
```javascript
function twoSort(s) {
  let arr = [];
  s.sort();
  for (let i = 0; i <= s.length; i++) {
    if (s[i] === s[0]) {
      arr.push(s[i]);
    }
    return (arr.join('').split('').join('***'));
  }
}
```
*8 kyu Bin to Decimal*
* https://www.codewars.com/kata/bin-to-decimal/train/javascript
```javascript
function binToDec(bin) {
  return parseInt(bin, 2);
}
```
*8 kyu Is it even?*
* https://www.codewars.com/kata/is-it-even/train/javascript
```javascript
function testEven(n) {
   return n % 2 === 0;
}
```
*8 kyu No Loops 2 - You only need one*
* https://www.codewars.com/kata/no-loops-2-you-only-need-one/train/javascript
```javascript
function check(a, x) {
  return a.includes(x);
}
```
*8 kyu Square(n) Sum*
* https://www.codewars.com/kata/square-n-sum/train/javascript
```javascript
function squareSum(numbers) {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i] ** 2;
  }
  return sum;
}
```
*8 kyu noobCode 02: TRICKY QUESTIONS*
* https://www.codewars.com/kata/noobcode-02-tricky-questions-primitives-and-operator-precedence/train/javascript
```javascript
function greaterThanLessThan(a, b, c) {
  return a < b < c === true;
}
```
*8 kyu Triple Trouble*
* https://www.codewars.com/kata/triple-trouble-2/train/javascript
```javascript
function tripleTrouble(one, two, three) {
  let res = '';
  for (let i = 0; i < one.length; i++) {
    res += `${one[i]}${two[i]}${three[i]}`;
  }
  return res;
}
```
*8 kyu FIXME: Replace all dots*
* https://www.codewars.com/kata/fixme-replace-all-dots/train/javascript
```javascript
const replaceDots = function(str) {
  return str.replace(/\./g, '-');
}
```
*8 kyu Invert values*
* https://www.codewars.com/kata/invert-values/train/javascript
```javascript
function invert(arr) {
  let res = [];
  for (let i = 0; i < arr.length; i++) {
    arr[i] = -arr[i];
    res.push(arr[i]);
  }
  return res;
}
```
*8 kyu Sum of Multiples*
* https://www.codewars.com/kata/sum-of-multiples/train/javascript
```javascript
function sumMul(n, m) {
  let sum = 0;
  for (let i = n; i < m; i += n)
    sum += i;
  return (n >= m) ? "INVALID" : sum;
}
```
*8kyu repeatIt*
* https://www.codewars.com/kata/repeatit/train/javascript
```javascript
let repeatIt = function(str, n) {
  if (typeof str !== 'string') return 'Not a string';
  return str.repeat(n);
  }
```
*8 kyu My head is at the wrong end!*
* https://www.codewars.com/kata/my-head-is-at-the-wrong-end/train/javascript
```javascript
function fixTheMeerkat(arr) {
  return arr.reverse();
}
```
*8 kyu I love you, a little , a lot, passionately ... not at all*
* https://www.codewars.com/kata/i-love-you-a-little-a-lot-passionately-dot-dot-dot-not-at-all/train/javascript
```javascript
function howMuchILoveYou(nb_petals) {
    let res = nb_petals % 6;
    switch(res) {
        case 1:
            return "I love you";
        case 2:
            return "a little";
        case 3:
            return "a lot";
        case 4:
            return "passionately";
        case 5:
            return "madly";
        default:
            return "not at all";
    }
}
```
*8 kyu Potenciation*
* https://www.codewars.com/kata/potenciation/train/javascript
```javascript
function power(x, y) {
  return x **y;
}
```
*8 kyu Can we divide it?*
* https://www.codewars.com/kata/can-we-divide-it/train/javascript
```javascript
function isDivideBy(number, a, b) {
  if (number % a === 0 && number % b === 0) return true;
  return false;
}
```
*8 kyu For Twins: 1. Types*
* https://www.codewars.com/kata/for-twins-1-types/train/javascript
```javascript
function typeValidation(variable, type) {
  return (typeof variable === type) ? true : false;
}
```
*8 kyu Mr. Freeze*
* https://www.codewars.com/kata/mr-freeze/train/javascript
```javascript
Object.freeze(MrFreeze)
```
*8 kyu Playing with cubes I Java*
* https://www.codewars.com/kata/playing-with-cubes-i/train/csharp
```javascript
public class Cube {
    int side;

    int getSide(){
        return side;
    }

    void setSide(int side) {
        this.side = side;
    }
}
```
*8 kyu isReallyNaN*
* https://www.codewars.com/kata/isreallynan/train/javascript
```javascript
const isReallyNaN = (val) => {
  return (val === val) ? false : true;
}
```
*8 kyu !a == a ?!*
* https://www.codewars.com/kata/a-equals-equals-a/train/javascript
```javascript
const a = [];
```
*8 kyu Grasshopper - Terminal game move function*
* https://www.codewars.com/kata/grasshopper-terminal-game-move-function/train/javascript
```javascript
function move (position, roll) {
  return position + roll * 2;
}
```
*7 kyu Sum of a Beach*
* https://www.codewars.com/kata/sum-of-a-beach/train/javascript
```javascript
function sumOfABeach(beach) {
  let reg = /sand|water|fish|sun/gi;
  let arr = beach.match(reg);
  return arr === null ? 0 : arr.length;
}
```
*7 kyu Array Leaders (Array Series #3)*
* https://www.codewars.com/kata/array-leaders-array-series-number-3/train/javascript
```javascript
let arrayLeaders = num => {
  let arr = [];
  for (let i = 0; i < num.length; i++) {
    let sum = 0;
    for (let j = i + 1; j < num.length; j++) {
      sum += num[j];
    }
    if (num[i] > sum) {
      arr.push(num[i]);
    }
  }
  return arr;
}
```
*8 kyu Switch/Case - Bug Fixing #6*
* https://www.codewars.com/kata/switch-slash-case-bug-fixing-number-6/train/javascript
```javascript
function evalObject(value) {
  switch (value.operation) {
    case '+':
      return value.a + value.b;
    case '-':
      return value.a - value.b;
    case '/':
      return value.a / value.b;
    case '*':
      return value.a * value.b;
    case '%':
      return value.a % value.b;
    case '^':
      return Math.pow(value.a, value.b);
  }
}
```
*7 kyu Mumbling*
* https://www.codewars.com/kata/mumbling/train/javascript
```javascript
function accum(s) {
  let str = s.toUpperCase();
  let newStr = '';
  for (let i = 0; i < str.length; i++) {
    newStr += str[i] + str[i].toLowerCase().repeat(i) + '-';
  }
  return newStr.substr(0, newStr.length - 1);
}
```
*7 kyu Sum of Array Averages*
* https://www.codewars.com/kata/sum-of-array-averages/train/javascript
```javascript
const sumAverage = (arr) => {
  let res = 0;
  for(let i = 0; i < arr.length; i++) {
    let sum = 0;
    for(let j = 0; j < arr[i].length; j++) {
    sum += arr[i][j];
    }
  res += sum/arr[i].length;
  }
  return Math.floor(res);
}
```
*7 kyu Number of People in the Bus*
* https://www.codewars.com/kata/number-of-people-in-the-bus/train/javascript
```javascript
let number = function(busStops) {
  return busStops.reduce((sum, [a, b]) => {
    return sum + a - b;
  }, 0);
}
```
*7 kyu Sum of two lowest positive integers*
* https://www.codewars.com/kata/sum-of-two-lowest-positive-integers/train/javascript
```javascript
function sumTwoSmallestNumbers(num) {
  let arr = num.sort((a, b) => a - b);
  return arr[0] + arr[1];
}
```
*7 kyu Square Every Digit*
* https://www.codewars.com/kata/square-every-digit/train/javascript
```javascript
function squareDigits(num){
return (+(num + '').split('').map(el => el * el).join(''));
}
```
*7 kyu Array Appender*
* https://www.codewars.com/kata/array-appender/train/javascript
```javascript
function appendArrays(arr1, arr2) {
  return arr1.concat(arr2);
}
```
*7 kyu Reverse words*
* https://www.codewars.com/kata/reverse-words/train/javascript
```javascript
function reverseWords(str) {
  return str.split('').reverse().join('').split(' ').reverse().join(' ');
}
```
*7 kyu One Line Task: Area Or Perimeter*
* https://www.codewars.com/kata/one-line-task-area-or-perimeter/train/javascript
```javascript
areaOrPerimeter=(l,w)=>l-w?2*l+2*w:l*w
```
*8 kyu Are arrow functions odd?*
* https://www.codewars.com/kata/are-arrow-functions-odd/train/javascript
```javascript
function odds(values) {
  return values.filter(a => a % 2 === 1);
}
```
*5 kyu Valid Parentheses*
* https://www.codewars.com/kata/valid-parentheses/train/javascript
```javascript
function validParentheses(parens) {
  let count = 0;
  for (let i = 0; i < parens.length; i++) {
    if (parens[i] === '(') {
      count++;
    }
    if (parens[i] === ')') {
      count--;
    }
    if (count < 0) {
      return false;
    }
  }
  if (count === 0) {
    return true;
  } else {
    return false;
  }
}
```
*6 kyu Valid Braces*
* https://www.codewars.com/kata/valid-braces/train/javascript
```javascript
function validBraces(braces) {
  let arr = [];
  for (let i = 0; i < braces.length; i++) {
    if (braces[i] === '{') {
      arr.unshift('}');
    } else if (braces[i] === '[') {
      arr.unshift(']');
    } else if (braces[i] === '(') {
      arr.unshift(')');
    } else if (braces[i] !== arr[0]) {
      return false;
    } else {
      arr.shift();
    }
  }
  return arr.length === 0;
}
```
*8 kyu Beginner Series #1 School Paperwork*
* https://www.codewars.com/kata/beginner-series-number-1-school-paperwork/train/csharp
```javascript
function paperwork(n, m) {
  if (n < 0 || m < 0) return 0;
  return n * m;
}
```
*8 kyu Messi goals function*
* https://www.codewars.com/kata/grasshopper-messi-goals-function/train/javascript
```javascript
function goals (laLigaGoals, copaDelReyGoals, championsLeagueGoals) {
  return laLigaGoals + copaDelReyGoals + championsLeagueGoals;
}
```
*7 kyu Get the Middle Character*
* https://www.codewars.com/kata/get-the-middle-character/train/javascript
```javascript
function getMiddle(s) {
    let res;
    let mid = Math.floor(s.length / 2)
    if (s.length % 2 === 0) {
      res = s[mid - 1] + s[mid];
    } else {
      res = s[mid];
    }
    return res;
  }
```
*7 kyu Two fighters, one winner. Java*
* https://www.codewars.com/kata/two-fighters-one-winner/train/javascript
```javascript
public class Kata {
  public static String declareWinner(Fighter fighter1, Fighter fighter2, String firstAttacker) {
    while (true) {
            fighter1.health -= fighter2.damagePerAttack;
            fighter2.health -= fighter1.damagePerAttack;

            if (fighter1.health <= 0 && fighter2.health <= 0) return firstAttacker;
            if (fighter1.health <= 0) return fighter2.name;
            if (fighter2.health <= 0) return fighter1.name;
    }
  }
}
```
*8 kyu What's the real floor?*
* https://www.codewars.com/kata/whats-the-real-floor/train/javascript
```javascript
function getRealFloor(n) {
  if (n <= 0) return n;
  if (n <= 13) return n - 1;
  return n - 2;
}
```
*8 kyu Remove exclamation marks*
* https://www.codewars.com/kata/remove-exclamation-marks/train/javascript
```javascript
function removeExclamationMarks(s) {
   return s.replace(/!/gi,'');
}
```
*7 kyu Disemvowel Trolls*
* https://www.codewars.com/kata/disemvowel-trolls/train/javascript
```javascript
function disemvowel(str) {
  let vow = 'AaEeIiOoUu';
  let res = '';
  for (let i = 0; i < str.length; i++) {
    if (!vow.includes(str[i])) {
      res += str[i];
    }
  }
  return res;
}
```
*8 kyu Is the string uppercase?*
* https://www.codewars.com/kata/is-the-string-uppercase/train/javascript
```javascript
String.prototype.isUpperCase = function() {
  return this.toString() === this.toUpperCase()
}
```
*8 kyu Is n divisible by x and y?*
* https://www.codewars.com/kata/is-n-divisible-by-x-and-y/train/javascript
```javascript
function isDivisible(n, x, y) {
  return n % x === 0 && n % y === 0;
}
```
*8 kyu Grasshopper - Debug*
* https://www.codewars.com/kata/grasshopper-debug/train/javascript
```javascript
function weatherInfo(temp) {
  let celsius = (temp - 32) * (5 / 9);
  if (celsius > 0) {
    return (celsius + " is above freezing temperature")
  } else {
    return (celsius + " is freezing temperature")
  }
}

function convertToCelsius(temperature) {
  let celsius = (temperature - 32) * (5 / 9);
  return temperature;
}
```
*8 kyu Total amount of points*
* https://www.codewars.com/kata/total-amount-of-points/train/javascript
```javascript
function points(games) {
  let count = 0;
  games.forEach (item => {
    if (item[0] > item[2]) count += 3;
    if (item[0] === item[2]) count += 1;
  });
  return count;
}
```
*8 kyu Abbreviate a Two Word Name*
* https://www.codewars.com/kata/abbreviate-a-two-word-name/train/javascript
```javascript
const abbrevName = name =>
  name
  .split(' ')
  .map(name => name[0].toUpperCase())
  .join('.');
```
*8 kyu What's up next?*
* https://www.codewars.com/kata/whats-up-next/train/javascript
```javascript
function nextItem(xs, item) {
  let found = false;
  for (let el of xs) {
    if (found) return el;
    if (el === item) found = true;
  }
  return undefined;
}
```
*8 kyu You only need one - Beginner*
* https://www.codewars.com/kata/you-only-need-one-beginner/train/javascript
```javascript
function check(a, x) {
  if (a.indexOf(x) >= 0) return true;
  return false;
}
```
*8 kyu Sum The Strings*
* https://www.codewars.com/kata/sum-the-strings/train/javascript
```javascript
function sumStr(a, b) {
  return (+a + +b).toString();
}
```
*8 kyu Beginner - Reduce but Grow*
* https://www.codewars.com/kata/beginner-reduce-but-grow/train/javascript
```javascript
function grow(x) {
  return x.reduce((a, b) => a * b);
}
```
*8 kyu Find Maximum and Minimum Values of a List*
* https://www.codewars.com/kata/find-maximum-and-minimum-values-of-a-list/train/javascript
```javascript
let min = function(list) {
  let min = list[0];
  for (let i = 1; i < list.length; i++) {
    if (list[i] < min) {
      min = list[i];
    }
  }
  return min;
}
let max = function(list) {
  let max = list[0];
  for (let i = 1; i < list.length; i++) {
    if (list[i] > max) {
      max = list[i];
    }
  }
  return max;
}
```
*8 kyu Beginner - Lost Without a Map*
* https://www.codewars.com/kata/beginner-lost-without-a-map/train/javascript
```javascript
function maps(x) {
  return x.map(num => num * 2);
}
```
*8 kyu All Star Code Challenge #18*
* https://www.codewars.com/kata/all-star-code-challenge-number-18/train/javascript
```javascript
function strCount(str, letter) {
  return str.split(letter).length -1;
}
```
*8 kyu Check the exam*
* https://www.codewars.com/kata/check-the-exam/train/javascript
```javascript
function checkExam(arr1, arr2) {
  let sum = 0;
  for (let i = 0; i < arr1.length; i++) {
    if (arr1[i] === arr2[i]) {
      sum += 4;
    } else if (arr1[i] !== arr2[i] && arr2[i] !== '') {
      sum -= 1;
    }
  }
  if (sum < 0) {
    sum = 0;
  }
  return sum;
}
```
*7 kyu Array comparator*
* https://www.codewars.com/kata/array-comparator/train/javascript
```javascript
function matchArrays(a, b) {
  return a.filter((el) => b.includes(el)).length;
}
```
*7 kyu Adding Arrays*
* https://www.codewars.com/kata/adding-arrays/train/javascript
```javascript
function arrAdder(arr) {
  let newArr = [];
  for (let i = 0; i < arr[0].length; i++) {
    let res = [];
    for (let j = 0; j < arr.length; j++) {
      if (arr[j][i] !== '')
        res.push(arr[j][i]);
    }
    newArr.push(res.join(''));
  }

  return newArr.join(' ').trim();
}
```
*7 kyu Add property to every object in array*
* https://www.codewars.com/kata/add-property-to-every-object-in-array/train/javascript
```javascript
questions.forEach(function(q) {
  q.usersAnswer = null;
});
```
*7 kyu Nice Array*
* https://www.codewars.com/kata/nice-array/train/javascript
```javascript
function isNice(arr) {
  if (arr.length === 0) return false;
  let a;
  for (let i = 0; i < arr.length; i++) {
    a = 0;
    for (let j = 0; j < arr.length; j++) {
      if (arr[i] === arr[j] + 1 || arr[i] === arr[j] - 1) {
        a = 1;
      }
    }
    if (a === 0) return false;
  }
  return true;
}
```
*8 kyu Enumerable Magic #25 - Take the First N Elements*
* https://www.codewars.com/kata/enumerable-magic-number-25-take-the-first-n-elements/train/javascript
```javascript
let take = (arr, n) => arr.slice(0, n);
```
*6 kyu Persistent Bugger*
* https://www.codewars.com/kata/55bf01e5a717a0d57e0000ec
```javascript
function persistence(num) {
  let res = 0;
  num = num.toString();
  while (num.length > 1) {
    res++;
    num = num.split('').map(Number).reduce((a, b) => a * b).toString();
  }
  return res;
}
```
*8 kyu Are You Playing Banjo?*
* https://www.codewars.com/kata/are-you-playing-banjo/train/javascript
```javascript
function areYouPlayingBanjo(name) {
   if(name[0] === 'R' || name[0] === 'r') {
   return name + ' plays banjo';
   } else {
   return name + ' does not play banjo';
   }
}
```
*8 kyu Opposites Attract*
* https://www.codewars.com/kata/opposites-attract/train/javascript
```javascript
function lovefunc(flower1, flower2) {
  return (flower1 % 2 !== flower2 % 2);
}
```
*8 kyu Welcome to the City*
* https://www.codewars.com/kata/welcome-to-the-city/train/javascript
```javascript
function sayHello(name, city, state) {
 return `Hello, ${name.join(' ')}! Welcome to ${city}, ${state}!`;
}
```
*8 kyu Basic Mathematical Operations*
* https://www.codewars.com/kata/basic-mathematical-operations/train/javascript
```javascript
function basicOp(operation, value1, value2) {
  if(operation === '+')return value1 + value2;
  if(operation === '-')return value1 - value2;
  if(operation === '*')return value1 * value2;
  if(operation === '/')return value1 / value2;
}
```
*8 kyu Square(n) Sum*
* https://www.codewars.com/kata/square-n-sum/train/javascript
```javascript
function squareSum(numbers) {
  return numbers.reduce((a, b) => a + Math.pow(b, 2), 0);
}
```
*8 kyu "this" is a problem*
* https://www.codewars.com/kata/this-is-a-problem/train/javascript
```javascript
function NameMe(first, last) {
  this.firstName = first;
  this.lastName = last;
  return this.name = `${first} ${last}`;
}
```
*8 kyu Plural*
* https://www.codewars.com/kata/plural/train/javascript
```javascript
function plural(n) {
  return n !== 1;
}
```