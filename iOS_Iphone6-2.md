#### Test 93142442ff07d87_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/08746F91-6F38-48A6-BC5C-C3199D1B65A1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/08746F91-6F38-48A6-BC5C-C3199D1B65A1/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56487"
,(lldb)     command script import "/tmp/08746F91-6F38-48A6-BC5C-C3199D1B65A1/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 04:58:09.858 ThaliTest[3270:7298790] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/89AD7FA8-93CA-47CF-B4F4-15912A5553AF/Library/Cookies/Cookies.binarycookies
,2016-11-10 04:58:09.953 ThaliTest[3270:7298790] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 04:58:09.955 ThaliTest[3270:7298790] Multi-tasking -> Device: YES, App: YES
,2016-11-10 04:58:09.978 ThaliTest[3270:7298790] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 04:58:10.631 ThaliTest[3270:7298790] Using UIWebView
2016-11-10 04:58:10.637 ThaliTest[3270:7298790] [CDVTimer][handleopenurl] 0.371993ms
,2016-11-10 04:58:10.647 ThaliTest[3270:7298790] [CDVTimer][intentandnavigationfilter] 9.204984ms
2016-11-10 04:58:10.648 ThaliTest[3270:7298790] [CDVTimer][gesturehandler] 0.306010ms
2016-11-10 04:58:10.648 ThaliTest[3270:7298790] [CDVTimer][TotalPluginStartup] 11.441052ms
,2016-11-10 04:58:18.009 ThaliTest[3270:7298790] Resetting plugins due to page load.
,2016-11-10 04:58:18.701 ThaliTest[3270:7298790] Finished load of: file:///var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/index.html
,2016-11-10 04:58:19.116 ThaliTest[3270:7298790] JXcore Cordova plugin initializing
2016-11-10 04:58:19.117 ThaliTest[3270:7298999] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 12:58:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 12:58:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 12:58:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-10 12:58:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 12:58:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 12:58:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-10 12:58:52 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  102
Number of passed tests:  99
Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  23.09384900331497
,Failed to execute UT.
,2016-11-10 12:58:52 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-11-10 12:58:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-11-10 12:58:53 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-2'
2016-11-10 12:58:53 - WARN testUtils: 'myNameCallback not set!'
2016-11-10 12:58:53 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-11-10 12:58:55 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-10 12:58:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-10 12:58:56 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-10 12:58:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-10 12:58:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-10 12:58:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-10 12:58:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-10 12:58:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-10 12:58:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-10 12:58:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2B56CE8B,-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2B56CE8B,-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-10 12:59:01 - DEBUG CoordinatedClient: 'reconnected to the test server'
2016-11-10 12:59:01 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-11-10 12:59:01 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2016-11-10 12:59:01 - DEBUG CoordinatedClient: 'test client failed'
,2016-11-10 12:59:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-11-10 12:59:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A,/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:184:20
tryCatcher@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype.,_settlePromiseFromHandler@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/B,undle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC,7,F77A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/2B56CE8B-643C-4487-A58B-3A0FBCC7F77A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2016-11-10 12:59:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
