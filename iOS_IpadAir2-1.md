#### Test 90009723439aaa5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/33AFEF15-8278-4ADC-BD84-CEA17AF226B2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/33AFEF15-8278-4ADC-BD84-CEA17AF226B2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/90009723439aaa5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42415883-568A-499D-A241-AA27B1A676A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58997"
,(lldb)     command script import "/tmp/33AFEF15-8278-4ADC-BD84-CEA17AF226B2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 16:23:00.148 ThaliTest[4485:8806007] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C9B7A6B3-6F72-4F74-8E22-6D7FE6EA0B6D/Library/Cookies/Cookies.binarycookies
,2016-10-19 16:23:00.426 ThaliTest[4485:8806007] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 16:23:00.427 ThaliTest[4485:8806007] Multi-tasking -> Device: YES, App: YES
,2016-10-19 16:23:00.444 ThaliTest[4485:8806007] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 16:23:02.279 ThaliTest[4485:8806007] Using UIWebView
,2016-10-19 16:23:02.289 ThaliTest[4485:8806007] [CDVTimer][handleopenurl] 0.357985ms
,2016-10-19 16:23:02.296 ThaliTest[4485:8806007] [CDVTimer][intentandnavigationfilter] 6.503999ms
,2016-10-19 16:23:02.297 ThaliTest[4485:8806007] [CDVTimer][gesturehandler] 0.311017ms
,2016-10-19 16:23:02.297 ThaliTest[4485:8806007] [CDVTimer][TotalPluginStartup] 8.701026ms
,2016-10-19 16:23:08.679 ThaliTest[4485:8806007] Resetting plugins due to page load.
,2016-10-19 16:23:11.882 ThaliTest[4485:8806007] Finished load of: file:///var/mobile/Containers/Bundle/Application/42415883-568A-499D-A241-AA27B1A676A2/ThaliTest.app/www/index.html
,2016-10-19 16:23:12.106 ThaliTest[4485:8806007] JXcore Cordova plugin initializing
,2016-10-19 16:23:12.107 ThaliTest[4485:8806271] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 14:23:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 14:23:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 14:23:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-19 14:23:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 14:23:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-19 14:23:54 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  33.03635096549988
,Failed to execute UT.
,2016-10-19 14:23:54 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
