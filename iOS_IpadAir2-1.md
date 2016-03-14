#### Test 62560673a3c76e9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62560673a3c76e9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/837B1A8F-D0D3-4042-847F-C66D2BB0DEB8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/837B1A8F-D0D3-4042-847F-C66D2BB0DEB8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62560673a3c76e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62560673a3c76e9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50394"
,(lldb)     command script import "/tmp/837B1A8F-D0D3-4042-847F-C66D2BB0DEB8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-14 12:14:54.339 ThaliTest[1360:2187245] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9DBF193F-92FD-46CE-A5D5-59EEB7EE8F8B/Library/Cookies/Cookies.binarycookies
,2016-03-14 12:14:54.721 ThaliTest[1360:2187245] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-14 12:14:54.723 ThaliTest[1360:2187245] Multi-tasking -> Device: YES, App: YES
,2016-03-14 12:14:54.745 ThaliTest[1360:2187245] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-14 12:14:56.722 ThaliTest[1360:2187245] Using UIWebView
,2016-03-14 12:14:56.729 ThaliTest[1360:2187245] [CDVTimer][handleopenurl] 0.404000ms
,2016-03-14 12:14:56.736 ThaliTest[1360:2187245] [CDVTimer][intentandnavigationfilter] 6.612003ms
,2016-03-14 12:14:56.737 ThaliTest[1360:2187245] [CDVTimer][gesturehandler] 0.302970ms
,2016-03-14 12:14:56.737 ThaliTest[1360:2187245] [CDVTimer][TotalPluginStartup] 8.916020ms
,2016-03-14 12:15:03.520 ThaliTest[1360:2187245] Resetting plugins due to page load.
,2016-03-14 12:15:06.958 ThaliTest[1360:2187245] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/index.html
,2016-03-14 12:15:07.149 ThaliTest[1360:2187245] JXcore Cordova plugin initializing
,2016-03-14 12:15:07.149 ThaliTest[1360:2187464] JXcore instance initializing
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

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-14 12:15:18.835 ThaliTest[1360:2187464] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-14 12:15:18.835 ThaliTest[1360:2187464] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-14 12:15:18.835 ThaliTest[1360:2187464] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-14 12:15:18.836 ThaliTest[1360:2187464] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0747DF2-35BB-418A-9BFF-5AFDEC0B5002/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
