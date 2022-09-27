# Code-Splitting 

## Static Import
Import code that has been exported by another module

<br/>

## Dynamic Import
Import parts of your code on demand. in React we can use `Lazy()`  

<br/>

## Import on Visibility
Load non-critical components when they are visible in the viewport. As we're not requesting all images instantly, we can reduce the initial loading
time. We can do the same with components! In order to know whether
components are currently in our viewport, we can use the
IntersectionObserver API, or use libraries such as `react-lazyload`
or `react-loadable-visibility` to quickly add import on visibility to our
application.

<br/>

## Import on Interaction
Load non-critical resources when a user interacts with UI requiring it. Breaking the loading of this work up is relatively straight-forward with code-splitting. The `React.lazy` method makes it easy to code-split a React
application on a component level using dynamic imports.

<br/>

## Tree Shaking
Reduce the bundle size by eliminating dead code