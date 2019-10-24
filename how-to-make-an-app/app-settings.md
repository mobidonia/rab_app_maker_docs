# App Settings

By clicking on the **App settings**, will bring you to your App settings and there you have options to preview the individual settings you want. Click on the sub menu below and change the option you want.

### [Logins](https://mobidonia.support-hub.io/articles/app-settings#spanloginsspan)

From here you can manage and change all Login settings.

Login settings include this options \[Facebook, FacebookLogin, GoogleAndroidId, GoogleIOSid, GoogleLogin, WelcomeText\]

**Set up facebook login**

First, you should make your facebook app id.  


- [https://developers.facebook.com/apps](https://developers.facebook.com/apps) create your facebook app.

- When the app is created then go to settings and scroll to the bottom, now you will see **add platform** button. Just add iOS and Android.

- For iOS in the BundleID just add **host.exp.Exponent**, look at the picture below.

![](../.gitbook/assets/obsb8yc0zqxbivbvinlcntb55r8poajxa9cmmukh.png)

- For Android in the Key Hashes just add **rRW++LUjmZZ+58EbN5DVhGAnkX4=** , look at the picture below.

![](../.gitbook/assets/okwaoj58by3kbf7ayydhecv8z0bycixhb3jn7pbw.png)

- On the top of [https://developers.facebook.com/apps](https://developers.facebook.com/apps) you should see your **APP ID**, copy the id and set it to the facebookID field in your React App Builder.

**Set up Google login**

First, you should make your google ids.  


* Get an app set up on the [Google Developer Console](https://console.developers.google.com/apis/credentials?pli=1)
* Go to the Credentials Page
* Create an app for your project if you haven't already. 
* Once that's done, click "Create Credentials" and then "OAuth client ID." You will be prompted to set the product name on the consent screen, go ahead and do that. 

Create an iOS OAuth Client ID

* Select "iOS Application" as the Application Type. Give it a name if you want \(e.g. "iOS Development"\). 
* Use host.exp.exponent as the bundle identifier. 
* Click "Create" 
* You will now see a modal with the client ID.

Create an Android OAuth Client ID

* Select "Android Application" as the Application Type. Give it a name if you want \(maybe "Android Development"\). 
* Run openssl rand -base64 32 \| openssl sha1 -c in your terminal, it will output a string that looks like A1:B2:C3 but longer. Copy the output to your clipboard. 
* Paste the output from the previous step into the "Signing-certificate fingerprint" text field. 
* Use host.exp.exponent as the "Package name". 
* Click "Create" 
* You will now see a modal with the Client ID. 

And \* Now you have googleIOSId and googleAndroidID set them to your React App Builder in the fields named  googleIOSId and googleAndroidID.

![](../.gitbook/assets/v6fk5inaa2ikn0skgcabrsao5b4cjeeldsj76ao9.png)

### [Orders](https://mobidonia.support-hub.io/articles/app-settings#orders)

From here you can manage and change all Order settings.

Order settings include this options \[SendEmailOnOrder, SendToEmail\]

![](../.gitbook/assets/gjnuq1ewxcdtvzddg5vtyfya7twpttzizjirb8ei.png)

### [Ads](https://mobidonia.support-hub.io/articles/app-settings#ads)

From here you can manage and change all Add settings.

Ads settings include this options \[BannerID, InterstitialID, IsTesting, ShowBannerAds, ShowinterstitialAds\]

On this [link](https://admob.google.com/home/) you can create your banner and interstitial ads. When you will have the ids please set them to the BannerId and InterstitialId.

![](../.gitbook/assets/ndalbtsj79jxf9g75gs8scm7cqe9rv6e8wcltzqt.png)

### [PayPal](https://mobidonia.support-hub.io/articles/app-settings#paypal)

From here you can manage and change all PayPal payment settings.

PayPal payment settings include this options \[AcceptPayments, Cancel url, City, Clientid, Country code, Currency, IncludeShippingInfo, Postal code, Return url, SandBoxMode, SecretKey, State\]

**Create a Paypal account**

On this [link](https://developer.paypal.com/developer/accounts/) to create your PayPal account. And there create **Paypal Merchant Account.** After creating the account you should set up the fields in your React App Builder.

![](../.gitbook/assets/9crxtxhp4q7wdwzb4jbrce9qpujmikaf9bum8g1f.png)

