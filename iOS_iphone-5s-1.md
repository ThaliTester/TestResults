#### Test 99373674dc17873_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E3101798-E520-45F2-843F-E83160AEC51D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E3101798-E520-45F2-843F-E83160AEC51D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B2D9BD20-8254-4368-8F8A-AA65581996F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56599"
,(lldb)     command script import "/tmp/E3101798-E520-45F2-843F-E83160AEC51D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 10:51:41.532 ThaliTest[1481:3175896] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/64C447EA-F6FE-499E-AAC1-4207C8202F63/Library/Cookies/Cookies.binarycookies
,2016-12-27 10:51:41.646 ThaliTest[1481:3175896] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 10:51:41.649 ThaliTest[1481:3175896] Multi-tasking -> Device: YES, App: YES
,2016-12-27 10:51:41.674 ThaliTest[1481:3175896] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 10:51:43.215 ThaliTest[1481:3175896] Using UIWebView
,2016-12-27 10:51:43.224 ThaliTest[1481:3175896] [CDVTimer][handleopenurl] 0.569999ms
,2016-12-27 10:51:43.235 ThaliTest[1481:3175896] [CDVTimer][intentandnavigationfilter] 10.213971ms
2016-12-27 10:51:43.236 ThaliTest[1481:3175896] [CDVTimer][gesturehandler] 0.381052ms
2016-12-27 10:51:43.236 ThaliTest[1481:3175896] [CDVTimer][TotalPlugin,Startup] 13.158023ms
,2016-12-27 10:51:48.974 ThaliTest[1481:3175896] Resetting plugins due to page load.
,2016-12-27 10:51:52.278 ThaliTest[1481:3175896] Finished load of: file:///var/mobile/Containers/Bundle/Application/B2D9BD20-8254-4368-8F8A-AA65581996F0/ThaliTest.app/www/index.html
,2016-12-27 10:51:52.594 ThaliTest[1481:3175896] JXcore Cordova plugin initializing
,2016-12-27 10:51:52.596 ThaliTest[1481:3176112] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 09:52:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 09:52:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 09:52:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-27 09:52:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 09:52:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "found peer from another AppContext". in file: Optional("<unknown>"), line: 0
,2016-12-27 09:52:39 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  33.62117999792099
,Failed to execute UT.
,2016-12-27 09:52:39 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
