# Assignment-06
 1) What is the difference between var, let, and const?
 Answer: var - This is the old way. When we make variable with var, it works in whole function or globally. We can change the value and even declare it again with same name. 
         let - This is newer from ES6. The difference is "block scope" - means it only works inside the curly braces {} where we created it. We can change its value later, but we cannot declare same variable name    twice in same scope.
         const-Also from ES6 with block scope like let. The main thing is we cannot change value after we set it.
2) What is the difference between map(), forEach(), and filter()?
Answer: map() - This also goes through every element and runs code, but it creates completely new array with changed values. Original array stays same. 
       forEach() - This runs code on every item in array, but it doesn't return anything. It just does action on each element.
       filter() - This checks condition for every element. It returns new array with only elements that pass the test (return truthy).
3) What are arrow functions in ES6?
Answer: Arrow functions are shorter way to write functions. Introduced in ES6.
4) How does destructuring assignment work in ES6?
Answer: Destructuring is fancy way to unpack values from arrays or objects into separate variables quickly.
5) Explain template literals in ES6. How are they different from string concatenation?
Answer: Template literals use backticks (`) instead of quotes. They are called "template strings" before.

Main differences:
a) Easier to read - No need for many plus signs (+). We may put variables directly inside using ${variable} syntax​
b) Multi-line strings - We can write strings across multiple lines without special characters like \n. Template literals recognize line breaks automatically​
c) Can include expressions - Not just variables, we can do calculations inside: `Total: ${price * quantity}`​
d) No escaping quotes - We can use both ' and " inside without problems

