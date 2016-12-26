#### Test 99374565da5d395_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565da5d395/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7B4DC3FA-E585-4EF2-B039-415C0F41A532/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7B4DC3FA-E585-4EF2-B039-415C0F41A532/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565da5d395/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565da5d395/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/477E2CBE-5AF0-41BD-9D72-C9888006C3B2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52954"
,(lldb)     command script import "/tmp/7B4DC3FA-E585-4EF2-B039-415C0F41A532/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 17:51:28.755 ThaliTest[1439:3067119] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EACC6CD6-728D-4DAA-85BC-2F98B55D3B2F/Library/Cookies/Cookies.binarycookies
,2016-12-26 17:51:28.875 ThaliTest[1439:3067119] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 17:51:28.878 ThaliTest[1439:3067119] Multi-tasking -> Device: YES, App: YES
,2016-12-26 17:51:28.903 ThaliTest[1439:3067119] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 17:51:30.432 ThaliTest[1439:3067119] Using UIWebView
,2016-12-26 17:51:30.440 ThaliTest[1439:3067119] [CDVTimer][handleopenurl] 0.422001ms
,2016-12-26 17:51:30.451 ThaliTest[1439:3067119] [CDVTimer][intentandnavigationfilter] 9.912014ms
2016-12-26 17:51:30.451 ThaliTest[1439:3067119] [CDVTimer][gesturehandler] 0.387013ms
2016-12-26 17:51:30.452 ThaliTest[1439:3067119] [CDVTimer][TotalPluginS,tartup] 12.836993ms
,2016-12-26 17:51:36.166 ThaliTest[1439:3067119] Resetting plugins due to page load.
,2016-12-26 17:51:39.575 ThaliTest[1439:3067119] Finished load of: file:///var/mobile/Containers/Bundle/Application/477E2CBE-5AF0-41BD-9D72-C9888006C3B2/ThaliTest.app/www/index.html
,2016-12-26 17:51:39.879 ThaliTest[1439:3067119] JXcore Cordova plugin initializing
,2016-12-26 17:51:39.881 ThaliTest[1439:3067356] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 16:51:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 16:51:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 16:51:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-26 16:51:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 16:51:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 43
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x15e4a9600> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 55
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 16:52:28 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  113
Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  35.61232000589371
,Failed to execute UT.
,2016-12-26 16:52:28 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
