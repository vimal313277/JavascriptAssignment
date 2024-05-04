# question-1

---

### What is JavaScript. How to use it?

```
javascript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. and javascript is scripting language.
```

# question-2

---

### How many type of Variable in JavaScript?

```
In JavaScript, there are three different variable types

        1.let
            Let is block-scoped
            Let can be declared globally, but its access is limited to the block in which it is declared

            example :
            let a = 5;
            let b = 5;
            let c = a + b;
            console.log(c)//output = 10

        2.var
            Var is globally scoped
            Var can be declared and accessed globally


            example :
            var a = 10;
            var b = 10;
            var c = a + b;
            console.log(c)//output = 20

        3.const
           In JavaScript,const are
            used to declare v ariables,
            but they have some differences.
            const is used to declare a value
             that cannot be not use re use



            example :
            const a = 15;
            const b = 15;
            const c = a + b;
            console.log(c)//output = 30

```

# question-3

---

### Define a Data Types in js?

```
 JavaScript provides different data types to hold different types of values. There are two types of data types in JavaScript.

        1.Primitive data type
           1.String
           2.Number
           3.Boolean
           4.Undefined
           5.Null

        2.Non-primitive data type
           1.Object
           2.Array
```

# question-4

---

### Write a mul Function Which will Work Properly When invoked With Following Syntax

```
        let mul = function (num1, num2) {
            return num1 * num2
        }
        console.log(mul(10, 10))// output = 100
```

# question-5

---

### What the deference between undefined and undeclare in JavaScript?

```

       1. Undefined:-
         It occurs when a variable has been
         declared but has not been assigned
         any value. Undefined is not a keyword.

         example:-
         let vimal;
         undefined
         console.log(vimal)//output = undefined

        2.Undeclared:
         It occurs when we try to access any
          variable that is not initialized
          or declared earlier using the var
          or const keyword.

         example:-
         ReferenceError: myClass is not defined
         console.log(myClass)
         //output = ReferenceError: myClass is not defined

```

# question-6

---

### Using console.log() print out the following statement:

```
let print = ' The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.'
 console.log(print)

```

# question-7

---

### Check if typeof '10' is exactly equal to 10. If not make it exactly equal?

```
this 10 is number
let cheek1 = 10;

this '10' is string
let cheek2 = '10';

not are that sem this === operator number and value camper operator
console.log(cheek1===cheek2)//output = false

```

# question-8

---

### Write a JavaScript Program to find the area of a triangle?

```
let vimal = prompt('enter your vimal value')
let mitesh = prompt('enter your mitesh value ')
 let final = (vimal * mitesh) / 2;
 document.write('vimal:', + vimal + 'mitesh:' + mitesh
 + 'final:' + final)

```

# question-9

---

### Write a JavaScript program to calculate days left until next Christmas?

```

         currentDay = new Date().getDate();
      let isLeapYear = false;
      //   currentMonth = new Date().getMonth();
      currentMonth = 28;
      //   console.log(currentDay);
      //   console.log(currentMonth);

      let countOfDayInCurrentMonth;
      if (
        currentMonth == '0' ||
        currentMonth == '2' ||
        currentMonth == '4' ||
        currentMonth == '6' ||
        currentMonth == '7' ||
        currentMonth == '9' ||
        currentMonth == '11'
      ) {
        countOfDayInCurrentMonth = 31;
      } else if (currentMonth == '1') {
        if (isLeapYear) {
          countOfDayInCurrentMonth = 29;
        } else {
          countOfDayInCurrentMonth = 28;
        }
      } else {
        countOfDayInCurrentMonth = 30;
      }

      daysLeftInCurrentMonth = countOfDayInCurrentMonth - currentDay;
      daysLeftTillDecMonth = 30 + 31 + 30 + 31 + 31 + 30 + 31 + 30;
      //   console.log(daysLeftIncurrentMonth);
      //   console.log(daysLeftTillDecMonth);

      daysLeftTillChristmasFromToday =
        daysLeftInCurrentMonth + daysLeftTillDecMonth + 25;

      console.log(daysLeftTillChristmasFromToday);

      function mul(firstNumber, secondNumber) {
        console.log(firstNumber * secondNumber);
      }

      mul(10, 20);

```

# question-10

---

### What is Condition Statement?

