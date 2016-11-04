#### Test 92300911d00ab7e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/EAF3599B-8A0B-4BC1-840B-16010C10769F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/EAF3599B-8A0B-4BC1-840B-16010C10769F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/92300911d00ab7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8C8C1D21-0C44-4EF9-A692-0E400B1A9B1F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60740"
,(lldb)     command script import "/tmp/EAF3599B-8A0B-4BC1-840B-16010C10769F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 09:57:14.711 ThaliTest[3023:7328117] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/029294C6-70E7-46CC-9E83-0689EB01ED14/Library/Cookies/Cookies.binarycookies
,2016-11-04 09:57:14.752 ThaliTest[3023:7328117] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 09:57:14.753 ThaliTest[3023:7328117] Multi-tasking -> Device: YES, App: YES
,2016-11-04 09:57:14.765 ThaliTest[3023:7328117] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 09:57:15.073 ThaliTest[3023:7328117] Using UIWebView
,2016-11-04 09:57:15.078 ThaliTest[3023:7328117] [CDVTimer][handleopenurl] 0.324965ms
,2016-11-04 09:57:15.082 ThaliTest[3023:7328117] [CDVTimer][intentandnavigationfilter] 3.683984ms
2016-11-04 09:57:15.082 ThaliTest[3023:7328117] [CDVTimer][gesturehandler] 0.150979ms
2016-11-04 09:57:15.083 ThaliTest[3023:7328117] [CDVTimer][TotalPluginStartup] 5.074978ms
,2016-11-04 09:57:20.443 ThaliTest[3023:7328117] Resetting plugins due to page load.
,2016-11-04 09:57:20.803 ThaliTest[3023:7328117] Finished load of: file:///var/containers/Bundle/Application/8C8C1D21-0C44-4EF9-A692-0E400B1A9B1F/ThaliTest.app/www/index.html
,2016-11-04 09:57:21.173 ThaliTest[3023:7328117] JXcore Cordova plugin initializing
,2016-11-04 09:57:21.173 ThaliTest[3023:7328280] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 08:57:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 08:57:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 08:57:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-04 08:57:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 08:57:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-11-04 08:57:56 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  23.90212094783783
Failed to execute UT.
,2016-11-04 08:57:56 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
