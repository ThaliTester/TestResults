#### Test 6275440391a6bae_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6275440391a6bae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F44D7A98-EDB1-49FF-B7BE-2DA8882AEC0B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F44D7A98-EDB1-49FF-B7BE-2DA8882AEC0B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6275440391a6bae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6275440391a6bae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49943"
,(lldb)     command script import "/tmp/F44D7A98-EDB1-49FF-B7BE-2DA8882AEC0B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 20:34:53.865 ThaliTest[1467:2342953] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/049BDF49-46C1-44FA-B4BD-550317E26DB7/Library/Cookies/Cookies.binarycookies
,2016-03-15 20:34:54.282 ThaliTest[1467:2342953] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 20:34:54.284 ThaliTest[1467:2342953] Multi-tasking -> Device: YES, App: YES
,2016-03-15 20:34:54.309 ThaliTest[1467:2342953] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 20:34:56.288 ThaliTest[1467:2342953] Using UIWebView
,2016-03-15 20:34:56.296 ThaliTest[1467:2342953] [CDVTimer][handleopenurl] 0.424981ms
,2016-03-15 20:34:56.303 ThaliTest[1467:2342953] [CDVTimer][intentandnavigationfilter] 7.156014ms
2016-03-15 20:34:56.304 ThaliTest[1467:2342953] [CDVTimer][gesturehandler] 0.334024ms
2016-03-15 20:34:56.305 ThaliTest[1467:2342953] [CDVTimer][TotalPluginStartup] 9.656012ms
,2016-03-15 20:35:02.646 ThaliTest[1467:2342953] Resetting plugins due to page load.
,2016-03-15 20:35:06.097 ThaliTest[1467:2342953] Finished load of: file:///var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/index.html
,2016-03-15 20:35:06.322 ThaliTest[1467:2342953] JXcore Cordova plugin initializing
,2016-03-15 20:35:06.323 ThaliTest[1467:2343201] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 20:35:18.864 ThaliTest[1467:2343201] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 20:35:18.864 ThaliTest[1467:2343201] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 20:35:18.864 ThaliTest[1467:2,343201] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 20:35:18.866 ThaliTest[1467:2343201] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/1B0F3BB7-6DEC-4500-9002-4D70143C6E76/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
