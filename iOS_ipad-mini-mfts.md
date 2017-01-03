#### Test 99530606e7215e5_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2748AD8C-9044-41C4-8069-BFE2D4B4447D/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/2748AD8C-9044-41C4-8069-BFE2D4B4447D/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C18369BA-E846-4C3F-A2DB-11675E63C827/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60304"
,(lldb)     command script import "/tmp/2748AD8C-9044-41C4-8069-BFE2D4B4447D/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 14:54:48.904 ThaliTest[1274:4064020] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C35A0B7-53B6-4FF2-BE46-54D644076466/Library/Cookies/Cookies.binarycookies
,2017-01-03 14:54:49.058 ThaliTest[1274:4064020] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 14:54:49.061 ThaliTest[1274:4064020] Multi-tasking -> Device: YES, App: YES
,2017-01-03 14:54:49.091 ThaliTest[1274:4064020] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 14:54:49.516 ThaliTest[1274:4064020] Using UIWebView
2017-01-03 14:54:49.522 ThaliTest[1274:4064020] [CDVTimer][handleopenurl] 0.429034ms
,2017-01-03 14:54:49.530 ThaliTest[1274:4064020] [CDVTimer][intentandnavigationfilter] 7.411003ms
,2017-01-03 14:54:49.530 ThaliTest[1274:4064020] [CDVTimer][gesturehandler] 0.336945ms
2017-01-03 14:54:49.531 ThaliTest[1274:4064020] [CDVTimer][TotalPluginStartup] 9.636045ms
,2017-01-03 14:54:55.396 ThaliTest[1274:4064020] Resetting plugins due to page load.
,2017-01-03 14:54:55.905 ThaliTest[1274:4064020] Finished load of: file:///var/containers/Bundle/Application/C18369BA-E846-4C3F-A2DB-11675E63C827/ThaliTest.app/www/index.html
,2017-01-03 14:54:56.158 ThaliTest[1274:4064020] JXcore Cordova plugin initializing
2017-01-03 14:54:56.160 ThaliTest[1274:4064164] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-03 13:55:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-03 13:55:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 13:55:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-03 13:55:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-03 13:55:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser peer found Advertiser peer". in file: Optional("<unknown>"), line: 0
,failed - BrowserManager does not have available peers to connect in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 133
,2017-01-03 13:56:10 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  114
Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  37.60645401477814
,Failed to execute UT.
,2017-01-03 13:56:10 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
