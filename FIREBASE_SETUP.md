# Firebase Setup

This project uses Firebase (Auth + Firestore). The Firebase web config has been
replaced with placeholders. To run locally:

1. Create a Firebase project at https://console.firebase.google.com
2. Enable **Authentication** (Email/Password) and **Firestore Database**
3. Copy your web app config from Project Settings → Your apps
4. Replace the placeholder values (`YOUR_FIREBASE_API_KEY`, etc.) in the HTML/JS files
5. Set up Firestore Security Rules to protect your data
6. Add your domain under Authentication → Settings → Authorized domains

> Firebase web config keys are safe to expose client-side **only** when protected
> by proper Security Rules and domain restrictions.
