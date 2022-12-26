# What language constructions do you use for iterating over object properties and array items
## for objects
- for-in , for (var property in obj) { console.log(property); } , this will itarate throw inherited objects also and will add object.hasOwnProperty(property), to check it before using 
- Object.keys() - Object.keys(obj).forEach(function (property) { ... }). Object.keys() is a static method that will lists all enumerable properties of the object that you pass it.
- Object.getOwnPropertyNames() - Object.getOwnPropertyNames(obj).forEach(function (property) { ... }). Object.getOwnPropertyNames() is a static method that will lists all enumerable and non-enumerable properties of the object that you pass it.
## for arrays
- for loop
- for.each
- map
- for of
