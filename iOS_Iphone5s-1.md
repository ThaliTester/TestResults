#### Test 9376531757daca3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9376531757daca3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/856B00F0-8D2E-4139-A461-73B0A3A3C299/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/856B00F0-8D2E-4139-A461-73B0A3A3C299/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9376531757daca3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9376531757daca3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DFF9DDD7-3816-4988-9497-AD3465B05835/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57351"
,(lldb)     command script import "/tmp/856B00F0-8D2E-4139-A461-73B0A3A3C299/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 14:12:28.677 ThaliTest[5880:14873549] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FA06A12A-762D-4010-ABF7-E1C32E6044A2/Library/Cookies/Cookies.binarycookies
,2016-11-17 14:12:28.739 ThaliTest[5880:14873549] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 14:12:28.740 ThaliTest[5880:14873549] Multi-tasking -> Device: YES, App: YES
,2016-11-17 14:12:28.760 ThaliTest[5880:14873549] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 14:12:29.636 ThaliTest[5880:14873549] Using UIWebView
,2016-11-17 14:12:29.639 ThaliTest[5880:14873549] [CDVTimer][handleopenurl] 0.189006ms
,2016-11-17 14:12:29.643 ThaliTest[5880:14873549] [CDVTimer][intentandnavigationfilter] 2.927959ms
2016-11-17 14:12:29.643 ThaliTest[5880:14873549] [CDVTimer][gesturehandler] 0.141978ms
2016-11-17 14:12:29.643 ThaliTest[5880:14873549] [CDVTimer][TotalPlug,inStartup] 3.978968ms
,2016-11-17 14:12:32.980 ThaliTest[5880:14873549] Resetting plugins due to page load.
,2016-11-17 14:12:34.731 ThaliTest[5880:14873549] Finished load of: file:///var/mobile/Containers/Bundle/Application/DFF9DDD7-3816-4988-9497-AD3465B05835/ThaliTest.app/www/index.html
,2016-11-17 14:12:34.926 ThaliTest[5880:14873549] JXcore Cordova plugin initializing
,2016-11-17 14:12:34.927 ThaliTest[5880:14873727] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 13:12:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 13:12:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 13:12:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-17 13:12:47 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2016-11-17 13:12:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 13:13:11 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  23.85531502962112
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