```
<p>There are several methods that can be used to perform Conditional Statements in JavaScript.</p>


        1.if Statement

             Example:-
                  let a = 30;
                  let b = 20;

                  if (a == b) {
                      console.log('Right condition')
                  } if (a > b) {
                      console.log('not can be Right condition')
                  }


        2.if-else Statement

                EXAMPLE:-

                let age = 25;

                   if (age >=18) {
                       console.log("You are eligible of driving license")
                   } else {
                       console.log("You are not eligible for driving license")
                   };



        3.else if Statement

                   Example:-

                   let num = 10;

                   if (num > 10) {
                       console.log("Given number is positive.");
                   } else if (num < 10) {
                       console.log("Given number is negative.");
                   } else {
                       console.log("Given number is zero.");
                   };



        4.switch Statement

                   Example:-
                   const marks = 85;

                   let Branch;

                   switch (true) {
                       case marks >= 90:
                           Branch = "Computer science engineering";
                           break;
                       case marks >= 80:
                           Branch = "Mechanical engineering";break;
                       case marks >= 70:
                           Branch = "Chemical engineering";
                           break;
                       case marks >= 60:
                           Branch = "Electronics and communication";
                           break;
                       case marks >= 50:
                           Branch = "Civil engineering";
                           break;
                       default:
                           Branch = "Bio technology";
                           break;
                   }

                   console.log(`Student Branch name is : ${Branch}`);



                      5.Ternary Operator

                      Example:-

                      let age = 21;

                       const result =
                           (age >= 18) ? "You are eligible to vote."
                               : "You are not eligible to vote.";

                       console.log(result);

```

# question-11

---

### Find circumference of Rectangle formula : C = 4 \* a ?

```
        let a = 50;
        let b = 30;
        let c = 30 * a;

        document.write(c)
```

# question-12

---

### WAP to convert years into days and days into years?

```
 day = 6524;
 document.write(Math.floor(day / 365));
 year = 5;
 document.write(Math.floor(year * 365));
```

# question-13

---

### Convert temperature Fahrenheit to Celsius? (Conditional logic Question)

```
(F) = (C) * 9/5 + 32
let F = c = 10;
let fc = 10 * 9 / 5 + 32;
console.log(fc)//50
```

# question-14

---

### Write a JavaScript exercise to get the extension of a filename.?

```
fileName = 'vimal.html';
fileName = 'vimal.htm';
fileName = 'vimal.js';
fileName = 'vimal.py';
fileName = 'vimal.c';
fileName = 'vimal.css';
fileName = 'vimal.c++';

let indexOfVimal = fileName.indexOf('.');
// document.write(indexOfVimal)
document.write('vimal.c++'.slice(fileName.indexOf('.')))
// output is a = .c++
```

# question-15

---

### What is the result of the expression (5 > 3 && 2 < 4)?

```
let a = 5
        let b = 3
        let c = 2
        let d = 4

        if (a > 3 && c < 4) {
            console.log(true)
        }
        else {
            console.log(false)
        }// output is a = true
```

# question-16

---

### What is the result of the expression(true && 1 && "hello") ?

```
document.write(true && 2 && 'hello');//output is a = hello
```

# question-17

---

### What is the result of the expression true && false || false && true?

```
document.write((true && false) || (false && true));
//output is a = false

```

# question-18

---

### What is a Loop and Switch Case in JavaScript define that ?

```
 A for loop is a control structure that allows you to repeat a block of code a certain number of times, while a switch case is a control structure that allows you to execute different blocks of code based on the value of an expression.


        loop case:-
          let loop;

        for (let i = 0; i < 10; i++) {
            console.log(i)
        }


        JavaScript switch:-

          let day;
        switch (new Date().getDay()) {
            case 0:
                day = "Sunday";
                break;
            case 1:
                day = "Monday";
                break;
            case 2:
                day = "Tuesday";
                break;
            case 3:
                day = "Wednesday";
                break;
            case 4:
                day = "Thursday";
                break;
            case 5:
                day = "Friday";
                break;
            case 6:
                day = "Saturday";
        }

        console.log(day)

```

# question-19

---

### What is the use of is Nan function?

```

meaning of nun function :-
In JavaScript NaN is short for "Not-a-Number"
The isNaN method returns true if a value is NaN
The isNaN method converts the value to a number before testing it

console.log(isNaN("Hello"));//true
console.log(isNaN(123));//false
console.log(isNaN(NaN));//true

```

# question-20

---

### What is the difference between && and || in JavaScript?

```
        1.&&
        ;- The && operator returns true
        if both expressions are true
         otherwise it returns false

        2.||
        ;-The || returns true if one
        or both expressions are true
         otherwise it returns false

                if (true && true && true) {
                    console.log('//output is a = true')
                }


                if (true || false || true) {
                    console.log('//output is a = true')
                }

```

# question-21

---

### What is the use of Void (0)?

