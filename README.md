simlink: 

	$ sudo ln  /Users/randymcmillan/FTHomeCam/net.randymcmillan.fthomecam.plist /Library/LaunchDaemons

codesign:

	$ codesign -s - --resource-rules=/Users/randymcmillan/FTHomeCam/ResourceRules-ignoring-Scripts.plist FTHomeCam.app