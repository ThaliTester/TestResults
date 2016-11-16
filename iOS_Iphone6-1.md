#### Test 93986313a169e88_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1BC0C141-9976-4867-B8A6-123B13417911/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1BC0C141-9976-4867-B8A6-123B13417911/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93986313a169e88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BC5711CB-6E4A-46F7-BF64-7A8772E22703/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59895"
,(lldb)     command script import "/tmp/1BC0C141-9976-4867-B8A6-123B13417911/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 17:09:18.796 ThaliTest[3527:9038888] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D7E340AA-002D-4F9C-BA3A-7123FAA75165/Library/Cookies/Cookies.binarycookies
,2016-11-16 17:09:18.832 ThaliTest[3527:9038888] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-16 17:09:18.833 ThaliTest[3527:9038888] Multi-tasking -> Device: YES, App: YES
,2016-11-16 17:09:18.846 ThaliTest[3527:9038888] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 17:09:19.136 ThaliTest[3527:9038888] Using UIWebView
,2016-11-16 17:09:19.139 ThaliTest[3527:9038888] [CDVTimer][handleopenurl] 0.205994ms
,2016-11-16 17:09:19.143 ThaliTest[3527:9038888] [CDVTimer][intentandnavigationfilter] 3.576040ms
2016-11-16 17:09:19.144 ThaliTest[3527:9038888] [CDVTimer][gesturehandler] 0.141025ms
2016-11-16 17:09:19.144 ThaliTest[3527:9038888] [CDVTimer][TotalPluginStartup] 4.729033ms
,2016-11-16 17:09:24.831 ThaliTest[3527:9038888] Resetting plugins due to page load.
,2016-11-16 17:09:25.222 ThaliTest[3527:9038888] Finished load of: file:///var/containers/Bundle/Application/BC5711CB-6E4A-46F7-BF64-7A8772E22703/ThaliTest.app/www/index.html
,2016-11-16 17:09:25.555 ThaliTest[3527:9038888] JXcore Cordova plugin initializing
2016-11-16 17:09:25.555 ThaliTest[3527:9039065] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 16:09:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 16:09:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 16:09:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 16:09:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 16:09:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-16 16:10:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.2997630238533
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
