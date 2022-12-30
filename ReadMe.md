B9IS124 Web and Mobile Technologies (B9IS124_2223_TMD1S)
Student ID: 10632656
Student Name: Rashmee Saxena

Developed Android application using Ionic Framework with Angular 
Hybrid mobile application for android platform is buid on the pharmacy 
concept or the business idea is - Mobile app for Online pharmacy: Where people can by medicine online through mobile app
Content of the Pharmacy Application:

Splash Screen:
Splash screen is for 3000 miliseconds
Splash screen has icon image size of 1024x1024
Splash screen has Splash image size of 4096x4096 dimension

Home Page: 
Includes banner on the home page with slider
Page is displayed with nearby pharmacy listed
Thumbnail for the pharmacy images 
label description for each pharmacy shops
rating for each pharmacy is given
Distance for each pharmacy is mentioned
Product content for each pharmacy type
Share the pharmacy with friends functionlaity is given under each pharmacy: 
 here the link for pharmacy can be shared with friends via email or copy link
Thumbnail and labels for each pharmacy listed is clickable 
The links routes the user to the search page, where user can find the medicine for specific pharmacy

Search Page:
Includes Search box on the top
List of medicines including gels onitments, Medicines, Injections are listed under Medcines
User can select the medicine as these are clickable
User on selectig any medicine is routed to cart page 

Cart Page:
User is displayed with the notification that they need to upload the prescription first before they buy these medicine
Cart Page has Take a photo button
User click on photo button and camera launches

Plugin: Camera, Share, keyboard, Splash screen, status-bar

Added plugins and functionality 

@capacitor/app@4.1.1
       @capacitor/camera@4.1.4
       @capacitor/haptics@4.1.0
       @capacitor/keyboard@4.1.0
       @capacitor/share@4.1.0
       @capacitor/splash-screen@4.1.2
       @capacitor/status-bar@4.1.1

implementation project(':capacitor-app')
    implementation project(':capacitor-camera')
    implementation project(':capacitor-haptics')
    implementation project(':capacitor-keyboard')
    implementation project(':capacitor-share')
    implementation project(':capacitor-splash-screen')
    implementation project(':capacitor-status-bar')
