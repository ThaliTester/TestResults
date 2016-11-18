#### Test 93765317141d42a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93765317141d42a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/011FDDB8-D707-4B0E-A22C-F306408C749E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/011FDDB8-D707-4B0E-A22C-F306408C749E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93765317141d42a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93765317141d42a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D07D215A-840C-47B0-A0D1-6C331AB77F24/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54572"
,(lldb)     command script import "/tmp/011FDDB8-D707-4B0E-A22C-F306408C749E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 16:48:03.447 ThaliTest[3682:9324415] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/973F0464-1DEE-4F4C-A237-60C04BCBB2B4/Library/Cookies/Cookies.binarycookies
,2016-11-18 16:48:03.492 ThaliTest[3682:9324415] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 16:48:03.493 ThaliTest[3682:9324415] Multi-tasking -> Device: YES, App: YES
,2016-11-18 16:48:03.504 ThaliTest[3682:9324415] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 16:48:03.799 ThaliTest[3682:9324415] Using UIWebView
,2016-11-18 16:48:03.804 ThaliTest[3682:9324415] [CDVTimer][handleopenurl] 0.168025ms
,2016-11-18 16:48:03.807 ThaliTest[3682:9324415] [CDVTimer][intentandnavigationfilter] 2.712965ms
2016-11-18 16:48:03.808 ThaliTest[3682:9324415] [CDVTimer][gesturehandler] 0.108004ms
2016-11-18 16:48:03.808 ThaliTest[3682:9324415] [CDVTimer][TotalPluginStartup] 3.638029ms
,2016-11-18 16:48:08.910 ThaliTest[3682:9324415] Resetting plugins due to page load.
,2016-11-18 16:48:09.220 ThaliTest[3682:9324415] Finished load of: file:///var/containers/Bundle/Application/D07D215A-840C-47B0-A0D1-6C331AB77F24/ThaliTest.app/www/index.html
,2016-11-18 16:48:09.556 ThaliTest[3682:9324415] JXcore Cordova plugin initializing
,2016-11-18 16:48:09.557 ThaliTest[3682:9324613] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 15:48:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 15:48:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 15:48:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 15:48:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 15:48:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 15:48:45 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.5925589799881
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
