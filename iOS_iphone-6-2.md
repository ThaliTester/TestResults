#### Test 996748488b0f149_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DEE3289E-7CBD-4349-B5F9-4C09D92482BD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/DEE3289E-7CBD-4349-B5F9-4C09D92482BD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E15A0047-9D1D-4C20-883B-BD52CA0ADE06/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54029"
,(lldb)     command script import "/tmp/DEE3289E-7CBD-4349-B5F9-4C09D92482BD/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 12:54:06.097 ThaliTest[1998:4311478] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7BDB7B0-8844-4153-8C85-7133C758AFB2/Library/Cookies/Cookies.binarycookies
,2017-01-09 12:54:06.135 ThaliTest[1998:4311478] Apache Cordova native platform version 4.3.1 is starting.
2017-01-09 12:54:06.136 ThaliTest[1998:4311478] Multi-tasking -> Device: YES, App: YES
,2017-01-09 12:54:06.151 ThaliTest[1998:4311478] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 12:54:06.401 ThaliTest[1998:4311478] Using UIWebView
,2017-01-09 12:54:06.404 ThaliTest[1998:4311478] [CDVTimer][handleopenurl] 0.124991ms
,2017-01-09 12:54:06.407 ThaliTest[1998:4311478] [CDVTimer][intentandnavigationfilter] 2.973020ms
2017-01-09 12:54:06.407 ThaliTest[1998:4311478] [CDVTimer][gesturehandler] 0.096023ms
2017-01-09 12:54:06.407 ThaliTest[1998:4311478] [CDVTimer][TotalPluginStartup] 3.748000ms
,2017-01-09 12:54:09.882 ThaliTest[1998:4311478] Resetting plugins due to page load.
,2017-01-09 12:54:10.158 ThaliTest[1998:4311478] Finished load of: file:///var/containers/Bundle/Application/E15A0047-9D1D-4C20-883B-BD52CA0ADE06/ThaliTest.app/www/index.html
,2017-01-09 12:54:10.493 ThaliTest[1998:4311478] JXcore Cordova plugin initializing
,2017-01-09 12:54:10.494 ThaliTest[1998:4311645] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-09 11:54:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-09 11:54:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 11:54:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-09 11:54:21 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-09 11:54:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 43
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x14db37170> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 55
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser's mock node client received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-09 11:54:51 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  113
Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  30.24091303348541
Failed to execute UT.
,2017-01-09 11:54:51 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
