#### Test 625481247756efd_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7C012CEE-9F40-4B37-9388-9FE63A2E8B94/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7C012CEE-9F40-4B37-9388-9FE63A2E8B94/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247756efd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49440"
,(lldb)     command script import "/tmp/7C012CEE-9F40-4B37-9388-9FE63A2E8B94/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 16:05:46.756 ThaliTest[1183:1777760] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E2AAC1E0-8197-42EB-940A-5F4E5D25E241/Library/Cookies/Cookies.binarycookies
,2016-03-11 16:05:47.182 ThaliTest[1183:1777760] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 16:05:47.184 ThaliTest[1183:1777760] Multi-tasking -> Device: YES, App: YES
,2016-03-11 16:05:47.210 ThaliTest[1183:1777760] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 16:05:48.837 ThaliTest[1183:1777760] Using UIWebView
,2016-03-11 16:05:48.844 ThaliTest[1183:1777760] [CDVTimer][handleopenurl] 0.454009ms
,2016-03-11 16:05:48.853 ThaliTest[1183:1777760] [CDVTimer][intentandnavigationfilter] 7.902980ms
2016-03-11 16:05:48.854 ThaliTest[1183:1777760] [CDVTimer][gesturehandler] 0.420034ms
2016-03-11 16:05:48.854 ThaliTest[1183:1777760] [CDVTimer][TotalPluginStartup] 10.649979ms
,2016-03-11 16:05:55.050 ThaliTest[1183:1777760] Resetting plugins due to page load.
,2016-03-11 16:05:58.095 ThaliTest[1183:1777760] Finished load of: file:///var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/index.html
,2016-03-11 16:05:58.336 ThaliTest[1183:1777760] JXcore Cordova plugin initializing
,2016-03-11 16:05:58.338 ThaliTest[1183:1777957] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-Iphone5s-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-11 16:06:14.203 ThaliTest[1183:1777957] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-11 16:06:14.204 ThaliTest[1183:1777957] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 16:06:14.205 ThaliTest[1183:1777957] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-11 16:06:14.206 ThaliTest[1183:1777957] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/57A17AC3-6039-4941-86B5-BDED3981E535/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,Reconnected to the test server

,--= Surplus to requirements =--

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
