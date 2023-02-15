# Stage Manager bug in MacOS Ventura 13.2.1

When a system settings help dialog window is minimized with stage manager enabled, the window is minimized and you’re unable to focus on any open application, making the user unable to do their work. I was able to reproduce this multiple times using different help dialogs in the systems settings. As well, I was able to drag windows into another desktop and use them there without issue.

How to reproduce:
1. Open system settings
2. Click any of the help buttons at the bottom of any page
3. Minimize the help popup window

I expected to be able to minimize the help window and then continue using the systems settings app. Instead, I was unable to use any application in that desktop.

See `screenrecording.mp4`.
