#### Test 61362366121daa0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61362366121daa0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F87E0449-DA92-42BB-B96C-07A1309F4FE1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F87E0449-DA92-42BB-B96C-07A1309F4FE1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61362366121daa0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61362366121daa0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50561"
,(lldb)     command script import "/tmp/F87E0449-DA92-42BB-B96C-07A1309F4FE1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-02 14:34:50.578 ThaliTest[484:511093] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AACAE770-F606-49F0-90BB-033AF3B92ACE/Library/Cookies/Cookies.binarycookies
,2016-03-02 14:34:50.931 ThaliTest[484:511093] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-02 14:34:50.932 ThaliTest[484:511093] Multi-tasking -> Device: YES, App: YES
,2016-03-02 14:34:50.952 ThaliTest[484:511093] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-02 14:34:53.021 ThaliTest[484:511093] Using UIWebView
,2016-03-02 14:34:53.027 ThaliTest[484:511093] [CDVTimer][handleopenurl] 0.409007ms
,2016-03-02 14:34:53.035 ThaliTest[484:511093] [CDVTimer][intentandnavigationfilter] 6.963968ms
,2016-03-02 14:34:53.036 ThaliTest[484:511093] [CDVTimer][gesturehandler] 0.348985ms
,2016-03-02 14:34:53.037 ThaliTest[484:511093] [CDVTimer][TotalPluginStartup] 9.736955ms
,2016-03-02 14:35:00.247 ThaliTest[484:511093] Resetting plugins due to page load.
,2016-03-02 14:35:03.727 ThaliTest[484:511093] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/index.html
,2016-03-02 14:35:03.965 ThaliTest[484:511093] JXcore Cordova plugin initializing
,2016-03-02 14:35:03.966 ThaliTest[484:511328] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-02 14:35:15.705 ThaliTest[484:511328] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-02 14:35:15.705 ThaliTest[484:511328] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-02 14:35:15.705 ThaliTest[484:511328] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-02 14:35:15.706 ThaliTest[484:511328] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB23E959-8FEF-4EAE-A16D-430CB2951216/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
