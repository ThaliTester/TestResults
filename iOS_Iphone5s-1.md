#### Test 62947189e430ee9_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E007BE0C-CE44-4F2C-B967-0ED4EF0C5600/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E007BE0C-CE44-4F2C-B967-0ED4EF0C5600/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62947189e430ee9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49843"
,(lldb)     command script import "/tmp/E007BE0C-CE44-4F2C-B967-0ED4EF0C5600/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 19:11:24.500 ThaliTest[1500:2398186] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A1842757-9DC4-4797-8A16-C906B19C6F72/Library/Cookies/Cookies.binarycookies
,2016-03-15 19:11:24.944 ThaliTest[1500:2398186] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 19:11:24.946 ThaliTest[1500:2398186] Multi-tasking -> Device: YES, App: YES
,2016-03-15 19:11:24.973 ThaliTest[1500:2398186] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 19:11:27.013 ThaliTest[1500:2398186] Using UIWebView
,2016-03-15 19:11:27.021 ThaliTest[1500:2398186] [CDVTimer][handleopenurl] 0.479996ms
,2016-03-15 19:11:27.030 ThaliTest[1500:2398186] [CDVTimer][intentandnavigationfilter] 8.086026ms
2016-03-15 19:11:27.031 ThaliTest[1500:2398186] [CDVTimer][gesturehandler] 0.375986ms
2016-03-15 19:11:27.031 ThaliTest[1500:2398186] [CDVTimer][TotalPluginStartup] 10.779023ms
,2016-03-15 19:11:33.841 ThaliTest[1500:2398186] Resetting plugins due to page load.
,2016-03-15 19:11:37.742 ThaliTest[1500:2398186] Finished load of: file:///var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/index.html
,2016-03-15 19:11:37.987 ThaliTest[1500:2398186] JXcore Cordova plugin initializing
,2016-03-15 19:11:37.988 ThaliTest[1500:2398380] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 19:11:51.962 ThaliTest[1500:2398380] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 19:11:51.962 ThaliTest[1500:2398380] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 19:11:51.962 ThaliTest[1500:2398380] jxcore: didRegisterToNative networkChanged
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-15 19:11:51.964 ThaliTest[1500:2398380] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0E3D494E-7B18-4C20-A3D0-44D67597D177/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
