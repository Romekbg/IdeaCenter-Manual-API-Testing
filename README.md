# IdeaCenter-Manual-API-Testing
This repository contains manual API testing for the SoftUni Idea Center, performed using Postman. The goal of this project is to validate various API endpoints for managing users, ideas, and authentication within the Idea Center.

## Project Overview

The Idea Center is a platform where users can create, update, and delete ideas. The project also supports user authentication, allowing registered users to interact with the system. Below are the APIs tested in this project:

- **Create User**: Allows the creation of new user accounts.
- **Get Authentication Token**: Retrieves an authentication token for user access.
- **Get All Ideas**: Fetches a list of all ideas in the system.
- **Create a New Idea**: Allows users to submit a new idea.
- **Update Idea**: Allows users to modify an existing idea.
- **Delete Idea**: Allows users to remove an idea from the system.
- **Supported Methods**: Retrieves all the supported methods of the API.

## Tested API Endpoints

The following endpoints were tested:
- `POST /api/User/Create`: Create a new user
- `POST /api/Auth/Token`: Get authentication token
- `GET /api/Idea`: Get all ideas
- `POST /api/Idea`: Create a new idea
- `PUT /api/Idea/{id}`: Update an existing idea
- `DELETE /api/Idea/{id}`: Delete an idea
- `GET /api/Info/Methods`: List supported methods

## Tools Used

- **Postman**: For creating and running API test cases.
- **GitHub**: For version control and repository management.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/IdeaCenter-API-Testing.git

2. Open Postman and import the collection from the repository.

3. Adjust the Postman environment settings, especially the base URL and the authorization token if required.

4. Run the test cases by selecting the "Idea Center" collection and clicking "Run".

## Test Scenarios
- Create User: Verified that new users can be created with valid details.
- Get Authentication Token: Checked that users can retrieve a valid authentication token.
- Get All Ideas: Validated that all ideas can be fetched without issues.
- Create New Idea: Ensured that users can submit a new idea.
- Update Idea: Confirmed that an existing idea can be updated with valid data.
- Delete Idea: Checked the ability to delete an idea from the system.
- Supported Methods: Tested retrieval of all supported API methods.
  
## Conclusion
The tests confirmed that the core functionalities of the Idea Center API work as expected, with successful responses for all valid requests.
