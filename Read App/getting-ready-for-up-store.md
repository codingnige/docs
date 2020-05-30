# Getting ready for App Store


## Details for Apple Developer Program 


Provisional Name (before 31st of August): ReadApp Lounge

Legal entity name: Bearings Point Media 

Apple ID: [x]

Username: [x]

Headquarters address: ****

Mailing address: ****

Your work contact information: 

Apple Support:  eurodev@apple.com  

Apple Support Contact:  Cillian

D-U-N-S Numbers( https://developer.apple.com/support/D-U-N-S/):

##  Test Flight:
  
  a. docs -  https://developer.apple.com/testflight/ 
  
  b. download - https://apps.apple.com/us/app/testflight/id899247664
  
 #### [Connecting to Test Flight]

## Protocol

You can't have multiple apps with the same app id. Google Play Store allows multiple apps to have same app name as long as they have a different app id. 

iOS requires both app id and app name (but not display name) to be unique from other apps in the store.

If a desired name isn't available, this can be solved  by adding a bit of description to the name, making it unique, e.g. "ReadApp  - Social Engagement and Hospitality", "ReadApp  - Lounge" when "ReadApp" isn't available.


```

Until recently there was a significant name-squatting problem, with devs creating 
placeholder apps that tied up names indefinitely. Apple has  cleared all this mess,
making a large number of names available again. 

Now an app created in iTunes Connect but not submitted for review will receive a warning
after 150 days and if there's still no submission 30 days later, 
the placeholder is deleted and the name is freed up to other developers 
(as per the policy you quote). Significantly, that specific name is no longer 
available to the developer that first used it.

So be certain you're going to submit soon after creating the app in ITC.

```

### Process

- xCode (Code)

- AppStore Connect. Create a listing for:

i. Title

ii. Description

iii. Screen shots

- Back to xCode

i. Create archive of the App

- Submit to App Store Connect

i. Reveal the archive to the listing information

ii. Submit to App Certification Team. Checks on guidelines, best practices, tresholds, no restricted content

- Response: (Greeen light) - If guideline are met, app  released in 24 hours or ASAP.


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

### Apple Developer Programme 

Sign up to ADP

Connecting to  the App Store Connect Website -  $99.

1. 
https://idmsa.apple.com/IDMSWebAuth/signin.html?path=%2Fcontact%2F&appIdKey=891bd3417a7776362562d2197f89480a8547b108fd934911bcbea0110d07f757

2. ACCOUNT
https://developer.apple.com/account/#/welcome 

3. Join Apple Developer Program
https://developer.apple.com/programs/  

4. Enrol
https://developer.apple.com/programs/enroll/ 

5. Begin enrolement - https://developer.apple.com/enroll/identity/edit

6. Programs - https://developer.apple.com/programs/

7. Test Flight - https://developer.apple.com/testflight/

| Team  | Bundle Identifier  | Provisioning Profile | Signing Certificate |
| :---:   | :-: | :-: | :-: |
| Busola Sodeinde | ??? | Xcode Managed Profile | iPhone Developer : Busola Sodeinde |


2. In Xcode, preference menu confirm Apple ID:


| Apple ID  | Description  | Team | Role |
| :---:   | :-: | :-: | :-: |
| ????| ??? | Busola Sodeinde  | agent |


- Dashboaard Manual Profiles

- Manage Certificates  

3. In Xcode

Project => Signing & Capabiiities: copy to memory value of 'Bundle Identifier'

4. Back to ADP(Be registered - $99) => Certificate/Identifier/Profiles

5. In Identifier:

i. click + (add)

ii. Register a new Identifier

iii. Add (paste from Signing & Capabiiities ) value of 'Bundle ID' - Choose explicit.

iv. Choose Platform, Description, Enable any associated capabilities. Confirm and register. Check is registered and move to App Store Connect Website, and refresh.

v. After refresh, click My Apps. Click on + followed by New App to add details of App. Rfresh main content if in drop down of overlay, you cant find the new App's name/description field.

vi. Complete the details for the app. The SKU is any string you construct at this stage. Put thought to it and make sure is unique, if more apps will follow. No spaces in the sku: my-comic-app

vi. Privacy policy - Adjust and customise a templated version, and upload to a server or company website. Get link and insert in app information.

vi. Go through  other Tabs. Including Test Flight

vi. Test Flight - For BETA Testing

vii. Activity - This is where builds are organised from when it is archived.
