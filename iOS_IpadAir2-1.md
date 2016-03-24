#### Test 640346198400100_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/75EF202F-B092-477E-880B-F0AA6DDC47B9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/75EF202F-B092-477E-880B-F0AA6DDC47B9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/640346198400100/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55556"
,(lldb)     command script import "/tmp/75EF202F-B092-477E-880B-F0AA6DDC47B9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 15:02:03.099 ThaliTest[2147:3732651] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B3DDB051-9233-444B-9F1A-8644C301D82F/Library/Cookies/Cookies.binarycookies
,2016-03-24 15:02:03.417 ThaliTest[2147:3732651] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 15:02:03.418 ThaliTest[2147:3732651] Multi-tasking -> Device: YES, App: YES
,2016-03-24 15:02:03.432 ThaliTest[2147:3732651] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 15:02:05.078 ThaliTest[2147:3732651] Using UIWebView
,2016-03-24 15:02:05.084 ThaliTest[2147:3732651] [CDVTimer][handleopenurl] 0.374019ms
,2016-03-24 15:02:05.089 ThaliTest[2147:3732651] [CDVTimer][intentandnavigationfilter] 4.690945ms
,2016-03-24 15:02:05.089 ThaliTest[2147:3732651] [CDVTimer][gesturehandler] 0.213027ms
,2016-03-24 15:02:05.090 ThaliTest[2147:3732651] [CDVTimer][TotalPluginStartup] 6.359994ms
,2016-03-24 15:02:12.719 ThaliTest[2147:3732651] Resetting plugins due to page load.
,2016-03-24 15:02:16.414 ThaliTest[2147:3732651] Finished load of: file:///var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/index.html
,2016-03-24 15:02:16.651 ThaliTest[2147:3732651] JXcore Cordova plugin initializing
,2016-03-24 15:02:16.652 ThaliTest[2147:3732891] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 15:02:23.082 ThaliTest[2147:3732891] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 15:02:23.082 ThaliTest[2147:3732891] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 15:02:23.083 ThaliTest[2147:3732891] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 15:02:23.084 ThaliTest[2147:3732891] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0F4BDA93-C030-40DF-89A0-F06001C3A205/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 15:02:28.259 ThaliTest[2147:3732651] THREAD WARNING: ['JXcore'] took '4901.750000' ms. Plugin should use a background thread.

```
