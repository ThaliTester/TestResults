#### Test 93390913232c8a0_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/81AC2EF0-DCDC-4751-A216-26A442C7C4CF/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/81AC2EF0-DCDC-4751-A216-26A442C7C4CF/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B6267BE2-C121-410A-973F-D98CCD5A7CA1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54437"
,(lldb)     command script import "/tmp/81AC2EF0-DCDC-4751-A216-26A442C7C4CF/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-11 12:58:01.940 ThaliTest[3344:7466948] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6FA3EA3-41FD-4C51-A932-EDB001304AA6/Library/Cookies/Cookies.binarycookies
,2016-11-11 12:58:02.037 ThaliTest[3344:7466948] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-11 12:58:02.040 ThaliTest[3344:7466948] Multi-tasking -> Device: YES, App: YES
,2016-11-11 12:58:02.066 ThaliTest[3344:7466948] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-11 12:58:02.474 ThaliTest[3344:7466948] Using UIWebView
,2016-11-11 12:58:02.481 ThaliTest[3344:7466948] [CDVTimer][handleopenurl] 0.371039ms
,2016-11-11 12:58:02.490 ThaliTest[3344:7466948] [CDVTimer][intentandnavigationfilter] 7.906973ms
2016-11-11 12:58:02.490 ThaliTest[3344:7466948] [CDVTimer][gesturehandler] 0.311017ms
2016-11-11 12:58:02.491 ThaliTest[3344:7466948] [CDVTimer][TotalPluginStartup] 10.150015ms
,2016-11-11 12:58:08.327 ThaliTest[3344:7466948] Resetting plugins due to page load.
,2016-11-11 12:58:08.624 ThaliTest[3344:7466948] Finished load of: file:///var/containers/Bundle/Application/B6267BE2-C121-410A-973F-D98CCD5A7CA1/ThaliTest.app/www/index.html
,2016-11-11 12:58:08.988 ThaliTest[3344:7466948] JXcore Cordova plugin initializing
,2016-11-11 12:58:08.989 ThaliTest[3344:7467133] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-11 20:58:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-11 20:58:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-11 20:58:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-11 20:58:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-11 20:58:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-11 20:58:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.80520904064178
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
