# Project: Flask email API and Client

## Description 
A Lenny Kravitz fan page built in fullstack with react on the client, flask on the server and is connected to an email service using flask-mail. Users can join the mailing list, view all albums and suggest a name and release date for a new album. Subscribers will receive a welcome email and updates of new albums. 

## Installation and Usage
- Clone or download this repo
- Navigate to root directory of this repository
- Open the terminal and navigate to the api subdirectory
    `pipenv shell`
    `pipenv install`
    `pipenv run dev`
    Flask API will be running on port 5000

To run API test suite:    
    `pipenv run test`

- Navigate to the client subdirectory
    `npm install`
    `npm run dev`
    The client will open on port 8080

## Technologies
- HTML, CSS, JavaScript, Python

### Dependencies: 
   - Server: flask, flask-mail, flask-cors, gunicorn
   
   - Client: axios, react, router-dom, react-router-dom, react-icons
   
### DevDependencies:
   - Server: pytest, pytest-cov
   
   - Client: babel, react-testing-library, jest

## Process 
1. Decide on flow and idea and what is needed for a MVP
2. Listen to some Lenny Kravitz music!
3. Create seed data to be used for API
3. Drive and navigation between collaborators 
4. Start with backend then create a front-end client
5. Add styling and finalise!

## Bugs
- [x] MailTrap still sending emails during testing

## Changelog

### React-Client
1. Set up pages and components   
3. Use axios to set up GET request from API
4. Implement socket.io client 
5. Styling!

### API
1. Set up server with routes and controllers
3. Complete GET, POST routes 
4. Test!

## Wins & Challenges

### Wins
- Created in one day!
- Finding MailTrap which is a great way to test emails without using own account

### Challenges
- Testing with flask mail - mail still sending during testing 
- Switching between both Python and JavaScript!

## Future Features 
??
