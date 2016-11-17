#### Test 937653172c2e8c7_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/67895049-80DD-4530-8048-61407BDCA35D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/67895049-80DD-4530-8048-61407BDCA35D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9BEE70A0-6D31-4BD8-B1BB-AB29E4C3EFEC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51282"
,(lldb)     command script import "/tmp/67895049-80DD-4530-8048-61407BDCA35D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 11:52:00.185 ThaliTest[3599:9152219] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/853900DF-CEDC-476F-99BF-A41EEDBE55A4/Library/Cookies/Cookies.binarycookies
,2016-11-17 11:52:00.226 ThaliTest[3599:9152219] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 11:52:00.227 ThaliTest[3599:9152219] Multi-tasking -> Device: YES, App: YES
,2016-11-17 11:52:00.240 ThaliTest[3599:9152219] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 11:52:00.512 ThaliTest[3599:9152219] Using UIWebView
,2016-11-17 11:52:00.517 ThaliTest[3599:9152219] [CDVTimer][handleopenurl] 0.151992ms
,2016-11-17 11:52:00.519 ThaliTest[3599:9152219] [CDVTimer][intentandnavigationfilter] 2.647996ms
2016-11-17 11:52:00.520 ThaliTest[3599:9152219] [CDVTimer][gesturehandler] 0.123024ms
2016-11-17 11:52:00.520 ThaliTest[3599:9152219] [CDVTimer][TotalPluginStartup] 3.578007ms
,2016-11-17 11:52:05.731 ThaliTest[3599:9152219] Resetting plugins due to page load.
,2016-11-17 11:52:06.016 ThaliTest[3599:9152219] Finished load of: file:///var/containers/Bundle/Application/9BEE70A0-6D31-4BD8-B1BB-AB29E4C3EFEC/ThaliTest.app/www/index.html
,2016-11-17 11:52:06.356 ThaliTest[3599:9152219] JXcore Cordova plugin initializing
,2016-11-17 11:52:06.357 ThaliTest[3599:9152407] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 10:52:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 10:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 10:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 10:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 10:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 10:52:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.98844397068024
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
