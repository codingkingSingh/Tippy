Tip Calculator - My First Android App
What is this app?
This is a tip calculator I built for my mobile dev class. It helps you figure out exactly how much to tip based on your bill. You can use a slider to pick a percentage, and the app updates the math instantly. I also added a "Cyberpunk" dark theme because the default white screens were a bit too bright!

The Extra Features I Added
I went beyond the basic tutorial and added two cool features:

Bill Splitting: You can type in how many people are at the table, and it will show the "Each" amount. No more awkward math at the end of dinner!

Quick Preset Buttons: I added buttons for 10%, 15%, and 20%. It’s way faster than trying to slide the bar to exactly 15% with your thumb.

How to Run It
Download or clone this folder.

Open it in Android Studio.

Let the Gradle sync finish (it might take a minute).

Hit the green Run button to launch it on your emulator.

If you just want the app, you can install the TipCalculator_Manvinder.apk file I included.

Screenshots
<img width="1919" height="1039" alt="Screenshot 2026-04-06 201212" src="https://github.com/user-attachments/assets/177b7a45-b265-4928-8066-b6f8d24e90a3" />
<img width="1059" height="576" alt="Screenshot 2026-04-06 202110" src="https://github.com/user-attachments/assets/352e4b21-6fcd-49a7-8140-53ba0a0a195b" />


Demo Video
You can watch me walk through the app and show off the features here: The video is uploaded on blackboard along with apk file. 


How I Built It (and what I'd change)
The Logic: I used TextWatchers so the math happens the second you type a number. You don't have to hit a "Calculate" button, which feels a lot smoother.

The Colors: I used something called ColorUtils to make the "Tip Description" (like "Poor" or "Great") change color from red to green as you slide the bar.

Trade-offs: Right now, all the code is stuck in one file (MainActivity.kt). It works fine for a small app like this, but if the app got bigger, it would get pretty messy.

Next Steps: If I had more time, I’d move the math into a ViewModel. That way, if you rotate your phone sideways, the app wouldn't "reset" and lose the numbers you just typed in.

Quick Submission Checklist
[x] App compiles and runs without crashes

[x] Baseline features match the video app

[x] Two enhancements implemented and visible in the demo

[x] Readme includes overview, features, setup, screenshots, and video link

[x] APK uploaded; repo access granted
