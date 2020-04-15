# React-Components

A simple repo about React components

What are React components? Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions.

Basically a component is a function or class which accepts input and returns an element that is rendered to the DOM.

React components let you break up the user interface into separate pieces that can then be reused and handled independently.

Below is an example of a React Component

  ````
  function nameComponent (props) {
           return React.createElement(
               'h1',
               null,
               props.name,
           )
       }
       
   ````    
