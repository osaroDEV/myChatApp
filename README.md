# Chat App using React Native Expo & Firebase

## How to Clone

Clone the repo
```
git clone https://github.com/osaroDEV/myChatApp.git
```

cd into the just created project and install dependencies with yarn
```
cd ChatApp && yarn
```

Add your firebase backend config in the `firebase.js` file
```
const firebaseConfig = {
  apiKey: Constants.manifest.extra.apiKey,
  authDomain: Constants.manifest.extra.authDomain,
  projectId: Constants.manifest.extra.projectId,
  storageBucket: Constants.manifest.extra.storageBucket,
  messagingSenderId: Constants.manifest.extra.messagingSenderId,
  appId: Constants.manifest.extra.appId,
  databaseURL: Constants.manifest.extra.databaseURL
};
```

Run the project
```
expo start
```
