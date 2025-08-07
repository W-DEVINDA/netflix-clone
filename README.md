# Firebase Setup Guide for Netflix Clone

Follow the steps below to set up Firebase for this project.

---

## Step 1: Create a Firebase Project

1. Go to [https://firebase.google.com](https://firebase.google.com) and sign in with your Google account.  
2. Click **"Add Project"**.  
3. Enter a project name:  
   `netflix-clone`  
4. Click **Continue**.  
5. Turn off **Google Analytics** (optional).  
6. Click **Create Project**.  
7. Once the project is created, click **Continue** to open the dashboard.

---

## Step 2: Enable Authentication

1. In the Firebase Console, navigate to **Build > Authentication**.  
2. Click **Get Started**.  
3. Under **Sign-in Method**, enable the **Email/Password** option.  
4. Click **Save**.

---

## Step 3: Set Up Firestore Database

1. Go to **Build > Firestore Database**.  
2. Click **Create Database**.  
3. Choose your nearest location.  
4. Click **Next**, select **Start in test mode**, then click **Enable**.

---

## Step 4: Register a Web App

1. Go to the **Project Overview** in Firebase.  
2. Click the **Web** icon (`</>`).  
3. Enter an app nickname:  
   `netflix-clone`  
4. Click **Register App**.  
5. Copy the generated **Firebase configuration**.

---

## Step 5: Add Firebase Configuration to the Project

1. Open the project in **VS Code** or your preferred code editor.  
2. Navigate to the `firebase.js` file.  
3. Replace the existing config object with the configuration you copied from Firebase.  
4. Save the file.

---

## Step 6: Run the Project

In your terminal, run the following commands:


npm install
npm run dev
