#### Test 10258170873f290a_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/11B7977A-764D-44E8-B276-5483F0A1FE2A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/11B7977A-764D-44E8-B276-5483F0A1FE2A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10258170873f290a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C48CF62A-367D-4DE3-8D7D-825B19BF3FC1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59897"
,(lldb)     command script import "/tmp/11B7977A-764D-44E8-B276-5483F0A1FE2A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 12:35:44.251 ThaliTest[2726:7068482] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/06BF6B03-20A7-4EBC-BBEA-43FA1C73A3AE/Library/Cookies/Cookies.binarycookies
,2017-01-24 12:35:44.487 ThaliTest[2726:7068482] Apache Cordova native platform version 4.3.1 is starting.
2017-01-24 12:35:44.488 ThaliTest[2726:7068482] Multi-tasking -> Device: YES, App: YES
,2017-01-24 12:35:44.500 ThaliTest[2726:7068482] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 12:35:45.357 ThaliTest[2726:7068482] Using UIWebView
,2017-01-24 12:35:45.359 ThaliTest[2726:7068482] [CDVTimer][handleopenurl] 0.100017ms
,2017-01-24 12:35:45.361 ThaliTest[2726:7068482] [CDVTimer][intentandnavigationfilter] 1.785994ms
2017-01-24 12:35:45.361 ThaliTest[2726:7068482] [CDVTimer][gesturehandler] 0.078976ms
2017-01-24 12:35:45.361 ThaliTest[2726:7068482] [CDVTimer][TotalPluginStartup] 2.386987ms
,2017-01-24 12:35:48.604 ThaliTest[2726:7068482] Resetting plugins due to page load.
,2017-01-24 12:35:50.080 ThaliTest[2726:7068482] Finished load of: file:///var/mobile/Containers/Bundle/Application/C48CF62A-367D-4DE3-8D7D-825B19BF3FC1/ThaliTest.app/www/index.html
,2017-01-24 12:35:50.222 ThaliTest[2726:7068482] JXcore Cordova plugin initializing
2017-01-24 12:35:50.222 ThaliTest[2726:7068667] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 11:36:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-24 11:36:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 11:36:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-24 11:36:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-24 11:36:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-24 11:36:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
,Number of failed tests:  1
Number of ignored tests:  0
,Total duration:  26.56745499372482
,Failed to execute UT.
,2017-01-24 11:36:27 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
