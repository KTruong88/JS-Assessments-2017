ls### Javascript Course Assessment
 
## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:

- React was created to be simple, so that even people with minimal code experience could use it and create Single Page Applications (SPAs)
- React is a modern, efficient answer to complex UI applications
- React is a flexible library that plays the role of V in an MVC framework

 
 #### 2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.
 
 
 //Your Answer
 Smart components deal with state. Dumb does not.
 
 //Googled Answer
 Smart Component Characteristics
 Describe how things work
 Provide no DOM markup or styles
 Provide application data, do data fetching
 Call Flux actions
 Named *Container by convention
 
 Dumb Component Characteristics
 Describe how things look
 Have no app dependencies
 Receive only props, providing data and callbacks
 Rarely have own state, when they do, it’s just UI state
 Named anything that’s a UI noun
 
 
#### 3. Write a simple component that simply prints "I am a dumb component" to the screen. Be sure to include all necessary imports, expots, etc...
function Dumb(props) {
return (
<div className={props.css.awesomeLayout}>
<p>I am a dumb component</p>
</div>
)
}

#### 4. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

 
 //Your Answer
 Yarn is a package manager. It is fetching modules. Package.JSON gets updated.
 
 
 //Googled Answer
 In general, a package is simply a folder with code and a package.json file that describes the contents. When you want to use another package, you first need to add it to your dependencies. This means running yarn add [package-name] to install it into your project.
 
 This will also update your package.json and your yarn.lock so that other developers working on the project will get the same dependencies as you when they run yarn or yarn install.
#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

    import React, { Component } from 'react';

    class Recipes extends Component {
      constructor(props){
        super(props)
        this.state = {
          recipes: 
            {name: 'Meatballs'},
            {name: 'Mac & Cheese'}
      
        }
      }

      render() {
    
        return (
          let recipes = this.state.recipes.map(function(recipe){
            return(
            <div>
              <li key={recipe.name}>{recipe.name}</li>
              })
              <ul>
                {recipes}
              </ul>
            </div>
        );
      }
    }

    module.exports = default Recipes;

#### 6. Name three input types. (NOTE: text is the default type - so it doesn't count in this case)
 
 //Your Answer
 string, integer, boolean
 
 //Googled Answer
 string, integer, boolean
 
 #### 7. How would you explain state to a friend who doesn't know code?
 
 //Your Answer
 What part of the app is on depending on your previous action
 
 //Googled Answer
 In information technology and computer science, a program is described as stateful if it is designed to remember preceding events or user interactions; the remembered information is called the state of the system. The set of states a system can occupy is known as its state space.
 
 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 Props can only be passed from component to component, State can be stored locally in the object and set with setState.
 
 #### 9. Name three benefits of testing and TDD:
 
 
 //Your Answer
 Focused code, know exactly what you want from your app, not wasting time
 
 //Googled Answer
 Focus, Tidier code, Fewer Bugs
   
#### 10. List two helpful testing matchers and two helpful enzyme simulators that we can use when writing our tests:
 
 
 //Your Answer
 no idea
 
 //Googled Answer
 toBeEmpty(), toBePresent()
