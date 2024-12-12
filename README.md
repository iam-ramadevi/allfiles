[
Does it make sense to use Vuejs and Reactjs on the same project
No. Both Vue.js and React are for the same purpose - building UI components.
I'm diving into Vue.js and React.js for a project, and I'm curious about how Vue.js handles state updates and re-renders compared to React.js. Specifically, I'm interested in understanding the underlying mechanisms that make one faster or more efficient than the other.
Actually in Vue 3 both local and global state management are the same, because the reactive objects, implemented as ES6 proxies, will automatically subscribe the surrounding object, updating it when needed. So it doesn't matter where the reactive object is declared (local or global). The same subscribing logic is also applied to computed values.
Vue and React both use a Virtual DOM,
Re-rendering components in ReactJS refers to the process of updating the component due to changes in props or state and reflecting the updated output on the web page.
what is re-render in vue js
The ref function is used to define a reactive state in the Vue Composition API, which triggers the component to rerender when what it returns changes value. To do the same thing with the Vue Options API, we declare a reactive value by putting it in the object returned by the data method
Redux -> state management
Redux is a state management tool. Redux is for client state, by default it's in-memory only. 
Redux use internal memory for all data. For example, when you subscribe to Store, Redux just push listener to private array and do not use Cookies or Local Storage.
styles, tailwind, Axios service calls, interceptors, OKTA authentication, redux, context API, code splitting, webpack build, JEST unit test, BFF, API Gateway, Circuit breaker, Spring, Java, ORM, Swagger, Microservices, CICD processes.
Redis is caching 
Optimizing -> caching 
JSX -> Extension of javascript
Axios service calls -> advanced Ajax, to call API
webpack build -> front end all bundle only frontend
webpack build
JEST unit test -> test cases, developer unit test cases, front end unit test cases
API Gateway->code scanning
cross site request (CSRF)
Axios:
 
Postman or vs code using npm can run and test react UI
 
 
 
 
Npm install
Npm start 
next.js, backend half front end half
 
 
 
 
 
 
 
 
 
 
 
Navigation links:
 
Webpack:

 

 

Webpack:
 
Npm run build
 

Plugins in webpack: 
 
Reactjs:
JSX :
 
 
 
Immutable-> React DOM

 

React JSX
 
 
 
.JSX
 
 
 
 

 
 
Map: In React.js, the map() function is used to iterate over an array and apply a function to each item in the array, returning a new array with the modified values. It's typically used to render a list of elements dynamically.

List in react you should add Keys
 

array aslist  is immutable? Use filter method to do mutable.
Keys help React identify which items have changed, are added, or are removed. Define keys in MAP() function
Babel is a JavaScript compiler that is widely used in the React ecosystem. It allows developers to write code using the latest ECMAScript features (including those from ES6, ES7, ES8, etc.)
React installation:
 
 
Create React -app package 
 
 
 
 

Install react router:
 

 

Single page application to multiple routes:
 
Angular:

 

 
 
 
 
 

  
 
App-component.html is the root file of html
 
 
 
 
 
 

 
 
 
 
 
 
 
Flex: Tailwind flex, you can easily position flex items vertically or horizontally, switch between row and column layouts, align items along the main or cross axis, control wrapping behavior, and much more.
Reusable component: It encapsulates the login that can be reused again.
What is a composite component in React?
Compound components are a pattern in React, where several components are used together such that they share an implicit state that allows them to communicate with each other in the background. This pattern is used when multiple components work together to have a shared state and handle logic together

how do you manipulate the date time? Adding holidays or leaves.
 
 
 
What is a callback function giving an example? (asyn)
We want to log a message to the console, but it should be there after 3 seconds. In other words, the message function is being called after something happened (after 3 seconds passed for this example), but not before. So, the message function is an example of a callback function.
 
 
carName = "Saab";
  let carName = "Volvo";
 
The event loop is a component of the JavaScript engine that manages the execution of code, collecting and processing events, and executing queued sub-tasks
 
Sync vs async
 
 
 it uses XMLHttpRequests.
 
 
 
 
 
 
 
 
 
Java version 21
 
 
Package.json
Dependencies
Package-lock. Json : sub-dependencies
 
 
 
 
 
 
 
 
 
 
 
1.	apply lock on HashMap
2.	retrieve.
3.	process.
4.	put into HashMap.
5.	release lock.
 
 
 
 
Constructor injection, is generally recommended
Setter injection: We can easily change the value by setter injection. It doesn't create a new bean instance always like constructor. So setter injection is flexible than constructor injection.
what is cache evict in spring boot
 
the clear () method will clear all the cache entries, and the evict() method will clear values based on a key
•	structure the URL for get method.
 
Use path parameters or query parameters.
 
The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory

Redux: Redux is a state management tool. Redux is for client state, by default it's in-memory only. 

  
  
 
 
 
Interceptors
 
 
React-thunk for dispatch method

Tailwind:
 
server-side rendering, Next. Js
write next js file in .tsx , and helper function would be in .ts (angular)
 
If file is in .jsx helper function would be in js file. 
 
 

React Hooks :
 
 
 
 
 
 
 
 
 
 
what is AOP in spring boot
Aspect-Oriented Programming (AOP)
Object-oriented programming (OOP) is a programming paradigm that uses objects to design applications and computer programs. The main difference between AOP and OOP is that AOP focuses on the separation of concerns while OOP focuses on the encapsulation of data and behavior into objects
Dependency injection (DI)
IoC (Inversion of Control) Container
 
@Service is a @component in annotations.
 

=====Spring boot—

Servlets no longer (spring MVC was replaced)
Tomcat is a servlet container
Run springboot applications using Intellij and Maven (build tool)
Run java –version o/p is 21.
 
To inject the objects need DI(dependency injection)
IOC (Inversion of control): is principal
DI: Dependency injection is design pattern
Spring boot is :  
 
Create spring boot project
 

Without DI(Dependency injection)
 
Insected the @component in Alien class
 
Here @component is Dependency injection 
Task2: Create 2 classes
 
 
@Autowired

 
Maven project : version for spring context
 

)](https://github.com/sudheerj/vuejs-interview-questions?tab=readme-ov-file#what-is-global-registration-in-components
https://github.com/sudheerj/reactjs-interview-questions?tab=readme-ov-file#can-i-use-javascript-urls-in-react169 
Does it make sense to use Vuejs and Reactjs on the same project
No. Both Vue.js and React are for the same purpose - building UI components.
I'm diving into Vue.js and React.js for a project, and I'm curious about how Vue.js handles state updates and re-renders compared to React.js. Specifically, I'm interested in understanding the underlying mechanisms that make one faster or more efficient than the other.
Actually in Vue 3 both local and global state management are the same, because the reactive objects, implemented as ES6 proxies, will automatically subscribe the surrounding object, updating it when needed. So it doesn't matter where the reactive object is declared (local or global). The same subscribing logic is also applied to computed values.
Vue and React both use a Virtual DOM,
Re-rendering components in ReactJS refers to the process of updating the component due to changes in props or state and reflecting the updated output on the web page.
what is re-render in vue js
The ref function is used to define a reactive state in the Vue Composition API, which triggers the component to rerender when what it returns changes value. To do the same thing with the Vue Options API, we declare a reactive value by putting it in the object returned by the data method
Redux -> state management
Redux is a state management tool. Redux is for client state, by default it's in-memory only. 
Redux use internal memory for all data. For example, when you subscribe to Store, Redux just push listener to private array and do not use Cookies or Local Storage.
styles, tailwind, Axios service calls, interceptors, OKTA authentication, redux, context API, code splitting, webpack build, JEST unit test, BFF, API Gateway, Circuit breaker, Spring, Java, ORM, Swagger, Microservices, CICD processes.
Redis is caching 
Optimizing -> caching 
JSX -> Extension of javascript
Axios service calls -> advanced Ajax, to call API
webpack build -> front end all bundle only frontend
webpack build
JEST unit test -> test cases, developer unit test cases, front end unit test cases
API Gateway->code scanning
cross site request (CSRF)
Axios:
 
Postman or vs code using npm can run and test react UI
 
 
 
 
Npm install
Npm start 
next.js, backend half front end half
 
 
 
 
 
 
 
 
 
 
 
Navigation links:
 
Webpack:

 

 

Webpack:
 
Npm run build
 

Plugins in webpack: 
 
Reactjs:
JSX :
 
 
 
Immutable-> React DOM

 

React JSX
 
 
 
.JSX
 
 
 
 

 
 
Map: In React.js, the map() function is used to iterate over an array and apply a function to each item in the array, returning a new array with the modified values. It's typically used to render a list of elements dynamically.

List in react you should add Keys
 

array aslist  is immutable? Use filter method to do mutable.
Keys help React identify which items have changed, are added, or are removed. Define keys in MAP() function
Babel is a JavaScript compiler that is widely used in the React ecosystem. It allows developers to write code using the latest ECMAScript features (including those from ES6, ES7, ES8, etc.)
React installation:
 
 
Create React -app package 
 
 
 
 

Install react router:
 

 

Single page application to multiple routes:
 
Angular:

 

 
 
 
 
 

  
 
App-component.html is the root file of html
 
 
 
 
 
 

 
 
 
 
 
 
 
Flex: Tailwind flex, you can easily position flex items vertically or horizontally, switch between row and column layouts, align items along the main or cross axis, control wrapping behavior, and much more.
Reusable component: It encapsulates the login that can be reused again.
What is a composite component in React?
Compound components are a pattern in React, where several components are used together such that they share an implicit state that allows them to communicate with each other in the background. This pattern is used when multiple components work together to have a shared state and handle logic together

how do you manipulate the date time? Adding holidays or leaves.
 
 
 
What is a callback function giving an example? (asyn)
We want to log a message to the console, but it should be there after 3 seconds. In other words, the message function is being called after something happened (after 3 seconds passed for this example), but not before. So, the message function is an example of a callback function.
 
 
carName = "Saab";
  let carName = "Volvo";
 
The event loop is a component of the JavaScript engine that manages the execution of code, collecting and processing events, and executing queued sub-tasks
 
Sync vs async
 
 
 it uses XMLHttpRequests.
 
 
 
 
 
 
 
 
 
Java version 21
 
 
Package.json
Dependencies
Package-lock. Json : sub-dependencies
 
 
 
 
 
 
 
 
 
 
 
1.	apply lock on HashMap
2.	retrieve.
3.	process.
4.	put into HashMap.
5.	release lock.
 
 
 
 
Constructor injection, is generally recommended
Setter injection: We can easily change the value by setter injection. It doesn't create a new bean instance always like constructor. So setter injection is flexible than constructor injection.
what is cache evict in spring boot
 
the clear () method will clear all the cache entries, and the evict() method will clear values based on a key
•	structure the URL for get method.
 
Use path parameters or query parameters.
 
The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory

Redux: Redux is a state management tool. Redux is for client state, by default it's in-memory only. 

  
  
 
 
 
Interceptors
 
 
React-thunk for dispatch method

Tailwind:
 
server-side rendering, Next. Js
write next js file in .tsx , and helper function would be in .ts (angular)
 
If file is in .jsx helper function would be in js file. 
 
 

React Hooks :
 
 
 
 
 
 
 
 
 
 
what is AOP in spring boot
Aspect-Oriented Programming (AOP)
Object-oriented programming (OOP) is a programming paradigm that uses objects to design applications and computer programs. The main difference between AOP and OOP is that AOP focuses on the separation of concerns while OOP focuses on the encapsulation of data and behavior into objects
Dependency injection (DI)
IoC (Inversion of Control) Container
 
@Service is a @component in annotations.
 

=====Spring boot—

Servlets no longer (spring MVC was replaced)
Tomcat is a servlet container
Run springboot applications using Intellij and Maven (build tool)
Run java –version o/p is 21.
 
To inject the objects need DI(dependency injection)
IOC (Inversion of control): is principal
DI: Dependency injection is design pattern
Spring boot is :  
 
Create spring boot project
 

Without DI(Dependency injection)
 
Insected the @component in Alien class
 
Here @component is Dependency injection 
Task2: Create 2 classes
 
 
@Autowired

 
Maven project : version for spring context
 

)
