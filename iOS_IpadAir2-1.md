#### Test 64065450860dd96_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C40EAE96-012A-41FC-BCF1-2AB5B37432C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C40EAE96-012A-41FC-BCF1-2AB5B37432C2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/64065450860dd96/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55813"
,(lldb)     command script import "/tmp/C40EAE96-012A-41FC-BCF1-2AB5B37432C2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 18:24:03.178 ThaliTest[2182:3758900] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2419D8D2-8C43-4EE9-B76F-D25C15222C38/Library/Cookies/Cookies.binarycookies
,2016-03-24 18:24:03.514 ThaliTest[2182:3758900] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 18:24:03.515 ThaliTest[2182:3758900] Multi-tasking -> Device: YES, App: YES
,2016-03-24 18:24:03.529 ThaliTest[2182:3758900] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 18:24:05.491 ThaliTest[2182:3758900] Using UIWebView
,2016-03-24 18:24:05.499 ThaliTest[2182:3758900] [CDVTimer][handleopenurl] 0.398040ms
,2016-03-24 18:24:05.507 ThaliTest[2182:3758900] [CDVTimer][intentandnavigationfilter] 7.775009ms
,2016-03-24 18:24:05.508 ThaliTest[2182:3758900] [CDVTimer][gesturehandler] 0.349998ms
2016-03-24 18:24:05.509 ThaliTest[2182:3758900] [CDVTimer][TotalPluginStartup] 11.424005ms
,2016-03-24 18:24:13.486 ThaliTest[2182:3758900] Resetting plugins due to page load.
,2016-03-24 18:24:17.734 ThaliTest[2182:3758900] Finished load of: file:///var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/index.html
,2016-03-24 18:24:17.964 ThaliTest[2182:3758900] JXcore Cordova plugin initializing
,2016-03-24 18:24:17.965 ThaliTest[2182:3759151] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 18:24:24.463 ThaliTest[2182:3759151] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 18:24:24.463 ThaliTest[2182:3759151] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 18:24:24.463 ThaliTest[2182:3759151] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 18:24:24.465 ThaliTest[2182:3759151] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/0AF69DB6-1C5A-4BBC-8D52-0B2840FC03A2/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 18:24:29.712 ThaliTest[2182:3758900] THREAD WARNING: ['JXcore'] took '4971.821045' ms. Plugin should use a background thread.

```
