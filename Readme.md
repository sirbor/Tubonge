# Tubonge

A Full Stack Chat Application using React and Firebase


## Features

- Group Chats
- Google Sign In
- Sending Images
- Profile Editing
- View Other Users Profile
- Show Unread Messages Count
- Edit / Delete Messages
- Light / Dark mode toggler

## Setup Firebase Project

- Create Firebase Project
- Enable Authentication ( Email and Google Auth )
- Enable Firestore DB and Storage
- Create Collections ( users, userChats, chats, globalChats )

## Installation Process

Step 1: Clone Repository and Install Packages.

```bash
  git clone https://github.com/sirbor/Tubonge  && cd Tubonge  && npm install
```

Step 2: Create firebaseConfig.ts file inside **src/setup/firebase** directory.

```bash
// firebaseConfig.ts
export const firebaseConfig = {
  apiKey: "",
  authDomain: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: "",
  measurementId: "",
};

```

Step 3: Start the development server.

```bash
  npm start
```

## Support

You can support this project by leaving a star, Thank you 😁

## Authors

- [@Sirbor](https://www.github.com/sirbor)
