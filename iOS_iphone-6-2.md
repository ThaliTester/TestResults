#### Test 993933123c9286c_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/874EC9CC-81DD-40C6-B4B2-12D17DEFE2A1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/874EC9CC-81DD-40C6-B4B2-12D17DEFE2A1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2DC9BDE5-8557-4753-B89B-9790B52E005C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54770"
,(lldb)     command script import "/tmp/874EC9CC-81DD-40C6-B4B2-12D17DEFE2A1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 00:21:53.633 ThaliTest[1363:2464956] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8BBA2BBF-A3DD-4591-B08F-86C533842B8E/Library/Cookies/Cookies.binarycookies
,2016-12-27 00:21:53.697 ThaliTest[1363:2464956] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 00:21:53.699 ThaliTest[1363:2464956] Multi-tasking -> Device: YES, App: YES
,2016-12-27 00:21:53.720 ThaliTest[1363:2464956] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 00:21:54.079 ThaliTest[1363:2464956] Using UIWebView
,2016-12-27 00:21:54.084 ThaliTest[1363:2464956] [CDVTimer][handleopenurl] 0.220001ms
,2016-12-27 00:21:54.091 ThaliTest[1363:2464956] [CDVTimer][intentandnavigationfilter] 5.979002ms
2016-12-27 00:21:54.091 ThaliTest[1363:2464956] [CDVTimer][gesturehandler] 0.199974ms
2016-12-27 00:21:54.091 ThaliTest[1363:2464956] [CDVTimer][TotalPluginStartup] 7.565022ms
,2016-12-27 00:22:00.078 ThaliTest[1363:2464956] Resetting plugins due to page load.
,2016-12-27 00:22:00.426 ThaliTest[1363:2464956] Finished load of: file:///var/containers/Bundle/Application/2DC9BDE5-8557-4753-B89B-9790B52E005C/ThaliTest.app/www/index.html
,2016-12-27 00:22:00.754 ThaliTest[1363:2464956] JXcore Cordova plugin initializing
,2016-12-27 00:22:00.755 ThaliTest[1363:2465128] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 23:22:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 23:22:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 23:22:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-26 23:22:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 23:22:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 23:22:37 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.40866804122925
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
