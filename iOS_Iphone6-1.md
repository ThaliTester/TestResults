#### Test 93371269c81e6ec_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/46A5D5CA-EC03-42DA-BDAA-0790780D5769/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/46A5D5CA-EC03-42DA-BDAA-0790780D5769/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/14501685-46DA-4B83-9F9D-6788DF990B91/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57414"
,(lldb)     command script import "/tmp/46A5D5CA-EC03-42DA-BDAA-0790780D5769/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 19:44:52.352 ThaliTest[3702:9344486] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/94C64B5F-57F0-4C35-8C78-6F68BCB65FD8/Library/Cookies/Cookies.binarycookies
,2016-11-18 19:44:52.393 ThaliTest[3702:9344486] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 19:44:52.394 ThaliTest[3702:9344486] Multi-tasking -> Device: YES, App: YES
,2016-11-18 19:44:52.406 ThaliTest[3702:9344486] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 19:44:52.695 ThaliTest[3702:9344486] Using UIWebView
,2016-11-18 19:44:52.698 ThaliTest[3702:9344486] [CDVTimer][handleopenurl] 0.263035ms
,2016-11-18 19:44:52.702 ThaliTest[3702:9344486] [CDVTimer][intentandnavigationfilter] 2.839029ms
2016-11-18 19:44:52.702 ThaliTest[3702:9344486] [CDVTimer][gesturehandler] 0.108004ms
2016-11-18 19:44:52.702 ThaliTest[3702:9344486] [CDVTimer][TotalPluginStartup] 3.926039ms
,2016-11-18 19:44:58.722 ThaliTest[3702:9344486] Resetting plugins due to page load.
,2016-11-18 19:44:59.195 ThaliTest[3702:9344486] Finished load of: file:///var/containers/Bundle/Application/14501685-46DA-4B83-9F9D-6788DF990B91/ThaliTest.app/www/index.html
,2016-11-18 19:44:59.590 ThaliTest[3702:9344486] JXcore Cordova plugin initializing
2016-11-18 19:44:59.590 ThaliTest[3702:9344699] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:45:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:45:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:45:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:45:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 18:45:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 18:45:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.65203803777695
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteringBackground wasn't registered

```
