A real-time collaborative bucket list app for couples to track and achieve their dreams together.

Features

Real-time Sync: Changes appear instantly across all devices using Firebase
Dual Contributors: Track who added each goal (Storm or Greyton)
Goal Tracking: Mark goals as completed and see achievement dates
Edit & Delete: Modify or remove goals anytime
Progress Stats: View completion percentage and individual contributions
Dark Purple Theme: Stylish purple and black aesthetic

Technologies Used

HTML5
CSS3 (Gradients, Animations, Flexbox)
Vanilla JavaScript
Firebase Firestore (Real-time Database)

Setup Instructions
Prerequisites

A Firebase account (free)
A web browser
Basic knowledge of HTML/CSS/JS

Installation

Clone the repository

bash   git clone https://github.com/yourusername/storm-greyton-bucketlist.git
   cd storm-greyton-bucketlist

Set up Firebase

Go to Firebase Console
Create a new project or use existing one
Enable Firestore Database (start in test mode)
Copy your Firebase config


Update Firebase Config

Open index.html
Replace the firebaseConfig object with your own config (lines 400-407)


Deploy

Upload to GitHub Pages, Netlify, or Vercel
Or simply open index.html in your browser for local testing

How to Use

Select who's adding the goal (Storm or Greyton)
Type your dream/goal in the input field
Click "Add Goal" or press Enter
Check off goals when you achieve them together!
Edit or delete goals using the action buttons

Customization
Want to personalize it? Here's what you can change:

Names: Search for "Storm" and "Greyton" in the code and replace with your names
Colors: Modify the CSS color variables (purple theme is #b366ff)
Firebase Collection: Change 'goals' to whatever collection name you prefer

Mobile Friendly
Fully responsive design works great on phones, tablets, and desktops!
Security Note
Currently using Firebase test mode for easy development. For production:

Go to Firebase Console → Firestore Database → Rules
Update security rules to restrict access

Contributing
This is a personal project, but feel free to fork it and make it your own!
License
Free to use and modify for personal projects.
Built With Love
Created by Greyton Dixon as a beginner web development project.
