#### Test 61699762a45f11c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/61699762a45f11c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E26F2F23-F661-4CFC-89D9-CD1A1C1A3DE3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E26F2F23-F661-4CFC-89D9-CD1A1C1A3DE3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/61699762a45f11c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/61699762a45f11c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49633"
,(lldb)     command script import "/tmp/E26F2F23-F661-4CFC-89D9-CD1A1C1A3DE3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-04 12:53:08.594 ThaliTest[660:749852] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E0BFFEE5-108F-4475-A1C5-9319773E1978/Library/Cookies/Cookies.binarycookies
,2016-03-04 12:53:08.999 ThaliTest[660:749852] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-04 12:53:09.000 ThaliTest[660:749852] Multi-tasking -> Device: YES, App: YES
,2016-03-04 12:53:09.022 ThaliTest[660:749852] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-04 12:53:10.845 ThaliTest[660:749852] Using UIWebView
,2016-03-04 12:53:10.853 ThaliTest[660:749852] [CDVTimer][handleopenurl] 0.712991ms
,2016-03-04 12:53:10.862 ThaliTest[660:749852] [CDVTimer][intentandnavigationfilter] 8.031011ms
2016-03-04 12:53:10.862 ThaliTest[660:749852] [CDVTimer][gesturehandler] 0.382960ms
2016-03-04 12:53:10.863 ThaliTest[660:749852] [CDVTimer][TotalPluginStartup,] 11.047006ms
,2016-03-04 12:53:18.625 ThaliTest[660:749852] Resetting plugins due to page load.
,2016-03-04 12:53:22.630 ThaliTest[660:749852] Finished load of: file:///var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/index.html
,2016-03-04 12:53:22.886 ThaliTest[660:749852] JXcore Cordova plugin initializing
,2016-03-04 12:53:22.888 ThaliTest[660:750086] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-04 12:53:31.632 ThaliTest[660:750086] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-04 12:53:31.633 ThaliTest[660:750086] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-04 12:53:31.633 ThaliTest[660:750086,] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-04 12:53:31.637 ThaliTest[660:750086] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/98CBE254-37F4-4978-AE81-95237114EAA1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Unit Test app is loaded

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
