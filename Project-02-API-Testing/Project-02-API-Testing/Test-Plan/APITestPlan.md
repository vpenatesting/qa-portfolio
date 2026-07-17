# API Test Plan - JSONPlaceholder REST API

## Project Overview

This project focuses on testing REST API functionality using Postman. The purpose of testing is to verify API requests, validate responses, and ensure endpoints return expected results.

## Application Under Test

API Name:
JSONPlaceholder

Base URL:
https://jsonplaceholder.typicode.com

## Testing Objective

The objective of this API testing project is to verify that API endpoints perform correctly and return accurate responses.

## Scope of Testing

The following API methods will be tested:

- GET
- POST
- PUT
- DELETE

## Testing Types

- Functional API Testing
- Response Validation Testing
- Status Code Testing
- Data Validation Testing

## Test Environment

Tool:
Postman

Browser:
Google Chrome

Operating System:
macOS

## API Endpoints

### GET
Retrieve existing resources.

Example:
GET /posts/1

### POST
Create a new resource.

Example:
POST /posts

### PUT
Update an existing resource.

Example:
PUT /posts/1

### DELETE
Delete a resource.

Example:
DELETE /posts/1

## Expected Results

- API requests should return expected HTTP status codes.
- Response data should match expected format.
- Required fields should be present.
- Error responses should be handled correctly.

## Entry Criteria

Testing begins when:

- API endpoints are available.
- Postman environment is ready.

## Exit Criteria

Testing is completed when:

- All planned API test cases are executed.
- Results are documented.
- Test summary report is completed.

## Defect Reporting

Any issues found will be documented with:

- Defect ID
- API Endpoint
- Request Method
- Steps to Reproduce
- Expected Response
- Actual Response
- Severity
- Status