```
JavaScript void 0 means returning
 undefined (void) as a primitive value.
  You might come across the term
   “JavaScript:void(0)” while going through
    HTML documents. It is used to prevent any side
    effects caused while inserting an expression in a web page.
```

# question-22

---

### Check Number Is Positive or Negative in JavaScript?

```
     const number = prompt("Enter a number");
        if (number > 0) {
            console.log("The number is positive");
        }
        else if (number < 0) {
            console.log("The number is negative");
        }
        else {
            console.log("The number is zero");
        };
```

# question-23

---

### Find the Character Is Vowel or Not ?

```
let yesAndNo = prompt('Enter your vowels  Character')
        let vowels =
            ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U'];
        let result = vowels.includes(yesAndNo);
        document.write(result);
```

# question-24

---

### Write to check whether a number is negative, positive or zero?

```
           const number = prompt("Enter a number");
        if (number > 0) {
            console.log("The number is positive");
        }
        else if (number < 0) {
            console.log("The number is negative");
        }
        else {
            console.log("The number is zero");}
```

# question-25

---

### 5 Write to find number is even or odd using ternary operator in JS?

```
function checkOddOrEven(num)  {
  return num % 2 === 0 ? 'Even' : 'Odd';
}

console.log(checkOddOrEven(21));//output is a = old
console.log(checkOddOrEven(12));//output is a = even
```

# question-26

---

### Write find maximum number among 3 numbers using ternary operator in JS?

```
 function findLargest(num1, num2, num3) {
  return num1 >= num2 && num1 >= num3 ? num1
  : num2 >= num1 && num2 >= num3 ? num2
  : num3;
  }
  const largestNumber = findLargest(10, 5, 3);
  document.write("Largest number:", largestNumber);
```

# question-27

---

### Write to find minimum number among 3 numbers using ternary operator in JS?

```
function findMinimum(num1, num2, num3) {
            return num1 <= num2 && num1 <= num3 ? num1
                : num2 <= num1 && num2 <= num3 ? num2
                    : num3;}

        const minimum = findMinimum(10, 5, 5);
        document.write("minimum number:", minimum);
```

# question-28

---

### Write to find the largest of three numbers in JS?

```

            function findLargest(num1, num2, num3) {
            return num1 >= num2 && num1 >= num3 ? num1
                : num2 >= num1 && num2 >= num3 ? num2
                    : num3;
        }

        const largestNumber = findLargest(10, 5, 3);
        document.write("Largest number:", largestNumber);
```

# question-29

---

### answer:- 1.. Monday to Sunday using switch case in JS?

### 2. Vowel or Consonant using switch case in JS?

```

          JavaScript switch:-

          let day;
        switch (new Date().getDay()) {
            case 0:
                day = "Sunday";
                break;
            case 1:
                day = "Monday";
                break;
            case 2:
                day = "Tuesday";
                break;
            case 3:
                day = "Wednesday";
                break;
            case 4:
                day = "Thursday";
                break;
            case 5:
                day = "Friday";
                break;
            case 6:
                day = "Saturday";
        }

        console.log(day)

  (Vowel or Consonant using switch case )

        function isVowel(Character) {
            let check = 'Consonant';
            switch (Character) {
                case 'a':
                case 'e':
                case 'i':
                case 'o':
                case 'u':
                case 'A':
                case 'E':
                case 'I':
                case 'O':
                case 'U':
                    check = 'Vowel';
            }
            return check;
        }

        // vowel
        document.write(isVowel('i') + "<br>");

        //  Consonant
        document.write(isVowel('b') + "<br>");

```

# question-30

---

### What are the looping structures in JavaScript? Any one Example?

```
Loops are handy, if you want to run the same code over and over again, each time with a different value.

        example:-
        1.for
        example:-
        const cars = ["BMW", "Volvo", "Audi"];
        let car = "";
        for (let i = 0; i < cars.length; i++) {
            car += cars[i] + '=';
        }console.log(car);//output is a = BMW=Volvo=Audi


        2.for/in
        example:-
        const person = {fname:"Virat", lname:"Kholi", age:25};
        let man = "";
        for (let x in person) {
          man += person[x] + " ";
        }console.log(man)//output is a = virat kholi 25


        3.for/of
        example:-
        const boys = ["vimal", "jayesh", "Navasad"];
        let boy = "";
        for (let i = 0; i < cars.length; i++) {
            boy += cars[i] + '=';
        }console.log(boy);//output is a = vimal=jayesh=navasad

        4.while
        example:-
        let check = "";
        let i = 0;
        while (i < 10) {
            check += "The number is" + i + '\n';
            i++;
        } console.log(check)


        5.do/while
        example:-
        let num = "";
        let i = 0;
        do {
            num += i + "\n";
            i++;
        }
        while (i < 5);
        console.log(num)
```

