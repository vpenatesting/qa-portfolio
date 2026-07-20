# API Test Cases - JSONPlaceholder

## Test Case 1: Verify GET Request Retrieves Post

**Test Case ID:** API_TC001

**Test Scenario:**
Verify that the GET API retrieves a single post successfully.

**Request Method:**
GET

**Endpoint:**
https://jsonplaceholder.typicode.com/posts/1

**Expected Result:**
- Response status code should be 200.
- Response should contain post information.
- Response should include userId, id, title, and body fields.

**Actual Result:**
API returned status code 200 OK.
Response contained userId, id, title, and body fields.

**Status:**
Pass



## Test Case 2: Verify POST Request Creates a New Post

**Test Case ID:** API_TC002

**Test Scenario:**
Verify that a POST request successfully creates a new resource.

**Request Method:**
POST

**Endpoint:**
https://jsonplaceholder.typicode.com/posts

**Request Body:**
{
  "title": "QA Portfolio Test",
  "body": "Testing POST request using Postman",
  "userId": 1
}

**Expected Result:**
- Response status code should be 201 Created.
- Response should include the submitted data.
- Response should include a newly assigned id.

**Actual Result:**
The API returned status code 201 Created. The response contained the submitted data along with a generated id.

**Status:**
Pass





## Test Case 3: Verify PUT Request Updates an Existing Post

**Test Case ID:** API_TC003

**Test Scenario:**
Verify that a PUT request updates an existing resource.

**Request Method:**
PUT

**Endpoint:**
https://jsonplaceholder.typicode.com/posts/1

**Expected Result:**
- Response status code should be 200 OK.
- Response should contain the updated title and body.

**Actual Result:**
The API returned status code 200 OK. The response contained the updated title and body values.

**Status:**
Pass



## Test Case 4: Verify DELETE Request Removes a Post

**Test Case ID:** API_TC004

**Test Scenario:**
Verify that a DELETE request successfully removes a resource.

**Request Method:**
DELETE

**Endpoint:**
https://jsonplaceholder.typicode.com/posts/1

**Expected Result:**
- Response status code should indicate a successful delete (200 OK or 204 No Content).

**Actual Result:**
The API returned a successful response indicating the delete request was processed.

**Status:**
Pass
