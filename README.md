# Griffin React Native Starter Template

Bootstrap your app development by using this awesome react native starter kit, integrated with Firebase Auth and Facebook Login. Clone this boilerplate app to get you up and running quickly.

## Fully working features

- Login with Facebook
- Sign in with Google
- User Management with Firebase Auth
- Firebase Firestore Integration
- Email/Password Registration
- Persistent Login Credentials (a.k.a Remember password)
- Logout Functionality


## Google signin

- when signing in with google on android and you get "developer_error google sign in".
- take the following steps:

      	* in the command line, enter:
      		keytool -exportcert -list -v -alias androiddebugkey -keystore ~/.android/debug.keystore

      	*  when prompted for password, enter:
      		android

      	* you should successfully generate some keys.
      	* copy the "SHA1:" key
      	* visit firestore console in your browser
      	* under settings>>Project settings select "RN Starter Kit Android"
      	* click "add fingerprint"
      	* paste the copied "SHA1:" key

      	* then rebuild app


