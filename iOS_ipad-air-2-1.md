#### Test 969189473645b2d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/74A0043C-41AE-41D9-B6FE-452FA36947C3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/74A0043C-41AE-41D9-B6FE-452FA36947C3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/969189473645b2d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49832"
,(lldb)     command script import "/tmp/74A0043C-41AE-41D9-B6FE-452FA36947C3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 16:57:06.842 ThaliTest[1368:2961225] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/319430E8-04B0-4343-AF9C-02BC08E1D256/Library/Cookies/Cookies.binarycookies
,2016-12-26 16:57:07.159 ThaliTest[1368:2961225] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 16:57:07.160 ThaliTest[1368:2961225] Multi-tasking -> Device: YES, App: YES
,2016-12-26 16:57:07.175 ThaliTest[1368:2961225] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 16:57:08.939 ThaliTest[1368:2961225] Using UIWebView
,2016-12-26 16:57:08.948 ThaliTest[1368:2961225] [CDVTimer][handleopenurl] 0.328004ms
,2016-12-26 16:57:08.955 ThaliTest[1368:2961225] [CDVTimer][intentandnavigationfilter] 6.233990ms
,2016-12-26 16:57:08.956 ThaliTest[1368:2961225] [CDVTimer][gesturehandler] 0.271022ms
,2016-12-26 16:57:08.956 ThaliTest[1368:2961225] [CDVTimer][TotalPluginStartup] 8.351982ms
,2016-12-26 16:57:15.290 ThaliTest[1368:2961225] Resetting plugins due to page load.
,2016-12-26 16:57:18.322 ThaliTest[1368:2961225] Finished load of: file:///var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/index.html
,2016-12-26 16:57:18.529 ThaliTest[1368:2961225] JXcore Cordova plugin initializing
,2016-12-26 16:57:18.530 ThaliTest[1368:2961440] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-12-26 15:57:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 15:57:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.99059796333313
,2016-12-26 15:57:55 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-12-26 15:57:56 - DEBUG UnitTest_app: 'My device name is: Apple-ipad-air-2-1'
,2016-12-26 15:57:56 - WARN testUtils: 'myNameCallback not set!'
,2016-12-26 15:57:58 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2016-12-26 15:57:58 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-12-26 15:57:58 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-12-26 15:57:58 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-12-26 15:57:59 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-12-26 15:58:00 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-12-26 15:58:01 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-12-26 15:58:01 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2016-12-26 16:58:01.933 ThaliTest[1368:2961225] THREAD WARNING: ['JXcore'] took '6462.143066' ms. Plugin should use a background thread.
,2016-12-26 15:58:02 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-12-26 16:02:48 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-12-26 16:02:48 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655,F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/en,gine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobi,le/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-26 16:02:48 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 16:02:48 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655,F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/en,gine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobi,le/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2016-12-26 16:02:48 - DEBUG CoordinatedClient: 'test client failed'
,2016-12-26 16:02:48 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modul,es/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocke,t.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/106C34FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/106C3,4FE-D925-4526-84DF-6BFD6D4655F5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2016-12-26 16:02:48 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
