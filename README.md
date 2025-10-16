**Overview:**
This repository contains Postman collections and environments for API testing. It demonstrates automated testing of APIs using all standard HTTP methods, variable handling, dynamic request body generation, JSON parsing, and Chai assertions, including intentional failing test cases.

**Features:**
1. **API Methods Used:** GET, POST, PUT, PATCH, DELETE  
2. **Base URL as Variable:** All requests use environment variables for base URL.  
3. **Dynamic Request Body Generation:** Randomized data is generated using pre-request scripts.  
4. **JSON Parsing and Logging:** Responses are parsed and key values are logged in the console.  
5. **Chai Assertions:** Validations include both passing and failing test cases.  
6. **Pre-request and Post-response Scripts:** Pre-request and Post-response Scripts are used for variable handling.
7. **API Chaining:** Response data from one request is used in subsequent requests.

**File Structure:**
a. **Collections/:** Contains all exported Postman collections ('.json' files).  
b. **Environments/:** Contains all exported Postman environments ('.json' files).  

**Instructions for Running:**
1. Download the repository.  
2. Open Postman.  
3. Import the desired collection from the 'Collections/' folder.  
4. Import the corresponding environment from the 'Environments/' folder.  
5. Select the environment from the environment dropdown.  
6. Run the collection to see all tests executed, including passing and failing cases.

**Notes:**
a. Each collection has its own environment variables. Make sure to select the correct environment before running a collection.  
b. Dynamic data generation ensures unique test cases on every run.
