# Getting ready for App Store

##  Test Flight:
  
  a. docs -  https://developer.apple.com/testflight/ 
  
  b. download - https://apps.apple.com/us/app/testflight/id899247664

## Protocol

You can't have multiple apps with the same app id. Google Play Store allows multiple apps to have same app name as long as they have a different app id. 

iOS requires both app id and app name (but not display name) to be unique from other apps in the store.

If a desired name isn't available, this can be solved  by adding a bit of description to the name, making it unique, e.g. "ReadApp  - Social Engagement and Hospitality", "ReadApp  - Lounge" when "ReadApp" isn't available.


```

Until recently there was a significant name-squatting problem, with devs creating 
placeholder apps that tied up names indefinitely. Apple cleared all of those out last Fall,
making a large number of names available again. Now an app created in iTunes Connect 
but not submitted for review will receive a warning after 150 days and if there's still no
submission 30 days later, the placeholder is deleted and the name is freed up to other 
developers (as per the policy you quote). Significantly, that specific name is no longer 
available to the developer that first used it, so be certain you're going to submit 
soon after creating the app in ITC.

=> xCode

=> AppStore Connect. Create a listing for:
i. Title

ii. Description

iii. Screen shots

=> Back to xCode

i. Create archive of the App

=> Submit to App Store Comnnect

i. Reveal the archive to the listing information

=> Submit to App Certification Team. Checks on guidelines, best practices, tresholds, no restricted content

=> Greeen light - If guideline are met, app  released in 24 hours or ASAP.

```



## Create iOS Developer Account and Apple Account:
ii. Setting up Developer Account (ID):    https://www.youtube.com/watch?v=OtErU9Um3DE  


iii. Setting up Apple Account : Keychain and  certificate - https://www.youtube.com/watch?v=OwXIJchrDdA  


## Submitting to App Store

This is a three stage process:



### Provisioning Profile

```
a. Identity

b. Permissions

```

Each App has to be tied back to:

- A known Developer

- Installed on a known device

- Have right permissions for sytems and services


### App Store Connect

 - https://developer.apple.com/support/app-store-connect/#//apple_ref/doc/uid/TP40011225-CH13-SW20

This is the website where you submit and manage your app in the App Store. In App Sore conect, you can manage your listings where you can:

- Check on Analytics

- Sales

- Financial reports

- Banking information on payment

### xCode

Ones you finish building and testing your app in xCode, you create an archive of the app. This is a bundle or package that contains your code and other dependency resources you submit to the App Connect Website.

### Apple Developer Programme ($99)

Gives access to the App Store Connect Website.


