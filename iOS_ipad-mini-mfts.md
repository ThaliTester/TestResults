#### Test 102706742b5bb046_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102706742b5bb046/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B30F8F85-522C-4F8A-9AE9-6F941BCD18AD/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/B30F8F85-522C-4F8A-9AE9-6F941BCD18AD/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102706742b5bb046/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102706742b5bb046/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9DC728B5-B270-49E7-BAA6-585F44419970/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57859"
,(lldb)     command script import "/tmp/B30F8F85-522C-4F8A-9AE9-6F941BCD18AD/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 09:41:41.891 ThaliTest[1852:6752911] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF992B12-A072-4D95-87D7-5C8AF62F7FD5/Library/Cookies/Cookies.binarycookies
,2017-01-24 09:41:42.031 ThaliTest[1852:6752911] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 09:41:42.033 ThaliTest[1852:6752911] Multi-tasking -> Device: YES, App: YES
,2017-01-24 09:41:42.056 ThaliTest[1852:6752911] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 09:41:42.538 ThaliTest[1852:6752911] Using UIWebView
,2017-01-24 09:41:42.544 ThaliTest[1852:6752911] [CDVTimer][handleopenurl] 0.647962ms
2017-01-24 09:41:42.552 ThaliTest[1852:6752911] [CDVTimer][intentandnavigationfilter] 6.989002ms
2017-01-24 09:41:42.553 ThaliTest[1852:6752911] [CDVTimer][gesturehandle,r] 0.333011ms
2017-01-24 09:41:42.553 ThaliTest[1852:6752911] [CDVTimer][TotalPluginStartup] 9.266019ms
,2017-01-24 09:41:49.316 ThaliTest[1852:6752911] Resetting plugins due to page load.
,2017-01-24 09:41:49.881 ThaliTest[1852:6752911] Finished load of: file:///var/containers/Bundle/Application/9DC728B5-B270-49E7-BAA6-585F44419970/ThaliTest.app/www/index.html
,2017-01-24 09:41:50.129 ThaliTest[1852:6752911] JXcore Cordova plugin initializing
,2017-01-24 09:41:50.131 ThaliTest[1852:6753053] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-24 08:42:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 08:42:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 08:42:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-24 08:42:28 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-24 08:42:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-24 08:43:01 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
,Total duration:  31.91480600833893
,Failed to execute UT.
,2017-01-24 08:43:01 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
