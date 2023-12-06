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
- Postman
- Newman

## Key Steps and Activities:
- API Endpoint Identification
- Postman Collection Creation
- Environment Setup
- Data-Driven Testing
- Authorization Testing
- Automation with Newman
- Report Generation

## How to Run
#### 1. Clone the repository to your local machine:

```http
  git clone https://github.com/your-username/API_Testing_RestfulBooker_Postman_and_report_generate_using_Newman.git
```
#### 2. Import the collection and environment files into Postman.

```http
  npm install
```

#### 3.Open a terminal in the project directory and install the required dependencies:

#### 4.Get item

```http
  npm test
```
This command executes the tests and generates an HTML report in the reports/ directory.

## Viewing Reports
After running the tests, navigate to the reports/ directory and open the generated HTML report in a web browser for a detailed overview of test results.

## Acknowledgments
This API testing project successfully ensured the reliability and performance of the web application's APIs, providing valuable insights into potential issues early in the development process. The combination of Postman and Newman proved to be a powerful and efficient solution for API testing and automation.

Special thanks to the creators of Postman and Newman for providing powerful tools for API testing. Feel free to contribute, open issues, or provide feedback to make this project even better!
