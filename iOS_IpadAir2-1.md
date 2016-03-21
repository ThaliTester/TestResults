#### Test 625481246894564_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D7D075DF-CD21-427F-89F7-605CEFA3FF20/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D7D075DF-CD21-427F-89F7-605CEFA3FF20/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481246894564/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54165"
,(lldb)     command script import "/tmp/D7D075DF-CD21-427F-89F7-605CEFA3FF20/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 13:02:15.988 ThaliTest[1945:3253379] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1AE10A5E-7FFB-4BDD-BFAF-E913022A79CE/Library/Cookies/Cookies.binarycookies
,2016-03-21 13:02:16.409 ThaliTest[1945:3253379] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 13:02:16.410 ThaliTest[1945:3253379] Multi-tasking -> Device: YES, App: YES
,2016-03-21 13:02:16.428 ThaliTest[1945:3253379] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 13:02:18.259 ThaliTest[1945:3253379] Using UIWebView
,2016-03-21 13:02:18.265 ThaliTest[1945:3253379] [CDVTimer][handleopenurl] 0.411034ms
,2016-03-21 13:02:18.273 ThaliTest[1945:3253379] [CDVTimer][intentandnavigationfilter] 7.252991ms
,2016-03-21 13:02:18.274 ThaliTest[1945:3253379] [CDVTimer][gesturehandler] 0.356972ms
2016-03-21 13:02:18.274 ThaliTest[1945:3253379] [CDVTimer][TotalPluginStartup] 9.618998ms
,2016-03-21 13:02:24.889 ThaliTest[1945:3253379] Resetting plugins due to page load.
,2016-03-21 13:02:28.477 ThaliTest[1945:3253379] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/index.html
,2016-03-21 13:02:28.746 ThaliTest[1945:3253379] JXcore Cordova plugin initializing
,2016-03-21 13:02:28.747 ThaliTest[1945:3253642] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 13:02:35.230 ThaliTest[1945:3253642] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 13:02:35.231 ThaliTest[1945:3253642] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-21 13:02:35.231 ThaliTest[1945:3253642] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 13:02:35.233 ThaliTest[1945:3253642] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/EE8AD340-923F-462E-9406-1EB922FA7745/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 13:02:40.444 ThaliTest[1945:3253379] THREAD WARNING: ['JXcore'] took '4935.026855' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
