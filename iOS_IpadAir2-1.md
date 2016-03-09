#### Test 6012434764ab483_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0D52A2D9-EBC5-4412-A653-8B866C539C5B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0D52A2D9-EBC5-4412-A653-8B866C539C5B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6012434764ab483/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49653"
,(lldb)     command script import "/tmp/0D52A2D9-EBC5-4412-A653-8B866C539C5B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-09 02:36:45.198 ThaliTest[948:1429579] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/92D160E8-D4B7-4E81-9F24-5376AF947726/Library/Cookies/Cookies.binarycookies
,2016-03-09 02:36:45.618 ThaliTest[948:1429579] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-09 02:36:45.619 ThaliTest[948:1429579] Multi-tasking -> Device: YES, App: YES
,2016-03-09 02:36:45.637 ThaliTest[948:1429579] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-09 02:36:47.497 ThaliTest[948:1429579] Using UIWebView
,2016-03-09 02:36:47.504 ThaliTest[948:1429579] [CDVTimer][handleopenurl] 0.411987ms
,2016-03-09 02:36:47.511 ThaliTest[948:1429579] [CDVTimer][intentandnavigationfilter] 6.769001ms
,2016-03-09 02:36:47.512 ThaliTest[948:1429579] [CDVTimer][gesturehandler] 0.315011ms
,2016-03-09 02:36:47.513 ThaliTest[948:1429579] [CDVTimer][TotalPluginStartup] 9.092987ms
,2016-03-09 02:36:54.288 ThaliTest[948:1429579] Resetting plugins due to page load.
,2016-03-09 02:36:57.963 ThaliTest[948:1429579] Finished load of: file:///var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/index.html
,2016-03-09 02:36:58.175 ThaliTest[948:1429579] JXcore Cordova plugin initializing
,2016-03-09 02:36:58.177 ThaliTest[948:1429836] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-09 02:37:04.771 ThaliTest[948:1429836] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-09 02:37:04.771 ThaliTest[948:1429836] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-09 02:37:04.771 ThaliTest[948:1429836] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":false,"wifi":true,"blueTooth":true,"cellular":true,"bssidName":null}

,2016-03-09 02:37:04.773 ThaliTest[948:1429836] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0236B624-1320-4506-96C6-166235DCEAB2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Unit Test app is loaded


```
