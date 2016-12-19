#### Test 9856377440205b4_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/00149FA7-6E46-4590-B9EB-C69B38642EFC/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/00149FA7-6E46-4590-B9EB-C69B38642EFC/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377440205b4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9B175A8F-4916-4F6A-8346-AF646F5DBA5C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59622"
,(lldb)     command script import "/tmp/00149FA7-6E46-4590-B9EB-C69B38642EFC/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 14:44:48.082 ThaliTest[731:1891129] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/083587ED-7A30-46BA-9F34-72B1C8EA0F37/Library/Cookies/Cookies.binarycookies
,2016-12-19 14:44:48.232 ThaliTest[731:1891129] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 14:44:48.235 ThaliTest[731:1891129] Multi-tasking -> Device: YES, App: YES
,2016-12-19 14:44:48.264 ThaliTest[731:1891129] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 14:44:49.056 ThaliTest[731:1891129] Using UIWebView
,2016-12-19 14:44:49.063 ThaliTest[731:1891129] [CDVTimer][handleopenurl] 0.575006ms
,2016-12-19 14:44:49.070 ThaliTest[731:1891129] [CDVTimer][intentandnavigationfilter] 7.157981ms
2016-12-19 14:44:49.071 ThaliTest[731:1891129] [CDVTimer][gesturehandler] 0.329018ms
2016-12-19 14:44:49.071 ThaliTest[731:1891129] [CDVTimer][TotalPluginStartup] 9.423018ms
,2016-12-19 14:44:59.540 ThaliTest[731:1891129] Resetting plugins due to page load.
,2016-12-19 14:45:00.593 ThaliTest[731:1891129] Finished load of: file:///var/containers/Bundle/Application/9B175A8F-4916-4F6A-8346-AF646F5DBA5C/ThaliTest.app/www/index.html
,2016-12-19 14:45:00.820 ThaliTest[731:1891129] JXcore Cordova plugin initializing
,2016-12-19 14:45:00.823 ThaliTest[731:1891328] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 13:45:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 13:45:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 13:45:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-19 13:45:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 13:45:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,2016-12-19 13:46:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  28.922867000103
,Failed to execute UT.
,2016-12-19 13:46:05 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
