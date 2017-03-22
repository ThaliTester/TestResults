#### Test 112016147e249d1d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/112016147e249d1d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5D5843AA-BFF8-458B-B0A5-B9230E7C2842/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5D5843AA-BFF8-458B-B0A5-B9230E7C2842/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/112016147e249d1d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/112016147e249d1d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55040"
,(lldb)     command script import "/tmp/5D5843AA-BFF8-458B-B0A5-B9230E7C2842/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:85:e6:c2","bluetoothLowEnergy":"on"}'
,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-22 17:34:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
(lldb) ,AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
(lldb) ,Optional(false)
Optional(true)
,AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-22 17:34:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
,Total duration:  1.398513078689575
(lldb) ,2017-03-22 17:34:05 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-03-22 17:34:05 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-03-22 17:34:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-22 17:34:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-22 17:34:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
(lldb) ,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
(lldb) ,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-22 17:34:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,(lldb) ,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-22 17:34:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-22 17:34:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-22 17:34:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-22 17:34:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-22 17:34:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-03-22 17:34:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-22 17:34:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:34:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:34:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:34:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:34:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:34:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:34:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:35:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:35:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:35:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:35:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:35:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:35:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:36:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:36:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:36:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:36:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:36:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:36:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:37:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:37:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:37:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:37:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:37:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:37:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:37:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:37:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:38:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:38:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:38:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:38:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:38:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:38:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:39:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:39:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:39:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:39:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:39:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:39:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:39:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:39:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:40:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:40:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:40:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:40:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:40:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:40:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:41:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:41:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:41:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:41:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:41:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:41:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:42:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:42:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:42:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:42:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:42:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:42:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:42:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:42:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:43:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:43:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:43:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:43:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:43:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:43:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:44:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:44:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:44:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:44:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:44:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:44:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:45:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:45:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:45:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:45:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:45:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:45:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:45:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:45:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:46:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:46:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:46:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:46:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:46:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:46:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:47:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:47:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:47:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:47:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:47:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:47:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:48:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:48:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:48:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:48:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: web,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:48:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:48:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:48:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:48:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-42(lldb) ,90-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node,_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/(lldb) ,containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:49:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:49:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:49:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:49:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:49:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:49:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:50:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:50:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:50:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) -840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:50:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:50:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:50:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:50:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:50:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:51:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:51:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:51:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:51:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:51:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:51:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:52:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:52:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:52:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:52:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:52:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:52:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:53:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:53:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:53:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:53:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 17:53:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:53:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:53:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:53:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 17:54:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290(lldb) ,-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 17:54:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D9A115CE-5876-4290-840A-0C274928BB4A/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
