#### Test 113351851b596518_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851b596518/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C325A55A-3B4F-42BA-86EC-E2817A4204B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C325A55A-3B4F-42BA-86EC-E2817A4204B3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851b596518/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851b596518/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52636"
,(lldb)     command script import "/tmp/C325A55A-3B4F-42BA-86EC-E2817A4204B3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 06:55:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-06-22 06:55:18 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
(lldb) ,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.568049013614655
,2017-06-22 06:55:18 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-06-22 06:55:18 - WARN testUtils: 'myNameCallback not set!'
,2017-06-22 06:55:22 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-22 06:55:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-22 06:55:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-22 06:55:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-22 06:55:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-22 06:55:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-22 06:55:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-22 06:55:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-22 06:55:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-06-22 06:55:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-22 06:55:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1B32E068-1B39-428(lldb) ,7-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-22 06:55:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1B32E068-1B39-428(lldb) ,7-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-22 06:55:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-22 06:55:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1B32E068-1B39-428(lldb) ,7-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-22 06:55:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-22 06:55:44 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-06-22 06:55:44 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-22 06:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-22 06:56:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-22 06:56:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-06-22 06:56:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-06-22 06:56:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-22 06:56:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-06-22 06:56:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
(lldb) ,# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-06-22 06:56:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
(lldb) ,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
,# teardown
(lldb) ,# setup
(lldb) ,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
(lldb) ,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
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
(lldb) ,# mix enqueue and enqueueAtTop
,ok 31 fourth
(lldb) ,ok 32 fourth
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
,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
(lldb) ,# teardown
,# setup
(lldb) ,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
,# teardown
(lldb) ,# setup
,# basic
(lldb) ,ok 44 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
,ok 45 sane
(lldb) ,# teardown
,# setup
(lldb) ,# skip
,2017-06-22 06:57:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# another skip
(lldb) ,2017-06-22 06:57:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
(lldb) ,# setup
,# test sinon sansbox spy
(lldb) ,2017-06-22 06:58:21 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
(lldb) ,ok 48 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox restore after test end
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
,# teardown
(lldb) ,# setup
(lldb) ,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
(lldb) ,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
(lldb) ,ok 61 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-06-22 07:00:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
(lldb) ,# teardown
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:00:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
(lldb) ,2017-06-22 07:00:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:00:45 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:00:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 63 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow,n
2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:00:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:00:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-06-22 07:00:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:00:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-22 07:00:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-22 07:00:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-22 07:00:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-06-22 07:00:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:55 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 70 Can call stopListeningForAdvertisements without error
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:55 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
,2017-06-22 07:00:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:00:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:00:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-06-22 07:00:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:00 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:01:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:01:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,2017-06-22 07:01:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 78 Can call startUpdateAdvertisingAndListening without error
,2017-06-22 07:01:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-22 07:01:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
(lldb) ,# teardown
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',(lldb) ,
2017-06-22 07:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,bilityChanged registered to native'
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:01:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-06-22 07:01:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 82 Can call startUpdateAdvertisingAndListening without error
2017-06-22 07:01:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:14 - INFO thaliMobile:(lldb) , 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:01:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardow,n
2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:01:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# peerAvailabilityChange is called
(lldb) ,2017-06-22 07:01:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
2017-06-22 07:01:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-22(lldb) , 07:01:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-06-22 07:01:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,ok 88 peers must be an array
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
(lldb) ,# teardown
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',
2017-06-22 07:01:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,b(lldb) ,ilityChanged registered to native'
(lldb) ,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:01:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can connect to a remote peer
(lldb) ,2017-06-22 07:01:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can connect to a remote peer''
,# teardown
(lldb) ,2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:01:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Should be able to call stopAdvertisingAndListening in teardow,n
2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:01:46 -(lldb) , DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:01:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# Can shift data
(lldb) ,2017-06-22 07:01:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:01:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:01:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 98 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:01:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:01:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:01:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:01:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
(lldb) ,2017-06-22 07:01:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data via parallel connections''
,# teardown
(lldb) ,2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:02:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 99 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopAdvertisingAndListening in teardo,wn
2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:02:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data securely
(lldb) ,2017-06-22 07:02:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data securely''
,# teardown
(lldb) ,2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 101 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:27 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat,ive'
2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:02:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:02:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift large amounts of data
,2017-06-22 07:02:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift large amounts of data''
(lldb) ,# teardown
,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 103 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:32 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
(lldb) ,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
(lldb) ,2017-06-22 07:02:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:02:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:02:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 105 Ready to advertise
2017-06-22 07:02:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-06-22 07:02:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-06-22 07:02:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Ready to listen
,2017-06-22 07:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:02:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 107 stop ads worked
,2017-06-22 07:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,ok 108 test stop worked
(lldb) ,# teardown
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 109 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 110 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Test updating advertising and parallel data transfer
,(lldb) ,2017-06-22 07:02:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 111 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 112 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# discoveryAdvertisingStateUpdateNonTCP is called
(lldb) ,ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
ok 115 discoveryActive should be false
ok 116 advertisingActive should be true
,ok 117 discoveryActive should be false
ok 118 advertisingActive should be true
ok 119 discoveryActive should be false
ok 120 advertisingActive should be true
ok 121 Can call stopAdvertisingAndListening without error
(lldb) ,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-(lldb) ,91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":8,"ok":true,"name":"Can call stopAdvertisingAndListening without error","operator":"notOk","actu(lldb) ,al":null,"expected":false}''
,ok 122 Can call stopListeningForAdvertisements without error
(lldb) ,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-(lldb) ,91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":9,"ok":true,"name":"Can call stopListeningForAdvertisements without error","operator":"notOk","a(lldb) ,ctual":null,"expected":false}''
,ok 123 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-(lldb) ,91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":10,"ok":true,"name":"Can call startUpdateAdvertisingAndListening without error","operator":"notO(lldb) ,k","actual":null,"expected":false}''
,ok 124 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-(lldb) ,91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/1B32E068-1B39-4287-91E1-9C1F18304335/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":11,"ok":true,"name":"Can call startListeningForAdvertisements without error","operator":"notOk",(lldb) ,"actual":null,"expected":false}''
,# teardown
(lldb) ,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# cannot call connect when start listening for advertisements is not active
(lldb) ,2017-06-22 07:02:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
(lldb) ,2017-06-22 07:03:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 127 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:26 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 128 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# Get error when trying to double connect to a peer on Android
(lldb) ,2017-06-22 07:03:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
(lldb) ,2017-06-22 07:03:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:03:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teard,own
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-06-22 07:03:34 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:03:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:03:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teard,own
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
(lldb) ,2017-06-22 07:03:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,2017-06-22 07:03:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:36 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 134 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
(lldb) ,2017-06-22 07:03:37 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
(lldb) ,2017-06-22 07:03:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:03:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 135 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-22 07:03:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:03:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-06-22 07:03:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 137 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:39 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# setup
(lldb) ,# cannot call multiConnect when start listening for advertisements is not active
,ok 139 Got null as expected
2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IoYNnKdXxIjRPiU0bNZ6nnM1arUgDVo5","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 140 Should only get ca(lldb) ,lled after multiConnect returned
ok 141 SyncValue matches
ok 142 Got right error
,ok 143 listeningPort is null
2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9f25ff5c-fea7-46df-8d43-e6b4d256f84d","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-06-(lldb) ,22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9f25f(lldb) ,f5c-fea7-46df-8d43-e6b4d256f84d","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 144 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:03:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:03:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# cannot call multiConnect with illegal peerID
,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:04:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:04:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 146 No error on starting
ok 147 Got null as expected
(lldb) ,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WUFKZIjJieLsGa106oOj3xnQmsjAnKbr","error":"Illegal peerID","portNumber":null}'
ok 148 Should only get called after multiConnect returned
ok 149 SyncValue matches
,ok 150 Got right error
ok 151 listeningPort is null
(lldb) ,# teardown
,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:02 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 153 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# multiConnect properly fails on legal but non-existent peerID
(lldb) ,2017-06-22 07:04:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:04:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:04:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 154 No error on starting
,ok 155 Got null as expected
2017-06-22 07:04:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FNt7G2Y5gJPe6CKhV9CpAXhLMI09uqix","error":"Connection could not be established","portNumber":null}'
ok 156 Should only get called after(lldb) , multiConnect returned
ok 157 SyncValue matches
ok 158 Got right error
,ok 159 listeningPort is null
(lldb) ,2017-06-22 07:04:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"c361a91b-ff79-4c32-88bc-b61e649732eb","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-06-22 07:04:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,2017-06-22 07:04:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"c361a91b-ff79-4c32-88bc-b61e649732eb","peerAvailable":true,"portNumber":null,"recreated":true}'
(lldb) ,2017-06-22 07:04:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
(lldb) ,2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:26 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat,ive'
2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:04:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# cannot call multiConnect with invalid syncValue
,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:04:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:04:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 162 No error on starting
(lldb) ,ok 163 Got right error
,# teardown
(lldb) ,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:04:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 164 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:04:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 165 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# disconnect doesn't fail on bad peer id
(lldb) ,ok 166 No error
(lldb) ,# teardown
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 167 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:36 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 168 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat,ive'
2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:04:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
(lldb) ,ok 169 No error
(lldb) ,# teardown
,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 170 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:51 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 171 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Get same port when trying to connect multiple times on iOS
(lldb) ,2017-06-22 07:04:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:05:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 172 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:05:06 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:05:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# initial peer discovery
(lldb) ,2017-06-22 07:05:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
(lldb) ,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:13 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:05:13 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# update peer discovery 1
,2017-06-22 07:05:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
(lldb) ,# teardown
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:15 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# update peer discovery 2
,2017-06-22 07:05:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
(lldb) ,# teardown
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:17 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# check latest peer discovery
(lldb) ,2017-06-22 07:05:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:20 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Set up for no peer discovery test
,2017-06-22 07:05:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# no peer discovery
(lldb) ,2017-06-22 07:05:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
(lldb) ,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:06:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:06:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# calling createNativeListener directly rejects
(lldb) ,2017-06-22 07:06:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-06-22 07:06:11 - DEBUG createNativeListener: 'listening 53193'
(lldb) ,ok 174 Should throw
,# teardown
(lldb) ,2017-06-22 07:06:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:06:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:06:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# emits incomingConnectionState
,2017-06-22 07:06:27 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:06:27 - DEBUG createNativeListener: 'listening 53195'
(lldb) ,2017-06-22 07:06:27 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:06:27 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 175 initial connection state should be CONNECTED
(lldb) ,2017-06-22 07:06:27 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 176 final connection state should be DISCONNECTED
(lldb) ,# teardown
,2017-06-22 07:06:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:06:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:06:27 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# emits routerPortConnectionFailed
(lldb) ,2017-06-22 07:06:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:06:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:06:35 - DEBUG createNativeListener: 'listening 53198'
,2017-06-22 07:06:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:06:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:06:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:06:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
(lldb) ,ok 177 tried to connect to right port
(lldb) ,ok 178 failed due to refused connection
,ok 179 routerPortConnectionFailed is emitted
,# teardown
(lldb) ,2017-06-22 07:06:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:06:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-22 07:06:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:06:36 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:06:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-06-22 07:06:36 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,# native server connections all up
(lldb) ,2017-06-22 07:07:17 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-22 07:07:17 - DEBUG createNativeListener: 'listening 53202'
(lldb) ,2017-06-22 07:07:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-22 07:07:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
(lldb) ,ok 180 Send/recvd #1 should be equal length
,ok 181 Send/recvd #1 should be same
(lldb) ,ok 182 Send/recvd #2 should be equal length
,ok 183 Send/recvd #2 should be same
(lldb) ,ok 184 Should be exactly 2 client sockets
,# teardown
(lldb) ,2017-06-22 07:07:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:07:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:07:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-06-22 07:07:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:07:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-06-22 07:07:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-22 07:07:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-06-22 07:07:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
(lldb) ,2017-06-22 07:07:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# native server - closing incoming stream cleans outgoing socket
(lldb) ,2017-06-22 07:07:25 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:25 - DEBUG createNativeListener: 'listening 53207'
,2017-06-22 07:07:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:25 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-22 07:07:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,ok 185 socket shouldn't close until after stream
(lldb) ,ok 186 incoming remains open
,# teardown
(lldb) ,2017-06-22 07:07:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:07:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:07:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:31 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:07:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-06-22 07:07:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,# native server - closing incoming connection cleans outgoing socket
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:35 - DEBUG createNativeListener: 'listening 53211'
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 187 we should not have gotten an error
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 socket shouldn't close until after incoming
(lldb) ,ok 189 incoming is cleaned up
,# teardown
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:07:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:07:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# native server - closing outgoing socket cleans associated mux stream
,2017-06-22 07:07:37 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-22 07:07:37 - DEBUG createNativeListener: 'listening 53215'
,2017-06-22 07:07:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-22 07:07:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-22 07:07:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,ok 190 stream was closed
,ok 191 incoming should survive
(lldb) ,ok 192 mux should have no streams
,# teardown
(lldb) ,2017-06-22 07:07:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:07:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:41 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:07:41 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <(lldb) ,-> Mux - 0 - close'
2017-06-22 07:07:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
(lldb) ,# native server - closing the whole server cleans everything up
(lldb) ,2017-06-22 07:07:45 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:45 - DEBUG createNativeListener: 'listening 53219'
,2017-06-22 07:07:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 193 we should not have gotten an error
(lldb) ,2017-06-22 07:07:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 194 Buffers are identical
(lldb) ,2017-06-22 07:07:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:07:45 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-22 07:07:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-22 07:07:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 195 native server is nulled out
,ok 196 native server should be closed
(lldb) ,ok 197 incoming has been removed
,ok 198 Incoming should be done
(lldb) ,ok 199 The mux object should be closed
,ok 200 The mux stream should be closed
(lldb) ,2017-06-22 07:07:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
(lldb) ,2017-06-22 07:07:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:07:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:51 - DEBUG createNativeListener: 'listening 53223'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
(lldb) ,ok 201 native server is nulled out
,ok 202 native server should be closed
(lldb) ,ok 203 incoming has been removed
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# teardown
,2017-06-22 07:08:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
(lldb) ,# native server - simulate mux failure, make sure everything is cleaned up
(lldb) ,2017-06-22 07:08:13 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:08:13 - DEBUG createNativeListener: 'listening 53275'
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:08:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 204 we should not have gotten an error
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 205 Buffers are identical
(lldb) ,2017-06-22 07:08:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:08:13 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 206 server should be fine
(lldb) ,ok 207 server should be open
,ok 208 incoming has been removed
(lldb) ,ok 209 The mux object should be closed
,ok 210 The mux stream should be closed
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# teardown
,2017-06-22 07:08:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:08:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:08:13 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# native server - timing out the incoming connection cleans everything up
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:08:23 - DEBUG createNativeListener: 'listening 53279'
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:08:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 211 we should not have gotten an error
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 212 Buffers are identical
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-22 07:08:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 213 server should be fine
,ok 214 server should be open
(lldb) ,ok 215 incoming has been removed
,ok 216 The mux object should be closed
(lldb) ,ok 217 The mux stream should be closed
,# teardown
(lldb) ,2017-06-22 07:08:23 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:08:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:08:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:08:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# can create servers manager
,ok 218 serversManager must not be null
(lldb) ,ok 219 serversManager must be an object
,# teardown
(lldb) ,# setup
,# calling stop without start causes error
(lldb) ,ok 220 We need to call start first
(lldb) ,# teardown
,# setup
(lldb) ,# can start/stop servers manager
(lldb) ,2017-06-22 07:09:04 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-22 07:09:04 - DEBUG createNativeListener: 'listening 53282'
,ok 221 port must be in range
(lldb) ,# teardown
,2017-06-22 07:09:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:09:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# starting twice resolves with listening port
,2017-06-22 07:09:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:09:06 - DEBUG createNativeListener: 'listening 53283'
ok 222 second start should return same port
(lldb) ,# teardown
,2017-06-22 07:09:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:09:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# terminateIncomingConnection will terminate a connection
,2017-06-22 07:09:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:09:29 - DEBUG createNativeListener: 'listening 53285'
(lldb) ,2017-06-22 07:09:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:09:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 223 we should be connected
2017-06-22 07:09:29 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 224 now we are disconnected
,2017-06-22 07:09:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# teardown
,2017-06-22 07:09:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:09:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# terminate an Outgoing connection
(lldb) ,2017-06-22 07:09:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
(lldb) ,ok 225 Passed bogus id
,2017-06-22 07:09:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
(lldb) ,ok 226 Passed good id but bogus port
,2017-06-22 07:09:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
(lldb) ,ok 227 Passed right context
,ok 228 Right server
(lldb) ,ok 229 No error should be set
,ok 230 Retry should be false
,(lldb) ,ok 231 We called close server
,# teardown
,# setup
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:10:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
(lldb) ,ok 232 specific error should be returned
,# teardown
(lldb) ,ok 233 must be stopped
2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
(lldb) ,ok 234 specific error should be returned
,# teardown
(lldb) ,ok 235 must be stopped
,2017-06-22 07:10:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:39 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:10:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #stopListeningForAdvertisements many times
(lldb) ,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'listening 53287'
,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:10:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 236 no errors
,2017-06-22 07:10:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:10:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
(lldb) ,# teardown
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped st,ate).'
2017-06-22 07:10:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'listening 53288'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:10:46 - INFO thaliMobi,le: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
201(lldb) ,7-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 239 no errors
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisin,gActive":false}'
2017-06-22 07:10:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router(lldb) ,",:null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 240 still no errors
(lldb) ,# teardown
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:10:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:10:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:10:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisi(lldb) ,ngStateUpdate (was in stopped state).'
2017-06-22 07:10:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 241 must be stopped
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:47 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:10:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:10:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:49 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'listening 53289'
2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:11:07 - INFO thaliMobi(lldb) ,le: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
201,7-06-22 07:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 242 no errors
,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:11:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,(lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 243 still no errors
(lldb) ,# teardown
(lldb) ,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped st(lldb) ,ate).'
,2017-06-22 07:11:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
(lldb) ,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:11:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'listening 53292'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 245 no errors
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 246 still no errors
,# teardown
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false,}'
2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:11:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 must be stopped
2017-06-22 07:11:10 - DEBUG thaliMo(lldb) ,bileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Meth,od multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:11:16 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
(lldb) ,ok 248 network status should have certain non-empty properties
(lldb) ,# teardown
,ok 249 must be stopped
(lldb) ,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:11:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:11:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
(lldb) ,2017-06-22 07:12:04 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 250 specific error expected
,# teardown
(lldb) ,ok 251 must be stopped
(lldb) ,2017-06-22 07:12:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:12:14 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# all services are started when we call start
,2017-06-22 07:12:15 - DEBUG thaliMobileNativeWrapper: 'listening 53293'
2017-06-22 07:12:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-22 07:12:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-06-22 07:12:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:12:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive(lldb) ,":true,"advertisingActive":true}'
,2017-06-22 07:12:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre(lldb) ,t":null,"networkType":null}})'
,2017-06-22 07:12:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 all connection succeed
(lldb) ,# teardown
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisi(lldb) ,ngStateUpdate (was in stopped state).'
2017-06-22 07:12:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 253 must be stopped
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:16 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:12:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:17 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# TCP Servers Manager should be null when we call start on iOS
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 53296'
2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:18 - INFO thaliMobi,le: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
201(lldb) ,7-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2,017-06-22 07:12:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre(lldb) ,t":null,"networkType":null}})'
,2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 254 TCP Servers Manager doesn't exists
(lldb) ,# teardown
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisi(lldb) ,ngStateUpdate (was in stopped state).'
2017-06-22 07:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 255 must be stopped
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:18 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# all services are stopped when we call stop
,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'listening 53298'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-06-22 07:12:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre(lldb) ,t":null,"networkType":null}})'
,2017-06-22 07:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-22 07:12:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
(lldb) ,2017-06-22 07:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-22 07:12:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 256 is stopped after calling stop
(lldb) ,ok 257 connection should fail after stopping
,# teardown
(lldb) ,ok 258 must be stopped
,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:30 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# make sure terminateConnection is properly hooked up
,2017-06-22 07:12:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
(lldb) ,# teardown
,ok 259 must be stopped
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# make sure terminateConnection is return error if we get called on iOS
,ok 260 error description matches
(lldb) ,# teardown
,ok 261 must be stopped
2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
(lldb) ,2017-06-22 07:12:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
(lldb) ,ok 262 must be stopped
(lldb) ,2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:13 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
(lldb) ,ok 263 error description matches
(lldb) ,# teardown
,ok 264 must be stopped
2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:33 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
(lldb) ,ok 265 IMPLEMENT ME!!!!!!
(lldb) ,# teardown
,ok 266 must be stopped
(lldb) ,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:40 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
(lldb) ,2017-06-22 07:13:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
(lldb) ,ok 267 must be stopped
(lldb) ,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:41 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-06-22 07:13:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
(lldb) ,# teardown
,ok 268 must be stopped
2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:43 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:43 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-06-22 07:13:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
(lldb) ,# teardown
(lldb) ,ok 269 must be stopped
2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-06-22 07:13:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
(lldb) ,# teardown
(lldb) ,ok 270 must be stopped
(lldb) ,2017-06-22 07:13:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:14:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:11 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:14:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 271 NOT IMPLEMENTED # SKIP
(lldb) ,# teardown
,ok 272 must be stopped
2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# make sure bad PSK connections fail
,2017-06-22 07:14:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
(lldb) ,ok 273 must be stopped
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# peer changes handled from a queue
,2017-06-22 07:14:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
(lldb) ,# teardown
(lldb) ,ok 274 must be stopped
(lldb) ,2017-06-22 07:14:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:14:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:14:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:14:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:48 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:14:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:14:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-06-22 07:14:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
(lldb) ,# teardown
,ok 275 must be stopped
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:15:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:15:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:15:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
(lldb) ,2017-06-22 07:15:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
(lldb) ,ok 276 must be stopped
2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:15:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:15:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup

```
