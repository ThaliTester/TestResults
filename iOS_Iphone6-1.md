#### Test 901767747b3ba04_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/49AED0CA-639B-41ED-AD52-21B1A18E201B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/49AED0CA-639B-41ED-AD52-21B1A18E201B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4A57C88B-2D70-4560-A0E5-40529AD37F1C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61492"
,(lldb)     command script import "/tmp/49AED0CA-639B-41ED-AD52-21B1A18E201B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 13:14:41.828 ThaliTest[2519:5335182] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/17B26342-CCDB-4309-AF81-3E06940A148F/Library/Cookies/Cookies.binarycookies
,2016-10-20 13:14:41.909 ThaliTest[2519:5335182] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 13:14:41.912 ThaliTest[2519:5335182] Multi-tasking -> Device: YES, App: YES
,2016-10-20 13:14:41.934 ThaliTest[2519:5335182] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 13:14:42.414 ThaliTest[2519:5335182] Using UIWebView
,2016-10-20 13:14:42.422 ThaliTest[2519:5335182] [CDVTimer][handleopenurl] 0.510037ms
,2016-10-20 13:14:42.431 ThaliTest[2519:5335182] [CDVTimer][intentandnavigationfilter] 8.317053ms
2016-10-20 13:14:42.431 ThaliTest[2519:5335182] [CDVTimer][gesturehandler] 0.342965ms
2016-10-20 13:14:42.432 ThaliTest[2519:5335182] [CDVTimer][TotalPluginStartup] 10.803998ms
,2016-10-20 13:14:47.618 ThaliTest[2519:5335182] Resetting plugins due to page load.
,2016-10-20 13:14:48.000 ThaliTest[2519:5335182] Finished load of: file:///var/containers/Bundle/Application/4A57C88B-2D70-4560-A0E5-40529AD37F1C/ThaliTest.app/www/index.html
,2016-10-20 13:14:48.335 ThaliTest[2519:5335182] JXcore Cordova plugin initializing
2016-10-20 13:14:48.336 ThaliTest[2519:5335345] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 11:14:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 11:14:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 11:14:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 11:14:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 11:14:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-20 11:15:24 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
Number of ignored tests:  0
,Total duration:  25.15615397691727
Failed to execute UT.
,2016-10-20 11:15:24 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
