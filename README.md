# Student API Automation - Postman + Newman
## Project Overview
This project contains automated test cases for the Student Management APIs.

We have automated the complete CRUD flow:

- Create Student (POST)

- Get All Students (GET)

- Get Student by Registration ID (GET)

- Search Student by Name (GET with query param)

- Update Student (PUT)

- Delete Student (DELETE)

The collection is built using Postman test scripts and can be executed using Newman to generate HTML reports.

## Tools Used
- Postman
- Newman
- Node.js

## Project Structure
The collection includes:
1. Create Student (POST)
   - Validates Status Code
   - Validates Response structure
   - Stores created student data in collection variables
  
## How to run
- Clone the project
- give command ```npm i newman```
- Add env file to the project root
- Finally give command to execute ```npm test```

- Documentation: [Postman documentation] (https://documenter.getpostman.com/view/38863803/2sBXcDH231)
- Test Cases: [Test Cases]

## HTML Report Output:
<img width="1219" height="898" alt="image" src="https://github.com/user-attachments/assets/95c129ad-0c67-424e-8a99-275d631123d7" />
