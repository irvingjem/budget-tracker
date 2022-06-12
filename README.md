# Budget Tracker

## USER STORY
AS A social media startup <br>
I WANT an API for my social network that uses a NoSQL database <br>
SO THAT my website can handle large amounts of unstructured data <br>

## Table of Contents 
------

* [Installation](#installation)

* [About](#about)

* [Demo](#demo)

* [Author](#author)

## Installation
1. Clone repository using 'git clone"
2. Install necessary dependencies, run the following command: <br> 'npm install'
3. To run application 'node server.js' in the command line

## About
This a project was built using <br>
* Node.js
* Inquirer
* MongoDB
* javaScript

## Demo
![social api example video](/walkthrough//social-api-walkthrough.gif) <br>
https://drive.google.com/file/d/17qc58Ah9WSprPx86uf1-AMntVc1e-k42/view Link to video
## Author 
Me :)

## SPECIFICATIONS
GIVEN a social network API <br> 
WHEN I enter the command to invoke the application <br> 
THEN my server is started and the Mongoose models are synced to the MongoDB database <br> 
WHEN I open API GET routes in Insomnia for users and thoughts <br> 
THEN the data for each of these routes is displayed in a formatted JSON <br> 
WHEN I test API POST, PUT, and DELETE routes in Insomnia <br> 
THEN I am able to successfully create, update, and delete users and thoughts in my database <br> 
WHEN I test API POST and DELETE routes in Insomnia <br> 
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list <br> 