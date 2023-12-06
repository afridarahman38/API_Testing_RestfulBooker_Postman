# API Testing with Postman and Report Generation using Newman

## Overview
The project aimed to conduct comprehensive API testing for a web application using Postman and Newman, ensuring functionality, reliability, and performance. Key steps included API endpoint identification, collection creation, environment setup, data-driven testing, authorization testing, and automation.

## Prerequisites
Postman: Ensure that you have Postman installed on your machine. You can download it from [Postman's official website](https://www.postman.com/downloads/)

Node.js and npm: Newman is built on Node.js, so you need to have Node.js and npm installed. You can download them from [Node.js official website.](https://nodejs.org/en)

## Project Structure
- RestfulBooker_API_Collection.postman_collection.json: This file contains the collection of API requests for RestfulBooker.

- RestfulBooker_Environment.postman_environment.json: This file includes the environment variables used in the collection, such as base URL.

- scripts/: This directory contains scripts used for report generation and other automation tasks.


## Tools Used:
- Postman: Postman was chosen for its user-friendly interface and robust features that facilitate API testing, request creation, and response validation.
  
- Newman: Newman, the command-line collection runner for Postman, was utilized for automating the API testing process. It allows for the execution of Postman collections directly from the command line, making it convenient for integration into continuous integration/continuous deployment (CI/CD) pipelines.

## Key Steps and Activities:
- API Endpoint Identification
- Postman Collection Creation
- Environment Setup
- Data-Driven Testing
- Authorization Testing
- Automation with Newman
- Report Generation

## Viewing Reports
After running the tests, navigate to the reports/ directory and open the generated HTML report in a web browser for a detailed overview of test results.

## Acknowledgments
This API testing project successfully ensured the reliability and performance of the web application's APIs, providing valuable insights into potential issues early in the development process. The combination of Postman and Newman proved to be a powerful and efficient solution for API testing and automation.

Special thanks to the creators of Postman and Newman for providing powerful tools for API testing. Feel free to contribute, open issues, or provide feedback to make this project even better!
