# Explain how JSONP works?
-  when we want to fetch sripts with data into browser our document will get this scripts and will read if it is only one request and one response beacause our server can add one response into special veraieble, but if there is a lot request we need different referals to fetch them from browser, so here JSONP can help us beacause it is <script src /> getting method but with more functionality for example when client will request some data we will put in this callback function one extra parameter after server will parse it to json and will response data back to us with the name which was given with callback function parameter for ex: onUserLoad:({
   name:'misha',
   age:26
   });
   
this is JsonP(with padding)
