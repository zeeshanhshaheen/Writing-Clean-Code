# Writing-Clean-Code

> “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.” — Martin Fowler’

Writing a clean code is a much-needed skill that every developer should learn. In this article I will share tips to write a clean code. 

### Clean Variables (How to name variables)

Choosing the best and relevant names for your variables and function will save you lots of time. So, when declaring a variable keep in mind why you are declaring it when it will be used.

For Example:

```javascript
var a, b
function do(a, b) {
     return a+b
}
```

the above code will give you the sum of two numbers. But the variables and function names are not explaining what this code does.
Let’s see the following example,

```javascript
var num1, num2
function addNumbers(num1, num2) {
      return num1+num2
}
```

The above code is completely explaining that a function will take two arguments and will give you the sum of these two numbers.

### Clean Functions (How to write functions)
