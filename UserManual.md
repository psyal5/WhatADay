# User Manual

## Introduction  

This is the user manual for the WhatADay mobile phone app. Whether a first-time or experienced user, this manual will guide you through the features and functions of the app, helping you get the most out of it. 

This manual includes detailed instructions on how to sign up for the app as a new user and troubleshoots common issues for regular users. The language used is clear and easy to understand, making the instructions accessible for a wide range of users. 

Throughout the manual helpful visuals have been included such as diagrams and images to give visual aids to the written instructions and make it easier for you to understand the app. The content is organised into a logical and user-friendly manner so you can quickly find all the information you need. 


### Goals of the product 

The goal of this product is to provide more valuable experiences and encourage moments of spontaneity. This apps’ primary goal is to inspire positivity for our users, with no concept of popularity metrics to add pressure.  

Short simple tasks are delivered daily to users that are easy to achieve and aimed at creating opportunities for the user to try new things. It allows users to post photos to prove that they have completed tasks and share this with their friends. 

Completion of tasks give users the opportunity to earn badges to display on their profile without pressuring or punishing users for not completing tasks. Overall, the goal is to make the university journey more valuable and rewarding for students by providing positive experiences and encouraging personal growth. 


## Installation and configuration manual 

To install and configure the WhatADay app, please use the following steps based on your device. 

* Clone the GitLab project onto a computer using the relevant installation guide. 

* Install flutter onto your Windows or Mac computer using the relevant installation guide. 


### Android Installation 

* To install WhatADay on an Android device, first the ‘Developer options’ need to be enabled by going to Settings > About Phone > Software Information and tapping the ‘Build number’ seven times. 

* Then go back to the Settings page and the ‘Developer options’ should be available. 

* Turn on the USB debugging toggle and tap ‘Ok’ on the ‘Allow USB debugging?’ popup. 

* Plug the phone into the computer and select the phone device from the ‘Select a device to use’ list. 

* Locate the main.dart file in the following directory: Frontend > WhatADay > lib. 

* Click the ‘run’ button located at the top right side of the screen. This will install and open the WhatADay app on the connected phone. 


### iOS Installation 

* To install WhatADay on a IOS device, we need to have the version of xcode that is compatible with the current ios version on the phone I.e, latest version of ios will require to update xcode. 

* Developer mode must be enabled on the iphone. 

* Connect and trust the iphone to a macbook 

* Open the flutter app and run open ios/Runner.xcworkspace  in the command line. 

* In Xcode, select the 'Runner' project in the navigator. 

* Under the Signing & Capabilities section, make sure that a 'Development Team' is selected. If not, log in with your Apple ID in Xcode first, then select your team. 

* Finally, trust your newly created Development Certificate on your iOS device by going to Settings > General > Device Management > [your new certificate] > Trust. 

* Create a unique bundle ID for the app  

* Connect your iOS device to your Mac, select it in Xcode's Devices and Simulators window, then click the 'Use for Development' button. 

* Let Xcode automatically provision a profile for your app. Xcode should create a new Provisioning Profile for your app automatically. If not, you may need to create one manually. 

* Build/run your project again. 


## Getting started 

### New user sign up 

* Open the WhatADay app on your phone. 

* Tap the ‘Login’ button. 

* Login with your UNiDAYS account and tap ‘allow’. 

* Enter desired username, please note this must be unique and tap the ‘Sign Up’ button. 

* Once your account has been created you will be redirected to the Tasks Page where you can see the current daily task 


### Edit profile 

You can easily edit your profile on the WhatADay app to update your user and/or profile image. 

* Open the WhatADay app on your phone. 

* Tap the ‘Account’ icon at the bottom right of the screen. 

* Tap the arrow icon to the right of ‘Edit profile’. 

* To change profile image, tap the current profile image and select your desired one from your device’s gallery. 

* To change your username, tap on the current username and change the text to your desired username. 

* To save these changes and update your profile tap the ‘Save’ button. 

* Popup will appear to notify you if the update was successful. 


## Features and Functions 

### Add a friend 

* Open the WhatADay app on your phone. 

* Tap the friend’s icon at the bottom of the screen (3rd from the left), this will take you to the friend’s page. 

* At the top of the screen enter your friend’s username and tap the add icon to the right of the search bar. 

* A popup will appear to notify you of successful friend request sent. 

* A screenshot of a phone


### Accept or deny friend request 

* Open the WhatADay app on your phone. 

* Tap the friend’s icon at the bottom of the screen (3rd from the left), this will take you to the friend’s page. 

* All pending requests will appear at the top of the screen in the ‘Requests’ section. 

* To accept a friend request, tap the ‘Accept’ button underneath the username. Once accepted the user will be added to your friends list. 

* To deny a friend request, tap the ‘Deny’ button underneath the username. This will reject the friend request and remove it from your ‘Requests’ section. 


### Delete friend 

* Open the WhatADay app on your phone. 

* Tap the friend’s icon at the bottom of the screen (3rd from the left), this will take you to the friend’s page. 

* Find the friend you would like to delete in the ‘Friends’ section. 

* Tap the delete icon to the right of the username. 

