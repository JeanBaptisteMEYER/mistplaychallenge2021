# Mistplay Android Challenge 2021
Solution by Jean-Baptiste Meyer

# The Challenge
Create a vertical scrolling list of horizontally scrolling lists.

The requirements for this mini project are to:
1) Build the functionality for the list of lists. Make sure to do this using Object-Oriented programming principles as well as design patterns.
2) Use the Kotlin programming language.
3) Incorporate the classes you build into a sample
application. This sample application can use any design you choose.
4) Well commented and formatted code.


# The Solution
https://youtu.be/paBY7wweu2U

Simple Android app written in Kotlin that:
1) Uses Fragments and Bottom navigation bar for the UI
2) Uses a Service for the background tasks like the JSON parsing
3) Loads a list of game from a JSON file stored in res/raw
4) Dynamicly builds the UI base on the JSON file
5) Uses ScrollViews for the scrolling features
6) Uses the Picasso lib to handle the game's images download from the cloud
7) Runs on API >23 (Android 6.0 and newer)
