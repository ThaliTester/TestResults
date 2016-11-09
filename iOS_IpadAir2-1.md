#### Test 896247965a92e74_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/116D7015-E18A-4B2C-8293-FF155BDB868F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/116D7015-E18A-4B2C-8293-FF155BDB868F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/22A12A47-3638-48FD-9890-D66650391DDE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61953"
,(lldb)     command script import "/tmp/116D7015-E18A-4B2C-8293-FF155BDB868F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 14:57:07.770 ThaliTest[5311:11391271] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4878E88E-0654-4E73-8398-E722C46F342C/Library/Cookies/Cookies.binarycookies
,2016-11-09 14:57:08.006 ThaliTest[5311:11391271] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 14:57:08.007 ThaliTest[5311:11391271] Multi-tasking -> Device: YES, App: YES
,2016-11-09 14:57:08.018 ThaliTest[5311:11391271] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 14:57:08.888 ThaliTest[5311:11391271] Using UIWebView
,2016-11-09 14:57:08.890 ThaliTest[5311:11391271] [CDVTimer][handleopenurl] 0.094950ms
,2016-11-09 14:57:08.892 ThaliTest[5311:11391271] [CDVTimer][intentandnavigationfilter] 1.819968ms
2016-11-09 14:57:08.892 ThaliTest[5311:11391271] [CDVTimer][gesturehandler] 0.091016ms
2016-11-09 14:57:08.892 ThaliTest[5311:11391271] [CDVTimer][TotalPluginStartup] 2.415001ms
,2016-11-09 14:57:12.215 ThaliTest[5311:11391271] Resetting plugins due to page load.
,2016-11-09 14:57:13.706 ThaliTest[5311:11391271] Finished load of: file:///var/mobile/Containers/Bundle/Application/22A12A47-3638-48FD-9890-D66650391DDE/ThaliTest.app/www/index.html
,2016-11-09 14:57:13.844 ThaliTest[5311:11391271] JXcore Cordova plugin initializing
,2016-11-09 14:57:13.845 ThaliTest[5311:11391452] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 13:57:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 13:57:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 13:57:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 13:57:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 13:57:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 341
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-09 13:57:56 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  33.68362802267075
,Failed to execute UT.
,2016-11-09 13:57:56 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
