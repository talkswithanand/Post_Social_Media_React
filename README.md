
![Screenshot (16)](https://github.com/user-attachments/assets/369813f7-0cda-4936-a97a-dab28743b4ff)
![Screenshot (15)](https://github.com/user-attachments/assets/26880663-b6e1-49e4-aa67-d1dfed8e2111)
![Screenshot (14)](https://github.com/user-attachments/assets/d9a09163-5e5c-4d6b-a3c1-e2e7a47733f9)
![Screenshot (13)](https://github.com/user-attachments/assets/4e3e3940-53d7-4736-b403-85251a0fce53)
![Screenshot (12)](https://github.com/user-attachments/assets/f8d442ec-ace7-4da3-8bfe-c83eb0f27944)



Project Description
This project is a simple React-based web application that allows users to create and manage posts. Users can enter their user ID, post title, content, number of reactions, and tags for their posts. The application features a sidebar for navigation between the home page (where posts are displayed) and the create post page. The posts are managed using React's Context API and the useReducer hook, providing a scalable way to handle state management for the list of posts.

Key Features
Create Post: Users can submit new posts with various details.
Display Posts: The home page displays a list of posts with their details.
Sidebar Navigation: Users can switch between the home page and the create post page.
State Management: Utilizes React's Context API and useReducer for efficient state management of posts.
Technologies Used
React: The core library for building the user interface.
JavaScript (ES6): For writing the application logic.
HTML/CSS: For structuring and styling the application.
Bootstrap: For responsive design and ready-to-use components.
React Context API: For managing global state across components.
React Hooks: Specifically useState and useReducer for handling component state and side effects.
Folder Structure
components/: Contains reusable components like Header, Footer, Sidebar, CreatePost, and PostList.
store/: Contains the post-list-store.js for managing post-related state using Context API and Reducer.
App.jsx: The main application component that ties everything together.
index.js: Entry point for rendering the application.
Styling
App.css: Contains custom styles for the application layout and components.
Bootstrap CSS: Integrated for consistent styling and responsive design.
Conclusion
This project serves as a foundational example of how to build a simple post management application using React. It demonstrates effective state management with the Context API and provides a clean, user-friendly interface with Bootstrap. This can be further extended with features like editing posts, deleting posts, or integrating a backend for persistent storage.

