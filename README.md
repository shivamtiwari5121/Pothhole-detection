 

### Introduction

A major problem being faced by municipalities around the world is maintaining the
condition of roads be it summer, the monsoons (when it is at its worst) or any weather
condition as a matter of fact. And although it’s the responsibility of the authorities to make
sure the roads are free of damage, at times they overlook the problem, and most times don’t
even know that the problem exists. According to “Safety Resource Center”, approximately
3 Billion US Dollars are spent by motorists for repair of blown tires, busted axles, and other
damage to their vehicles. Over the past five years around 16 million drivers across the U.S. have suffered damage
from potholes as per an article from “American Automobile Association (AAA)”


Maintaining the road condition is a challenge with constant weather changes, wear
and tear, low budgets for the municipalities. Also, not to forget keeping people informed is
a task. So, this is an app aimed at solving the challenges mentioned. A reporting system,
where the citizen can capture the scene of an area, which will be fed to a machine learning
model that will geocode, validate and track down potholes in the scene. This has been
achieved by training for object tracking on multiple images and developed using
convolutional neural networks. Users can see the damage on the roads using a
mobile application or through their browsers. A dynamic report is also  generated for the closest authority of concern which they can view and update to
create and manage work orders using their own jurisdiction-based web/mobile app-based
dashboard.

### Motivation
In articles covered by Guardian News & Media potholes took a deadly toll in 2017, claiming almost 10 lives daily. IndiaTimes stated that "Bereaved Father Mr. Dadarao" filled 600 Potholes in Mumbai in memory of son he lost in a road accident! Inshorts reported, potholes killed more people than terrorists reporting 14,926 deaths in road accidents.

When we look at the other side of the world, there is a similar situation as reported by American Automobile Association.

Keeping the roads in good condition along with tracking damages is a challenge with constant changes in weather, low budgets for the municipalities. Not to forget keeping the people informed is a task. This project was aimed at solving the challenges mentioned.

### App Preview

#### From Wire Frames to Reality! 
<kbd><img src="https://media.giphy.com/media/Q7pFE51bnytSQrbd3s/giphy.gif"/></kbd>

### Important URLs

#### Home (Landing Page)
Link to Landing Page: https://nirbhay.me/spothole/home

#### Demo 
Link to App Demo: https://nirbhay.me/spothole/

#### Presentation
Link to Canva Presentation: https://bit.ly/spothole-ppt

#### Citizen's App Wire Frames
Link to App Wire Frames: https://nirbhay.me/spothole/WireFrames/

#### Authority App Repository 
Link to Authority App's Repository: https://github.com/nirbhayph/spothole.authority

#### Flask and Deep Learning Backend Repository 
Link to Backend Source Code: https://github.com/nirbhayph/spothole.core

#### Citizen's App Project Structure
Link to Project's Directory Structure: https://nirbhay.me/spothole/ProjectStructure/

### Feature Stack 
| Feature Name | Screen Name |
| --- | --- |
| Report a Pothole (Using Camera, WebRTC)  | Report |
| Report a Pothole (Using Media from the File System) | Report |
| Deep Learning Powered Media Validation Check | Report |
| Report Pothole Using Current Location | Report |
| Report Pothole Using Custom Location (Auto Complete Search) | Report |
| Severity Indicator (0-10) | Report |
| Custom Text Area Description Box (For Additional Comments) | Report |
| Custom Alerts (Single and Multi Actionables) | Report |
| Successful Report Submission Feedback | Report |
| Invalid Report Feedback (Powered by Deep Learning Results) | Report |
| Minified Report View Card (Summarized Report Details) | My Complaints |
| Stepper Indicator (Report Status) | My Complaints, View Report |
| Static Image based Geographic Map | View Report |
| Disabled Severity Indicator | View Report |
| Comments Section (Communication Exchange Between Citizen and Authority) | View Report |
| Custom Location Search (Auto Complete) | Route Navigation |
| Custom Error Alerts | Route Navigation, Report |
| Map Based Directions Renderer | Route Navigation |
| Map Legend Indicating Severity Levels | Route Navigation |
| Street View Renderer | Route Navigation |
| Custom Markers for Potholes Distributed by Severity | Route Navigation |
| Custom Info Window (When Clicked on Marker) | Route Navigation | 
| Map Full Screen View | Route Navigation | 
| Wrapper Function For IsLocationOnEdge (To Display Potholes Reported on the Route Chosen) | Route Navigation |
| Estimated Time with Number of Miles | Route Navigation |
| Pothole Count for the Route | Route Navigation |
| Profile Details (Avatar, Name , Email Id) | Profile |
| Citizen's Summarized Report Statistics Based on Status (Submitted, Approved, Completed) | Profile |
| Awards Section Indicator for New Users | Profile |
| Awards Section Badge for Users with at least One Report | Profile | 
| Weighted Average Function for Calculating Badge Score | Profile |
| Custom Random Background | Log In | 
| O-Auth 2.0 Sign In | Log In |
| Fixed App Bar | All Screens |
| Left Menu Drawer (App Bar) | All Screens |
| App Bar Menu Icons (App Bar - Float Right) | All Screens |
| Floating Action Button (New Report) | All Screens | 
| 404, 401 | Error Pages |

### Libraries Used
* The Application has been built using React.js
* Material Design has been used throughout the App.
* Material UI Icons have been used for Icons. 
* MUI-Treasury Components have been used for additional needs (Like Card View in the My Complaints Screen)
* Axios has been used for making REST Calls to the Backend.
* FilePond and Supporting Libraries have been used for File Uploading to the Backend. 
* GitHub Pages has been used for Static Deployment of the Application. 
* React Google Maps has been used for all Mapping, Direction Rendering, Geocoding and Reverse Geocoding Needs. 
* React HTML5 Camera Component has been used for WebRTC based Media Capturing for Creating New Reports.
* Google Oauth 2.0 has been used Application Wide for Authentication Purposes. 

#### Libarary Details
| Library Name | Version |
| --- | --- |
| @material-ui/core | ^4.9.5 |
| @material-ui/icons | ^4.9.1 |
| @material-ui/lab | ^4.0.0-alpha.45 |
| @mui-treasury/components | ^1.0.0 |
| @mui-treasury/styles | ^1.0.0 |
| @mui-treasury/styling | ^0.2.8 |
| @testing-library/jest-dom | ^4.2.4 |
| @testing-library/react | ^9.5.0 |
| @testing-library/user-event | ^7.2.1 |
| autosuggest-highlight | ^3.1.1 |
| axios | ^0.19.2 |
| bootstrap | ^4.4.1 |
| dateformat | ^3.0.3 |
| filepond | ^4.12.0 |
| filepond-plugin-file-validate-size | ^2.2.1 |
| filepond-plugin-file-validate-type | ^1.2.4 |
| filepond-plugin-image-exif-orientation | ^1.0.6 |
| filepond-plugin-image-preview | ^4.6.1 |
| gh-pages | ^2.2.0 |
| lodash | ^4.17.15 |
| react | ^16.13.0 |
| react-dom | ^16.13.0 |
| react-filepond | ^7.0.1 |
| react-google-maps | ^9.4.5 |
| react-html5-camera-photo | ^1.5.4 |
| react-router | ^5.1.2 |
| react-router-dom | ^5.1.2 |
| react-scripts | 3.4.0 |
| recompose | ^0.30.0 |

1.Clone this on your machine
2.Npm install
3.start npm