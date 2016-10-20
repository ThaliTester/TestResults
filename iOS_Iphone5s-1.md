#### Test 901473369726ba5_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CA593414-85FC-4E30-8022-E76FB193068C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CA593414-85FC-4E30-8022-E76FB193068C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/901473369726ba5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CAEADE60-6E50-478D-8DD2-D20F6B6719D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52429"
,(lldb)     command script import "/tmp/CA593414-85FC-4E30-8022-E76FB193068C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 09:57:30.856 ThaliTest[4540:10417132] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EB7A29C3-3E36-492E-81A2-EC0D36BDCEE2/Library/Cookies/Cookies.binarycookies
,2016-10-20 09:57:30.973 ThaliTest[4540:10417132] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 09:57:30.975 ThaliTest[4540:10417132] Multi-tasking -> Device: YES, App: YES
,2016-10-20 09:57:30.999 ThaliTest[4540:10417132] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 09:57:32.631 ThaliTest[4540:10417132] Using UIWebView
,2016-10-20 09:57:32.640 ThaliTest[4540:10417132] [CDVTimer][handleopenurl] 0.472009ms
,2016-10-20 09:57:32.650 ThaliTest[4540:10417132] [CDVTimer][intentandnavigationfilter] 10.183990ms
2016-10-20 09:57:32.651 ThaliTest[4540:10417132] [CDVTimer][gesturehandler] 0.382006ms
2016-10-20 09:57:32.652 ThaliTest[4540:10417132] [CDVTimer][TotalPlu,ginStartup] 13.109982ms
,2016-10-20 09:57:38.764 ThaliTest[4540:10417132] Resetting plugins due to page load.
,2016-10-20 09:57:42.361 ThaliTest[4540:10417132] Finished load of: file:///var/mobile/Containers/Bundle/Application/CAEADE60-6E50-478D-8DD2-D20F6B6719D3/ThaliTest.app/www/index.html
,2016-10-20 09:57:42.662 ThaliTest[4540:10417132] JXcore Cordova plugin initializing
,2016-10-20 09:57:42.663 ThaliTest[4540:10417354] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 07:57:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 07:57:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x12784dcd0> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-20 07:58:19 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  23.44118297100067
,Failed to execute UT.
,2016-10-20 07:58:19 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
