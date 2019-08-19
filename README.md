# Sample Minimum Repo to Reproduce Pusher Push Notifications Issue

So our company has used RNPusherPushNotifications for over a year in our RN app. This last week I started the upgrade to [RN 0.60.x](https://facebook.github.io/react-native/blog/2019/07/03/version-60) but I have been blocked by this package for the last couple days. Would really appreciate help.

So here are relevant portions of our app, you can look at the history of the app as well:

**package.json**
```
"dependencies": {
"react-native-pusher-push-notifications": "git+http://git@github.com/ZeptInc/react-native-pusher-push-notifications#v.2.4.1-zept-master",
}
```

But, when I try to build... **22 Errors break the builds**

![Aug-19-2019 16-50-15](https://user-images.githubusercontent.com/1245512/63304782-80ec3e00-c2a1-11e9-9cb9-72909522a76d.gif)


## Relevant Links
- https://github.com/b8ne/react-native-pusher-push-notifications
- https://github.com/pusher/push-notifications-swift
