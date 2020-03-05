# Angular State Management Host Into Firebase 

## Steps to follow to set up firebase 
1. Install firebase toolkit run "npm install -g firebase-tools"
2. Create the fire base project in the firebase https://console.firebase.google.com with the name "angular-state-management"
3. Run "firebase login" and complete the authentication
## Steps to follow to host angular project into firebase:
1. Clone the project
2. Run npm Install
3. open command prompt, run "firebase init"
   Here's the answers to the questions Firebase tools will ask:

    Are you ready to proceed? Yes
    Which Firebase CLI features? Hosting (In the future, use whatever you need! Press space to select.)
    Select a default Firebase project? angular-state-management (Choose whatever app you created in the earlier steps)
    What do you want to use as your public directory? dist/angular-state-management (This is important! Angular creates the dist folder.)
    Configure as a single-page app? Yes
4. npm run deploy (internally does ng build --prod && firebase deploy)
5. Open the mentioned hosted url in browser: https://angular-state-management.firebaseapp.com

For further reference please follow the following link:
https://scotch.io/tutorials/deploying-an-angular-cli-app-to-production-with-firebase

