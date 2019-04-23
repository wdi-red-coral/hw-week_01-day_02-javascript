# Javascript Homework

1.  Variables
    - https://www.youtube.com/watch?v=cXUWYZXru6o (7 min video)
    - https://www.codeanalogies.com/jsconstruction/ (interactive game)

2.  Conditions
    - https://blog.codeanalogies.com/2018/06/18/javascript-booleans-explained-by-going-to-court/ (reading)


## Assignment Operator
Without running the following code, try to determine:

```js
let a = 1;
let b = 'bongos';
let c = true;

a = b;
b = c;
c = a;
```

### Your solution here:1.  What is `a`?
```
a is ...bongos
```
2.  What is `b`?
```
b is ...true
```
3.  What is `c`?
```
c is ...bongos
```


## Concatenation
Use the `+` operator to concatenate these strings together within a `console.log()`: "Please", "squeeze", "the", "cheese". Make sure there are spaces in-between each word.

```js
const firstWord = "Please";
const secondWord = "squeeze";
const thirdWord = "the";
const fourthWord = "cheese";
```
Result should be:
```js
"Please squeeze the cheese"
```


### Your solution here:let firstWord = "Please";
let secondWord = "squeeze";
let thirdWord = "the";
let fourthWord = "cheese";
console.log(" "+firstWord+" "+secondWord+" "+thirdWord+" "+fourthWord+" ");
VM329:5  Please squeeze the cheese 
4.  Fill in the `console.log()`?
```js
console.log()
```

Output a console log `The sum of 5 and 10 is 15` where the values for 5 and 10 are saved to variables, and where 15 comes from those variables being summed.
```js
const num1 = 5;
const num2 = 10;
```

### Your solution here:let num1=5;
let num2=10;
let num3=num1+num2;
console.log("the "+num1+"+"+num2+"="+num3+" .");
VM535:4 the 5+10=15 .


5.  How can we make `num3` equal to the sum of `num1` and `num2`?
```js
// your solution here 
let num1=5;
let num2=10;
let num3=num1+num2;
console.log("the "+num1+"+"+num2+"="+num3+" .");
VM535:4 the 5+10=15 .
```


6.  Use variables `num1`, `num2` and `num3` to fill in the `console.log()` to complete the sentence: 

>The sum of 5 and 10 is 15

```js
console.log()
```
let num1=5;
let num2=10;
let num3=num1+num2;
console.log("the sum of "+num1+" and "+num2+" is "+num3+" .");
VM556:2 the sum of 5 and 10 is 15 .

## Comparisons
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false
```
a) 999 > 999
b) 999 === 999 
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5 
g) 81 / 9 === 9
h) 9 !== 8 + 1
```
### Your solution here:
7.  Write `true` or `false` based on the list above
```
a)  999 > 999
     false
b)  999 === 999 
     true
c)999 !== 999
     false
d)  -5 >= -4
     false
e) 100 <= -100
     false
f)  20 + 5 < 5 
     false
g)  81 / 9 === 9
     true
h)  9 !== 8 + 1
     false 
```

## Conditionals
Declare a variable equal to a number 0 to 100

Write a conditional statement that...
- If it is a multiple of 3, print “Fizz” instead of the number.
- If it is a multiple of 5, print “Buzz” instead of the number.
- If it is a multiple of both 3 and 5, print “FizzBuzz” instead of the number.
- Otherwise, print the number

### Your solution here:
8.  Write your javascript solution below
```js
// your answer here 
let num=15;
if (num%3==0 && num%5==0){console.log("FizzBuzz");} 
else if(num%3==0){console.log("Fizz");}
else if (num%5==0){console.log("Buzz");} 
else {console.log("not Fizz and Buzz");} 
console.log("the num is "+num+" .");

VM650:2 FizzBuzz
VM650:6 the num is 15 .
```


#### BONUS
9.  Research a [loop](https://javascript.info/while-for) so that your condition runs on every number from 0 to 100
```js
// your answer here
for(i=0;i>=0&&i<=100;i++){
console.log(+i);}

for(i=95;i>=0&&i<=100;i++){
console.log(+i);}
VM764:2 95
VM764:2 96
VM764:2 97
VM764:2 98
VM764:2 99
VM764:2 100
```
10.  Research a [function](https://javascript.info/function-basics) so that your condition runs on every number from 0 to whatever number is passed into the function
```js
// your answer here 
for(i=0;5>i;i++){
console.log(+i);}
VM804:2 0
VM804:2 1
VM804:2 2
VM804:2 3
VM804:2 4
```


# Additional Resources
For more practice read about...
- https://javascript.info/variables
- https://javascript.info/types
- https://javascript.info/operators
- https://javascript.info/comparison
- https://javascript.info/ifelse
- https://javascript.info/logical-operators