#### Test 8962479670bc939_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479670bc939/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/378369F9-BBF7-458B-912A-506EF6C681F8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/378369F9-BBF7-458B-912A-506EF6C681F8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479670bc939/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479670bc939/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8F6E797D-EFA2-4625-A636-4B55D96F7059/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52861"
,(lldb)     command script import "/tmp/378369F9-BBF7-458B-912A-506EF6C681F8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-08 17:40:50.261 ThaliTest[5248:11275603] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05F04E67-87EE-4F2D-A091-9C90308F7D44/Library/Cookies/Cookies.binarycookies
,2016-11-08 17:40:50.638 ThaliTest[5248:11275603] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 17:40:50.639 ThaliTest[5248:11275603] Multi-tasking -> Device: YES, App: YES
,2016-11-08 17:40:50.658 ThaliTest[5248:11275603] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 17:40:52.636 ThaliTest[5248:11275603] Using UIWebView
,2016-11-08 17:40:52.642 ThaliTest[5248:11275603] [CDVTimer][handleopenurl] 0.320971ms
,2016-11-08 17:40:52.650 ThaliTest[5248:11275603] [CDVTimer][intentandnavigationfilter] 7.103026ms
,2016-11-08 17:40:52.651 ThaliTest[5248:11275603] [CDVTimer][gesturehandler] 0.289977ms
,2016-11-08 17:40:52.651 ThaliTest[5248:11275603] [CDVTimer][TotalPluginStartup] 9.248018ms
,2016-11-08 17:40:59.189 ThaliTest[5248:11275603] Resetting plugins due to page load.
,2016-11-08 17:41:03.057 ThaliTest[5248:11275603] Finished load of: file:///var/mobile/Containers/Bundle/Application/8F6E797D-EFA2-4625-A636-4B55D96F7059/ThaliTest.app/www/index.html
,2016-11-08 17:41:03.228 ThaliTest[5248:11275603] JXcore Cordova plugin initializing
,2016-11-08 17:41:03.229 ThaliTest[5248:11275877] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 16:41:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 16:41:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 16:41:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-08 16:41:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 16:41:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-08 16:41:47 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  34.20303398370743
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