# question-31

---

### Write a print 972 to 897 using for loop in JS?

```
for (let i = 972; i > 897; i--) {
  console.log(i)
  }
```

# question-32

---

### Write to print factorial of given number?

```
let number = prompt('please Enter Your Number')
        let fact = 1;
        if (number == 0) {
            console.log(`the fact 0f ${number} is 1 `)
        } else if (number < 0) {
            console.log(`the fact of is negative number not possibles`)
        } else {
            for (let i = 1; i <= number; i++) {
                fact = fact * i;
                console.log(fact)
            }
        }
```

# question-33

---

### Write to print Fibonacci series up to given numbers?

```
        let a = 0;
        let b = 1;
        console.log(a)
        console.log(b)

        for (let i = 0; i <= 10; i++) {
            let add = a + b;
            console.log(add)
            a = b;
            b = add;
        }
```

# question-34

---

### Write to print number in reverse order e.g.: number = 64728 reverse =82746 in JS?

```
let num1 = 64728;
let result = num1.toString().split('').reverse().join('');
`console.log(result);

```

# question-35

---

### Write a program make a summation of given number (E.g., 1523 Ans: - 11) in JS?

```

        function digitSum(number) {
            let sum = 0;
            while (number > 0) {
                sum += number % 10;
                number = Math.floor(number / 10);
            }
            return sum;
        }

        let number = 1523;
        console.log(digitSum(number));

```

# question-36

---

### Write a program you have to make a summation of first and last Digit.

```

const sumFirstAndLastDigit = number =>
parseInt(number.toString()[0]) +
parseInt(number.toString().slice(-1));

const number = 1234;
console.log(sumFirstAndLastDigit(number))

```

# question-37

---

### Use console.log() and escape characters to print the following pattern in JS?

```
1 1 1 1 1
2 1 2 4 8
3 1 3 9 27
4 1 4 16 64
5 1 5 25 125

========
========
=========

```

# question-38

---

### Use pattern in console.log in JS?

```

        ========================  answer;-1
     1) 1
        1 0
        1 0 1
        1 0 1 0
        1 0 1 0 1

        let result = '';
        let counter = 0;
        for (i = 0; i < 5; i++) {
            for (j = 0; j < i; j++) {
                if (result.charAt(result.length - 1) == '1') {
                    result = result + '0';
                } else {
                    result = result + '1';
                }
            }
            result = result + '\n';
        }

        console.log(result);


        ========================= answer;-2

        2) A
           B C
           D E F
           G H I J
           K L M N O


        let alphabets = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';

        let result = '';
        let counter = 0;
        for (i = 0; i < 5; i++) {
            for (j = 0; j < i; j++) {
                result = result + ' ' + alphabets[counter];
                counter++;
            }
            result = result + '\n';
        }

        console.log(result);


        ========================= answer;-3

        3) 1
           2 3
           4 5 6
           7 8 9 10
           11 12 13 14 15

        let counter = 1;
        for (let i = 1; i <= 5; i++) {
            let result = "";
            for (let j = 1; j <= i; j++) {
                result = result + counter + ' ';
                counter++;
            }
            console.log(result);
        }

        ========================= answer;-4

        4) *
           * *
           * * *
           * * * *
           * * * * *

        let result = '';
        let counter = 0;
        for (i = 0; i < 5; i++) {
            for (j = 0; j < i; j++) {
                result = result + '*';
            }
            result = result + '\n';
        }

        console.log(result);
```

# question-39

---

### Accept 3 numbers from user using while loop and check each numbers palindrome?

```

        let string = prompt('please Enter your palindrome')
        let len = string.length;
        let msg = 'is a palindrome'
        for (let i = 0; i < len / 2; i++) {
            if (string[i] != string[len - 1 - i]) {
                msg = 'not is a palindrome';
            }
        }

        console.log(`${string}: ${msg}`)

