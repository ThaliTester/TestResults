#### Test 62509094764c200_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0A83D2F4-A1F6-4EE9-8885-A8CC93E714A2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0A83D2F4-A1F6-4EE9-8885-A8CC93E714A2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094764c200/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50950"
,(lldb)     command script import "/tmp/0A83D2F4-A1F6-4EE9-8885-A8CC93E714A2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 06:43:39.840 ThaliTest[1638:2616332] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BFF56C0A-1F0E-4428-81A5-CB82A07DB752/Library/Cookies/Cookies.binarycookies
,2016-03-17 06:43:40.170 ThaliTest[1638:2616332] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 06:43:40.171 ThaliTest[1638:2616332] Multi-tasking -> Device: YES, App: YES
,2016-03-17 06:43:40.186 ThaliTest[1638:2616332] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 06:43:41.852 ThaliTest[1638:2616332] Using UIWebView
,2016-03-17 06:43:41.859 ThaliTest[1638:2616332] [CDVTimer][handleopenurl] 0.517011ms
,2016-03-17 06:43:41.866 ThaliTest[1638:2616332] [CDVTimer][intentandnavigationfilter] 7.215977ms
,2016-03-17 06:43:41.867 ThaliTest[1638:2616332] [CDVTimer][gesturehandler] 0.344038ms
,2016-03-17 06:43:41.868 ThaliTest[1638:2616332] [CDVTimer][TotalPluginStartup] 10.046005ms
,2016-03-17 06:43:48.337 ThaliTest[1638:2616332] Resetting plugins due to page load.
,2016-03-17 06:43:51.446 ThaliTest[1638:2616332] Finished load of: file:///var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/index.html
,2016-03-17 06:43:51.644 ThaliTest[1638:2616332] JXcore Cordova plugin initializing
,2016-03-17 06:43:51.645 ThaliTest[1638:2616557] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,2016-03-17 06:43:55.428 ThaliTest[1638:2616557] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 06:43:55.428 ThaliTest[1638:2616557] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-17 06:43:55.428 ThaliTest[1638:2616557] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-17 06:43:55.431 ThaliTest[1638:2616557] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/95F10FA6-970D-4431-9A27-BB83D0B468A1/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

,2016-03-17 06:44:03.235 ThaliTest[1638:2616332] THREAD WARNING: ['JXcore'] took '5603.197021' ms. Plugin should use a background thread.

```
