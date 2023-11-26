# Flutter-for-Back4app
Flutter integration with back4app 22MT12456

GitHub Repository

The GitHub URL is https: https://github.com/pulkit5/Flutter-for-Back4app.git
************************
Documentation

For Better Reading Experience it is in PDF format named as Assignment 2 Flutter


************************
You can install flutter by referring following link.

https://docs.flutter.dev/get-started/install
To start this project on localhost. do as following:

Clone the project on your local system.
Open command prompty at project location in your system.
Write following command.
 PS> flutter pub get 
Run following commands to see emulators/devices.
 PS> flutter devices 
 PS> flutter emulators
Let's start android emulator.
 PS> flutter emulators --launch <emulator_name> 
Once you run emulator and ready, it will shown in list of devices.
output:-
    Found 4 connected devices:
    sdk gphone64 x86 64 (mobile) • emulator-5554 • android-x64    • Android 14 (API 34) (emulator)
    Windows (desktop)            • windows       • windows-x64    • Microsoft Windows [Version 10.0.22631.2715]
    Chrome (web)                 • chrome        • web-javascript • Google Chrome 119.0.6045.160
    Edge (web)                   • edge          • web-javascript • Microsoft Edge 119.0.2151.72
To run application on particular device, you need to run following command:-
 PS> flutter run -d <DEVICE_ID_OR_DEVICE_NAME> 
If you run app on android emulator or phone, you will see following screen:-



figure 1: Android Main Screen of app.
If you run app as Windows, you will see follwing screen:-



figure 2: Windows Main Screen of app.
"" Note:- While building app for windows, please enable following options in your windows menu ""




figure 3: Windows Enable Developer Mode.
Didn't explorer IOS/Web APP build yet.
Now you are done with Setup.
""" Note: Setup doesn't include how to setup Android Emulator and Windows MSVC Library, Windows SDK. """

App Screen-Shots According to Features.
Add Task Screen



Figure 4: Add to Task Screen.
it will accept Task name and description and also validating the response that it shouldn't empty.

View Task Screen



Figure 5: View Task Details Screen.
Edit Task Screen



Figure 6: Edit Task Details Screen.
Delete Task Screen



Figure 6: Delete Task Screen.
You will see following pop-up when you tap on dust-bin button in list.

To finish Task Screen



Figure 6: to done the Task Screen.
You will see following pop-up when you tap on check-mark button and it will open confirmation page. once you done the task you will see task with double check-mark like comment was read

Not Done Filter Task Screen



Figure 6: to filter not done Task Screen.
You can see Not Done filter is checked mark in bottom of screen.
