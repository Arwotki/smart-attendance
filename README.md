# Smart Attendance Web App Documentation

## Features
- User authentication through Firebase
- Real-time attendance tracking
- Notification system for absent students
- Comprehensive dashboard for teachers

## Quick Start
1. Clone the repository:  
   `git clone https://github.com/Arwotki/smart-attendance.git`
2. Navigate to the project directory:  
   `cd smart-attendance`
3. Install the dependencies:  
   `npm install`
4. Start the application:  
   `npm start`

## Usage Instructions
- To log in, use your Google account.  
- For attendance tracking, navigate to the attendance page and select the relevant class.
- To view notifications, check the alerts section in the dashboard.

## Project Structure
```
smart-attendance/
├── public/
│   ├── index.html
│   └── styles.css
├── src/
│   ├── App.js
│   ├── components/
│   └── services/
├── .env
├── package.json
└── README.md
```

## Firebase Setup
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Authentication and Firestore Database.
3. Replace the `.env` file with your Firebase credentials:
   ```
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

## Deployment Guides
- Deploy using Firebase Hosting:
  1. Install Firebase CLI:  
     `npm install -g firebase-tools`
  2. Login to Firebase:  
     `firebase login`
  3. Initialize your project:  
     `firebase init`
  4. Deploy:  
     `firebase deploy`

## Troubleshooting
- If you experience issues with Firebase setup, ensure that your configuration in the `.env` file is correct.
- For dependency issues, try running `npm install` again or check for version mismatches in `package.json`.  
- For more detailed debugging, check the console output for errors and consult relevant logs.
