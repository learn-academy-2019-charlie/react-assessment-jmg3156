# React Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:

- React is a modern, efficient answer to complex UI applications
- React is a flexible library that plays the role of V in an MVC framework

 
 #### 2. What are "smart"(logic) and "dumb"(display) components? Explain the difference and also add why we bother to make the distinction between them.
 
 
 //Your Answer
 Dumb components are used once.
 Smart Compenents have constructor functions
 
 
 //Googled Answer
 Dumb Components are called 'presentational' components because their only responsibility is to present it to the DOM. Once that is done, 
 the compenents is done with it. Puts the info on the page and moves on. 
 
 Smart compenents ( or container component)
 Keeps track of state and care about how the app works 
 They are class based compenents and have their own state defined in their constructor() functions
 
 
#### 3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?
 
 
 //Your Answer
 installing the react app package
 
 
 //Googled Answer
 installs the “latest” version of the package
 
 
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
          return (
    
          let recipes = this.state.recipes.map(function(recipe){
            return(
              <li key={recipe.name}>{recipe.name}</li>
            )
          })
    
          <ul>
            {recipes}
          </ul>
        );
      }

      render() {
    }

    export default Recipes;

#### 6. Name three html input types. (NOTE: text is the default type - so it doesn't count in this case)
 
 //Your Answer
 button
 sumbit
 text
 
 
 //Googled Answer
 date
 email
 reset
 
 
 #### 7. How would you explain state to a friend who doesn't know code?
 
 //Your Answer
 
 
 //Googled Answer
 A compenents dynamic data and determines the components behavior 
 
 
 
 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 
 
 //Your Answer
 
 
 //Googled Answer
 States is dynamic so it enables a component to keep track of changing information and can only be used in the Class component. Props 
 should never be changed in a child compenent.
 
   
#### 9. Write a paragraph or so about your experience with building tic-tac-toe. Some topics to start with might be: things you learned about yourself, concepts from React that stood out to you, something about pair programming (if you paired), or the experience of building something in code from scratch.
My group worked on the treasure hunt game. Honestly, it was very challenging. I still don't really understant react but it gave me a better
idea on how I should go about starting to build code from scratch. Meaning, I had to think about everything I need to include in our code and essentially
what outputs we were expecting from every piece. Still something I need to practice/study more on though.