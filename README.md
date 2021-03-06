Kender — Plan less. Do more. 
=======================================
Designed to help users optimize their coming weekend (or the next three days if the weekend *just* can't come fast enough), Kender provides one consolidated place to find an accurate, location-based weather forecast, a curated playlist based on moods associated with the weather, and some upcoming events in the user's city with detailed information. 

The weather, playlist, and events are dynamically generated by utilizing three different powerful API's from the Open Weather Map, Spotify, and Eventbrite, and users are presented with the option to further customize which sorts of playlists and events they will see on the page. User sign-in data is stored in a Firebase database, so that users can sign in when they revisit the app using the email and password they gave when they sign up on their first visit.
  
![demo image](/assets/images/kender-landing-page-demo.PNG)

## Technologies Used

+ Page elements and styling are written with **HTML5** and **CSS3**, and the app's logic is written with **Javascript**. 
  
+ The app utilizes the **jQuery** library to dynamically update elements on the page. 
  
+ Built using **Materialize.css**, a CSS framework that includes many built-in features that the app utilizes, such as cards, carousels, the parallax effect for background gifs/images, and modal popup windows that can be easily dismissed in place of obnoxious alerts. Materialize also uses the grid system, and provides built-in responsiveness to make our app more mobile-friendly.

+ User input data from the form on the app's landing page is stored with **Firebase**, so that user login information can be stored in a more permanent way and users won't need to re-enter information they've already entered upon re-visiting the app.
  
+ The app makes AJAX calls to three different API's: 
   +  **Open Weather API**: https://openweathermap.org/api
   +  **Spotify**: https://developer.spotify.com/documentation/web-api/
   +  **Eventbrite**: https://www.eventbrite.com/platform/api

## How to Use the App

1. When you enter the app for the first time, you will be prompted to sign up using your email and provide your location.
   
2. After signing-up/signing-in, you will be re-located to our main content page, where you will be able to see and interact with your upcoming weather, listen to your new playlist or choose a new one using the buttons you'll see below it, and peruse upcoming events in your area.
   
3. Enjoy! All of the features allow you to further customize or get some new options if you aren't satisfied with what you see, or if you just feel like browsing.

## Challenges

+ 

## Plans for the Future of the App

In the future, we aim to add a few features that would enhance our user experience and help to further integrate our API responses with the user-data stored in our Firebase database. These include: 

   + *One-click sign-ups and logins with Facebook or Google.* This would allow us to integrate more features such as a way of pinning or linking events that the user expresses interest in to their Facebook or Google account, which could then easily be accesed within the user's calenders and provide a seemless way to keep track of what user's find on our app.
  
     + This could easily be extended to our Spotify playlists as well, which currently do link to their counterparts on Spotify's site, but we would like user's to be able to *login to their own Spotify within our app*, which would allow them to save playlists and songs without needing to leave our app. 
  
   + *Further integration of API results*. In its current state, each API response is informed in some way by the other responses or by the user's input data such as their location and preferences. A goal of ours was to make our user's experience as seemless as possible, and to us this meant minimizing the amount of further data a user needs to input on the page after filling out the first form on the landing page after signing up/in. 
  
   + *Styling and responsiveness*. This mostly speaks for itself, but we would like to further refine the CSS stylings and perhaps integrate a few more Materialize features that would make our app more polished and user-friendly. 
  
   + *Automatic Spotify token generation using Node.js*. Currently, because of how the Spotify API works, it will only give you a token that's good for one hour, then stop working and require you to get a new token. The method for refreshing requires Node.js to implement, and we hadn't covered Node at the time of doing this project.
  
## Authors
This app was developed in collaboration by **Liam Condon**, **Samuel Thompson**, **Atif Tariq**, and **Thor Nolan** for UC Berkeley Extension's full-stack coding bootcamp. We appreciate all the help we recieved from our TA's and from the annals of Google and Stack Overflow.

   
[Click here to start getting more out of your weekend!](https://thornolan.github.io/Project-1/ "Deployed App")

