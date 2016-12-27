#### Test 99435972548f19d_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99435972548f19d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/713FC364-1556-4FA4-86B1-86D13B1E65C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/713FC364-1556-4FA4-86B1-86D13B1E65C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99435972548f19d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99435972548f19d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1047C972-069D-4968-BB3F-ED51A16A0C4D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63301"
,(lldb)     command script import "/tmp/713FC364-1556-4FA4-86B1-86D13B1E65C5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 13:49:19.608 ThaliTest[1499:3197042] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/654A59C5-50D6-4C65-BF47-FDB916031338/Library/Cookies/Cookies.binarycookies
,2016-12-27 13:49:19.725 ThaliTest[1499:3197042] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 13:49:19.727 ThaliTest[1499:3197042] Multi-tasking -> Device: YES, App: YES
,2016-12-27 13:49:19.750 ThaliTest[1499:3197042] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 13:49:21.266 ThaliTest[1499:3197042] Using UIWebView
,2016-12-27 13:49:21.278 ThaliTest[1499:3197042] [CDVTimer][handleopenurl] 0.433028ms
,2016-12-27 13:49:21.288 ThaliTest[1499:3197042] [CDVTimer][intentandnavigationfilter] 9.680986ms
2016-12-27 13:49:21.289 ThaliTest[1499:3197042] [CDVTimer][gesturehandler] 0.384033ms
2016-12-27 13:49:21.289 ThaliTest[1499:3197042] [CDVTimer][TotalPluginS,tartup] 12.567043ms
,2016-12-27 13:49:27.037 ThaliTest[1499:3197042] Resetting plugins due to page load.
,2016-12-27 13:49:29.677 ThaliTest[1499:3197042] Finished load of: file:///var/mobile/Containers/Bundle/Application/1047C972-069D-4968-BB3F-ED51A16A0C4D/ThaliTest.app/www/index.html
,2016-12-27 13:49:30.075 ThaliTest[1499:3197042] JXcore Cordova plugin initializing
,2016-12-27 13:49:30.076 ThaliTest[1499:3197239] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 12:49:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 12:49:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 12:49:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 12:49:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 12:49:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 12:50:08 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.32532101869583
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
