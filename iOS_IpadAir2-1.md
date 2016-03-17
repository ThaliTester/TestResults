#### Test 62509094141ff10_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/66ED47F4-F5F5-4CF2-A4EF-36E1F2164FE5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/66ED47F4-F5F5-4CF2-A4EF-36E1F2164FE5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51454"
,(lldb)     command script import "/tmp/66ED47F4-F5F5-4CF2-A4EF-36E1F2164FE5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 11:16:29.185 ThaliTest[1679:2649394] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/54B4B663-6498-4887-A1D9-A0B98CDFA6D2/Library/Cookies/Cookies.binarycookies
,2016-03-17 11:16:29.555 ThaliTest[1679:2649394] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 11:16:29.557 ThaliTest[1679:2649394] Multi-tasking -> Device: YES, App: YES
,2016-03-17 11:16:29.578 ThaliTest[1679:2649394] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 11:16:31.517 ThaliTest[1679:2649394] Using UIWebView
,2016-03-17 11:16:31.524 ThaliTest[1679:2649394] [CDVTimer][handleopenurl] 0.477016ms
,2016-03-17 11:16:31.531 ThaliTest[1679:2649394] [CDVTimer][intentandnavigationfilter] 6.601989ms
,2016-03-17 11:16:31.532 ThaliTest[1679:2649394] [CDVTimer][gesturehandler] 0.308037ms
,2016-03-17 11:16:31.532 ThaliTest[1679:2649394] [CDVTimer][TotalPluginStartup] 9.139001ms
,2016-03-17 11:16:38.436 ThaliTest[1679:2649394] Resetting plugins due to page load.
,2016-03-17 11:16:42.020 ThaliTest[1679:2649394] Finished load of: file:///var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/index.html
,2016-03-17 11:16:42.230 ThaliTest[1679:2649394] JXcore Cordova plugin initializing
,2016-03-17 11:16:42.231 ThaliTest[1679:2649616] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 11:16:46.025 ThaliTest[1679:2649616] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-17 11:16:46.025 ThaliTest[1679:2649616] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-03-17 11:16:46.026 ThaliTest[1679:2649616] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 11:16:46.028 ThaliTest[1679:2649616] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/18F8E2E2-F8E4-46E4-A5CF-E613FEFB028E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 11:16:53.816 ThaliTest[1679:2649394] THREAD WARNING: ['JXcore'] took '5597.839111' ms. Plugin should use a background thread.
,Reconnected to the test server
,--= Surplus to requirements =--
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
