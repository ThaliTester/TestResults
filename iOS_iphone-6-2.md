#### Test 98912682a6d9d3f_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/19C8118E-515E-4D87-BC8D-22B7F0C55B87/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/19C8118E-515E-4D87-BC8D-22B7F0C55B87/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/425DB14F-5DD1-48D3-834A-6ECE175B0533/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59234"
,(lldb)     command script import "/tmp/19C8118E-515E-4D87-BC8D-22B7F0C55B87/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-21 19:25:59.942 ThaliTest[1089:1796572] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4A162D83-C104-4F4D-A824-C86FA5B62405/Library/Cookies/Cookies.binarycookies
,2016-12-21 19:25:59.982 ThaliTest[1089:1796572] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-21 19:25:59.983 ThaliTest[1089:1796572] Multi-tasking -> Device: YES, App: YES
,2016-12-21 19:25:59.999 ThaliTest[1089:1796572] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-21 19:26:00.321 ThaliTest[1089:1796572] Using UIWebView
2016-12-21 19:26:00.324 ThaliTest[1089:1796572] [CDVTimer][handleopenurl] 0.142992ms
,2016-12-21 19:26:00.330 ThaliTest[1089:1796572] [CDVTimer][intentandnavigationfilter] 5.796015ms
2016-12-21 19:26:00.331 ThaliTest[1089:1796572] [CDVTimer][gesturehandler] 0.154972ms
2016-12-21 19:26:00.331 ThaliTest[1089:1796572] [CDVTimer][TotalPluginStartup] 6.849945ms
,2016-12-21 19:26:06.345 ThaliTest[1089:1796572] Resetting plugins due to page load.
,2016-12-21 19:26:06.691 ThaliTest[1089:1796572] Finished load of: file:///var/containers/Bundle/Application/425DB14F-5DD1-48D3-834A-6ECE175B0533/ThaliTest.app/www/index.html
,2016-12-21 19:26:07.042 ThaliTest[1089:1796572] JXcore Cordova plugin initializing
,2016-12-21 19:26:07.043 ThaliTest[1089:1796777] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-21 18:26:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-21 18:26:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-21 18:26:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2016-12-21 18:26:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-21 18:26:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-21 18:26:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.47315299510956
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
