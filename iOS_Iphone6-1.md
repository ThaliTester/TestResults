#### Test 93765317fadb314_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B7EDF195-3A45-4440-8A6F-86745C54CE97/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B7EDF195-3A45-4440-8A6F-86745C54CE97/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/857DEF91-443C-413B-AE20-46F68138B6F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57423"
,(lldb)     command script import "/tmp/B7EDF195-3A45-4440-8A6F-86745C54CE97/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 15:52:06.991 ThaliTest[3461:8888852] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5461AE03-C59B-41B0-97F2-F00A96200A46/Library/Cookies/Cookies.binarycookies
,2016-11-15 15:52:07.031 ThaliTest[3461:8888852] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-15 15:52:07.033 ThaliTest[3461:8888852] Multi-tasking -> Device: YES, App: YES
,2016-11-15 15:52:07.046 ThaliTest[3461:8888852] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 15:52:07.332 ThaliTest[3461:8888852] Using UIWebView
,2016-11-15 15:52:07.336 ThaliTest[3461:8888852] [CDVTimer][handleopenurl] 0.271976ms
,2016-11-15 15:52:07.339 ThaliTest[3461:8888852] [CDVTimer][intentandnavigationfilter] 3.203034ms
2016-11-15 15:52:07.339 ThaliTest[3461:8888852] [CDVTimer][gesturehandler] 0.109971ms
2016-11-15 15:52:07.339 ThaliTest[3461:8888852] [CDVTimer][TotalPluginStartup] 4.301965ms
,2016-11-15 15:52:13.013 ThaliTest[3461:8888852] Resetting plugins due to page load.
,2016-11-15 15:52:13.442 ThaliTest[3461:8888852] Finished load of: file:///var/containers/Bundle/Application/857DEF91-443C-413B-AE20-46F68138B6F4/ThaliTest.app/www/index.html
,2016-11-15 15:52:13.787 ThaliTest[3461:8888852] JXcore Cordova plugin initializing
,2016-11-15 15:52:13.789 ThaliTest[3461:8889025] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-15 14:52:49 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.35573601722717
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
