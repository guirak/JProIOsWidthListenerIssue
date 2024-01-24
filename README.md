# Issue with Stage width listener in JPRO in iOS

## Description

When rotating the screen, the stage width listener defined in HelloJProFXML.start is not always triggered in iPAD and iPHONE. 

All is working well in Android. 


## How to reproduce ? 

- Launch the app 
- Open the app in an iPad, iPhone browser
- Rotate the screen and check the logs 

=> Half time, the width listener log is not triggered.