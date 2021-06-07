# ISS Space Tracker
This program allows users to check if the International Space Station (ISS) is above a specified coordinate (latitude and longitude) location. An email will be sent to your gmail if the Space Station is above the specified coordinate.

## Setup
This project was written in Python, so please visit the [official website](https://www.python.org/downloads/) to download the latest version for your OS.

### Disclaimer
When using this code, it is important that you DO NOT POST your personal email and password online for security. This app is for personal use. Additionally, you will need to allow a less secure application to access your GMail, so please do so at your own discretion.

### Allowing Access to GMail
* Navigate to [myaccount.google.com](https://myaccount.google.com).
* Click on the "Security" tab on the left side of the screen.
* Navigate down to where you can see a section that says, "Less secure app access."
* Click the option that says "Turn on access."
* You will be brought to another page to turn on the app. Follow the instructions to toggle access ON or OFF.

### Choosing Coordinates and Email
Go to the main.py file and look for MY_LAT and MY_LONG at the beginning of the script. This will allow you to update the Latitude and Longitude coordinates from the current defaults.

Update the strings listed at MY_EMAIL and MY_PASSWORD to access your GMail account. This will allow the app to send an email message to that account when the International Space Station is above that location.

## Running the Script
If you are not using an IDE such as PyCharm, you can run the script from the command line by accessing the ISS_Tracking folder and entering:
    ```
    python.exe main.py
    ```
The code will update every 60 seconds. However, it is advised that you use a cloud service like [Python Anywhere](https://www.pythonanywhere.com/). This way the script can run without needing the app to be open on your device. I suggest hiding your email and password if you wanted to run the code online, but it is not necessary.