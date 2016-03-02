#### Test 61432979123161a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61432979123161a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/82AF28AC-061E-40BE-BCF1-2F59098DEBE3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/82AF28AC-061E-40BE-BCF1-2F59098DEBE3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61432979123161a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61432979123161a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50868"
,(lldb)     command script import "/tmp/82AF28AC-061E-40BE-BCF1-2F59098DEBE3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 18:35:42.985 ThaliTest[512:536310] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0CE618F0-844D-4736-8BF7-1EA3CC01EC58/Library/Cookies/Cookies.binarycookies
,2016-03-02 18:35:43.412 ThaliTest[512:536310] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 18:35:43.414 ThaliTest[512:536310] Multi-tasking -> Device: YES, App: YES
,2016-03-02 18:35:43.432 ThaliTest[512:536310] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 18:35:45.396 ThaliTest[512:536310] Using UIWebView
,2016-03-02 18:35:45.402 ThaliTest[512:536310] [CDVTimer][handleopenurl] 0.418007ms
,2016-03-02 18:35:45.409 ThaliTest[512:536310] [CDVTimer][intentandnavigationfilter] 6.546021ms
,2016-03-02 18:35:45.410 ThaliTest[512:536310] [CDVTimer][gesturehandler] 0.874996ms
2016-03-02 18:35:45.411 ThaliTest[512:536310] [CDVTimer][TotalPluginStartup] 9.481966ms
,2016-03-02 18:35:52.035 ThaliTest[512:536310] Resetting plugins due to page load.
,2016-03-02 18:35:55.680 ThaliTest[512:536310] Finished load of: file:///var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/index.html
,2016-03-02 18:35:55.900 ThaliTest[512:536310] JXcore Cordova plugin initializing
,2016-03-02 18:35:55.901 ThaliTest[512:536556] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 18:36:02.495 ThaliTest[512:536556] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 18:36:02.496 ThaliTest[512:536556] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-02 18:36:02.496 ThaliTest[512:536556] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-02 18:36:02.498 ThaliTest[512:536556] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1FF9D2B0-9BE6-4FCA-84EA-F7C7A71BECDA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
