# reimagined-succotash
Backend web application for the YTC Style Builder project, built with TypeScript and connected to Firestore and Firebase Authentication.
# YTC Style Builder Backend
This repository hosts the web application and backend configuration for the YTC Style Builder.
## Tech Stack
* **App Hosting**: Runs our Next.js/Angular frontend on serverless Cloud Run.
* **Authentication**: Firebase Identity Platform supporting Google Sign-In and Phone MFA.
* **Databases**: 
  * **Cloud Firestore**: Primary database for profiles, carts, and order history.
  * **Realtime Database**: Used for live inventory drops and real-time carts.
