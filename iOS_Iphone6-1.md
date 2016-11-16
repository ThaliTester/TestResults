#### Test 933712696ecca49_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/933712696ecca49/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F362B831-69DE-482B-BA6D-4974E48EBA4F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F362B831-69DE-482B-BA6D-4974E48EBA4F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/933712696ecca49/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/933712696ecca49/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B5F93E5E-CC11-4EC3-993F-CF5A3F95BF29/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61300"
,(lldb)     command script import "/tmp/F362B831-69DE-482B-BA6D-4974E48EBA4F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 17:40:19.005 ThaliTest[3538:9043001] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AA87C25B-9143-4A3E-AD8B-9B3DC30ACA4F/Library/Cookies/Cookies.binarycookies
,2016-11-16 17:40:19.088 ThaliTest[3538:9043001] Apache Cordova native platform version 4.2.1 is starting.
2016-11-16 17:40:19.090 ThaliTest[3538:9043001] Multi-tasking -> Device: YES, App: YES
,2016-11-16 17:40:19.112 ThaliTest[3538:9043001] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 17:40:19.610 ThaliTest[3538:9043001] Using UIWebView
,2016-11-16 17:40:19.617 ThaliTest[3538:9043001] [CDVTimer][handleopenurl] 0.652015ms
,2016-11-16 17:40:19.624 ThaliTest[3538:9043001] [CDVTimer][intentandnavigationfilter] 7.002950ms
2016-11-16 17:40:19.625 ThaliTest[3538:9043001] [CDVTimer][gesturehandler] 0.292003ms
2016-11-16 17:40:19.626 ThaliTest[3538:9043001] [CDVTimer][TotalPluginStartup] 9.598017ms
,2016-11-16 17:40:26.539 ThaliTest[3538:9043001] Resetting plugins due to page load.
,2016-11-16 17:40:26.876 ThaliTest[3538:9043001] Finished load of: file:///var/containers/Bundle/Application/B5F93E5E-CC11-4EC3-993F-CF5A3F95BF29/ThaliTest.app/www/index.html
,2016-11-16 17:40:27.214 ThaliTest[3538:9043001] JXcore Cordova plugin initializing
,2016-11-16 17:40:27.214 ThaliTest[3538:9043240] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 16:40:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 16:40:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 16:40:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 16:40:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 16:40:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-16 16:41:02 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.25629901885986
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