* Tap ‘Remove Friend’ on the popup to confirm removal of this friend from your friends list. Doing this means they will not be able to see your posts and you will not be able to see theirs. 


### Post daily task 

* Open the WhatADay app on your phone. 

* Tap the Tasks icon at the bottom of the screen (2nd from the right). 

* Read the current task for today and tap ‘Go!’ to open the camera and capture a photo. 

* Add a caption for your post and tap ‘Post. 

* To view your post, tap the tasks icon again at the bottom of the screen 

* Tap the ‘View Post!’ to see your current post, this is what your friends will be able to see 

* Check back the next day to see a new task, tasks reset at midnight every night. 


### View friends daily task post 

* Open the WhatADay app on your phone. 

* Tap the Home icon at the bottom of the screen (1st on the left). 

* Here you will see the posts from your friends for today’s task. 

* Please note this page may be blank if none of your friends have posted yet. 


### View friend’s profile 

* Open the WhatADay app on your phone. 

* Tap the Friends icon at the bottom of the screen (3rd on the right). 

* Find the friend you would like to view the profile of in the ‘Friends’ section. 

* Tap on that friend’s username. 

* Here you will be shown their profile. 

## Overview of Hardware and Software Requirements 

Before installing and using the WhatADay app you should check that your device meets the minimum hardware and software requirements. Meeting these requirements will ensure that the app functions properly and that you can enjoy all its features. 

### Hardware requirements 

* Operating system: iOS 12 or later, Android 5.0 or later 

* RAM: 2 GB or higher 

* Storage: 100 MB or higher 

### Software requirements 

* Internet connection: internet connectivity is necessary for the app to connect you to your friends 

Please note that these requirements may vary depending on the specific version of the app at time of install. 

## Frequently asked questions 

Here are some common questions and answers related to the WhatADay app. 

### What is WhatADay app? 

WhatADay is a mobile app that allows students to participate in daily tasks and share their experiences with their friends. 

 

### Is WhatADay app free? 

Yes, WhatADay is a free to use social app. 

 

### How do I download the WhatADay app? 

You can download the app from the Google Play Store on your mobile device. 

 

### What are the minimum requirements for the WhatADay app? 

The minimum requirements for iOS devices are iOS 12 or later and for Android devices are Android 5.0 or later. 

 

### Do I need an internet connection to use the WhatADay app? 

Yes, an internet connection is required to download and install the app, as well as to use some of its features. 

 

### Do I need a UNiDAYS account to sign up for WhatADay? 

Yes, as this is a student only app you are required to have and login with a UNiDAYS account before creating a WhatADay account. 

 

### How do I sign up for a WhatADay account? 

To sign up for a WhatADay account you must first install, open the app and tap ‘Login’. You are required to login with your UNiDAYS account first before creating a WhatADay account. 

 

### Can I connect with friends on the WhatADay app? 

Yes, you can connect with friends on WhatADay app by sending and accepting friend requests. 

 

### How do I view my friends’ daily task posts? 

To complete the current daily task, open the app and click on the Tasks icon. Tap the ‘Go!’ button to capture your photo and follow the instructions. 

 

### How do I delete a friend on the WhatADay app? 

To delete a friend on WhatADay app, open the app and click on the "Friends" icon. Tap the remove icon next to the username of the friend you wish to delete. 

 

### How do I get badges on my profile? 

You can earn badges by completing daily tasks. The badges you have earned will be displayed on your profile page. 

 

### What happens if I miss a task? 

Don’t worry! You can come back the next day for another task.  

 

### How do I keep my account private? 

Your privacy is important to use hence why all accounts are private with only accepted friends being able to see your posts. 

 

## Troubleshooting guide 

If you are experiencing issue with the WhatADay app, please try the following troubleshooting tips. 

* Check your internet connection: Ensure that you are connected to a stable internet connection and try restarting your device and router. 

* Update the app: Depending on your device go to its relevant app store and download the latest version. 

* Clear cache and data: Go to your device’s settings, find the WhatADay app, and clear the cache and data. 

* Restart the app: Close the app completely and reopen it. 

* Restart your device: Restart your phone to clear any system glitches that may be affecting the app. 

* Check the apps permissions: Ensure that the app has all necessary permissions to access your camera and files. 

* Contact support: If you have tried the above solutions and the issue persists, reach out to WhatADay support through the app's website, which is linked in the help section of the settings page. 

## Data gathering and protection policies 

We are committed to protecting our users’ data privacy and security. Here are some key points related to data gathering and protection policies: 

* Data Gathering: The WhatADay app collects user data, such as first name, last name, and university, from UNiDAYS to offer its services. The data is gathered for a specific and legal purpose and will not be processed in any way that is incompatible with that purpose.	 

* Data Usage: The WhatADay app uses user data to provide its services, such as displaying the daily task for a given day and allowing users to connect with friends. 

* Data Protection: The WhatADay app takes measures to protect users’ data, including encryption of sensitive information, secure storage, and use of HTTPS for data transfer. The app does not share user data with third-party companies or advertisers without the user's explicit consent. 

* Data Deletion: The WhatADay app deletes user post images at the end of each day. 

* Data Access: The WhatADay app provides users with the ability to view and modify their personal data through the app’s settings. This includes changing the username and profile image for their account. 
