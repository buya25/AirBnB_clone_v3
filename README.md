# AirBnB Clone v3

## Project Overview

Welcome to AirBnB Clone v3! This project is a continuation of the previous version (v2) and focuses on enhancing the existing codebase. The goal is to make improvements, add new features, and ensure the stability of the application. The project includes tasks related to testing, storage optimization, API development, and the implementation of various views for different objects.

## Project Setup

### Fork and Clone

To get started, fork the [AirBnB_clone_v2](https://github.com/your-username/AirBnB_clone_v2) repository. Then, clone your fork to your local machine:

```bash
git clone https://github.com/your-username/AirBnB_clone_v2.git
cd AirBnB_clone_v2
```

### Update Repository Name

Rename the repository to "AirBnB_clone_v3" to reflect the ongoing improvements and changes.

```bash
git remote rename origin upstream
git remote add origin https://github.com/your-username/AirBnB_clone_v3.git
```

## Task 0: Restart from Scratch

**Important:** Although the task suggests starting from scratch, it's clarified that restarting everything is not required. Instead, focus on a new codebase while maintaining the progress made in the previous version.

## Task 1: Never Fail!

Ensure the reliability of the codebase by implementing and maintaining unit tests. Make sure to follow the guidelines provided for running tests and validating their success.

## Task 2: Improve Storage

Optimize the storage system by adding two new methods (`get` and `count`). These methods should enhance the retrieval and counting of objects, and corresponding tests should be added to validate their functionality.

## Task 3: Status of your API

Start building the API by creating the first endpoint that returns the status of the API. This involves setting up Flask and creating a simple route to check the status.

## Task 4: Some Stats?

Implement an endpoint that retrieves the number of each object type. This task involves using the newly added `count()` method in storage and creating a route to expose the statistics.

## Task 5: Not Found

Design a JSON-formatted 404 error response for endpoints that are not found. This enhances the user experience by providing clear error messages in a structured format.

## Task 6-11: Object Views

Create views for different objects (State, City, Amenity, User, Place, Reviews) that handle various RESTful API actions such as retrieval, creation, updating, and deletion. Ensure that the views use the `to_dict()` method for serialization and follow the specified requirements for each object type.

## Task 12: HTTP Access Control (CORS)

Implement Cross-Origin Resource Sharing (CORS) using the `flask_cors` module to allow web clients to make requests to the API. This is crucial for proper communication between the API and web clients.

## Author

- Yabs Mullo

## Contribution

Feel free to contribute to this project by forking the repository, making improvements, and creating pull requests. Let's collaborate to make AirBnB Clone v3 even better!
