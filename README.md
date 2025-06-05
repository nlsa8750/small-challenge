TASK 1:

How to Use the Joke API via:
1. Frontend App (your React app)
2. Postman (API testing tool)

1.A How to run the project:

a. Clone the Repository:
git clone git@github.com:nlsa8750/small-challenge.git

b. Make sure node is installed. Then
npm install

c. Start the React App
npm start

d. View in Browser and Interact with the application

2.A How to execute it on Postman

a. Open Postman

b. On the right side, select Collection and then click on '+' button. It will create a new Collection and then after that make a new request, mentioned below the newly created Collection. Choose GET Method and then enter the URL:
1. https://v2.jokeapi.dev/joke/Any
2. https://v2.jokeapi.dev/joke/Programming
3. https://v2.jokeapi.dev/joke/Pun
4. https://v2.jokeapi.dev/joke/Dark

c. Click send and then view the response.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

TASK 2:

A.How to execute the Prime Checker App:

1. Open Postman

2. Create a new collection and then add new request. Choose GET Method.

3. In the URL bar, type : http://localhost:8080/api/isPrime?number=7
TIP: Type anything in the place of '7' at the end of the url, for the Testing purpose.

For example:
http://localhost:8080/api/isPrime?number=11
http://localhost:8080/api/isPrime?number=8
http://localhost:8080/api/isPrime?number=7.5
http://localhost:8080/api/isPrime?number=
http://localhost:8080/api/isPrime?number=abc

Response Status:
200 OK = Valid Inputs
400 BAD REQUEST = errors

4. Click on send and then check the response.

TIP: You can also use Params Tab in Postman:
Key => number
Value => 15




