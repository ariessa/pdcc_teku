# About the App

A Flutter application to manage visitors and check ins at PDCC Teku. It can run on Android version 5 and above. It uses Firebase Cloud Firestore as database.

</br> 

## Understanding the App

The features of this app are as follows: 

● Log In 

● Main Menu

● Dashboard
 - View total daily check in
 - View total monthly check in
 - View total visitors by gender
 
● Manage Check In
 - Add check in
 - View check in
 
● Manage Visitors
 - Add visitor
 - View visitor
 - Edit visitor 
 - Delete visitor
 
● Log Out

## Installing Release Builds

1. Refer to this [article](https://android.gadgethacks.com/how-to/android-basics-see-what-kind-processor-you-have-arm-arm64-x86-0168051/) to know your device's CPU architecture.

2. Download any [`latest-release`](https://github.com/ariessa/pdcc_teku/releases) builds:
   - Specific release APK based on your device's CPU architecture
   - Fat APK (can be installed on `ARM`, `ARM64`, and `x86_64`)
   - AppBundle (can be installed on `ARM`, `ARM64`, and `x86_64`)

3. Install it on your device or emulator.

> **_WARNING I:_** There is no apk for x86 Android. This is because Flutter does not currently support building for x86 Android. Refer to this [issue](https://github.com/flutter/flutter/issues/9253) on Github.

> **_WARNING II:_** Release APKs cannot be installed on emulators.
</br> 

## Installing Debug Builds

> **_NOTE I:_**  Refer to this [article](https://android.gadgethacks.com/how-to/android-basics-see-what-kind-processor-you-have-arm-arm64-x86-0168051/) to know your device's CPU architecture.

> **_NOTE II:_** If debug builds are not available, please rebuild them on your own.

Download the specific release APK based on your device's CPU architecture and install it.

+ [ARM](build/app/outputs/apk/debug/app-armeabi-v7a-debug.apk)
+ [ARM64](build/app/outputs/apk/debug/app-arm64-v8a-debug.apk)
+ [x86_64](build/app/outputs/apk/debug/app-x86_64-debug.apk)

Or, you can download the fat APK that can be installed on `ARM`, `ARM64`, and `x86_64`.

+ [Fat APK](build/app/outputs/apk/debug/app-universal-debug.apk)

> **_WARNING I:_** There is no apk for x86 Android. This is because Flutter does not currently support building for x86 Android. Refer to this [issue](https://github.com/flutter/flutter/issues/9253) on Github.

> **_WARNING II_** These builds are intended for debugging purposes only. Usage outside of debugging may cause unexpected crashes and performance lags. 

</br> 

## Using the App

> **_NOTE:_**  The following credentials are supplied for testing purposes only.

Log in using the following credentials:

+ Email: testuser1@gmail.com
+ Password: passwordtestuser1

</br>

+ Email: testuser2@gmail.com
+ Password: passwordtestuser2

For detailed documentation, see the
user manual (link will be added later).

</br> 

## Screens
> The screeshots are of different app. Will be updated with the ones from PDCC Teku app.

### Log In

<img src="https://github.com/ariessa/PowApp/blob/old/screens/login.jpg" width="256" height="450" title="Log In Screen">

### Homepage

<img src="https://github.com/ariessa/PowApp/blob/old/screens/homepage.jpg" width="256" height="450" title="Homepage Screen">

### Dashboard

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/dashboard1.jpg" width="256" height="450" title="Dashboard I Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/dashboard2.jpg" width="256" height="450" title="Dashboard II Screen">
</p>

### Billing

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/billing1.jpg" width="256" height="450" title="Billing I Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/billing2.jpg" width="256" height="450" title="Billing II Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/billing3.jpg" width="256" height="450" title="Billing III Screen">
</p>

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/billing4.jpg" width="256" height="450" title="Billing IV Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/billing5.jpg" width="256" height="450" title="Billing V Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/billing6.jpg" width="256" height="450" title="Billing VI Screen">
</p>

<img src="https://github.com/ariessa/PowApp/blob/old/screens/billing7.jpg" width="256" height="450" title="Billing VII Screen">

### Customers

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/customer1.jpg" width="256" height="450" title="Customer I Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/customer2.jpg" width="256" height="450" title="Customer II Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/customer3.jpg" width="256" height="450" title="Customer III Screen">
</p>

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/customer4.jpg" width="256" height="450" title="Customer IV Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/customer5.jpg" width="256" height="450" title="Customer V Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/customer6.jpg" width="256" height="450" title="Customer VI Screen">
</p>

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/billing4.jpg" width="256" height="450" title="Customer IV Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/billing5.jpg" width="256" height="450" title="Customer V Screen">
</p>

### Inventory

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory1.jpg" width="256" height="450" title="Inventory I Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory2.jpg" width="256" height="450" title="Inventory II Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory3.jpg" width="256" height="450" title="Inventory III Screen">
</p>

<p float="left">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory4.jpg" width="256" height="450" title="Inventory IV Screen">
<img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory5.jpg" width="256" height="450" title="Inventory V Screen">
  <img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory6.jpg" width="256" height="450" title="Inventory VI Screen">
</p>

<img src="https://github.com/ariessa/PowApp/blob/old/screens/inventory7.jpg" width="256" height="450" title="Inventory VII Screen">

### Log Out

<img src="https://github.com/ariessa/PowApp/blob/old/screens/logout.jpg" width="256" height="450" title="Log Out Screen">
