---
title: "How to Build Your First Android App with Kotlin"
datePublished: Sun Jul 16 2023 07:14:13 GMT+0000 (Coordinated Universal Time)
cuid: clk53piqe000n09l513uzhe5o
slug: how-to-build-your-first-android-app-with-kotlin
tags: android, kotlin

---

Kotlin is a modern and concise programming language that is officially supported for Android development. If you want to learn how to build your first Android app with Kotlin, this article will guide you through the steps of creating a simple app that displays a message on the screen.

## What you'll need

* A computer running Windows, Mac OS, or Linux
    
* Android Studio, the official IDE for Android development
    
* A basic understanding of object-oriented programming and how to use an IDE
    

## What you'll learn

* How to create a new Android Studio project with Kotlin support
    
* How to use the layout editor to design the user interface of your app
    
* How to write Kotlin code to display a message on the screen
    
* How to run your app on an emulator or a real device
    

## Step 1: Create a new project

To create a new project in Android Studio, follow these steps:

1. Open Android Studio and click Start a new Android Studio project.
    
2. Select Empty Activity and click Next.
    
3. Enter Happy Birthday as the name of your app, and com.example.happybirthday as the package name. Make sure the language is set to Kotlin and the minimum SDK is API 19: Android 4.4 (KitKat). Click Finish.
    
4. Wait for Android Studio to build and sync your project.
    

## Step 2: Design the user interface

To design the user interface of your app, you'll use the layout editor, which is a visual tool that lets you drag and drop UI elements onto the screen. Follow these steps:

1. Open the file activity\_main.xml, which is located in the res/layout folder. This file defines the layout of your main activity, which is the screen that users see when they launch your app.
    
2. In the layout editor, switch to the Design tab, which shows a preview of your layout. You can zoom in and out, and change the device and orientation using the buttons on the top bar.
    
3. On the left panel, find the Text category and drag a TextView onto the center of the screen. A TextView is a UI element that displays text.
    
4. On the right panel, find the Attributes tab, which shows the properties of the selected UI element. You can change the appearance and behavior of your TextView using these properties.
    
5. In the text property, enter Happy Birthday! as the text to display. You can also change other properties, such as textSize, textColor, fontFamily, etc., to customize your TextView.
    
6. Save your changes by clicking File &gt; Save All or pressing Ctrl+S (Windows) or Command+S (Mac).
    

## Step 3: Write Kotlin code

To write Kotlin code for your app, you'll use the code editor, which is a text editor that provides features such as syntax highlighting, code completion, refactoring, debugging, etc. Follow these steps:

1. Open the file MainActivity.kt, which is located in the java/com.example.happybirthday folder. This file defines the behavior of your main activity, which is linked to your layout file by the line setContentView(R.layout.activity\_main).
    
2. In the code editor, find the line class MainActivity : AppCompatActivity() { and place your cursor inside the curly braces {}.
    
3. Press Alt+Enter (Windows) or Option+Enter (Mac) to open a menu of actions. Select Create onCreate function, which will generate a function that is called when your activity is created.
    
4. Inside the onCreate() function, add this line of code: Toast.makeText(this, "This is a toast message", Toast.LENGTH\_SHORT).show(). This will create and show a toast message, which is a short pop-up message that appears on the screen for a few seconds.
    
5. Save your changes by clicking File &gt; Save All or pressing Ctrl+S (Windows) or Command+S (Mac).
    

## Step 4: Run your app

To run your app, you'll need either an emulator or a real device. An emulator is software that simulates an Android device on your computer. A real device is an actual Android device that you can connect to your computer using a USB cable. Follow these steps:

1. To run your app on an emulator, click Tools &gt; AVD Manager to open the Android Virtual Device Manager. This tool lets you create and manage emulators. Click Create Virtual Device and follow the instructions to create an emulator with your desired specifications. Once you have created an emulator, select it from the list and click Run.
    
2. To run your app on a real device, make sure your device is connected to your computer and has USB debugging enabled. You can check this by going to Settings &gt; Developer options &gt; USB debugging on your device. If you don't see the developer options, you may need to enable them by going to Settings &gt; About phone &gt; Build number and tapping it seven times. Once your device is ready, select it from the list of available devices and click Run.
    
3. Wait for Android Studio to build and install your app. You should see your app launch on the emulator or the device, and display the message "Happy Birthday!" on the screen. You should also see a toast message saying "This is a toast message" appear briefly.
    

Congratulations! You have successfully built your first Android app with Kotlin. You have learned how to create a project, design a layout, write code, and run your app. You can now explore more features and functionalities of Android development with Kotlin by following the other codelabs in this course. Happy coding!