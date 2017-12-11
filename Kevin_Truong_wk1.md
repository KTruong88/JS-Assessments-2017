### Javascript Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Name some of the data types in Javascript.

  //Your Answer
  Number, Boolean, Object, Null, String
  
  
  //Googled Answer
  Boolean, Null, Undefined, Number, String, Symbol


#### 2. Describe what "if" does in Javascript.

  //Your Answer
  If checks if the condition you specified in the () is true, then it will execute the block of code in the brackets {}
  
  //Googled Answer
  The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. The if/else statement is a part of JavaScript's "Conditional" Statements, which are used to perform different actions based on different conditions.


#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

  function (num) {
    if (num % 3 === 0) {
      console.log(`${num} is divisible by three`);
    } else {
      console.log(`${num} is not divisible by three`);
    }
  }

#### 4. What is JSON?

  //Your Answer
  JSON === JavaScript Object Notation
  
  
  //Googled Answer
  JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

#### 6. What is a closure?

  //Your Answer
  Closure is when you can access a variable from outside of its scope.
  
  
  //Googled Answer
  Operationally, a closure is a record storing a function together with an environment: a mapping associating each free variable of the function (variables that are used locally, but defined in an enclosing scope) with the value or reference to which the name was bound when the closure was created.

#### 7. What's the difference between =, ==, and === in JavaScript?

  //Your Answer
  = is assignment operator
  == is subject to typecasting and can result in undesired results
  === checks object type along with value
  //Googled Answer
  JavaScript has both strict and type-converting equality comparison. For strict equality the objects being compared must have the same type and: ... Two Boolean operands are strictly equal if both are true or both are false. Two objects are strictly equal if they refer to the same Object

#### 8. Create an array with at least 4 items inside it, then access two of the values and console.log() them. Try to access the two values in two different ways.
const array = [1, 2, 3, 4];
console.log(array[0]);
console.log(array[array.length - 1]);

#### 9. Describe the different kinds of loops and why you would use them.

  //Your Answer
  For loop compacts the variable declaration and assignment, looping condition, and the iterator in one line of code.

  While loop is a few lines longer than a for loop and you have to remember to iterate your variable and declare it.
  
  //Googled Answer
  For Loops allow you to run through the loop when you know how many times you'd like it to run through the problem such as for (var i; i < 10; i++); this will continually increase i untill that condition returns false, any number can replace the 10 even a variable. but it will quit once the condition is no longer being met. This is best used again for loops that you know how when they should stop.

  While Loops allow you a little more flexability in what you put in it, and when it will stop such as while ( i < 10) you can also substitue in a boolean(true/false) for 10 as well as many other types of varibles.

  The key difference between the two is organization between them, if you were going to increase to 10 it'd be a lot cleaner and more readable to use a for statement, but on the other hand if you were to use an existing variable in your program in your loop parameters it'd be cleaner to just wright a while loop. In the For loop you MUST create a new variable, thats not true for the While loop.
  
#### 10. How would you explain "scope" in javascript?

  //Your Answer
  What variables and functions are accessible to you depending on where you are
  
  
  //Googled Answer
  In JavaScript, scope refers to the current context of your code. Scopes can be globally or locally defined. Understanding JavaScript scope is key to writing bulletproof code and being a better developer. You’ll understand where variables/functions are accessible, be able to change the scope of your code’s context and be able to write faster and more maintainable code, as well as debug much faster.

  Thinking about scope is easy, are we inside Scope A or Scope B?


