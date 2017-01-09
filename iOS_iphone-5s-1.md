#### Test 1006908264485454_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/078C8F59-57AF-46BA-863A-16974536A227/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/078C8F59-57AF-46BA-863A-16974536A227/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/41C72FD1-2E4B-47E4-94B0-872C5C2721D9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57299"
,(lldb)     command script import "/tmp/078C8F59-57AF-46BA-863A-16974536A227/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 15:40:32.456 ThaliTest[2158:5091494] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F447BC0A-8F7B-44C2-84FB-21BFB4230987/Library/Cookies/Cookies.binarycookies
,2017-01-09 15:40:32.525 ThaliTest[2158:5091494] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-09 15:40:32.527 ThaliTest[2158:5091494] Multi-tasking -> Device: YES, App: YES
,2017-01-09 15:40:32.544 ThaliTest[2158:5091494] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 15:40:33.377 ThaliTest[2158:5091494] Using UIWebView
,2017-01-09 15:40:33.381 ThaliTest[2158:5091494] [CDVTimer][handleopenurl] 0.180960ms
,2017-01-09 15:40:33.386 ThaliTest[2158:5091494] [CDVTimer][intentandnavigationfilter] 4.582047ms
2017-01-09 15:40:33.386 ThaliTest[2158:5091494] [CDVTimer][gesturehandler] 0.153959ms
2017-01-09 15:40:33.386 ThaliTest[2158:5091494] [CDVTimer][TotalPluginS,tartup] 5.689025ms
,2017-01-09 15:40:36.587 ThaliTest[2158:5091494] Resetting plugins due to page load.
,2017-01-09 15:40:38.065 ThaliTest[2158:5091494] Finished load of: file:///var/mobile/Containers/Bundle/Application/41C72FD1-2E4B-47E4-94B0-872C5C2721D9/ThaliTest.app/www/index.html
,2017-01-09 15:40:38.387 ThaliTest[2158:5091494] JXcore Cordova plugin initializing
2017-01-09 15:40:38.388 ThaliTest[2158:5091656] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-09 14:41:17 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.71255695819855
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
