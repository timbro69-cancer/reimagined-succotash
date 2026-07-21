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
## Getting Started

1. **Clone the repository** and install dependencies:
   ```bash
   npm install

### 4. Running the Emulators
Since your Firestore and Realtime Database configs have strict security rules, developers should test their code offline using the emulator suite.
```markdown
## Local Emulation
Test your database security rules locally before deploying:
```bash
firebase emulators:start

### 5. Deployment Workflow
Explain how code changes are promoted to production using your Git-integrated App Hosting backend.
```markdown
## Deployment & Rollouts
This repository is connected to Firebase App Hosting.
* **Development/Preview**: Open a Pull Request to trigger a temporary preview deploy.
* **Production**: Merging or pushing to the `production` (or `main`) branch automatically initiates a new rollout.
