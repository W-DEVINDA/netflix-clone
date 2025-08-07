**Firebase Setup Guide for Netflix Clone**
Follow the steps below to set up Firebase for this project.

**Step 1: Create a Firebase Project**
Go to https://firebase.google.com and sign in with your Google account.
Click "Add Project".
Enter a project name:
netflix-clone
Click Continue.
Turn off Google Analytics (optional).
Click Create Project.

Once the project is created, click Continue to open the dashboard.

**Step 2: Enable Authentication**
In the Firebase Console, navigate to Build > Authentication.
Click Get Started.
Under Sign-in Method, enable the Email/Password option.
Click Save.

**Step 3: Set Up Firestore Database**
Go to Build > Firestore Database.
Click Create Database.
Choose your nearest location.
Click Next, select Start in test mode, then click Enable.

**Step 4: Register a Web App**
Go to the Project Overview in Firebase.
Click the Web icon (</>).
Enter an app nickname:
netflix-clone
Click Register App.
Copy the generated Firebase configuration.

**Step 5: Add Firebase Configuration to the Project**
Open the project in VS Code or your preferred code editor.
Navigate to the firebase.js file.
Replace the existing config object with the configuration you copied from Firebase.
Save the file.

**Step 6: Run the Project**
In the terminal, run the following commands:

npm install
npm run dev


