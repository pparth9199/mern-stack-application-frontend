# Mern Stack front end



The following mern stack front-end application is to manage an online book system. 


## Features
- Create new book title 
- Update existing book title
- Delete an existing book
- View all books in the database

## Prerequisite
Run the server present in this [ repo ](https://github.com/pparth9199/mern-stack-application-backend) 
## Installation and run
```sh
npm install
npm start
```
## Deployement
- The deployement of the app is carried out to AWS EC2 instances 
- The github actions was used to create a CI/CD pipeline for deployement to AWS

## Tech

The project uses a number of tech to work properly:

- [ReactJS] - HTML enhanced for web apps!
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Mongo DB] - database to store the books

# Performance analysis
- The performance in the image below shows that the time to loa the page with over 10,000 books in the database took around 235ms
- This performance analysis are done on a local running macbook air machine
- Actual performance on a server would be way faster than the analysis done here

![homepage](https://drive.google.com/uc?export=view&id=1tO4Rpqinuskk1M3WC2lRsnlGbTi1coCA)

