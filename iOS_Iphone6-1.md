#### Test 944077483e9c5d2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4819AE79-2EC0-49B2-AA2E-A62FF3BAF301/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4819AE79-2EC0-49B2-AA2E-A62FF3BAF301/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7D2765C6-B299-4AD8-86AD-E8A8F124B07B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56614"
,(lldb)     command script import "/tmp/4819AE79-2EC0-49B2-AA2E-A62FF3BAF301/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 19:20:05.843 ThaliTest[3694:9341162] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/86A6298A-5D28-4520-8019-01CCF526458E/Library/Cookies/Cookies.binarycookies
,2016-11-18 19:20:05.912 ThaliTest[3694:9341162] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 19:20:05.914 ThaliTest[3694:9341162] Multi-tasking -> Device: YES, App: YES
,2016-11-18 19:20:05.932 ThaliTest[3694:9341162] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 19:20:06.273 ThaliTest[3694:9341162] Using UIWebView
,2016-11-18 19:20:06.279 ThaliTest[3694:9341162] [CDVTimer][handleopenurl] 0.328004ms
,2016-11-18 19:20:06.285 ThaliTest[3694:9341162] [CDVTimer][intentandnavigationfilter] 4.750967ms
2016-11-18 19:20:06.285 ThaliTest[3694:9341162] [CDVTimer][gesturehandler] 0.199020ms
2016-11-18 19:20:06.285 ThaliTest[3694:9341162] [CDVTimer][TotalPluginStartup] 6.487966ms
,2016-11-18 19:20:11.364 ThaliTest[3694:9341162] Resetting plugins due to page load.
,2016-11-18 19:20:11.637 ThaliTest[3694:9341162] Finished load of: file:///var/containers/Bundle/Application/7D2765C6-B299-4AD8-86AD-E8A8F124B07B/ThaliTest.app/www/index.html
,2016-11-18 19:20:11.997 ThaliTest[3694:9341162] JXcore Cordova plugin initializing
,2016-11-18 19:20:11.997 ThaliTest[3694:9341353] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:20:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:20:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:20:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:20:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 18:20:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 18:20:47 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.2234520316124
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
