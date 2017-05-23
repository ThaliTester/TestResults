#### Test 11335185198f2854_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185198f2854/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/58363583-1359-497E-BE29-7DB8A7E82859/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/58363583-1359-497E-BE29-7DB8A7E82859/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185198f2854/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185198f2854/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60585"
,(lldb)     command script import "/tmp/58363583-1359-497E-BE29-7DB8A7E82859/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 12:08:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
(lldb) ,AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-05-23 12:08:09 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
(lldb) ,Total number of executed tests:  13
,Number of passed tests:  13
(lldb) ,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.36449122428894
(lldb) ,2017-05-23 12:08:09 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-05-23 12:08:09 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-23 12:08:12 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-23 12:08:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-23 12:08:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-05-23 12:08:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
(lldb) ,2017-05-23 12:08:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-23 12:08:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-23 12:08:15 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2017-05-23 12:08:15 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-05-23 12:08:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/AF9BDEE6-3024-472,7-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-23 12:08:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/AF9BDEE6-3024-472(lldb) ,7-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-23 12:08:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/AF9BDEE6-3024-4727-8FA0-A7C04668DD7B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-23 12:08:43 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-23 12:08:43 - DEBUG CoordinatedClient: 'test client failed'
2017-05-23 12:08:43 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-23 12:08:43 - DEBUG CoordinatedClient: 'test client failed'
,2017-05-23 12:08:43 - DEBUG CoordinatedClient: '20000'
2017-05-23 12:08:43 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-05-23 12:08:43 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
(lldb) 
```
