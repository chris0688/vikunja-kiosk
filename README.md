# vikunja-kiosk
-Some small scripts to make an nice big Kiosk Display with Vikunja as task overview

I wanted to use Vikunja as To-Do List with an View-Only Display on an TV-Screen for fast and easy overview about all Tasks.

The Idea was to use an old MiniPC and TV to Build this. I use Authentik SSO for Vikunja Login but i wanted to make it as easy and w/o any needed input of the user.
So at first i tryed with Login and Vikunja app but you needed to Login after some days of security reasons (and this is good as it is). Next try was to uses an shared View-Only link and this was the solution about the Login.
Now the Problem was that Vikunja doesnt use the full screen width, The Logo need many Space and if the List is to big you dont see all Task and it dosnt auto-reload.
The Solution was to use three things: an Tab Reload Extension (you can use any preferred), Stylus for use the whole Screen and Tampermonkey for Autoscroll.
After some Time it gets some more optical features like mark Task that are overdue and high priority with an blinking yellow Background behind the letters, do some Fade-Out - Fade-In so you dont see the hard reload and login-screen.

For me it works nicely.

My Setup:
-used HP MiniPC
-an old Grundig 43" TV
-Linux Mint
-Chromium with Tampermonky, Stylus, Auto Refresh Plus

For the Code i get some Help from gemini.

Just typed this fast, maybe if i have some time i will edit it.
