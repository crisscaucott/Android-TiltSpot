TiltSpot 
========================

It's a modified version of the "TiltSpot" app from the [Advanced Android Development Course](https://legacy.gitbook.com/book/google-developer-training/android-developer-advanced-course-concepts/details) which gives support to devices that not have magnetic field sensor (like the Moto G 5 in my case) using Gyroscope sensor instead. In the first gif the phone are rotated to the left (right circle appears), then to the right (left circle appears), rotate to the back (top circle appears), rotate to the front (bottom circle appears) and finally the phone is placed in a table.

![App example 1](https://rawgit.com/crisscaucott/Android-TiltSpot/master/screenshoots/TiltSpot_1.gif)

The respective dark circles are reoriented when the screen orientation changes, by remaping the coordinate system of the sensor.

![App example 2](https://rawgit.com/crisscaucott/Android-TiltSpot/master/screenshoots/TiltSpot2.gif)
