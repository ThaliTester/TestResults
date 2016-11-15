#### Test 93765317fadb314_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/68DF784C-AD5F-4EF5-BD66-000F8E7F503E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/68DF784C-AD5F-4EF5-BD66-000F8E7F503E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F2E22F46-A6F4-4389-8879-BAF4D0B5AA4A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57420"
,(lldb)     command script import "/tmp/68DF784C-AD5F-4EF5-BD66-000F8E7F503E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 15:51:52.246 ThaliTest[5716:14569284] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2CB16D58-7E17-40BD-81BE-1BD6566D42A0/Library/Cookies/Cookies.binarycookies
,2016-11-15 15:51:52.310 ThaliTest[5716:14569284] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-15 15:51:52.311 ThaliTest[5716:14569284] Multi-tasking -> Device: YES, App: YES
,2016-11-15 15:51:52.329 ThaliTest[5716:14569284] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 15:51:53.103 ThaliTest[5716:14569284] Using UIWebView
2016-11-15 15:51:53.106 ThaliTest[5716:14569284] [CDVTimer][handleopenurl] 0.162005ms
2016-11-15 15:51:53.108 ThaliTest[5716:14569284] [CDVTimer][intentandnavigationfilter] 2.707958ms
2016,-11-15 15:51:53.109 ThaliTest[5716:14569284] [CDVTimer][gesturehandler] 0.129998ms
2016-11-15 15:51:53.109 ThaliTest[5716:14569284] [CDVTimer][TotalPluginStartup] 3.609002ms
,2016-11-15 15:51:56.107 ThaliTest[5716:14569284] Resetting plugins due to page load.
,2016-11-15 15:51:57.749 ThaliTest[5716:14569284] Finished load of: file:///var/mobile/Containers/Bundle/Application/F2E22F46-A6F4-4389-8879-BAF4D0B5AA4A/ThaliTest.app/www/index.html
,2016-11-15 15:51:57.758 ThaliTest[5716:14569284] JXcore Cordova plugin initializing
,2016-11-15 15:51:57.759 ThaliTest[5716:14569450] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 14:52:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 14:52:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 14:52:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-15 14:52:10 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2016-11-15 14:52:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-15 14:52:34 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.44830602407455
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
