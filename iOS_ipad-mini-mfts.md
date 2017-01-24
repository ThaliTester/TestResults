#### Test 102271039975da4b_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102271039975da4b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BFB1FF10-BF8D-481C-944C-A39E70405E58/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/BFB1FF10-BF8D-481C-944C-A39E70405E58/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102271039975da4b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102271039975da4b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/00570B67-F4CB-4437-A4CE-E3E38D18CED1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61958"
,(lldb)     command script import "/tmp/BFB1FF10-BF8D-481C-944C-A39E70405E58/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2017-01-24 16:05:12.756 ThaliTest[1869:6793822] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/11373F4B-476A-46FA-A633-58CA6CE37EF5/Library/Cookies/Cookies.binarycookies
,2017-01-24 16:05:12.909 ThaliTest[1869:6793822] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 16:05:12.912 ThaliTest[1869:6793822] Multi-tasking -> Device: YES, App: YES
,2017-01-24 16:05:12.935 ThaliTest[1869:6793822] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 16:05:13.433 ThaliTest[1869:6793822] Using UIWebView
,2017-01-24 16:05:13.441 ThaliTest[1869:6793822] [CDVTimer][handleopenurl] 0.454962ms
,2017-01-24 16:05:13.449 ThaliTest[1869:6793822] [CDVTimer][intentandnavigationfilter] 7.319987ms
2017-01-24 16:05:13.450 ThaliTest[1869:6793822] [CDVTimer][gesturehandler] 0.331044ms
2017-01-24 16:05:13.450 ThaliTest[1869:6793822] [CDVTimer][TotalPluginStartup] 9.500027ms
,2017-01-24 16:05:20.330 ThaliTest[1869:6793822] Resetting plugins due to page load.
,2017-01-24 16:05:20.874 ThaliTest[1869:6793822] Finished load of: file:///var/containers/Bundle/Application/00570B67-F4CB-4437-A4CE-E3E38D18CED1/ThaliTest.app/www/index.html
,2017-01-24 16:05:21.127 ThaliTest[1869:6793822] JXcore Cordova plugin initializing
,2017-01-24 16:05:21.129 ThaliTest[1869:6793962] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-24 15:05:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 15:05:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 15:05:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-24 15:05:59 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-24 15:05:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,2017-01-24 15:06:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  32.93776804208755
,Failed to execute UT.
,2017-01-24 15:06:33 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
