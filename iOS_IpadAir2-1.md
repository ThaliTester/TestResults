#### Test 613623666a5dbc7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623666a5dbc7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/8A4B5C01-9EA9-48A1-AA7F-C405BED8405C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8A4B5C01-9EA9-48A1-AA7F-C405BED8405C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623666a5dbc7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623666a5dbc7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50127"
,(lldb)     command script import "/tmp/8A4B5C01-9EA9-48A1-AA7F-C405BED8405C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 09:07:00.119 ThaliTest[453:477798] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/10311181-D482-4CDB-82A8-B2650998DDB8/Library/Cookies/Cookies.binarycookies
,2016-03-02 09:07:00.409 ThaliTest[453:477798] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 09:07:00.410 ThaliTest[453:477798] Multi-tasking -> Device: YES, App: YES
,2016-03-02 09:07:00.427 ThaliTest[453:477798] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 09:07:02.378 ThaliTest[453:477798] Using UIWebView
,2016-03-02 09:07:02.384 ThaliTest[453:477798] [CDVTimer][handleopenurl] 0.396013ms
,2016-03-02 09:07:02.392 ThaliTest[453:477798] [CDVTimer][intentandnavigationfilter] 7.275999ms
,2016-03-02 09:07:02.393 ThaliTest[453:477798] [CDVTimer][gesturehandler] 0.362992ms
2016-03-02 09:07:02.393 ThaliTest[453:477798] [CDVTimer][TotalPluginStartup] 9.698033ms
,2016-03-02 09:07:10.052 ThaliTest[453:477798] Resetting plugins due to page load.
,2016-03-02 09:07:13.559 ThaliTest[453:477798] Finished load of: file:///var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/index.html
,2016-03-02 09:07:13.789 ThaliTest[453:477798] JXcore Cordova plugin initializing
,2016-03-02 09:07:13.791 ThaliTest[453:478060] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 09:07:20.409 ThaliTest[453:478060] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 09:07:20.409 ThaliTest[453:478060] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-02 09:07:20.409 ThaliTest[453:478060] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-02 09:07:20.412 ThaliTest[453:478060] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0D3051B5-20BA-49FC-BF9A-F5DB95078B6A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
