#Why is extending built-in JavaScript objects not a good idea?
It is not a good idea because if we are using an built in Array.prototype methods and we want to extend it with function or other it can make conflict because 
for example if we are using two libraries or more they can have similar method names but functionality can be different , what means that will be conflict with 
other library methods, we can use it only with polyfills so with old browsers which doesnt support new code
