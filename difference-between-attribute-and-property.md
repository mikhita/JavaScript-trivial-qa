#What's the difference between an "attribute" and a "property"
To answer on this question we can show an example where we can see that if we can change the value of element with property in javascript to do the same with attribute is not
possible, for ex: const input = document.querySelector('input');
                  console.log(input.getAttribute('value')); // Hello
                  console.log(input.value); // Hello
After we add World in the text field and we get :
                    console.log(input.getAttribute('value')); // Hello
                    console.log(input.value); // Hello World!
