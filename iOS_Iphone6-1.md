#### Test 9357216729ac2d0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/95908C76-6F70-4626-942A-D47444100AD6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/95908C76-6F70-4626-942A-D47444100AD6/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/83C00991-D046-4635-9478-CD5E779A471F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52318"
,(lldb)     command script import "/tmp/95908C76-6F70-4626-942A-D47444100AD6/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 12:16:42.931 ThaliTest[3607:9155684] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9A8D2B5B-E933-463F-99DF-E13FD8F271CB/Library/Cookies/Cookies.binarycookies
,2016-11-17 12:16:43.006 ThaliTest[3607:9155684] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 12:16:43.008 ThaliTest[3607:9155684] Multi-tasking -> Device: YES, App: YES
,2016-11-17 12:16:43.025 ThaliTest[3607:9155684] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 12:16:43.399 ThaliTest[3607:9155684] Using UIWebView
,2016-11-17 12:16:43.408 ThaliTest[3607:9155684] [CDVTimer][handleopenurl] 0.483990ms
,2016-11-17 12:16:43.415 ThaliTest[3607:9155684] [CDVTimer][intentandnavigationfilter] 6.880999ms
2016-11-17 12:16:43.416 ThaliTest[3607:9155684] [CDVTimer][gesturehandler] 0.289023ms
2016-11-17 12:16:43.416 ThaliTest[3607:9155684] [CDVTimer][TotalPluginStartup] 9.284019ms
,2016-11-17 12:16:49.277 ThaliTest[3607:9155684] Resetting plugins due to page load.
,2016-11-17 12:16:49.790 ThaliTest[3607:9155684] Finished load of: file:///var/containers/Bundle/Application/83C00991-D046-4635-9478-CD5E779A471F/ThaliTest.app/www/index.html
,2016-11-17 12:16:50.170 ThaliTest[3607:9155684] JXcore Cordova plugin initializing
,2016-11-17 12:16:50.171 ThaliTest[3607:9155853] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 11:17:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 11:17:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 11:17:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 11:17:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 11:17:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 11:17:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.65866899490356
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
