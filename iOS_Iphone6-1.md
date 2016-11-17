#### Test 935721672ca5349_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/43BBC08A-10F3-4601-B1E3-83EECD5BE716/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/43BBC08A-10F3-4601-B1E3-83EECD5BE716/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721672ca5349/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8866C7D8-42AE-4A35-992B-5069426328FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58657"
,(lldb)     command script import "/tmp/43BBC08A-10F3-4601-B1E3-83EECD5BE716/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 14:37:24.668 ThaliTest[3627:9171555] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F06A03C1-4EF4-4D55-9A5D-7F5C978A5907/Library/Cookies/Cookies.binarycookies
,2016-11-17 14:37:24.745 ThaliTest[3627:9171555] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 14:37:24.747 ThaliTest[3627:9171555] Multi-tasking -> Device: YES, App: YES
,2016-11-17 14:37:24.766 ThaliTest[3627:9171555] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 14:37:25.127 ThaliTest[3627:9171555] Using UIWebView
,2016-11-17 14:37:25.131 ThaliTest[3627:9171555] [CDVTimer][handleopenurl] 0.334978ms
,2016-11-17 14:37:25.136 ThaliTest[3627:9171555] [CDVTimer][intentandnavigationfilter] 4.728019ms
2016-11-17 14:37:25.137 ThaliTest[3627:9171555] [CDVTimer][gesturehandler] 0.200987ms
2016-11-17 14:37:25.137 ThaliTest[3627:9171555] [CDVTimer][TotalPluginS,tartup] 6.404996ms
,2016-11-17 14:37:30.493 ThaliTest[3627:9171555] Resetting plugins due to page load.
,2016-11-17 14:37:30.761 ThaliTest[3627:9171555] Finished load of: file:///var/containers/Bundle/Application/8866C7D8-42AE-4A35-992B-5069426328FF/ThaliTest.app/www/index.html
,2016-11-17 14:37:31.098 ThaliTest[3627:9171555] JXcore Cordova plugin initializing
,2016-11-17 14:37:31.099 ThaliTest[3627:9171738] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 13:37:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 13:37:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 13:37:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 13:37:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 13:37:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 13:38:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.59910798072815
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
