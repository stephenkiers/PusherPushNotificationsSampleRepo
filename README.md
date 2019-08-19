# Sample Minimum Repo to Reproduce Pusher Push Notifications Issue

So our company has used RNPusherPushNotifications for over a year in our RN app. This last week I started the upgrade to [RN 0.60.x](https://facebook.github.io/react-native/blog/2019/07/03/version-60) but I have been blocked by this package for the last couple days. Would really appreciate help.

So here are relevant portions of our app, you can look at the history of the app as well:

**package.json**
```
"dependencies": {
"react-native-pusher-push-notifications": "git+http://git@github.com/ZeptInc/react-native-pusher-push-notifications#v.2.4.1-zept-master",
}
```

But, when I try to build...
**22 Errors break the builds**
![Aug-16-2019 14-56-18-2](https://user-images.githubusercontent.com/1245512/63197804-08ce1000-c036-11e9-823b-dc11a140b683.gif)
