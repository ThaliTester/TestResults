#### Test 93572167fd0bc1d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93572167fd0bc1d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/563FC5CF-8BFD-4065-A66C-7D83631C3FF3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/563FC5CF-8BFD-4065-A66C-7D83631C3FF3/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93572167fd0bc1d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93572167fd0bc1d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7F5A2937-9A28-44E1-BA94-CEBB7B65ACCB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62763"
,(lldb)     command script import "/tmp/563FC5CF-8BFD-4065-A66C-7D83631C3FF3/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 18:34:56.476 ThaliTest[3547:9049793] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7A25A8A8-6575-4C3F-B567-EA1BF553AEA6/Library/Cookies/Cookies.binarycookies
,2016-11-16 18:34:56.577 ThaliTest[3547:9049793] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-16 18:34:56.580 ThaliTest[3547:9049793] Multi-tasking -> Device: YES, App: YES
,2016-11-16 18:34:56.608 ThaliTest[3547:9049793] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 18:34:57.213 ThaliTest[3547:9049793] Using UIWebView
2016-11-16 18:34:57.220 ThaliTest[3547:9049793] [CDVTimer][handleopenurl] 0.367999ms
,2016-11-16 18:34:57.228 ThaliTest[3547:9049793] [CDVTimer][intentandnavigationfilter] 8.014023ms
2016-11-16 18:34:57.230 ThaliTest[3547:9049793] [CDVTimer][gesturehandler] 0.371039ms
2016-11-16 18:34:57.230 ThaliTest[3547:9049793] [CDVTimer][TotalPluginS,tartup] 10.991991ms
,2016-11-16 18:35:03.822 ThaliTest[3547:9049793] Resetting plugins due to page load.
,2016-11-16 18:35:04.325 ThaliTest[3547:9049793] Finished load of: file:///var/containers/Bundle/Application/7F5A2937-9A28-44E1-BA94-CEBB7B65ACCB/ThaliTest.app/www/index.html
,2016-11-16 18:35:04.667 ThaliTest[3547:9049793] JXcore Cordova plugin initializing
,2016-11-16 18:35:04.668 ThaliTest[3547:9049986] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 17:35:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 17:35:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 17:35:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 17:35:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 17:35:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-16 17:35:39 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.26790297031403
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
