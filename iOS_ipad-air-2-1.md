#### Test 1133518510ecaa77_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518510ecaa77/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/17B795C2-1D32-4C3F-A64C-D2CA81CD5393/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/17B795C2-1D32-4C3F-A64C-D2CA81CD5393/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518510ecaa77/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518510ecaa77/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52149"
,(lldb)     command script import "/tmp/17B795C2-1D32-4C3F-A64C-D2CA81CD5393/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
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
,2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-25 10:03:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-05-25 10:03:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.353978991508484
(lldb) ,2017-05-25 10:03:09 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-05-25 10:03:09 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-25 10:03:12 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-25 10:03:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-25 10:03:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-25 10:03:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-25 10:03:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-25 10:03:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-25 10:03:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-25 10:03:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-25 10:03:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-25 10:03:15 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
(lldb) ,2017-05-25 10:03:15 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
,2017-05-25 10:03:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:03:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:03:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:03:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:03:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:03:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:03:58 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-25 10:03:58 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-05-25 10:08:54 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-05-25 10:08:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:08:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:10:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:10:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:10:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:10:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:10:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4,E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/nod(lldb) ,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:10:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:11:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:11:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:11:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4,E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/nod(lldb) ,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4,E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:13:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:13:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:15:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:15:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:15:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:15:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:15:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:15:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:16:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:16:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:17:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:17:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) 0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:18:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4(lldb) ,E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:18:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:20:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:20:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:20:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:20:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:20:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:20:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:21:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:21:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:21:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:21:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:21:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:21:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:22:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:22:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:22:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:22:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:22:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:22:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:23:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:23:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:23:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E9(lldb) ,0-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/BE9F4E7F-BE20-4E90-BC5B-B3A6323C82E6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
