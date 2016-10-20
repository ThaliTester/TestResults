#### Test 901767747b3ba04_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4F56CDC5-2FFA-4C07-B562-8F7C45A2037B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4F56CDC5-2FFA-4C07-B562-8F7C45A2037B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/901767747b3ba04/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/14387C4D-6A53-4A3E-B134-7DA2E24EA01C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61479"
,(lldb)     command script import "/tmp/4F56CDC5-2FFA-4C07-B562-8F7C45A2037B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-20 13:14:32.770 ThaliTest[4543:8915729] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/74FDAD8D-0657-4FF3-B883-0EE7B9F625F4/Library/Cookies/Cookies.binarycookies
,2016-10-20 13:14:33.164 ThaliTest[4543:8915729] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-20 13:14:33.166 ThaliTest[4543:8915729] Multi-tasking -> Device: YES, App: YES
,2016-10-20 13:14:33.186 ThaliTest[4543:8915729] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-20 13:14:35.203 ThaliTest[4543:8915729] Using UIWebView
,2016-10-20 13:14:35.212 ThaliTest[4543:8915729] [CDVTimer][handleopenurl] 0.346005ms
,2016-10-20 13:14:35.219 ThaliTest[4543:8915729] [CDVTimer][intentandnavigationfilter] 6.310999ms
,2016-10-20 13:14:35.220 ThaliTest[4543:8915729] [CDVTimer][gesturehandler] 0.301957ms
2016-10-20 13:14:35.220 ThaliTest[4543:8915729] [CDVTimer][TotalPluginStartup] 8.494973ms
,2016-10-20 13:14:41.646 ThaliTest[4543:8915729] Resetting plugins due to page load.
,2016-10-20 13:14:44.905 ThaliTest[4543:8915729] Finished load of: file:///var/mobile/Containers/Bundle/Application/14387C4D-6A53-4A3E-B134-7DA2E24EA01C/ThaliTest.app/www/index.html
,2016-10-20 13:14:45.176 ThaliTest[4543:8915729] JXcore Cordova plugin initializing
,2016-10-20 13:14:45.177 ThaliTest[4543:8915962] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-20 11:14:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-20 11:15:28 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  34.07227498292923
,Failed to execute UT.
,2016-10-20 11:15:28 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
