#Explain CORS.
- when browser is sending ajax response to the server it has also idintificator which is showing which user is sending that response.
- if we want to get responses from another api to our server, we can add special addresses from where we can deserve responses on our server
- app_header "Acsess-Control-Allow-Methods" "Get-Post-Put-Options" always, this code means that we will get only this kind of responses
- if we want to allow all responses we have to add "Acsess-Control-Allow-Credentials" "true"
- 