```

# question-40

---

### Write a JavaScript Program to display the current day and time in the following format.Sample Output: Today is Friday. Current Time is 12 PM: 12 : 22 2

```
let day = new Date().getDate();
        let hours = new Date().getHours();
        let minutes = new Date().getMinutes();
        let seconds = new Date().getSeconds();

        let time = `${hours}:${minutes}:${seconds} ${hours < 12 ? 'AM' : 'PM'}`;

        let dayInDigit = new Date().getDay();
        // dayInDigit = 2;
        let dayInWord;
        switch (dayInDigit) {
            case 0:
                dayInWord = 'Sunday';
                break;
            case 1:
                dayInWord = 'Monday';
                break;
            case 2:
                dayInWord = 'Tuesday';
                break;
            case 3:
                dayInWord = 'Wednesday';
                break;
            case 4:
                dayInWord = 'Thursday';
                break;
            case 5:
                dayInWord = 'Friday';
                break;
            case 6:
                dayInWord = 'Saturday';
                break;
        }

        console.log(dayInWord);
        console.log(time)

        let result = `Current day is ${dayInWord} and current time is ${time}`;
        console.log(result);

```

# question-41

---

### Write a JavaScript program to get the current date?

```
let currentDate = new Date().getDate()
document.write(currentDate)
```

# question-42

---

### Write a JavaScript program to compare two objects?

```

        let obj1 = {
            age: 25,
            roll: 10,
            bDate: 17 / 6 / 1998,
            // name: vimal,
        };
        let obj2 = {
            age: 25,
            roll: 10,
            bDate: 17 / 6 / 1998,

        };

        console.log(obj1 == obj2);
        console.log(obj1 === obj2);
```

# question-43

---

### Write a JavaScript program to convert an array of objects into CSV string?

```

        const convertCSV = data =>
            [Object.keys(data[0]).join(','), ...data.map(obj => Object.values(obj).join(','))].join('\n');

        // Example usage:
        const data = [
            { name: 'bhagat', age: 30, city: 'pipardi' },
            { name: 'mitesh', age: 25, city: 'vinchhiya' },
            { name: 'sanjay', age: 35, city: 'rajkot' }
        ];

        const csvString = convertCSV(data);
        console.log(csvString);
```

# question-44

---

### Write a JavaScript program to capitalize first letter of a string?

```

        let myString = 'vimal';

        let upperVimal = myString[0].toUpperCase();
        console.log(upperVimal)

        let sliceVimal = myString.slice(1, myString.length);
        console.log(sliceVimal);

        let resultedName = upperVimal + sliceVimal;
        console.log(resultedName);

```

# question-45

---

### Write a JavaScript program to determine if a variable is array?

```

        function isArray(variable) {
            return Array.isArray(variable)
        }

        let arr = [1, 2, 3];
        let notArr = "This is not an array";

        console.log(isArray(arr));
        console.log(isArray(notArr));
```

# question-46

---

### Write a JavaScript program to clone an array?

```

        let cloneArray = [1, 5, 6, 7, 5,];

        let clone = cloneArray.slice()

        console.log(clone)
```

# question-47

---

### What is the drawback of declaring methods directly in JavaScript objects?

```
let myObject = {
    try() {
        console.log("hello");
    }
};

const obj1 = Object.create(myObject);
const obj2 = Object.create(myObject);

console.log(obj1.method === obj2.method);
```

# question-48

---

### Print the length of the string on the browser console using console.log()?

```
let str = "H e llo world ! 1 ";
console.log(str.length);//output is a = 18
```

# question-49

---

### Change all the string characters to capital letters using toUpperCase() method?

```
        let main = 'vimal patel'
        let toUpperCase = main.toUpperCase()
        console.log(toUpperCase)//output is a = VIMAL PATEL
```

# question-50

---

### What is the drawback of declaring methods directly in JavaScript objects?

```
let myObject = {
    try() {
        console.log("hello");
    }
};

const obj1 = Object.create(myObject);
const obj2 = Object.create(myObject);

console.log(obj1.method === obj2.method);
```

# question-51

---

### Write a JavaScript program to get the current date. Expected Output : mm-dd-yyyy,mm / dd / yyyy or dd - mm - yyyy, dd / mm / yyyy ?

```

        let month = new Date().getMonth() + 1;
        let day = new Date().getDate();
        let year = new Date().getFullYear();

        console.log(`${month}/${day}/${year}`)//output is a = 5/3/2024



        let month2 = new Date().getMonth() + 1;
        let day2 = new Date().getDate();
        let year2 = new Date().getFullYear();

        console.log(`${day}/${month}/${year}`)//output is a = 3/5/2024
```

# question-52

---

### Use indexOf to determine the position of the first occurrence of a in 30 Days Of JavaScript?

```

        let main = '30 Days of javascript?'
        let indexOf = main.indexOf('of');
        console.log(indexOf)//output is a = 8
```

# question-53

---

### Use lastIndexOf to determine the position of the last occurrence of a in 30 Days Of JavaScript?

```

        let main = '30 Days of javascript?'
        let indexOf = main.lastIndexOf('a');
        console.log(indexOf)//output is a = 14
