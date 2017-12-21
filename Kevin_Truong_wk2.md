### Javascript Course Assessment
 
## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. How do you link a css file to your html page?
 
 //Your Answer
 <link src="./style.css" rel="stylesheet">
 //Googled Answer
 <link rel="stylesheet" type="text/css" href="theme.css">

 
 
 #### 2. What is a css class? How do you use declare one in html? How do you use it in css?
 
 
 //Your Answer
 Css class is declared by class="className" in the HTML tag. In CSS you use it by using .className { }
 //Googled Answer
 The .class selector selects elements with a specific class attribute.
 To select elements with a specific class, write a period (.) character, followed by the name of the class.
 
#### 3. The class "heading-box" exists in our html file - write the css code that would:
##### 1) align this box to the center of its container,
.heading-box { align: center; }
##### 2) give it a black border that is 5px wide,
.heading-box { border: 5px solid black; }
##### 3) make its text appear in the center of the box
.heading-box { text-align: center; }

#### 4. What is Bootstrap? Explain a few reasons that you might choose to use it in a project?
 
 //Your Answer
  bootstrap is a framework that was created by Twitter. You might use it in a project to speed up the front end design while making it look nice.
 
 //Googled Answer
 If you have any sort of interest in web development, you’ve likely heard of Bootstrap. According to the official website, Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web. Sounds great! Now how do I use it?
 
#### 5. Name 4 semantic html tags.
<aside>, <section>, <article>, <section>

#### 6. What is block scope that became available in ES6? Include how it differs from local and global scope, and what variables are block scoped. 
 
 //Your Answer
 functions declared with let and const are block-scoped. They are not available outside of the block it was delcared in.
 
 //Googled Answer
 When writing JS using var, it’s difficult to immediately discern which variables are scoped locally vs. globally. It’s very easy to accidentally create a variable on the global object in JavaScript. This generally doesn’t affect simple demo apps but can cause problems for enterprise level applications as team members accidentally obliterate each other’s variables.
 
 #### 7. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?
 
 //Your Answer
 Front end development handles the View of the MVC, They do the html, css, javascript, and work with other libraries and frameworks like React and Redux or Bootstrap.
 
 //Googled Answer
 Front-end web development is the practice of producing HTML, CSS and JavaScript for a website or Web Application so that a user can see and interact with them directly. The challenge associated with front-end development is that the tools and techniques used to create the front end of a website change constantly and so the developer needs to constantly be aware of how the field is developing.
 
 #### 8. Choose one of the new ES6 concepts we learned about this week (namely: block scope, classes, and string interpolation) and write example code that demonstrates the concept, with comments to explain what is going on. 
 function sayHello( ) => {
    let hi = 'hello';
    console.log(hi);
}

the hi variable is block scoped and not available outside of the function.
 
 #### 9. What is the difference between a div and a span? 
 
 
 //Your Answer
 <span> is an in-line element
 
 //Googled Answer
 <span> is an in-line element

   
#### 10. How would you explain the idea of "inheritance" in object oriented programming?
 
 
 //Your Answer
 Inheritance allows you to write less code by creating instances of objects that inherit certain traits from a parent class.
 
 //Googled Answer
 In object-oriented programming, inheritance enables new objects to take on the properties of existing objects. A class that is used as the basis for inheritance is called a superclass or base class. A class that inherits from a superclass is called a subclass or derived class
