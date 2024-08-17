This project is an implementation of the Contact Book application using React and Redux Toolkit. The main functionality of the application includes the ability to store, delete, and filter contacts. Contacts are stored on the backend created using the MockAPI service.

Features.
React and Redux Toolkit: The Redux Toolkit is used for state management, which makes it easier to work with global state and asynchronous operations.
Redux Thunk: CreateAsyncThunk is used to interact with the backend, which simplifies the process of executing asynchronous requests to the API.
CSS modules: Component styles are organized using CSS modules, which allows you to isolate the styles of each component and avoid name conflicts.
MockAPI: All contacts are stored and managed through a MockAPI-based backend. This makes it easy to test and extend the application's functionality.
State structure.
The following data is stored in the Redux state:

contacts: An array of contacts with additional properties for managing loading status and possible errors.
filters: An object to store the value of filtering contacts by name.

Commands to run
npm install: Install project dependencies.
npm run dev: Run the application in development mode.
npm run build: Build the project for production.
