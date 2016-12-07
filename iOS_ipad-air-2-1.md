#### Test 9691894766ea5e0_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/C5FA97DB-ABD3-48DD-B9BA-2EFCE5F8A8D6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C5FA97DB-ABD3-48DD-B9BA-2EFCE5F8A8D6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9691894766ea5e0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65524"
,(lldb)     command script import "/tmp/C5FA97DB-ABD3-48DD-B9BA-2EFCE5F8A8D6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 15:38:32.987 ThaliTest[408:272531] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A2F96870-FA0A-40F4-B0E5-E54A8B40C6C9/Library/Cookies/Cookies.binarycookies
,2016-12-07 15:38:33.319 ThaliTest[408:272531] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 15:38:33.320 ThaliTest[408:272531] Multi-tasking -> Device: YES, App: YES
,2016-12-07 15:38:33.336 ThaliTest[408:272531] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 15:38:35.188 ThaliTest[408:272531] Using UIWebView
,2016-12-07 15:38:35.195 ThaliTest[408:272531] [CDVTimer][handleopenurl] 0.420034ms
,2016-12-07 15:38:35.203 ThaliTest[408:272531] [CDVTimer][intentandnavigationfilter] 7.086992ms
2016-12-07 15:38:35.203 ThaliTest[408:272531] [CDVTimer][gesturehandler] 0.352025ms
2016-12-07 15:38:35.204 ThaliTest[408:272531] [CDVTimer][TotalPluginStartup] 9.563982ms
,2016-12-07 15:38:41.741 ThaliTest[408:272531] Resetting plugins due to page load.
,2016-12-07 15:38:44.947 ThaliTest[408:272531] Finished load of: file:///var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/index.html
,2016-12-07 15:38:45.165 ThaliTest[408:272531] JXcore Cordova plugin initializing
,2016-12-07 15:38:45.166 ThaliTest[408:272778] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-07 14:38:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Browser's mock node client received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 14:39:25 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  31.07790797948837
,Failed to execute UT.
,2016-12-07 14:39:25 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-12-07 14:39:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-12-07 14:39:26 - DEBUG UnitTest_app: 'My device name is: Apple-ipad-air-2-1'
,2016-12-07 14:39:26 - WARN testUtils: 'myNameCallback not set!'
,2016-12-07 14:39:28 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-12-07 14:39:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-07 14:39:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-07 14:39:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-07 14:39:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-07 14:39:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-07 14:39:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-07 14:39:31 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-07 15:39:31.924 ThaliTest[408:272531] THREAD WARNING: ['JXcore'] took '5995.977295' ms. Plugin should use a background thread.
,2016-12-07 14:39:32 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-07 14:39:33 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2016-12-07 14:39:33 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-07 14:39:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-07 14:39:33 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FB,F2BFFE7/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:250:22
tryCatcher@/private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Prom,ise.prototype._settlePromiseFromHandler@/private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/pri,vate/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/mobile/Containers/Bundle/Applicati,on/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/mobile/Containers/Bundle/Application/975631F4-3C51-47C9-8AE5-8B0FBF2BFFE7/Thal,iTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2016-12-07 14:39:33 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
