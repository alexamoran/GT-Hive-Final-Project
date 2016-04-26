# GT-Hive-Android
Code for the GT Hive Android Application


Install Guide:


The Android application is currently unavailable through the Google Play store, but it is still downloadable and ready to install on a device through Android Studio.


Requirements:

    1. Install or acquire the following requirements before proceeding with the application installation

        A. Android Studio

        B. (Optional) Android handheld device with minimum Android 3.0 installed


Installation Instructions:

    1. Clone the source code from the GitHub repository found at https://github.com/alexamoran/GT-Hive-Final-Project

    2. Open Android Studio and import the existing Android project

    3. Once imported, you have the option to either use the existing emulator, or to use an external device to install the application. If using an external device, connect it to the PC. If you are using a Mac, you may need to first install Android File Transfer

    4. Next, click “Run” to run the application on the emulator or to install and run the application on your external device




GT Hive Android Build 1.0.0


Release Date: April 25, 2016


Notable Bug Fixes:

    - Rerouted API queries through RESTful API to avoid crashing the RNOC API

    - Fixed main view to allow sorting of buildings alphabetically

    - Fixed issues with running too many processes on the main thread

    - Corrected issues with optimal times for each building based on timestamped data

    - Fixed issues with application crashing when the external API was unavailable

    - Graph x-axis correctly displays hours as 12-hour clock rather than 24-hour clock

    - Fixed graphing issues to make the plot points more readable

    - Fixed floor displaying issue so that the linear layout could handle a building with more than three floors

    - Fixed issue with “star” image button being the same color as the CardView by outlining the “star” image in black

    - Fixed issue with the more information page returning information on the wrong building

    - Fixed zooming issue with the Graph, made turned off both pinch zoom and double click zooming capabilities

    - Fixed the issue of the graph for a specific building displaying the occupancy data of the next building in the list instead of its own


Added Features:

    - Added floor by floor data for each building on campus

    - Added the ability to save favorite buildings between multiple sessions

    - Included graphs based on historical data to show averages for each hour of the day

    - Added the ability to view optimal times for each building based on local minima

    - Added the ability to swipe between more information pages


Known Bugs:

    - Favorites list does not initialize upon opening the application, but does initialize after pausing and resuming the main activity
    
    - Favorites list does not update between tab switches (it only updates when the activity is paused and resumed, which occurs when the more information page for a building is viewed.)





