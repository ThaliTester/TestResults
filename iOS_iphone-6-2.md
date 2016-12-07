#### Test 96293062c9b8e19_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/0BE2A71E-C37B-4D0A-A5C5-DDB00E67C3E1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/0BE2A71E-C37B-4D0A-A5C5-DDB00E67C3E1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3FF62706-BF21-411F-B4A1-B1D85AD830CE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55664"
,(lldb)     command script import "/tmp/0BE2A71E-C37B-4D0A-A5C5-DDB00E67C3E1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 17:12:24.718 ThaliTest[349:141785] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8BE7DA6D-A7D2-4B7D-AC5A-5981F083F6EC/Library/Cookies/Cookies.binarycookies
,2016-12-07 17:12:24.757 ThaliTest[349:141785] Apache Cordova native platform version 4.3.1 is starting.
2016-12-07 17:12:24.757 ThaliTest[349:141785] Multi-tasking -> Device: YES, App: YES
,2016-12-07 17:12:24.769 ThaliTest[349:141785] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 17:12:25.105 ThaliTest[349:141785] Using UIWebView
,2016-12-07 17:12:25.110 ThaliTest[349:141785] [CDVTimer][handleopenurl] 0.319004ms
,2016-12-07 17:12:25.116 ThaliTest[349:141785] [CDVTimer][intentandnavigationfilter] 5.816996ms
2016-12-07 17:12:25.117 ThaliTest[349:141785] [CDVTimer][gesturehandler] 0.197947ms
2016-12-07 17:12:25.117 ThaliTest[349:141785] [CDVTimer][TotalPluginStartup,] 7.428050ms
,2016-12-07 17:12:30.853 ThaliTest[349:141785] Resetting plugins due to page load.
,2016-12-07 17:12:31.163 ThaliTest[349:141785] Finished load of: file:///var/containers/Bundle/Application/3FF62706-BF21-411F-B4A1-B1D85AD830CE/ThaliTest.app/www/index.html
,2016-12-07 17:12:31.496 ThaliTest[349:141785] JXcore Cordova plugin initializing
,2016-12-07 17:12:31.497 ThaliTest[349:141998] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 16:12:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 16:12:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 16:12:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 16:12:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 16:12:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 16:13:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  27.05955100059509
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
