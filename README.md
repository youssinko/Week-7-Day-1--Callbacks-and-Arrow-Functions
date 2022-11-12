# Week-7-Day-1--Callbacks-and-Arrow-Functions
function add(a, b) {
  return a + b;
}

function subtract(a, b) {
  return a - b;
}

function compute(a, b, op) {
  return op(a, b);
}

let result1 = compute(10, 5, add);
let result2 = compute(10, 5, subtract);



Review Questions to turn in

❓ When the add and subtract functions are passed as arguments to the compute function - they are _ 'higher order'__ functions.

Also, note that we are passing named functions (add& sum) instead of using an anonymous inline function like with the forEach earlier.

One of the best ways to learn about callbacks is to first understand their use-cases.

//-------------------------------------------------------------
How many times would the anonymous callback function below be called?**:

=> answer is : Three Times


const flowers = ['rose', 'orchid', 'daisy'];

flowers.forEach(function(flower, idx) {
  console.log(`${idx + 1}) ${flower}`);
});
//------------------------------------
Review Questions to turn in

 

❓ In your own words describe what the term "implicit return" means.

answer is => it is a new / short way to write a function and you don't need to write (return) keyword to return a value 
❓ Describe what a callback function is in your own words.

answer is => it's a function passed on as argument in another function 
