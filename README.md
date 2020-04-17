# React-Components

A simple repo about React components

What are React components? Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions.Independent pieces of functionality

Basically a component is a function or class which accepts input and returns an element that is rendered to the DOM.Which 
Receives ‘properties’ object and returns a React element

Let's see React Componets like this...! React components let you break up the user interface into separate pieces that can then be reused and handled independently.

A React component can be either “stateful” or "stateless."
“Stateful” components are of the class type, and a  “stateless” component is of the function type.

So what is the difference between the two?



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
