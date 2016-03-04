#### Test 61432979f791f6f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61432979f791f6f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A2F2F842-756E-49DE-BBDA-7615EB706D64/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A2F2F842-756E-49DE-BBDA-7615EB706D64/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61432979f791f6f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61432979f791f6f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49500"
,(lldb)     command script import "/tmp/A2F2F842-756E-49DE-BBDA-7615EB706D64/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 09:04:21.257 ThaliTest[634:756519] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BA1C1D9E-6D3B-4BA3-8439-7F7224465737/Library/Cookies/Cookies.binarycookies
,2016-03-04 09:04:21.672 ThaliTest[634:756519] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 09:04:21.673 ThaliTest[634:756519] Multi-tasking -> Device: YES, App: YES
,2016-03-04 09:04:21.690 ThaliTest[634:756519] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 09:04:23.459 ThaliTest[634:756519] Using UIWebView
,2016-03-04 09:04:23.465 ThaliTest[634:756519] [CDVTimer][handleopenurl] 0.407994ms
,2016-03-04 09:04:23.473 ThaliTest[634:756519] [CDVTimer][intentandnavigationfilter] 6.854951ms
,2016-03-04 09:04:23.473 ThaliTest[634:756519] [CDVTimer][gesturehandler] 0.330985ms
,2016-03-04 09:04:23.474 ThaliTest[634:756519] [CDVTimer][TotalPluginStartup] 9.241998ms
,2016-03-04 09:04:29.935 ThaliTest[634:756519] Resetting plugins due to page load.
,2016-03-04 09:04:33.351 ThaliTest[634:756519] Finished load of: file:///var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/index.html
,2016-03-04 09:04:33.569 ThaliTest[634:756519] JXcore Cordova plugin initializing
,2016-03-04 09:04:33.570 ThaliTest[634:756773] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 09:04:40.158 ThaliTest[634:756773] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-04 09:04:40.159 ThaliTest[634:756773] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-04 09:04:40.159 ThaliTest[634:756773] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 09:04:40.161 ThaliTest[634:756773] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A4ED2430-2B04-43A5-BEC3-854ED77411C5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
