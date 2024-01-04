This project contains tasks for learning the basics of ECMAScript 2015 (ES6).

Tasks To Complete
 0. Const or let?
0- For the code below, make the following modifications:
function taskFirst to instantiate variables using const.
function taskNext to instantiate variables using let.

 1. Block Scope
1- For the code below, modify the variables inside the function taskBlock so that the variables aren't overwritten inside the conditional block.
export default function taskBlock(trueOrFalse)

 2. Arrow functions
2- For the code below, rewrite the following standard function to use ES6's arrow syntax of the function add.

3. Parameter defaults
3- For the code below, condense the internals of the following function to 1 line - without changing the name of each function/variable.

 4. Rest parameter syntax for functions
4- For the code below, modify the following function to return the number of arguments passed to it using the rest parameter syntax.

 5. The wonders of spread syntax
5- For the code below, using spread syntax, concatenate 2 arrays and each character of a string by modifying the function below. The function body should be one line long.

 6. Take advantage of template literals
6- For the code below, rewrite the return statement to use a template literal so you can the substitute the variables you’ve defined.

 7. Object property value shorthand syntax
7- For the code below, modify the following function’s budget object to simply use the keyname instead.
export default function getBudgetObject(income, gdp, capita)

 8. No need to create empty objects before adding in properties
8- For the code below, rewrite the getBudgetForCurrentYear function to use ES6 computed property names on the budget object.
function getCurrentYear()

 9. ES6 method properties
9- For the code below, rewrite getFullBudgetObject to use ES6 method properties in the fullBudget object.
import getBudgetObject from './7-getBudgetObject.js';

 10. For...of Loops
10- For the code below, rewrite the function appendToEachArrayValue to use ES6’s for...of operator. And don’t forget that var is not ES6-friendly.
export default function appendToEachArrayValue(array, appendString)
 
11. Iterator
11- Write a function named createEmployeesObject that will receive two arguments:
departmentName (String).

 12. Let's create a report object
12- Write a function named createReportObject whose parameter, employeesList, is the return value of the previous function createEmployeesObject.
export default function createReportObject(employeesList)

 13. Iterating through report objects
100- Write a function named createIteratorObject, that will take into argument a report Object created with the previous function createReportObject.

 14. Iterate through object
101- Write a function named iterateThroughObject. The function’s parameter reportWithIterator is the return value from createIteratorObject.
