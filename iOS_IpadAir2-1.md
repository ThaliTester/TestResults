#### Test 72145431fdae11f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/511F89F1-DA08-4073-9714-0D7356FE3D8B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/511F89F1-DA08-4073-9714-0D7356FE3D8B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/72145431fdae11f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64725"
,(lldb)     command script import "/tmp/511F89F1-DA08-4073-9714-0D7356FE3D8B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-06-30 10:33:18.044 ThaliTest[3409:12826551] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EB52A690-9A45-4453-87C6-9B6EB083371B/Library/Cookies/Cookies.binarycookies
,2016-06-30 10:33:18.287 ThaliTest[3409:12826551] Apache Cordova native platform version 4.1.1 is starting.
,2016-06-30 10:33:18.288 ThaliTest[3409:12826551] Multi-tasking -> Device: YES, App: YES
,2016-06-30 10:33:18.301 ThaliTest[3409:12826551] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-06-30 10:33:19.105 ThaliTest[3409:12826551] Using UIWebView
,2016-06-30 10:33:19.107 ThaliTest[3409:12826551] [CDVTimer][handleopenurl] 0.111997ms
,2016-06-30 10:33:19.109 ThaliTest[3409:12826551] [CDVTimer][intentandnavigationfilter] 1.839995ms
2016-06-30 10:33:19.110 ThaliTest[3409:12826551] [CDVTimer][gesturehandler] 0.095010ms
2016-06-30 10:33:19.110 ThaliTest[3409:12826551] [CDVTimer][TotalPluginStartup] 2.475977ms
,2016-06-30 10:33:22.260 ThaliTest[3409:12826551] Resetting plugins due to page load.
,2016-06-30 10:33:23.646 ThaliTest[3409:12826551] Finished load of: file:///var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/index.html
,2016-06-30 10:33:23.772 ThaliTest[3409:12826551] JXcore Cordova plugin initializing
,2016-06-30 10:33:23.773 ThaliTest[3409:12826724] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-06-30 10:33:30.176 ThaliTest[3409:12826724] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-06-30 10:33:30.177 ThaliTest[3409:12826724] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-06-30 10:33:30.177 ThaliTest[3409:12826724] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-06-30 10:33:30.178 ThaliTest[3409:12826724] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/013735A0-3022-4816-90CC-B5D5E517A7BA/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-06-30 10:33:35.334 ThaliTest[3409:12826551] THREAD WARNING: ['JXcore'] took '4884.333008' ms. Plugin should use a background thread.

```
