# Production-ready-react-app
This project focuses on building an efficient single-page application (SPA) using React, Firebase cloud and authentication, and the Context API.

## Features

- **Efficient SPA**: designed as a single-page application, providing a smooth and seamless user experience.
- **Firebase Integration**: The project utilizes Firebase for cloud storage and authentication, enabling secure and scalable data management.
- **Context API**: The Context API is utilized to manage state and provide global data accessibility across components.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/MaansiBisht/Production-ready-react-app.git
```
2. Navigate to the project directory and install the dependencies:

  ```bash
  cd [project_directory]
  npm install

``` 
3. Set up Firebase configuration:

    Create a Firebase project on the Firebase Console.
    Copy the Firebase configuration object.
    Paste the configuration into the .env file in the root directory of the project
```bash
  REACT_APP_FIREBASE_API_KEY=YOUR_API_KEY
  REACT_APP_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
  REACT_APP_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
  REACT_APP_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
  REACT_APP_FIREBASE_MESSAGING_SENDER_ID=YOUR_SENDER_ID
  REACT_APP_FIREBASE_APP_ID=YOUR_APP_ID
```
4. Start the development server:
```bash
 npm start
```
Open the application in your browser at http://localhost:3000.

## Screenshots

![Screenshot 1](https://github.com/MaansiBisht/Production-ready-react-app/blob/master/screenshots/Screenshot1.png)
 gallery view that allows users to browse and view multiple images in a visually appealing manner. This gallery view enhances the user experience by providing an immersive and intuitive way to explore images.

![Screenshot 2](https://github.com/MaansiBisht/Production-ready-react-app/blob/master/screenshots/Screenshot2.png)
This screenshot captures a relevant part of the application where an image upload form is displayed, allowing users to select an image file from their local machine and upload it to Firebase Cloud Storage. The uploaded image is then displayed on the website, demonstrating successful integration with Firebase Cloud Storage for image storage and retrieval of information from image buckets.

![Screenshot 3](https://github.com/MaansiBisht/Production-ready-react-app/blob/master/screenshots/Screenshot3.png)
The screenshot highlights the authentication flow using Firebase Authentication. It demonstrates the user interface where users can sign in with their Google accounts


   
