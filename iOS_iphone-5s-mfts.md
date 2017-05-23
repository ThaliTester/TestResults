#### Test 1219585698171119_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AB481D54-4772-49A4-99B1-31AADDEB5B8D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/AB481D54-4772-49A4-99B1-31AADDEB5B8D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59066"
,(lldb)     command script import "/tmp/AB481D54-4772-49A4-99B1-31AADDEB5B8D/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
(lldb) ,JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-05-23 11:31:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.846676886081696
(lldb) ,2017-05-23 11:31:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-05-23 11:31:58 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-23 11:32:02 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-23 11:32:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-23 11:32:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-23 11:32:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-23 11:32:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-05-23 11:32:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-05-23 11:32:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-23 11:32:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-23 11:32:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
(lldb) ,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-23 11:32:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-23 11:32:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-23 11:32:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-23 11:32:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-23 11:32:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-23 11:32:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-05-23 11:32:06 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-05-23 11:32:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A4,2-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-23 11:32:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A4(lldb) ,2-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-23 11:32:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-23 11:32:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A4(lldb) ,2-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-23 11:32:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-23 11:32:24 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-23 11:32:24 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-23 11:32:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-05-23 11:32:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-23 11:32:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-05-23 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-05-23 11:32:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-05-23 11:32:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
(lldb) ,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-05-23 11:32:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-05-23 11:32:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
(lldb) ,ok 5 should be equal
,ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
(lldb) ,ok 8 should be equal
,ok 9 should be equal
(lldb) ,ok 10 should be equal
,ok 11 should be equal
,ok 12 should be equal
(lldb) ,ok 13 should be equal
,ok 14 should be equal
,# teardown
(lldb) ,# setup
,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
(lldb) ,ok 23 thirdPromise testValue
,# teardown
(lldb) ,# setup
,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
(lldb) ,# teardown
,# setup
,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
(lldb) ,# teardown
,# setup
(lldb) ,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
(lldb) ,# teardown
,# setup
,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
,# teardown
(lldb) ,# setup
,# basic
(lldb) ,ok 44 sane
(lldb) ,# teardown
,# setup
,# another
(lldb) ,ok 45 sane
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox spy
,2017-05-23 11:33:09 - DEBUG testTests: 'test spy method for global sinon sansbox'
(lldb) ,ok 46 test sandbox spy works correctly
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
,# test sinon sansbox stub override
(lldb) ,ok 48 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox mock
,# teardown
(lldb) ,# setup
,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
(lldb) ,ok 50 test participant has uuid
ok 51 participant data matches
ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
(lldb) ,# teardown
,# setup
(lldb) ,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-05-23 11:33:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:33:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:33:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-05-23 11:33:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-05-23 11:33:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:33:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:33:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:33:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23(lldb) , 11:33:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
(lldb) ,ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:57 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:33:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:33:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-05-23 11:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:34:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:34:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
(lldb) ,2017-05-23 11:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:34:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:34:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:08 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:34:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:34:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-05-23 11:34:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 70 Can call stopListeningForAdvertisements without error
2017-05-23 11:34:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:32 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:37 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:34:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:34:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-05-23 11:35:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-23 11:35:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:35:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-05-23 11:35:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05(lldb) ,-23 11:35:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:36:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:36:03 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:36:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:36:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:36:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-05-23 11:37:04 - INFO Coord(lldb) ,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes(lldb) , that are in the checkpoints plugin delay interval'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-05,-(lldb) ,23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGE,R result: passed - enqueue and run in order'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enq(lldb) ,ueueAtTop'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
(lldb) ,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-05-23 11:37:04 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Calling startUpdateAdvertisingAndListening twice is NOT an error, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/75F30(lldb) ,ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modu,les/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
(lldb) ,2017-05-23 11:37:04 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-05-23 11:37:08 - DEBUG CoordinatedClient: 'all tests completed'
(lldb) ,2017-05-23 11:37:24 - DEBUG CoordinatedClient: 'test client disconnected'
2017-05-23 11:37:24 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-05-23 11:37:24 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_Can call start/stopUpdateAdvertisingAndListening_finished', test: 'Can call start/stopUpdateAdvertisingAndListening'', stack: ',CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:291:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/75F30ADF-E5,(lldb) ,F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/socket.io-clien,t/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Ap(lldb) ,p,lication/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/75F30ADF-E5F6-4A42-B993-BFE5796E3D5D/ThaliTest.app/www/jxcore/node_modules/(lldb) ,component-emitter/index.js:131:7''
2017-05-23 11:37:24 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
