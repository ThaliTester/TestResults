#### Test 896247960a9c9d6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/21928BEE-D1FC-410F-92AF-BCF647F7F936/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/21928BEE-D1FC-410F-92AF-BCF647F7F936/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960a9c9d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/243DCEED-D547-43CF-ABDE-920BEC129A3D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65242"
,(lldb)     command script import "/tmp/21928BEE-D1FC-410F-92AF-BCF647F7F936/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-10-18 16:11:58.525 ThaliTest[4433:10134051] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/886A5FD4-9DFD-443D-B30F-E88F6B2B29C4/Library/Cookies/Cookies.binarycookies
,2016-10-18 16:11:58.642 ThaliTest[4433:10134051] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 16:11:58.644 ThaliTest[4433:10134051] Multi-tasking -> Device: YES, App: YES
,2016-10-18 16:11:58.668 ThaliTest[4433:10134051] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 16:12:00.189 ThaliTest[4433:10134051] Using UIWebView
,2016-10-18 16:12:00.195 ThaliTest[4433:10134051] [CDVTimer][handleopenurl] 0.217021ms
,2016-10-18 16:12:00.201 ThaliTest[4433:10134051] [CDVTimer][intentandnavigationfilter] 5.796969ms
2016-10-18 16:12:00.202 ThaliTest[4433:10134051] [CDVTimer][gesturehandler] 0.208974ms
2016-10-18 16:12:00.202 ThaliTest[4433:10134051] [CDVTimer][TotalPlug,inStartup] 7.264018ms
,2016-10-18 16:12:05.677 ThaliTest[4433:10134051] Resetting plugins due to page load.
,2016-10-18 16:12:09.132 ThaliTest[4433:10134051] Finished load of: file:///var/mobile/Containers/Bundle/Application/243DCEED-D547-43CF-ABDE-920BEC129A3D/ThaliTest.app/www/index.html
,2016-10-18 16:12:09.442 ThaliTest[4433:10134051] JXcore Cordova plugin initializing
,2016-10-18 16:12:09.443 ThaliTest[4433:10134257] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x1356a0580> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x136fdee00> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-18 14:12:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  35.83757197856903
,Failed to execute UT.
,2016-10-18 14:12:58 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
