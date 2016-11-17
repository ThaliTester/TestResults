#### Test 9378027201b8727_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9378027201b8727/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F7134828-2F09-44C6-8CEF-FB32872B7D75/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F7134828-2F09-44C6-8CEF-FB32872B7D75/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9378027201b8727/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9378027201b8727/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/23C65ED9-D073-46DD-A145-5C0942A26760/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64234"
,(lldb)     command script import "/tmp/F7134828-2F09-44C6-8CEF-FB32872B7D75/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 09:41:04.158 ThaliTest[3582:9136668] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D016254A-91D8-4D3C-9B98-EEC67B4F63BE/Library/Cookies/Cookies.binarycookies
,2016-11-17 09:41:04.198 ThaliTest[3582:9136668] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 09:41:04.199 ThaliTest[3582:9136668] Multi-tasking -> Device: YES, App: YES
,2016-11-17 09:41:04.213 ThaliTest[3582:9136668] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 09:41:04.522 ThaliTest[3582:9136668] Using UIWebView
,2016-11-17 09:41:04.526 ThaliTest[3582:9136668] [CDVTimer][handleopenurl] 0.187993ms
,2016-11-17 09:41:04.529 ThaliTest[3582:9136668] [CDVTimer][intentandnavigationfilter] 3.482997ms
2016-11-17 09:41:04.530 ThaliTest[3582:9136668] [CDVTimer][gesturehandler] 0.158966ms
2016-11-17 09:41:04.530 ThaliTest[3582:9136668] [CDVTimer][TotalPluginStartup] 4.674017ms
,2016-11-17 09:41:09.727 ThaliTest[3582:9136668] Resetting plugins due to page load.
,2016-11-17 09:41:10.054 ThaliTest[3582:9136668] Finished load of: file:///var/containers/Bundle/Application/23C65ED9-D073-46DD-A145-5C0942A26760/ThaliTest.app/www/index.html
,2016-11-17 09:41:10.390 ThaliTest[3582:9136668] JXcore Cordova plugin initializing
2016-11-17 09:41:10.391 ThaliTest[3582:9136864] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 08:41:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 08:41:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 08:41:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 08:41:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 08:41:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 08:41:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.1793469786644
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