```

# question-54

---

### Form Validation in JS?

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .main-f {
            width: 30%;
        }

        #number,
        #email,
        #password {
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="main-f">
        <form action="">
            <label for="">phone</label>
            <div class="phone">
                <input type="number" id="number" placeholder="number">
            </div>
            <label for="">Email</label>
            <div class="email">
                <input type="email" id="email" placeholder="email">
            </div>
            <label for="">password</label>
            <div class="password">
                <input type="password" id="password" placeholder="password">
            </div>
            <div class="button">
                <input type="submit" id="button" value="Send Me">
            </div>
        </form>
    </div>

   </script>
        <!-- ====== phoneNumber Validation  ==========  -->

        let phoneNumber = document.getElementById('number');
        let button = document.getElementById('button').addEventListener('click', (event) => {
            event.preventDefault()
            let phoneNumberValue = document.getElementById('number').value;
            checkNumber(phoneNumberValue)
        });
        function checkNumber(phoneNumber) {
            console.log(!phoneNumber.includes('0000000000') && phoneNumber.length >= 10 && !phoneNumber.includes('+1'))
        }


        <!-- ============ Email Validation  =========== -->

        let button = document.getElementById('button').addEventListener('click', (event) => {
            event.preventDefault()
            let emailValue = document.getElementById('email').value;
            checkEmail(emailValue)
        });

        function checkEmail(emailName) {

            console.log(
                emailName.includes('@') && emailName.includes('.') && !emailName.includes('@.') && emailName.slice(0, emailName.includes('@')) != '' && emailName.slice(emailName.indexOf('.') + 1) != ''
            );
        }

         <!-- ==========  password validation ============ -->


        let button = document.getElementById('button').addEventListener('click', (event) => {
            event.preventDefault()
            let passwordValue = document.getElementById('password').value;
            isValidPassword(passwordValue)
        });


        function isValidPassword(passwordValue) {
            let pattern = /^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=.*[@#$%^&+=])(?!.*\s).{8,}$/;
            console.log(pattern.test('passwordValue'))
        }

        isValidPassword('passwordValue')

    </script>
</body>
</html>
```

# question-55

---

### Form in Email, number, Password, Validation?

```

   </script>
        <!-- ====== phoneNumber Validation  ==========  -->

        let phoneNumber = document.getElementById('number');
        let button = document.getElementById('button').addEventListener('click', (event) => {
            event.preventDefault()
            let phoneNumberValue = document.getElementById('number').value;
            checkNumber(phoneNumberValue)
        });
        function checkNumber(phoneNumber) {
            console.log(!phoneNumber.includes('0000000000') && phoneNumber.length >= 10 && !phoneNumber.includes('+1'))
        }


        <!-- ============ Email Validation  =========== -->

        let button = document.getElementById('button').addEventListener('click', (event) => {
            event.preventDefault()
            let emailValue = document.getElementById('email').value;
            checkEmail(emailValue)
        });

        function checkEmail(emailName) {

            console.log(
                emailName.includes('@') && emailName.includes('.') && !emailName.includes('@.') && emailName.slice(0, emailName.includes('@')) != '' && emailName.slice(emailName.indexOf('.') + 1) != ''
            );
        }

         <!-- ==========  password validation ============ -->


        let button = document.getElementById('button').addEventListener('click', (event) => {
            event.preventDefault()
            let passwordValue = document.getElementById('password').value;
            isValidPassword(passwordValue)
        });


        function isValidPassword(passwordValue) {
            let pattern = /^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=.*[@#$%^&+=])(?!.*\s).{8,}$/;
            console.log(pattern.test('passwordValue'))
        }

        isValidPassword('passwordValue')

    </script>
```

# question-56

---

### Dynamic Form Validation in JS?

```
Sem Question in 55
```

# question-57

---

### how many type of JS Event? How to use it ?

```
introduction:= JavaScript events can be categorized into several types based on their triggers and purposes. Here
are some common types of JavaScript events

    ****************************
    1.Mouse events
    ****************************

    ================= Event Performed ==============
    1.click
    2.mouseover
    3.mouseout
    4.mousemove

    ================ Event Handler ===================

    1.onclick
    2.onmouseover
    3.onmouseout
    4.onmousemove

    ********************************
    2.Keyboard events
    ********************************

    ================= Event Performed ==============
    1.Keydown

    ================ Event Handler ===================
    1.onKeydown

    *****************************
    3.Form events
    *****************************


    ================= Event Performed ==============
    1.focus
    2.blur

    ================ Event Handler ===================

    1.onfocus
    2.onblur

    ******************************
    4.Window/Document events
    ***************************
    ================= Event Performed ==============
    1.load
    2.unload

    ================ Event Handler ===================

    1.onload
    2.onunload

    <script>
        const button = document.getElementById('myButton');

        button.addEventListener('click', function (event) {
            console.log('Button clicked!');
        });
    </script>
```

