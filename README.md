# Aries Invitation Service

## Android Intents

Android Intents work on all the mobile browsers, some browsers will automatically prompt the user instead of requiring a button click on the website (which is preferred):

- [ ] Android Chrome (if only one app is installed matching the scheme or if a specific package/app is defined, Android Chrome will prompt the user)
- [x] Firefox
- [ ] Opera
- [x] Edge

## iOS Universal Links

### Notes:

If the user clicks the link and the app is not installed, the user will be directed to the website, not the app. This likely indicates the app owner should host a webpage providing instructions to install their app.

Will need to handle the case where the browser displays a banner if a user is just on the website and a user clicks on it--this likely should result in a "invite invalid" display or something of that nature.
