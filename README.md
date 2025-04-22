# Pupparazzi Workshop

This workshop involved building a server-side API for a puppy management application using Express and promises. Below is a summary of the learning objectives, tasks completed, and features implemented.

## Learning Objectives

- Understand and utilize the Express router.
- Practice using promises for asynchronous operations.

## Completed Tasks and Features

### Setup

- Cloned the repository and navigated to the directory.
- Installed dependencies and started the development server with `npm run dev`.

### Core Features Implemented

1. **Listing All Puppies**
   - Implemented a `GET /api/v1/puppies/` route to fetch and display a list of all puppies.
   - Utilized the Express router to organize puppy-related routes.
   - Leveraged the `store.getPuppies()` function to retrieve puppy data from `storage/data.json`.

2. **Displaying a Detailed Single Puppy Page**
   - Developed a `GET /api/v1/puppies/:id` route to fetch details of a specific puppy based on its unique ID.
   - Implemented logic to handle path parameters and return detailed information for each puppy.
   - Ensured proper error handling for cases where a puppy ID does not exist.

3. **Updating a Puppy**
   - Created a `PATCH /api/v1/puppies/:id` route to update a puppy's name, breed, and owner.
   - Implemented the `store.updatePuppy()` function to modify puppy data and persist changes to `storage/data.json`.
   - Ensured that updates are reflected in the application, even after restarting the server.

### Stretch Goals Achieved

4. **Adding a New Puppy**
   - Developed a React component and client-side route to display a form for adding new puppies.
   - Implemented the backend logic to handle puppy creation and update the data store accordingly.

5. **Adding a New Animal**
   - Extended the application to support the addition of new animal types, such as cats or iguanas.
   - Considered user experience and updated the app to accommodate different animal types.

### Testing and Quality Assurance

- Conducted end-to-end testing using Playwright to ensure all routes and functionalities perform as expected.
- Implemented comprehensive error handling and validation for all API routes.
- Ensured code quality and consistency through linting and adherence to best practices.

## Conclusion

This workshop provided hands-on experience with building a RESTful API using Express and managing asynchronous operations with promises. By completing this project, I reinforced my understanding of server-side development and data management in a Node.js environment.
