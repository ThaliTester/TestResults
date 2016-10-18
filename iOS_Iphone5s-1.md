#### Test 89786516a9cd264_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89786516a9cd264/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/07B45460-A8D1-409B-9E87-5D06FE3FBD71/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/07B45460-A8D1-409B-9E87-5D06FE3FBD71/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89786516a9cd264/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89786516a9cd264/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7F1107AE-BC70-4051-9439-55C69C7D5679/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59336"
,(lldb)     command script import "/tmp/07B45460-A8D1-409B-9E87-5D06FE3FBD71/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 12:43:42.493 ThaliTest[4401:10106776] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1D9787B-9D0F-45BF-AA88-DEB13B9CCCC3/Library/Cookies/Cookies.binarycookies
,2016-10-18 12:43:42.606 ThaliTest[4401:10106776] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 12:43:42.608 ThaliTest[4401:10106776] Multi-tasking -> Device: YES, App: YES
,2016-10-18 12:43:42.628 ThaliTest[4401:10106776] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 12:43:44.125 ThaliTest[4401:10106776] Using UIWebView
,2016-10-18 12:43:44.137 ThaliTest[4401:10106776] [CDVTimer][handleopenurl] 0.477016ms
,2016-10-18 12:43:44.148 ThaliTest[4401:10106776] [CDVTimer][intentandnavigationfilter] 10.153055ms
2016-10-18 12:43:44.149 ThaliTest[4401:10106776] [CDVTimer][gesturehandler] 0.382006ms
2016-10-18 12:43:44.149 ThaliTest[4401:10106776] [CDVTimer][TotalPlu,ginStartup] 13.273001ms
,2016-10-18 12:43:50.411 ThaliTest[4401:10106776] Resetting plugins due to page load.
,2016-10-18 12:43:54.124 ThaliTest[4401:10106776] Finished load of: file:///var/mobile/Containers/Bundle/Application/7F1107AE-BC70-4051-9439-55C69C7D5679/ThaliTest.app/www/index.html
,2016-10-18 12:43:54.440 ThaliTest[4401:10106776] JXcore Cordova plugin initializing
,2016-10-18 12:43:54.441 ThaliTest[4401:10107021] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 10:44:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 10:44:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 10:44:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 10:44:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 10:44:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-18 10:44:31 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  100
Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  23.73054403066635
,Failed to execute UT.
,2016-10-18 10:44:31 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
