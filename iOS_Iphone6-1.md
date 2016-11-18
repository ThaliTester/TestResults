#### Test 921522864f1c710_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A1FE63DA-7F7F-43F1-B610-95A62754EC32/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A1FE63DA-7F7F-43F1-B610-95A62754EC32/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/846A5D87-BE2E-4FD5-B03B-D8F3E6C9463D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63267"
,(lldb)     command script import "/tmp/A1FE63DA-7F7F-43F1-B610-95A62754EC32/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 14:31:02.820 ThaliTest[3672:9310109] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0972322E-C673-4B87-B87C-E78A663F24AA/Library/Cookies/Cookies.binarycookies
,2016-11-18 14:31:02.863 ThaliTest[3672:9310109] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 14:31:02.864 ThaliTest[3672:9310109] Multi-tasking -> Device: YES, App: YES
,2016-11-18 14:31:02.878 ThaliTest[3672:9310109] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 14:31:03.158 ThaliTest[3672:9310109] Using UIWebView
,2016-11-18 14:31:03.161 ThaliTest[3672:9310109] [CDVTimer][handleopenurl] 0.147998ms
,2016-11-18 14:31:03.164 ThaliTest[3672:9310109] [CDVTimer][intentandnavigationfilter] 2.744019ms
2016-11-18 14:31:03.164 ThaliTest[3672:9310109] [CDVTimer][gesturehandler] 0.117958ms
2016-11-18 14:31:03.165 ThaliTest[3672:9310109] [CDVTimer][TotalPluginStartup] 3.707051ms
,2016-11-18 14:31:08.421 ThaliTest[3672:9310109] Resetting plugins due to page load.
,2016-11-18 14:31:08.714 ThaliTest[3672:9310109] Finished load of: file:///var/containers/Bundle/Application/846A5D87-BE2E-4FD5-B03B-D8F3E6C9463D/ThaliTest.app/www/index.html
,2016-11-18 14:31:09.060 ThaliTest[3672:9310109] JXcore Cordova plugin initializing
,2016-11-18 14:31:09.061 ThaliTest[3672:9310278] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-18 13:31:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 13:31:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 13:31:45 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.3427619934082
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
