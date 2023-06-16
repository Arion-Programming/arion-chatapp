## Example Deployed to Firebase
https://arion-chat-app.web.app/

## Starting
Run `npm install` to install all needed dependencies.
Create a Firebase project and get the config and post it to the `//config here` comment.
Create a firestore with a Table called message with following fields:
createdAt - Timestamp
uid - String
text - String
photoURL - String

run `firebase login` to log into firebase
run `firebase init` to initialze the projct
Then you can run `firebase deploy` to deploy code to the remote server

If you want to test your code locally run `npm start`
