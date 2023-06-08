# Example-Angular_and_API
This tutorial prooves that i grasp the technical knowledge to Combine Angular(frontEnd) and C#.NetCore(backend Api)
#Angular and .Net Api and Data stored MS-SQL server
Example Project on how to develop and Build Angular App with DOTNET Web API
<br>
To run the Project on the backend(API) you need to navigate to the WebAPI
directory and run the solution .sln file .Then run the server ie by hitting F5
Remember to attach the .mdf database file to sql server and change the connection
string according to your configuration(found on appsettings.json)
<hr>
 
Open it in Code and again run the client that reads Angular code into functionality(-ies)
You do that By typing :
  npm start
  <br>
  
If there are any incmobatibilities remove node_modules folder and readd them via the following lines<br>
  in my-app folder run 
  <br>
  npm install -g @angular/cli  
  <br>
  ...to transfer all the environment you need fot the client side to run on a browser<br>
typing again: 
  npm start
  <br>    
  You will get the address you need to witness the small yet all-encompassing Dept-Employee app functionality.
  The departments and Employess are now synced to the database using WEB-Api automation
  <hr>
  
For my case, specifically i had to also set a parameter.Namely:<br>
set  NODE_OPTIONS=--openssl-legacy-provider <br>
berfore npm start<br>
I have a hunch that this lowers security however.It would be best to 
'set' and 'unset' the parameter after installing and using the client respectively.
