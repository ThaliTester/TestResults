#### Test 933712690a22074_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/933712690a22074/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FBB2F2A6-5926-408A-B23D-2903C92ED7A1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/FBB2F2A6-5926-408A-B23D-2903C92ED7A1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/933712690a22074/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/933712690a22074/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B4010377-DAAF-4756-A91E-6574843AF93A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50008"
,(lldb)     command script import "/tmp/FBB2F2A6-5926-408A-B23D-2903C92ED7A1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-16 13:26:14.171 ThaliTest[3518:9016995] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0946A64F-28F3-4BA2-8C17-3F696E33EED8/Library/Cookies/Cookies.binarycookies
,2016-11-16 13:26:14.222 ThaliTest[3518:9016995] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-16 13:26:14.223 ThaliTest[3518:9016995] Multi-tasking -> Device: YES, App: YES
,2016-11-16 13:26:14.237 ThaliTest[3518:9016995] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-16 13:26:14.533 ThaliTest[3518:9016995] Using UIWebView
,2016-11-16 13:26:14.538 ThaliTest[3518:9016995] [CDVTimer][handleopenurl] 0.190020ms
,2016-11-16 13:26:14.542 ThaliTest[3518:9016995] [CDVTimer][intentandnavigationfilter] 3.471971ms
2016-11-16 13:26:14.542 ThaliTest[3518:9016995] [CDVTimer][gesturehandler] 0.151038ms
2016-11-16 13:26:14.542 ThaliTest[3518:9016995] [CDVTimer][TotalPluginS,tartup] 4.656017ms
,2016-11-16 13:26:19.886 ThaliTest[3518:9016995] Resetting plugins due to page load.
,2016-11-16 13:26:20.230 ThaliTest[3518:9016995] Finished load of: file:///var/containers/Bundle/Application/B4010377-DAAF-4756-A91E-6574843AF93A/ThaliTest.app/www/index.html
,2016-11-16 13:26:20.570 ThaliTest[3518:9016995] JXcore Cordova plugin initializing
,2016-11-16 13:26:20.571 ThaliTest[3518:9017209] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-16 12:26:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-16 12:26:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-16 12:26:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-16 12:26:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-16 12:26:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-16 12:26:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.21197605133057
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
