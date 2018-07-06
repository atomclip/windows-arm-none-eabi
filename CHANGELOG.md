### Version 0.1.0
Replaced toolchain with Version 7-2018-q2-update for Windows.

### Version 0.0.5
The path separator punctiantion is a *colon :* in macOS and Linux and a 
*semicolon ;* in Windows. To handle these operating system specific differences 
I updated the tasks.json and added a simple makefile to test. You can use this 
tasks.json and makefile to check your paths. 

### Version 0.0.2
Changed ${env:HOME} to ${env:USERPROFILE}.
