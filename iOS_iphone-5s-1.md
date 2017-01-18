#### Test 1019105739e32531_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/83C034DB-2528-4F59-8DC0-E90E314E3F63/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/83C034DB-2528-4F59-8DC0-E90E314E3F63/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/588BB5D5-54D2-45D3-9584-4D117F56FD04/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63283"
,(lldb)     command script import "/tmp/83C034DB-2528-4F59-8DC0-E90E314E3F63/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-18 14:00:44.774 ThaliTest[2502:6116500] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD58F2B3-0071-4D12-A071-83BA484F1B64/Library/Cookies/Cookies.binarycookies
,2017-01-18 14:00:44.840 ThaliTest[2502:6116500] Apache Cordova native platform version 4.3.1 is starting.
2017-01-18 14:00:44.841 ThaliTest[2502:6116500] Multi-tasking -> Device: YES, App: YES
,2017-01-18 14:00:44.861 ThaliTest[2502:6116500] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-18 14:00:45.678 ThaliTest[2502:6116500] Using UIWebView
2017-01-18 14:00:45.682 ThaliTest[2502:6116500] [CDVTimer][handleopenurl] 0.155985ms
,2017-01-18 14:00:45.686 ThaliTest[2502:6116500] [CDVTimer][intentandnavigationfilter] 4.360974ms
2017-01-18 14:00:45.687 ThaliTest[2502:6116500] [CDVTimer][gesturehandler] 0.169992ms
2017-01-18 14:00:45.687 ThaliTest[2502:6116500] [CDVTimer][TotalPluginS,tartup] 5.474031ms
,2017-01-18 14:00:48.956 ThaliTest[2502:6116500] Resetting plugins due to page load.
,2017-01-18 14:00:50.802 ThaliTest[2502:6116500] Finished load of: file:///var/mobile/Containers/Bundle/Application/588BB5D5-54D2-45D3-9584-4D117F56FD04/ThaliTest.app/www/index.html
,2017-01-18 14:00:51.010 ThaliTest[2502:6116500] JXcore Cordova plugin initializing
,2017-01-18 14:00:51.011 ThaliTest[2502:6116687] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-18 13:01:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-18 13:01:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-18 13:01:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-18 13:01:06 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2017-01-18 13:01:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-18 13:01:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.57627201080322
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
