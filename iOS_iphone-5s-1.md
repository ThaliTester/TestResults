#### Test 124853546ae83d78_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/124853546ae83d78/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D2C64E73-C56B-4426-8B74-5077882F6622/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D2C64E73-C56B-4426-8B74-5077882F6622/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/124853546ae83d78/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/124853546ae83d78/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52294"
,(lldb)     command script import "/tmp/D2C64E73-C56B-4426-8B74-5077882F6622/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-09 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
,All tests finished
All tests finished
(lldb) ,2017-06-09 12:51:35 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
(lldb) ,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.496440052986145
(lldb) ,2017-06-09 12:51:35 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-06-09 12:51:35 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-06-09 12:51:38 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-09 12:51:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-09 12:51:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-09 12:51:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-09 12:51:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-09 12:51:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-09 12:51:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-06-09 12:51:42 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-09 12:51:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-09 12:51:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6(lldb) ,A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-09 12:51:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-09 12:51:50 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-09 12:51:50 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-09 12:52:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
(lldb) ,2017-06-09 12:52:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-09 12:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-09 12:53:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# teardown
,# setup
(lldb) ,2017-06-09 12:54:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
(lldb) ,2017-06-09 12:54:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-06-09 12:54:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning, set to false'
2017-06-09 12:54:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-06-09 12:54:28 - INFO CoordinatedClient: '***TEST_LOGGER result:(lldb) , failed - Call of onCheckpointReached handler on a single db change, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/bluebi,rd/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var(lldb) ,/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-06-09 12:54:28 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-06-09 12:54:43 - DEBUG CoordinatedClient: 'all tests completed'
(lldb) ,2017-06-09 12:57:01 - DEBUG CoordinatedClient: 'test client disconnected'
2017-06-09 12:57:01 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-06-09 12:57:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished', test: 'closeAll works even, with a server that is not listening yet witheatNotRunning set to true'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:291(lldb) ,:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/07A2981A,-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/socket(lldb) ,.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/07A2981A-FEC1-4E6A-A099-1C64F756CC71/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-06-09 12:57:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
(lldb) 
```
