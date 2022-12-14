# Pattern

## Singleton Pattern
Share a single global instance (classes) throughout our application

<br/>

## Proxy Pattern
With a Proxy object, we get more control over the interactions with certain
objects. Proxy Pattern useful for validation data

<br/>

## Provider Pattern
Make data available to multiple child components. (like useContext() in reactjs)

<br/>

## Provider Pattern
Make data available to multiple child components. (like useContext() in reactjs)

<br/>

## Provider Pattern
Share properties among many objects of the same type
![protodiagram](ss/Screenshot%20from%202022-09-27%2004-41-40.png)
<br/>
The prototype pattern is very powerful when working with objects that should
have access to the same properties. Instead of creating a duplicate of the
property each time, we can simply add the property to the prototype, since all
instances have access to the prototype object.
Since all instances have access to the prototype, it's easy to add properties to
the prototype even after creating the instances.
Say that our dogs shouldn't only be able to bark, but they should also be able
to play! We can make this possible by adding a play property to the prototype.<br/>

![protocode](ss/Screenshot%20from%202022-09-27%2004-45-36.png) <br/>
The term prototype chain indicates that there could be more than one step.
Indeed! So far, we've only seen how we can access properties that are directly
available on the rst object that __proto__ has a reference to. However,
prototypes themselves also have a __proto__ object! <br/>

## Container / Presentational Pattern
Enforce separation of concerns by separating the view from the application logic

<br/>

## Observer Pattern 
Use observables to notify subscribers when an event occurs

<br/>

## Module Pattern 
Split up your code into smaller, reusable pieces <br/>

<br/>

## Mixin Pattern
Add functionality to objects or classes without inheritance <br/>

<br/>

## Mediator / Middleware Pattern
just API stuff

<br/>

## Render Props Pattern
Pass JSX elements to components through props. ex: <br/>
```
const Title = props => props.render();

<Title render={()=> <h1>I am a render prop!</h1>}/>
```

<br/>

## Hooks Pattern
Use functions to reuse stateful logic among multiple components throughout the app

<br/>

## HOC Pattern
Pass reusable logic down as props to components throughout your application
