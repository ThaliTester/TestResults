#### Test 1022710398c29c0f_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1022710398c29c0f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EF102A4F-2BF8-45EB-B259-CEB4A9954E9D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EF102A4F-2BF8-45EB-B259-CEB4A9954E9D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1022710398c29c0f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1022710398c29c0f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9039FC9B-9CE2-4712-B8EC-6613D6198FBB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55815"
,(lldb)     command script import "/tmp/EF102A4F-2BF8-45EB-B259-CEB4A9954E9D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-20 13:56:00.942 ThaliTest[2582:6402479] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1815CE39-ECAF-4BA9-9E7B-51E377ED1AB4/Library/Cookies/Cookies.binarycookies
,2017-01-20 13:56:01.451 ThaliTest[2582:6402479] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-20 13:56:01.452 ThaliTest[2582:6402479] Multi-tasking -> Device: YES, App: YES
,2017-01-20 13:56:01.474 ThaliTest[2582:6402479] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-20 13:56:02.302 ThaliTest[2582:6402479] Using UIWebView
,2017-01-20 13:56:02.308 ThaliTest[2582:6402479] [CDVTimer][handleopenurl] 0.183046ms
,2017-01-20 13:56:02.312 ThaliTest[2582:6402479] [CDVTimer][intentandnavigationfilter] 4.532039ms
2017-01-20 13:56:02.313 ThaliTest[2582:6402479] [CDVTimer][gesturehandler] 0.164986ms
2017-01-20 13:56:02.313 ThaliTest[2582:6402479] [CDVTimer][TotalPluginS,tartup] 5.663991ms
,2017-01-20 13:56:05.524 ThaliTest[2582:6402479] Resetting plugins due to page load.
,2017-01-20 13:56:06.877 ThaliTest[2582:6402479] Finished load of: file:///var/mobile/Containers/Bundle/Application/9039FC9B-9CE2-4712-B8EC-6613D6198FBB/ThaliTest.app/www/index.html
,2017-01-20 13:56:07.087 ThaliTest[2582:6402479] JXcore Cordova plugin initializing
,2017-01-20 13:56:07.088 ThaliTest[2582:6402654] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-20 12:56:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-20 12:56:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-20 12:56:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-20 12:56:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-20 12:56:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-20 12:56:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  23.53095000982285
Failed to execute UT.
2017-01-20 12:56:46 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
