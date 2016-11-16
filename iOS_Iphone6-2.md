#### Test 933712696ecca49_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/933712696ecca49/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/40546C09-259E-4D67-A531-DB615E28849B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/40546C09-259E-4D67-A531-DB615E28849B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/933712696ecca49/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/933712696ecca49/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D6C40A39-6B10-4E51-93CB-420AE606FB94/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61298"
,(lldb)     command script import "/tmp/40546C09-259E-4D67-A531-DB615E28849B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 08:40:06.038 ThaliTest[3555:8076182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A137478B-71AC-4DD2-9416-91DBA94993D4/Library/Cookies/Cookies.binarycookies
,2016-11-16 08:40:06.137 ThaliTest[3555:8076182] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-16 08:40:06.140 ThaliTest[3555:8076182] Multi-tasking -> Device: YES, App: YES
,2016-11-16 08:40:06.167 ThaliTest[3555:8076182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 08:40:06.779 ThaliTest[3555:8076182] Using UIWebView
,2016-11-16 08:40:06.789 ThaliTest[3555:8076182] [CDVTimer][handleopenurl] 0.397980ms
,2016-11-16 08:40:06.797 ThaliTest[3555:8076182] [CDVTimer][intentandnavigationfilter] 6.887019ms
2016-11-16 08:40:06.798 ThaliTest[3555:8076182] [CDVTimer][gesturehandler] 0.298977ms
2016-11-16 08:40:06.798 ThaliTest[3555:8076182] [CDVTimer][TotalPluginS,tartup] 9.274006ms
,2016-11-16 08:40:12.785 ThaliTest[3555:8076182] Resetting plugins due to page load.
,2016-11-16 08:40:13.265 ThaliTest[3555:8076182] Finished load of: file:///var/containers/Bundle/Application/D6C40A39-6B10-4E51-93CB-420AE606FB94/ThaliTest.app/www/index.html
,2016-11-16 08:40:13.638 ThaliTest[3555:8076182] JXcore Cordova plugin initializing
,2016-11-16 08:40:13.639 ThaliTest[3555:8076339] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 16:40:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 16:40:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 16:40:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 16:40:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 16:40:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-16 16:40:47 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.55965501070023
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
