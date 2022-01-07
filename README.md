# YouTube Player App

This project is about getting an API key from YouTube Player. Java was used to create simple UIs and two main activities in order to get the URL and to play it in the different screen.

## Wireframe

The wireframe was designed to have two screens. </br>
In main activity, there is an `EditText` to get URL from user. Once the URL is inputted, the user can play the video by clicking a `Button`.

<img width="600" alt="wifeframe" src="https://user-images.githubusercontent.com/57608628/148474835-d634f6df-8e75-48f8-ba06-4c827241cc56.png">

## Main Activity

As mentioned above, `EditText` gets URL input and `Intent` is used to store the string (URL) and brings it to Play Activity.

<img width="600" alt="mainActivity" src="https://user-images.githubusercontent.com/57608628/148475830-e4d4d6db-8390-4e1d-b946-d26c3ca8d9bf.png">

## Play Activity

In Play Activity, `YouTubePlayerView` is used to place a video in the screen. Then, it gets the URL, initialises the listener by the authorised API key to load the video.

<img width="600" alt="playActivity" src="https://user-images.githubusercontent.com/57608628/148476092-8f9f8952-1beb-4360-a7ba-2ae04df9acaf.png">
