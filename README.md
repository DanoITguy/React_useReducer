# React_useReducer
Created with CodeSandbox

As with the other array methods, Array.reduce() takes in a callback function as its first argument. This callback function is called the reducer function, or simply the reducer.
Optionally, we can also pass in a second argument of an initial value. 
Array.reduce() returns a reduced value which can be of any data type, depending on how you write the reducer function and what initial value you specify.
The reducer has two parameters: an accumulator value, and the current value.
The current value is essentially the same as the first parameter for the callback functions in Array.map() or Array.filter(). That is, for each iteration over the array, it will contain the value of a different item in the array. 
The accumulator value is a bit different, and this value is really the key to understanding Array.reduce().
At the first iteration, if no initial value was provided, then the first item in the array is used as the accumulator, and the second item in the array is used as the current value. 

Lists that can be added to or removed from, whether shopping carts, to-do lists, or other types of lists, are very commonly required in applications.
The core logic within many item lists is a reducer function, similar to the one we were looking at in this project.
You will see how the useReducer hook built into React can be used, in an approach similar to Redux, to manage application state for a basic to-do/shopping list without needing a third-party state management library. 
An important takeaway here is that Redux is most useful with apps with large amounts of application state and complex updating logic, and it doesn't always make sense to reach for Redux right away when simpler solutions will do for a simpler application. 
