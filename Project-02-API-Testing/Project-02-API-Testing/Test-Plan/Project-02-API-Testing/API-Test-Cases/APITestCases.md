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
