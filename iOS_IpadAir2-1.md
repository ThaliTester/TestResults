#### Test 901473369726ba5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/9D5CA5E4-7CBB-4C2F-AB29-7B5A4E0BACF9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9D5CA5E4-7CBB-4C2F-AB29-7B5A4E0BACF9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/39CC1CCA-B08B-40D8-A851-343B2980ECB5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52431"
,(lldb)     command script import "/tmp/9D5CA5E4-7CBB-4C2F-AB29-7B5A4E0BACF9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 09:57:40.062 ThaliTest[4530:8898497] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/088828BA-465C-4936-A67D-BC3287DE2791/Library/Cookies/Cookies.binarycookies
,2016-10-20 09:57:40.439 ThaliTest[4530:8898497] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 09:57:40.441 ThaliTest[4530:8898497] Multi-tasking -> Device: YES, App: YES
,2016-10-20 09:57:40.462 ThaliTest[4530:8898497] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 09:57:42.457 ThaliTest[4530:8898497] Using UIWebView
,2016-10-20 09:57:42.463 ThaliTest[4530:8898497] [CDVTimer][handleopenurl] 0.448048ms
,2016-10-20 09:57:42.470 ThaliTest[4530:8898497] [CDVTimer][intentandnavigationfilter] 6.303966ms
,2016-10-20 09:57:42.471 ThaliTest[4530:8898497] [CDVTimer][gesturehandler] 0.297964ms
,2016-10-20 09:57:42.471 ThaliTest[4530:8898497] [CDVTimer][TotalPluginStartup] 8.574009ms
,2016-10-20 09:57:49.372 ThaliTest[4530:8898497] Resetting plugins due to page load.
,2016-10-20 09:57:52.583 ThaliTest[4530:8898497] Finished load of: file:///var/mobile/Containers/Bundle/Application/39CC1CCA-B08B-40D8-A851-343B2980ECB5/ThaliTest.app/www/index.html
,2016-10-20 09:57:52.855 ThaliTest[4530:8898497] JXcore Cordova plugin initializing
2016-10-20 09:57:52.856 ThaliTest[4530:8898762] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 07:58:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-20 07:58:35 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  33.13996601104736
,Failed to execute UT.
,2016-10-20 07:58:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
