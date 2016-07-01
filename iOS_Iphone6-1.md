#### Test 757892682308ffa_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/757892682308ffa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DF090A02-7470-456C-85E3-038F8DF46B7E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DF090A02-7470-456C-85E3-038F8DF46B7E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/757892682308ffa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/757892682308ffa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65335"
,(lldb)     command script import "/tmp/DF090A02-7470-456C-85E3-038F8DF46B7E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-01 10:54:34.115 ThaliTest[6103:18994761] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/817BC686-F15F-409B-9858-0719869E244C/Library/Cookies/Cookies.binarycookies
,2016-07-01 10:54:34.489 ThaliTest[6103:18994761] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-01 10:54:34.491 ThaliTest[6103:18994761] Multi-tasking -> Device: YES, App: YES
,2016-07-01 10:54:34.512 ThaliTest[6103:18994761] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-01 10:54:36.547 ThaliTest[6103:18994761] Using UIWebView
,2016-07-01 10:54:36.556 ThaliTest[6103:18994761] [CDVTimer][handleopenurl] 1.564026ms
,2016-07-01 10:54:36.563 ThaliTest[6103:18994761] [CDVTimer][intentandnavigationfilter] 7.085979ms
2016-07-01 10:54:36.564 ThaliTest[6103:18994761] [CDVTimer][gesturehandler] 0.356972ms
2016-07-01 10:54:36.565 ThaliTest[6103:18994761] [CDVTimer][TotalPluginStartup] 10.650992ms
,2016-07-01 10:54:43.672 ThaliTest[6103:18994761] Resetting plugins due to page load.
,2016-07-01 10:54:47.400 ThaliTest[6103:18994761] Finished load of: file:///var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/index.html
,2016-07-01 10:54:47.621 ThaliTest[6103:18994761] JXcore Cordova plugin initializing
,2016-07-01 10:54:47.622 ThaliTest[6103:18994951] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-01 10:54:55.130 ThaliTest[6103:18994951] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-01 10:54:55.130 ThaliTest[6103:18994951] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-01 10:54:55.131 ThaliTest[6103:18994951] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-01 10:54:55.133 ThaliTest[6103:18994951] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D8935B97-6DCD-4BA7-914B-A9ECF68A26D5/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-07-01 10:55:01.187 ThaliTest[6103:18994761] THREAD WARNING: ['JXcore'] took '5746.085938' ms. Plugin should use a background thread.
2016-07-01 10:55:01.188 ThaliTest[6103:18994761] ERROR: Method 'Test:' not defined in Plugin 'JXcore'
2016-07-01 10:,55:01.188 ThaliTest[6103:18994761] -[CDVCommandQueue executePending] [Line 142] FAILED pluginJSON = ["JXcore1097945387","JXcore","Test",[]]

```
