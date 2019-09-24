# FriendlyChat
A chat app use firebase that allows users to chat with friends in real-time and send texts and photo messages. Users can login with regilar email or with Google account.
## Prerequisites
Xcode 10.2+

Swift 5+

iOS 11.0+

Firebase

CocoaPads
## Installing
`git clone https://github.com/Xavierklop/FriendlyChat.git`
## Overview
The following features are provided by this app:

 1. Login by email/password or Google account.
 2. Send and receive texts or image.
 3. Tap a image message to see a larger version of a image. 
## Main View controllers
### FCViewController
Users can send and and receive texts or image in FCViewController. Users can tap a image message to see a larger version of a image.
## Technical features
- Use Firebase Realtime Database to storge text infomation.
- Use Firebase Authentication provide a way to use email/password and Google account sign-in.
- Use FirebaseUI implement email/password and Google account sign-in UI.
- Use Firebase Storage to storage image only if it is less than 3 MB.
- Use Firebase Analytics to automatically collects a handful of events of app.
## License
This code may be used free of cost for a non-commercial purpose, provided the intended usage is notified to the owner via the below email address.
Any questions, please email wuhaocll@gmail.com
