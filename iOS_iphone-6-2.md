#### Test 992612784a4c081_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992612784a4c081/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7830A013-B66B-4356-951B-D924CAB38BB8/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7830A013-B66B-4356-951B-D924CAB38BB8/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992612784a4c081/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992612784a4c081/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1C070488-3AC6-4B59-A5B8-F0ECB3C2D568/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57411"
,(lldb)     command script import "/tmp/7830A013-B66B-4356-951B-D924CAB38BB8/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-23 18:10:43.097 ThaliTest[1191:2047397] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A7735107-847A-4FE4-9A58-A3B68F432BEF/Library/Cookies/Cookies.binarycookies
,2016-12-23 18:10:43.182 ThaliTest[1191:2047397] Apache Cordova native platform version 4.3.1 is starting.
2016-12-23 18:10:43.184 ThaliTest[1191:2047397] Multi-tasking -> Device: YES, App: YES
,2016-12-23 18:10:43.211 ThaliTest[1191:2047397] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-23 18:10:43.627 ThaliTest[1191:2047397] Using UIWebView
,2016-12-23 18:10:43.636 ThaliTest[1191:2047397] [CDVTimer][handleopenurl] 0.325978ms
,2016-12-23 18:10:43.645 ThaliTest[1191:2047397] [CDVTimer][intentandnavigationfilter] 8.453012ms
2016-12-23 18:10:43.645 ThaliTest[1191:2047397] [CDVTimer][gesturehandler] 0.288010ms
2016-12-23 18:10:43.646 ThaliTest[1191:2047397] [CDVTimer][TotalPluginStartup] 10.865033ms
,2016-12-23 18:10:49.314 ThaliTest[1191:2047397] Resetting plugins due to page load.
,2016-12-23 18:10:49.660 ThaliTest[1191:2047397] Finished load of: file:///var/containers/Bundle/Application/1C070488-3AC6-4B59-A5B8-F0ECB3C2D568/ThaliTest.app/www/index.html
,2016-12-23 18:10:50.006 ThaliTest[1191:2047397] JXcore Cordova plugin initializing
,2016-12-23 18:10:50.007 ThaliTest[1191:2047608] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-23 17:11:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-23 17:11:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-23 17:11:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-23 17:11:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-23 17:11:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-23 17:11:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.54382401704788
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
