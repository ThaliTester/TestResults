#### Test 625481246b04bc0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F815D257-488D-449D-8E2A-FE6C9D21D6D4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F815D257-488D-449D-8E2A-FE6C9D21D6D4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246b04bc0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49493"
,(lldb)     command script import "/tmp/F815D257-488D-449D-8E2A-FE6C9D21D6D4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 12:45:00.766 ThaliTest[1423:2291583] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A590FB27-5B19-4E83-B016-EE342D5FCCBC/Library/Cookies/Cookies.binarycookies
,2016-03-15 12:45:01.132 ThaliTest[1423:2291583] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 12:45:01.133 ThaliTest[1423:2291583] Multi-tasking -> Device: YES, App: YES
,2016-03-15 12:45:01.154 ThaliTest[1423:2291583] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 12:45:02.886 ThaliTest[1423:2291583] Using UIWebView
,2016-03-15 12:45:02.893 ThaliTest[1423:2291583] [CDVTimer][handleopenurl] 0.607967ms
,2016-03-15 12:45:02.901 ThaliTest[1423:2291583] [CDVTimer][intentandnavigationfilter] 7.616043ms
2016-03-15 12:45:02.902 ThaliTest[1423:2291583] [CDVTimer][gesturehandler] 0.355005ms
2016-03-15 12:45:02.903 ThaliTest[1423:2291583] [CDVTimer][TotalPluginS,tartup] 10.180950ms
,2016-03-15 12:45:09.305 ThaliTest[1423:2291583] Resetting plugins due to page load.
,2016-03-15 12:45:12.567 ThaliTest[1423:2291583] Finished load of: file:///var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/index.html
,2016-03-15 12:45:12.787 ThaliTest[1423:2291583] JXcore Cordova plugin initializing
,2016-03-15 12:45:12.788 ThaliTest[1423:2291782] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone6-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 12:45:26.869 ThaliTest[1423:2291782] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-15 12:45:26.869 ThaliTest[1423:2291782] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-15 12:45:26.870 ThaliTest[1423:2291782] jxcore: didRegisterToNative networkChanged
,2016-03-15 12:45:26.871 ThaliTest[1423:2291782] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/81FD8965-58B0-4A3F-9583-F7049E79CE14/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
