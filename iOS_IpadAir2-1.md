#### Test 613623665d5a4d6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0E432E57-26FC-4D3A-9900-92BA91186330/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0E432E57-26FC-4D3A-9900-92BA91186330/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/613623665d5a4d6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50758"
,(lldb)     command script import "/tmp/0E432E57-26FC-4D3A-9900-92BA91186330/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-07 10:50:05.362 ThaliTest[814:1190602] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A0BAF774-84DB-4FCC-A510-03AFA4675B9B/Library/Cookies/Cookies.binarycookies
,2016-03-07 10:50:05.695 ThaliTest[814:1190602] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-07 10:50:05.696 ThaliTest[814:1190602] Multi-tasking -> Device: YES, App: YES
,2016-03-07 10:50:05.712 ThaliTest[814:1190602] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-07 10:50:07.627 ThaliTest[814:1190602] Using UIWebView
,2016-03-07 10:50:07.634 ThaliTest[814:1190602] [CDVTimer][handleopenurl] 0.400007ms
,2016-03-07 10:50:07.641 ThaliTest[814:1190602] [CDVTimer][intentandnavigationfilter] 6.581962ms
,2016-03-07 10:50:07.642 ThaliTest[814:1190602] [CDVTimer][gesturehandler] 0.306010ms
,2016-03-07 10:50:07.642 ThaliTest[814:1190602] [CDVTimer][TotalPluginStartup] 8.937001ms
,2016-03-07 10:50:14.643 ThaliTest[814:1190602] Resetting plugins due to page load.
,2016-03-07 10:50:18.459 ThaliTest[814:1190602] Finished load of: file:///var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/index.html
,2016-03-07 10:50:18.668 ThaliTest[814:1190602] JXcore Cordova plugin initializing
,2016-03-07 10:50:18.669 ThaliTest[814:1190856] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

,Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,INFO testUtils Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-07 10:50:30.260 ThaliTest[814:1190856] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-07 10:50:30.261 ThaliTest[814:1190856] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-07 10:50:30.261 ThaliTest[814:1190856] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}

,2016-03-07 10:50:30.262 ThaliTest[814:1190856] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/9CDC3F53-D8CB-4E26-822B-C20DAD25B876/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js


```
