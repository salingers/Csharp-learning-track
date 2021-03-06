# Lesson 17: Media
## Prep Work
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=dXaEj0CrB_3605244527) introducing the sound board project from the Windows 10 Development for Absolute Beginners course.  **Make sure you code along with Bob during this series.  See Assignment 17-1**
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=hL4pp1CrB_305244527) for the setup and main page layout for the sound board project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=816NS4CrB_3605244527) for creating the data model and setting up data binding for the sound board project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=INiyU8CrB_9105244527) on playing sounds with the sound board element for the media project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=keRE6ADrB_6205244527) to add drag and drop to the sound board project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=sNgivDDrB_4405244527) to add finishing touches to the sound board project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=bIih0GDrB_4605244527) to add assets with the Package.AppXManifest to the sound board project
* Watch and code along with [this lesson](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=X6CgQKDrB_9305244527) on submitting the sound board project to the Microsoft Store
* Read [this article](https://stephenhaunts.com/2014/10/10/simple-async-await-example-for-asynchronous-programming/) to better understand how to use C# for asynchronous programming, which avoids having your application freeze up during long running operations
* Microsoft introduced a new version of the Media Element control that Bob has been using called Media Player.  [Read the official documentation](https://stephenhaunts.com/2014/10/10/simple-async-await-example-for-asynchronous-programming/) on the new version
* When you move your application to the background or minimize it, the audio will stop playing.  Read [this article](https://docs.microsoft.com/en-us/windows/uwp/audio-video-camera/play-audio-and-video-with-mediaplayer) on how to keep it playing the background

## Learning Objectives
* Create a complete project from end-to-end
* Use the media element control to play audio
* Use the media element control to play video
* Add drag-and-drop sharing to an application
* Use asynchronous programming to prevent blocking and frozen screens
* Read and write files
* Search for results in an application
* Set the title and logo for your application

## Assignments
* Take the [Setup and MainPage Layout Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=Mpy613CrB_5605244527)
* Take the [Creating the Data Model and Data Binding Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=Mpy613CrB_5605244527)
* Take the [Playing Sounds with the Media Element Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=INiyU8CrB_9105244527)
* Take the [Adding Drag and Drop Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=keRE6ADrB_6205244527)
* Take the [Finishing Touches Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=sNgivDDrB_4405244527)
* Take the [Adding Assets with the Package.AppXManifest Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=bIih0GDrB_4605244527)
* Take the [Submitting to the Windows Store Assessment](https://mva.microsoft.com/en-US/training-courses/windows-10-development-for-absolute-beginners-14541?l=X6CgQKDrB_9305244527) and upload a screenshot of your score into Canvas
* Code along with Bob to create the Sound Board application.  Bob’s does not comment his code while he is going through the video, but you should be commenting your own code.  See the resources section for a review on code comments.  Upload your program to a new repository called CG 17-1
* Extend the Sound Board application with a new menu item that lets the user play videos instead of sounds.  You can start with some free sample videos from [Pixabay](https://pixabay.com/videos/).  Replace the Media Element control with the [Media Player Element](https://docs.microsoft.com/en-us/uwp/api/windows.ui.xaml.controls.mediaplayerelement) control, which is a newer version.  Upload your program to a new repository called CG 17-2
* Extend the Sound Board application further so that the audio will continue to play in the background even when the application is minimized.  You will need a longer sound file to make sure it is working.  You can download free music from [Opsound](http://opsound.org/) to test your application or have your audio loop continuously.  Upload your program to a new repository called CG 17-3
* Extend the Sound Board application further so that the video will continue to play in a picture in picture style mode over other applications.  Upload your program to a new repository called CG 17-4

## Resources
* [Comments in C#](https://www.c-sharpcorner.com/uploadfile/puranindia/comments-in-C-Sharp/) - A useful article with tips on what and how to comment
* [Paint.net](https://www.getpaint.net/) – A free application to help you edit images.  It is also available in the [Microsoft store](https://www.microsoft.com/en-us/p/paintnet/9nbhcs1lx4r0?ocid=badge&rtc=1) for a small fee to help support the developer
* [BuildCast Video Player UWP Sample](https://github.com/Microsoft/BuildCast) - BuildCast is an end-to-end sample built to showcase the Microsoft Fluent Design System as well as other capabilities of the Universal Windows Platform
* [TV Helpers](https://github.com/Microsoft/TVHelpers) - This project consists of several helper components, samples, and sample app to help you get started building applications for media, TV, and Xbox on the Universal Windows Platform for both C# and JavaScript developers

## Errata
* **Playing Sounds with the Media Element:** The Media Element is a deprecated control and has been replaced with the Media Player control.  The Media element should still work.  Media Player is covered in a later lesson.
* **Submitting to the Windows Store:** Microsoft makes changes to the store submission process on a regular basis.  This video will help you understand the process, but the interface on the web has changed.