# question-59

---

### What is Bom vs Dom in JS?

```

        answer:-Dom

        DOM (Document Object Model)
         The DOM represents the structure of an HTML document as a hiefrchical tree of nodes.
        Each node  to an element, attrbute, or text within the document. The DOM provides a way for JavaScript
        to interact with and manipulate the content, structure, and style of the HTML document dynamic. It allows
        developers to access, create, modify, and delete HTML elements and their attributes using JavaScript.

        Example of DOM manipulation:

        document.getElementById("demo").innerHTML = "Hello World!";


        ************************************************


        answer:- Bom

        BOM(Browser Object Model)
         The BOM represents the browser's window and its properties, which are not directly related to the document's content.It includes objects such as window, navigator, location, screen, history, and document.The BOM provides JavaScript with functionalities to interact with the browser itself, manipulate the browser window, control navigation, handle cookies, prompt alerts, set timers, and more.

         Example of BOM usage:

        let newWindow = window.open('');
        window.alert('This is an alert!');
        window.setTimeout(() => {
            console.log('Times out');
        }, 2000);
```

# question-60

---

### Array vs object defences in JS?

```
answer:- In JavaScript, both arrays and objects are data
structures used to store collections of values, but they have different characteristics and use cases. Here's a comparison of arrays and objects in terms of their features and typical use cases:

        Arrays:-
        1.Use square brackets ([]) to define an array literal.
        2.Elements are accessed by their numerical index.
        [Example]:-
        let names = ['mitesh', 'vimal', 'bhagat'];
        console.log(names[0]);//output is a = mitesh

        ********************************

        Objects:
        1.Unordered collection of key-value pairs.
        2.Use curly braces ({}) to define an object literal.
        [Example]:-
        const person = {
            name: 'vimal',
            age: 18,
            city: 'rajkot'
        };
        console.log(person.age);//output is a = 18

```

# question-61

---

### Split the string into an array using split() Method?

```
let string = "apple,banana,orange";
let array = string.split(",");
console.log(array);
```

# question-62

---

### Check if the string contains a word Script using includes() method?

```
let string = "This is a JavaScript program";

        if (string.includes("Script")) {
            console.log("The string contains the word 'Script'");
        } else {
            console.log("The string does not contain the word 'Script'");
        }
```

# question-63

---

### Change all the string characters to lowercase letters using toLowerCase() Method.

```
        let characters = 'JAY HIND JAY BHARAT';
        let Change = characters.toLowerCase();
        console.log(Change)
```

# question-64

---

### What is Character at index 15 in ’30 Days of JavaScript’ string? Use charAt() method.

```
        let str = '30 Days of JavaScript';
        let characterAtIndex15 = str.charAt(15);
        console.log(characsterAtIndex15);// output is a = 15
```

# question-65

---

### copy to one string to another string in JS?

```
        const originalString = 'Hello My Name Is Vimal Patel';
        let copiedString = originalString;
        console.log(copiedString);
```

# question-66

---

### Find the length of a string without using libraryFunction?

```
        let myString = "jay hind jay bharat";
        let length = myString.split('').length;
        console.log(length);
```

<b>What is JavaScript?</b>

<p>JavaScript is a scripting language used to create and control dynamic website content.JavaScript is a Client Side Scripting and Programming language </p>

---

<b> What is the use of isNaN function?</b>

<p>console.log(isNaN(123)); // Output: false

console.log(isNaN('hello')); // Output: true </p>

---

<b>Which company developed JavaScript?</b>

<p>JavaScript was created at Netscape Communications by Brendan Eich in 1995. Netscape and Eich designed
JavaScript as a scripting language for use with the company's flagship web browser, Netscape Navigator.</p>

---

<b>What are undeclared and undefined variables?</b>

<p>Undeclared Variables: These are variables that have not been declared using a var, let, or const keywordbefore being used. not access or assign a value to an undeclared variable, JavaScript will throw a ReferenceError.

EXAMPLE:-
console.log(x);</p>

<p>Undefined Variables: These are variables that have been declared but not assigned a value, or they have been assigned the value undefined

EXAMPLE:-
let x;
console.log(x);</p>

---

