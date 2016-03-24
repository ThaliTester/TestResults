#### Test 639107040172e2e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/639107040172e2e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2E42AE12-7DA5-444D-8A46-9B70E09CA85B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2E42AE12-7DA5-444D-8A46-9B70E09CA85B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/639107040172e2e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/639107040172e2e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55968"
,(lldb)     command script import "/tmp/2E42AE12-7DA5-444D-8A46-9B70E09CA85B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-24 22:19:27.469 ThaliTest[2199:3786505] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B905CEA4-C8C4-4D77-872A-214E8F18D13B/Library/Cookies/Cookies.binarycookies
,2016-03-24 22:19:27.779 ThaliTest[2199:3786505] Apache Cordova native platform version 4.1.0 is starting.
,2016-03-24 22:19:27.780 ThaliTest[2199:3786505] Multi-tasking -> Device: YES, App: YES
,2016-03-24 22:19:27.794 ThaliTest[2199:3786505] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-24 22:19:29.690 ThaliTest[2199:3786505] Using UIWebView
,2016-03-24 22:19:29.696 ThaliTest[2199:3786505] [CDVTimer][handleopenurl] 0.437975ms
,2016-03-24 22:19:29.703 ThaliTest[2199:3786505] [CDVTimer][intentandnavigationfilter] 6.546974ms
,2016-03-24 22:19:29.704 ThaliTest[2199:3786505] [CDVTimer][gesturehandler] 0.302017ms
,2016-03-24 22:19:29.704 ThaliTest[2199:3786505] [CDVTimer][TotalPluginStartup] 8.961022ms
,2016-03-24 22:19:37.126 ThaliTest[2199:3786505] Resetting plugins due to page load.
,2016-03-24 22:19:40.717 ThaliTest[2199:3786505] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/index.html
,2016-03-24 22:19:40.935 ThaliTest[2199:3786505] JXcore Cordova plugin initializing
,2016-03-24 22:19:40.936 ThaliTest[2199:3786739] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-24 22:19:47.374 ThaliTest[2199:3786739] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-03-24 22:19:47.374 ThaliTest[2199:3786739] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-24 22:19:47.375 ThaliTest[2199:3786739] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-24 22:19:47.376 ThaliTest[2199:3786739] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/6B551A7C-8C8A-4AAD-8D80-B79193C7008C/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-24 22:19:52.578 ThaliTest[2199:3786505] THREAD WARNING: ['JXcore'] took '4928.119873' ms. Plugin should use a background thread.

```
