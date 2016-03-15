#### Test 625481247d7767b_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BCC0A9B5-3EC3-492B-BDF4-2CA88A775AF7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BCC0A9B5-3EC3-492B-BDF4-2CA88A775AF7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49675"
,(lldb)     command script import "/tmp/BCC0A9B5-3EC3-492B-BDF4-2CA88A775AF7/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 14:59:36.359 ThaliTest[1126:2496537] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F508EEB6-71D5-41B6-B0AD-58A5A8EFCC65/Library/Cookies/Cookies.binarycookies
,2016-03-15 14:59:36.470 ThaliTest[1126:2496537] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 14:59:36.472 ThaliTest[1126:2496537] Multi-tasking -> Device: YES, App: YES
,2016-03-15 14:59:36.491 ThaliTest[1126:2496537] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 14:59:38.752 ThaliTest[1126:2496537] Using UIWebView
,2016-03-15 14:59:38.757 ThaliTest[1126:2496537] [CDVTimer][handleopenurl] 0.427008ms
,2016-03-15 14:59:38.763 ThaliTest[1126:2496537] [CDVTimer][intentandnavigationfilter] 5.948007ms
2016-03-15 14:59:38.764 ThaliTest[1126:2496537] [CDVTimer][gesturehandler] 0.293970ms
2016-03-15 14:59:38.764 ThaliTest[1126:2496537] [CDVTimer][TotalPluginS,tartup] 7.696986ms
,2016-03-15 14:59:47.049 ThaliTest[1126:2496537] Resetting plugins due to page load.
,2016-03-15 14:59:51.306 ThaliTest[1126:2496537] Finished load of: file:///var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/index.html
,2016-03-15 14:59:51.509 ThaliTest[1126:2496537] JXcore Cordova plugin initializing
,2016-03-15 14:59:51.511 ThaliTest[1126:2496728] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 15:00:16.951 ThaliTest[1126:2496728] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 15:00:16.952 ThaliTest[1126:2496728] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 15:00:16.954 ThaliTest[1126:2496728] jxcore: didRegisterToNative networkChanged
,2016-03-15 15:00:16.955 ThaliTest[1126:2496728] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9392F0A8-5ABD-4A3F-AB38-6A6D6169BBED/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