<b>Write the code for adding new elements dynamically??</b>

            <style>
                .container {
                    margin-top: 20px;
                }

                .box {
                    width: 100px;
                    height: 100px;
                    background-color: lightblue;
                    margin: 5px;
                    display: inline-block;
                }
            </style>
            <div class="container">
                <button onclick="addElement()">Add Element</button>
                <div id="elementContainer">
                </div>
            </div>
            <script>
            function addElement() {
            let newElement = document.createElement('div');
            newElement.className = 'box';
            newElement.textContent = 'New Element';
            document.getElementById('elementContainer').appendChild(newElement);
            }
            </script>

---

<b>What is the difference between ViewState and SessionState?</b>

<p>View state can only be visible from a single page and not multiple pages. Session state value availabilityis across all pages available in a user session.</p>

---

<b>What is === operator?</b>

<p>  The === operator, known as the "strict equality" operator in JavaScript, is used for comparing two values to check if they are equal in both value and data type

            EXAMPLE:-
            console.log(5 === 5); // true
            console.log(5 === '5'); // false
            console.log(5 === 6); // false
            console.log(null === null); // true
            console.log(null === undefined); // false</p>

---

<b>How can the style/class of an element be changed?</b>

<p>  You can change the style or class of an HTML element using JavaScript

            EXAMPLE:-
            document.getElementById("myElement").style.backgroundColor = "red";
            .classChange {
            background-color: yellow;
            }
            document.getElementById("myElement").classList.add("classChange");
            document.getElementById("myElement").classList.remove("classChange");
            document.getElementById("myElement").classList.toggle("classChange");

</p>

---

<b>How to read and write a file using JavaScript?</b>

<p>  js fs module. The fs. readFile() and rs. writeFile() methods are used to read and write of a file using javascript.</p>

---

<b>What are all the looping structures in JavaScript?</b>

<p>   1.for Loop

for (let i = 0; i < 5; i++) {
console.log(i);
}

                2.while Loop
                let i=0;
                while (i < 5) {
                    console.log(i); i++;
                }

                    3.do...while Loop
                    let i = 0;
                    do {
                        console.log(i);i++;
                    }
                     while (i < 5);

                        4.for...in
                            Loop const person={ name: 'vimal' , age:30
                            };
                            for (let key in person) {
                             console.log(key + ': ' + person[key]);
                              }

                        5.for...of Loop
                        const colors = ['red', 'green', 'blue'];
                        for (let color of colors) {
                            console.log(color);
                            }</p>

---

<b>How can you convert the string of any base to an integer in JavaScript?</b>

<p>There's a function called parseInt() in JavaScript, this is used for parsing a string as an argument and it returns an integer of the specified radix (basically the base of the numerical system) as output.

parseInt() converts the binary string "1234141" to its decimal equivalent number and the hexadecimal string "abcd" to its decimal equivalent.</p>

---

<b> What is the function of the delete operator?</b>

<P> 1.delete Object

            EXAMPLE:-
            const person = { name: 'mitesh', age: 25 };
            delete person.age;
            console.log(person);

            2.Deleting Array Elements
            const numbers = [1, 2, 3, 4, 5];
            delete numbers[2];
            console.log(numbers);

---

<b>What are all the types of Pop up boxes available in JavaScript?</b>

<p>   types of Pop up boxes available

            1.Alert Box
            EXAMPLE:-
            alert("This is an alert message!");
            2.Confirm Box
            EXAMPLE:-
            confirm("This is an alert message!");
            3.Prompt Box
            prompt("Please enter your name:");

</p>

---

<b>What is the use of Void (0)?</b>

<p>The void operator evaluates an expression and returns undefined . By running void(0) in the URL JavaScript code, nothing is evaluated or returned.</p>

---

<b>How can a page be forced to load another page in JavaScript?</b>

        <li>Using window.location.href="link";</li>
        <li>window.location.assign("link")</li>
        <li>window.location.replace("");</li>

---

<b> What are the disadvantages of using innerHTML in JavaScript?</b>

<li>
            
            1.Event handlers attached to any DOM element are preserved.
            2.Replacement is done everywhere.
            3.It is not possible to append innerHTML.
            4.Breaks the document.
            5.Used for Cross-site Scripting.

---

<b>Create password field with show hide functionalities</b>

```
<body>
    <h1>Click the radio button And check password</h1>
    <label>password:</label><br>
    <input type="password" id="showToHide"><br><br>
    <input type="checkbox" onclick="myFunction()">Show Password

    <script>
        function myFunction() {
            let check = document.getElementById("showToHide");
            if (check.type === "password") {
                check.type = "text";
            } else {
                check.type = "password";
            }
        }
    </script>
</body>
```
