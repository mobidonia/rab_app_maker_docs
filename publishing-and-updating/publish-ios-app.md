# Publish iOS App

#### [Building your iPhone app. ](https://mobidonia.support-hub.io/articles/publish-ios-app#building-your-iphone-app) <a id="building-your-iphone-app"></a>

Soon as you have your app.json file in place and you have installer expo cli, you are able to proceed with making your iPhone app. 

But first, you will need to have iOS Developer Account.  This will cost you 99$ / year. You pay directly to Apple. 

You can register [iOS Developer Account here](https://developer.apple.com/programs/enroll/).

To make your iPhone app run 

```text
expo bi --no-publish
```

The console will ask you for your username/password.

[Here are docs by Expo](https://docs.expo.io/versions/latest/distribution/building-standalone-apps/#if-you-choose-to-build-for-ios).

Follow the onscreen instruction. 

In the end, an IPA file will be produced. This is the app file you will be able to upload on App Store Connect.

#### [Publishing app on App Store Connect](https://mobidonia.support-hub.io/articles/publish-ios-app#publishing-app-on-app-store-connect) <a id="publishing-app-on-app-store-connect"></a>

In the previous step, you have produced the IPA file. This file needs to be uploaded on App Store Connect. 

There is one problem. You will need a MAC computer in order to submit the ipa file. 

**Option 1- You own a MAC computer**

Great, then all you have to do is run the following command

```text
expo ui
```

Then expo will upload your ipa in Test Flight. And from there you can publish your app,

**Option 2 - I don't own a MAC computer.** 

Then we will suggest this. 

[https://www.macincloud.com/](https://www.macincloud.com/)

You will be able to run a mac in remote, for low as 1$/hour. 

Then you can either use application called "Application Loader" to upload your IPA or run the command

```text
expo ui
```

Then expo will upload your ipa in Test Flight. And from there you can publish your app.

