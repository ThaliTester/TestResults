#### Test 98912682a6d9d3f_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0BAD0F71-5EA7-492D-B42C-7F8AFEEB03A6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/0BAD0F71-5EA7-492D-B42C-7F8AFEEB03A6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7E0BF07E-AB4E-4906-B22B-66C8A8485189/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59227"
,(lldb)     command script import "/tmp/0BAD0F71-5EA7-492D-B42C-7F8AFEEB03A6/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-21 19:25:07.566 ThaliTest[804:2204151] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D612AF85-5BEC-46B8-806F-EC2EA1DC9F4F/Library/Cookies/Cookies.binarycookies
,2016-12-21 19:25:07.729 ThaliTest[804:2204151] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-21 19:25:07.732 ThaliTest[804:2204151] Multi-tasking -> Device: YES, App: YES
,2016-12-21 19:25:07.756 ThaliTest[804:2204151] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-21 19:25:08.538 ThaliTest[804:2204151] Using UIWebView
,2016-12-21 19:25:08.544 ThaliTest[804:2204151] [CDVTimer][handleopenurl] 0.460029ms
,2016-12-21 19:25:08.553 ThaliTest[804:2204151] [CDVTimer][intentandnavigationfilter] 7.978022ms
2016-12-21 19:25:08.553 ThaliTest[804:2204151] [CDVTimer][gesturehandler] 0.374973ms
2016-12-21 19:25:08.554 ThaliTest[804:2204151] [CDVTimer][TotalPluginStartup] 10.235012ms
,2016-12-21 19:25:19.154 ThaliTest[804:2204151] Resetting plugins due to page load.
,2016-12-21 19:25:19.951 ThaliTest[804:2204151] Finished load of: file:///var/containers/Bundle/Application/7E0BF07E-AB4E-4906-B22B-66C8A8485189/ThaliTest.app/www/index.html
,2016-12-21 19:25:20.181 ThaliTest[804:2204151] JXcore Cordova plugin initializing
2016-12-21 19:25:20.184 ThaliTest[804:2204328] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-21 18:25:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-21 18:25:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-21 18:25:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-21 18:25:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-21 18:25:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 4 seconds, with unfulfilled expectations: "Advertiser disposed after delay". in file: Optional("<unknown>"), line: 0
,XCTAssertEqual failed: ("Optional(2)") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/AdvertiserManagerTests.swift"), line: 202
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-21 18:26:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  114
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  30.8148689866066
,Failed to execute UT.
,2016-12-21 18:26:27 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
