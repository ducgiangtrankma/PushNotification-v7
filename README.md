/*  Config - Flow https://rnfirebase.io/messaging/usage */

1. yarn add @react-native-firebase/messaging
2. yarn add react-native-push-notification : in v6,7 not support local push notify. So you need install react-native-push-notification
3. yarn add @react-native-community/push-notification-ios
4. cd ios/  run pod install
5. flow ios Permissions
6. Config IOS flow : https://github.com/react-native-community/push-notification-ios
7. Config FCMService.js, LocalNotificationService.js and index.js
8. Config IOS : https://rnfirebase.io/messaging/usage/ios-setup#linking-apns-with-fcm
-------------------------------------------------------------------------------------
Note : IOS not working because Linking APNs with FCM required Apple dev account.