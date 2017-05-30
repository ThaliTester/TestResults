#### Test 12302516380258fe_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/12302516380258fe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6A7960E0-010E-4D71-8E49-A1CAB52A05AC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6A7960E0-010E-4D71-8E49-A1CAB52A05AC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/12302516380258fe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/12302516380258fe/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49360"
,(lldb)     command script import "/tmp/6A7960E0-010E-4D71-8E49-A1CAB52A05AC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
(lldb) ,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-30 11:50:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
(lldb) ,AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-05-30 11:50:59 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.85356193780899
(lldb) ,2017-05-30 11:50:59 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-05-30 11:50:59 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-30 11:51:02 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-30 11:51:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-30 11:51:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-30 11:51:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-30 11:51:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-30 11:51:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-30 11:51:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-05-30 11:51:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-05-30 11:51:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 11:51:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:51:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 11:51:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:51:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 11:51:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:51:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 11:51:37 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-30 11:51:37 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-30 11:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-05-30 11:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-30 11:51:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-05-30 11:51:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-05-30 11:52:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
,2017-05-30 11:52:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-05-30 11:52:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-05-30 11:52:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
(lldb) ,ok 5 should be equal
ok 6 should be equal
,# teardown
(lldb) ,# setup
,# test defaultAdapter
(lldb) ,ok 7 should be equal
(lldb) ,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
ok 14 should be equal
(lldb) ,# teardown
,# setup
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
(lldb) ,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
(lldb) ,ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
(lldb) ,# setup
(lldb) ,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
(lldb) ,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
,# teardown
(lldb) ,# setup
(lldb) ,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
(lldb) ,# teardown
,# setup
(lldb) ,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
(lldb) ,# teardown
,# setup
(lldb) ,# basic
,ok 44 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
,ok 45 sane
(lldb) ,# teardown
,2017-05-30 11:56:47 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-05-30 11:56:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:56:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 11:56:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:56:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 11:57:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:57:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 11:57:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A(lldb) ,3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 11:57:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/93DD824B-95B1-46A3-B834-2C8712E42D03/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 11:57:43 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-30 11:57:43 - DEBUG CoordinatedClient: 'test client failed'
2017-05-30 11:57:43 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-30 11:57:43 - DEBUG CoordinatedClient: 'test client failed'
,2017-05-30 11:57:43 - DEBUG CoordinatedClient: '20000'
2017-05-30 11:57:43 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-05-30 11:57:43 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
(lldb) 
```
