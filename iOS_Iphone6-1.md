#### Test 62754403b276699_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62754403b276699/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2AF809A2-D5B6-43FC-9937-1BF0CAAA957C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2AF809A2-D5B6-43FC-9937-1BF0CAAA957C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62754403b276699/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62754403b276699/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50903"
,(lldb)     command script import "/tmp/2AF809A2-D5B6-43FC-9937-1BF0CAAA957C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 18:16:07.557 ThaliTest[1357:2178259] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A41EFD08-5354-4E02-856C-A4A79031488F/Library/Cookies/Cookies.binarycookies
,2016-03-14 18:16:07.955 ThaliTest[1357:2178259] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 18:16:07.957 ThaliTest[1357:2178259] Multi-tasking -> Device: YES, App: YES
,2016-03-14 18:16:07.979 ThaliTest[1357:2178259] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 18:16:09.925 ThaliTest[1357:2178259] Using UIWebView
,2016-03-14 18:16:09.932 ThaliTest[1357:2178259] [CDVTimer][handleopenurl] 0.413001ms
,2016-03-14 18:16:09.939 ThaliTest[1357:2178259] [CDVTimer][intentandnavigationfilter] 7.188976ms
2016-03-14 18:16:09.940 ThaliTest[1357:2178259] [CDVTimer][gesturehandler] 0.363946ms
2016-03-14 18:16:09.941 ThaliTest[1357:2178259] [CDVTimer][TotalPluginStartup] 9.691954ms
,2016-03-14 18:16:16.788 ThaliTest[1357:2178259] Resetting plugins due to page load.
,2016-03-14 18:16:20.397 ThaliTest[1357:2178259] Finished load of: file:///var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/index.html
,2016-03-14 18:16:20.689 ThaliTest[1357:2178259] JXcore Cordova plugin initializing
,2016-03-14 18:16:20.690 ThaliTest[1357:2178470] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 18:16:33.185 ThaliTest[1357:2178470] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 18:16:33.185 ThaliTest[1357:2178470] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 18:16:33.186 ThaliTest[1357:2178470] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 18:16:33.187 ThaliTest[1357:2178470] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6FD44DEC-B083-4E0E-BF5D-1287F0491F52/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
