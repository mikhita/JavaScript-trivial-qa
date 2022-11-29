#Explain Hoisting
Hoisting is javascript engine specification because we can use variable or function names before declaration and assignment, so how it works for example 
: console.log(name); // undefined
let name = "Misha"l
console.log(name); // Misha

this means that engine will assign to our variable undefined value in memory before its declaration, same way is working with functions
console.log(foo()) //undefined
foo(){
  return 11
}
console.log(foo())//11
here also javascript assigned undefined to the foo() function because of that we call it and engine understands that it should be function
