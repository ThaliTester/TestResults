#### Test 113351851b596518_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851b596518/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/84F56814-9A87-432D-9CD5-B2F12C16C944/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/84F56814-9A87-432D-9CD5-B2F12C16C944/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851b596518/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851b596518/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52635"
,(lldb)     command script import "/tmp/84F56814-9A87-432D-9CD5-B2F12C16C944/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
(lldb) ,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 06:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
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
Total duration:  1.562655210494995
,2017-06-22 06:55:18 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
(lldb) ,2017-06-22 06:55:18 - WARN testUtils: 'myNameCallback not set!'
,2017-06-22 06:55:21 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-22 06:55:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-22 06:55:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-22 06:55:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
(lldb) ,2017-06-22 06:55:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-22 06:55:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-22 06:55:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-06-22 06:55:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-22 06:55:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D(lldb) ,0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-22 06:55:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D(lldb) ,0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-22 06:55:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-22 06:55:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D(lldb) ,0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-22 06:55:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-22 06:55:42 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-22 06:55:42 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-22 06:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-22 06:56:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-22 06:56:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-22 06:56:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
,2017-06-22 06:56:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
,# setup
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
(lldb) ,ok 5 should be equal
,ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
(lldb) ,ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
(lldb) ,ok 14 should be equal
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
ok 23 thirdPromise testValue
(lldb) ,# teardown
,# setup
(lldb) ,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
(lldb) ,# teardown
,# setup
(lldb) ,# mix enqueue and enqueueAtTop
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
,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
(lldb) ,# teardown
,# setup
(lldb) ,# exceptions in the executor are properly handled
,ok 43 got expected error
(lldb) ,# teardown
,# setup
(lldb) ,# basic
,ok 44 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
(lldb) ,ok 45 sane
,# teardown
(lldb) ,# setup
,# skip
(lldb) ,2017-06-22 06:57:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
(lldb) ,# setup
(lldb) ,# another skip
(lldb) ,2017-06-22 06:58:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox spy
(lldb) ,2017-06-22 06:58:21 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
,ok 50 test participant has uuid
ok 51 participant data matches
(lldb) ,ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
,# Correctly parses/stringifies USN
(lldb) ,ok 57 correctly parses USN string
,ok 58 throws if usn has invalid prefix
(lldb) ,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
(lldb) ,ok 61 correctly stringifies peer
,# teardown
(lldb) ,# setup
(lldb) ,# onPeerLost calls jxcore
,2017-06-22 07:00:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
(lldb) ,# teardown
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:00:43 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:00:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-06-22 07:00:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:00:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-22 07:00:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
(lldb) ,2017-06-22 07:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-22 07:00:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:00:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-06-22 07:00:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:00:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-22 07:00:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:00:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:00:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:00:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:00:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:00:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:00:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:00:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-06-22 07:00:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:00:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:00:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
2017-06-22 07:00:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 (lldb) ,07:00:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-06-22 07:00:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:55 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
(lldb) ,2017-06-22 07:00:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:00:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
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
2017-06(lldb) ,-22 07:00:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
(lldb) ,2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:00:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:00:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:00:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:00:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-06-22 07:01:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
2017-06-22 07:01:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-,22 07:01:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul(lldb) ,l,,"networkType":null}})'
2017-06-22 07:01:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-06-22 07:01:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
(lldb) ,2017-06-22 07:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:01:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 81 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:01:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-06-22 07:01:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 82 Can call startUpdateAdvertisingAndListening without error
2017-06-22 07:01:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:14 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:16 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:01:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# peerAvailabilityChange is called
(lldb) ,2017-06-22 07:01:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
2017-06-22 07:01:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-06-22 07:01:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-06-22 07:01:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
(lldb) ,ok 88 peers must be an array
(lldb) ,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
(lldb) ,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
(lldb) ,# teardown
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:01:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:01:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-06-22 07:01:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,bilityChanged registered to native'
(lldb) ,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:01:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:01:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can connect to a remote peer
(lldb) ,2017-06-22 07:01:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can connect to a remote peer''
,# teardown
(lldb) ,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 95 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:53 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:01:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:01:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data
(lldb) ,2017-06-22 07:01:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data''
,# teardown
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:01:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:01:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 98 Should be able to call stopAdvertisingAndListening in teardow,n
2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:01:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:01:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift data via parallel connections
(lldb) ,2017-06-22 07:02:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data via parallel connections''
,# teardown
(lldb) ,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:02:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 99 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopAdvertisingAndListening in teardo(lldb) ,wn
2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:02:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data securely
(lldb) ,2017-06-22 07:02:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data securely''
,# teardown
(lldb) ,2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Should be able to call stopAdvertisingAndListening in teard,own
2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:02:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift large amounts of data
(lldb) ,2017-06-22 07:02:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift large amounts of data''
,# teardown
(lldb) ,2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 Should be able to call stopAdvertisingAndListening in teard,own
2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:02:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# We do not emit peerAvailabilityChanged events until one of the start methods is called
(lldb) ,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:02:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:02:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 105 We should start listening fine
,2017-06-22 07:02:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-22 07:02:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di(lldb) ,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:02:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 106 We should start updating fine
(lldb) ,# teardown
,2017-06-22 07:02:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"53CE0C87-A157-4614-8452-0CE57CD58F52","generation":0}]'
2017-06-22 07:02:34 - DEBUG thaliMobileNativeW(lldb) ,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"53CE0C87-A157-4614-8452-0CE57CD58F52","generation":0}'
2017-06-22 07:02:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent du,e to not being in started state'
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:02:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 107 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',
2017-06-22 07:02:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:02:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:02:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:02:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Test updating advertising and parallel data transfer
,2017-06-22 07:02:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
(lldb) ,# teardown
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 109 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 110 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
(lldb) ,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
ok 115 discoveryActive should be false
ok 116 advertisingActive should be true
ok 117 discov,eryActive should be false
(lldb) ,ok 118 advertisingActive should be true
ok 119 Can call stopAdvertisingAndListening without error
2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/contain,ers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC4,59BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"(lldb) ,id":8,"ok":true,"name":"Can call stopAdvertisingAndListening without error","operator":"notOk","actual":null,"expected":false}''
ok 120 Can call stopListeningForAdvertisements without error
,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-,9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":9,"ok":true,"name":"Can call stopListeningForAdvertisements without error","operator":"notOk",",actual":null,"expected":false}''
(lldb) ,ok 121 Can call startUpdateAdvertisingAndListening without error
,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-,9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":10,"ok":true,"name":"Can call startUpdateAdvertisingAndListening without error","operator":"notO,k","actual":null,"expected":false}''
(lldb) ,ok 122 Can call startListeningForAdvertisements without error
,2017-06-22 07:02:39 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-,9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/B4F1C74F-B2D7-44D0-9E49-DC459BC5BA9C/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":11,"ok":true,"name":"Can call startListeningForAdvertisements without error","operator":"notOk",,"actual":null,"expected":false}''
(lldb) ,# teardown
,ok 123 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,ok 124 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,(lldb) ,2017-06-22 07:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# cannot call connect when start listening for advertisements is not active
(lldb) ,2017-06-22 07:02:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
(lldb) ,2017-06-22 07:03:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 125 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:09 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# Get error when trying to double connect to a peer on Android
(lldb) ,2017-06-22 07:03:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
(lldb) ,2017-06-22 07:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 128 Should be able to call stopAdvertisingAndListening in teard,own
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
(lldb) ,2017-06-22 07:03:34 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
(lldb) ,2017-06-22 07:03:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:03:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teard,own
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
(lldb) ,2017-06-22 07:03:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
(lldb) ,2017-06-22 07:03:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:36 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
(lldb) ,2017-06-22 07:03:38 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
(lldb) ,2017-06-22 07:03:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:38 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 134 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
(lldb) ,2017-06-22 07:03:39 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
(lldb) ,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 135 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:39 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# setup
(lldb) ,# cannot call multiConnect when start listening for advertisements is not active
,ok 137 Got null as expected
(lldb) ,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k5xdxkujuUQGusrQNn3QYsUTpN1CCKSX","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 138 Should only get called after multiConnect returned
(lldb) ,ok 139 SyncValue matches
,ok 140 Got right error
(lldb) ,ok 141 listeningPort is null
,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3dfa07b0-796c-4a51-9f0d-0cf81312b242","peerAvailable":false,"portNumber":null,"recreated":true}'
(lldb) ,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3dfa07b0-796c-4a51-9f0d-0cf81312b242","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-06-22 07:03:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,# teardown
,2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:03:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:03:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Should be able to call stopAdvertisingAndListening in teard,own
2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:03:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:03:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# cannot call multiConnect with illegal peerID
(lldb) ,2017-06-22 07:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:04:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 144 No error on starting
ok 145 Got null as expected
2017-06-22 07:04:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SXNQUOePt8AxdXlVaCjiuP4UayrvvafK","error":"Illegal peerID","portNumber"(lldb) ,:null}'
ok 146 Should only get called after multiConnect returned
,ok 147 SyncValue matches
ok 148 Got right error
ok 149 listeningPort is null
(lldb) ,# teardown
,2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 150 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:03 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 151 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:04:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# multiConnect properly fails on legal but non-existent peerID
(lldb) ,2017-06-22 07:04:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:04:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:04:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 152 No error on starting
ok 153 Got null as expected
(lldb) ,2017-06-22 07:04:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wCcmYGk9tLOS6Nzu0PiCRDy0ljeolB9R","error":"Connection could not be established","portNumber":null}'
ok 154 Should only get called after multiConnect returned
ok 15,5 SyncValue matches
ok 156 Got right error
ok 157 listeningPort is null
(lldb) ,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"c73885d5-f97c-4e8f-a330-ed9edda82686","peerAvailable":false,"portNumber":null,"recreated":true}'
(lldb) ,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"c73885d5-f97c-4e8f-a330-ed9edda82686","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,# teardown
,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:22 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 159 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:04:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# cannot call multiConnect with invalid syncValue
(lldb) ,2017-06-22 07:04:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:04:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:04:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 160 No error on starting
ok 161 Got right error
,# teardown
(lldb) ,2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 162 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:32 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# disconnect doesn't fail on bad peer id
,ok 164 No error
(lldb) ,# teardown
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 165 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:36 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 166 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:04:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
(lldb) ,ok 167 No error
(lldb) ,# teardown
,2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:04:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 168 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:04:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 169 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:04:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:04:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:04:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Get same port when trying to connect multiple times on iOS
(lldb) ,2017-06-22 07:04:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:05:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 170 Should be able to call stopListeningForAdvertisements in teardown
2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:05:06 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 171 Should be able to call stopAdvertisingAndListening in teardown
2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat,ive'
2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:05:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# initial peer discovery
(lldb) ,2017-06-22 07:05:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
(lldb) ,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:13 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:05:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# update peer discovery 1
(lldb) ,2017-06-22 07:05:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# update peer discovery 2
,2017-06-22 07:05:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
(lldb) ,# teardown
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:05:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# check latest peer discovery
,2017-06-22 07:05:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
(lldb) ,# teardown
(lldb) ,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:20 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:05:20 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Set up for no peer discovery test
(lldb) ,2017-06-22 07:05:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
(lldb) ,2017-06-22 07:05:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:05:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:05:47 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:05:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:05:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:05:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:05:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:05:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# no peer discovery
(lldb) ,2017-06-22 07:05:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
(lldb) ,2017-06-22 07:06:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:06:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:06:05 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:06:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:06:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:06:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:06:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:06:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# calling createNativeListener directly rejects
,2017-06-22 07:06:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:06:14 - DEBUG createNativeListener: 'listening 52954'
(lldb) ,ok 172 Should throw
,# teardown
(lldb) ,2017-06-22 07:06:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:06:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:06:14 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# emits incomingConnectionState
(lldb) ,2017-06-22 07:06:25 - DEBUG createNativeListener: 'Creating Native Server'
,2017-06-22 07:06:25 - DEBUG createNativeListener: 'listening 52956'
(lldb) ,2017-06-22 07:06:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-22 07:06:25 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 173 initial connection state should be CONNECTED
(lldb) ,2017-06-22 07:06:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 174 final connection state should be DISCONNECTED
,# teardown
(lldb) ,2017-06-22 07:06:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:06:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:06:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# emits routerPortConnectionFailed
,2017-06-22 07:06:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:06:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:06:34 - DEBUG createNativeListener: 'listening 52959'
(lldb) ,2017-06-22 07:06:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-22 07:06:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:06:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-22 07:06:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 175 tried to connect to right port
(lldb) ,ok 176 failed due to refused connection
,ok 177 routerPortConnectionFailed is emitted
(lldb) ,# teardown
,2017-06-22 07:06:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-22 07:06:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-22 07:06:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:06:38 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:06:38 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-06-22 07:06:38 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,# native server connections all up
(lldb) ,2017-06-22 07:06:56 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:06:56 - DEBUG createNativeListener: 'listening 52963'
(lldb) ,2017-06-22 07:06:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:06:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:06:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-22 07:06:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 178 Send/recvd #1 should be equal length
(lldb) ,ok 179 Send/recvd #1 should be same
(lldb) ,ok 180 Send/recvd #2 should be equal length
,ok 181 Send/recvd #2 should be same
(lldb) ,ok 182 Should be exactly 2 client sockets
,# teardown
(lldb) ,2017-06-22 07:07:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:07:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:22 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:07:22 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-06-22 07:07:22 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-06-22 07:07:22 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP cli(lldb) ,ent connection <-> Mux - 0 - close'
,2017-06-22 07:07:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,2017-06-22 07:07:22 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
(lldb) ,2017-06-22 07:07:22 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# native server - closing incoming stream cleans outgoing socket
,2017-06-22 07:07:30 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-22 07:07:30 - DEBUG createNativeListener: 'listening 52968'
,2017-06-22 07:07:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-22 07:07:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-22 07:07:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 183 socket shouldn't close until after stream
(lldb) ,ok 184 incoming remains open
,# teardown
(lldb) ,2017-06-22 07:07:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:07:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:32 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:07:32(lldb) , - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-22 07:07:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
(lldb) ,# native server - closing incoming connection cleans outgoing socket
,2017-06-22 07:07:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:35 - DEBUG createNativeListener: 'listening 52972'
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 185 we should not have gotten an error
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 186 socket shouldn't close until after incoming
(lldb) ,ok 187 incoming is cleaned up
,# teardown
(lldb) ,2017-06-22 07:07:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:07:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:36 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# native server - closing outgoing socket cleans associated mux stream
(lldb) ,2017-06-22 07:07:37 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-22 07:07:37 - DEBUG createNativeListener: 'listening 52976'
,2017-06-22 07:07:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-22 07:07:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-22 07:07:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,ok 188 stream was closed
(lldb) ,ok 189 incoming should survive
,ok 190 mux should have no streams
(lldb) ,# teardown
,2017-06-22 07:07:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:07:41 - DEBUG createNativeListener: 'Native Server - close'
2017-06-22 07:07:41(lldb) , - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-22 07:07:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
(lldb) ,# native server - closing the whole server cleans everything up
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:47 - DEBUG createNativeListener: 'listening 52980'
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:07:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 191 we should not have gotten an error
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 192 Buffers are identical
,2017-06-22 07:07:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 193 native server is nulled out
(lldb) ,ok 194 native server should be closed
,ok 195 incoming has been removed
(lldb) ,ok 196 Incoming should be done
,ok 197 The mux object should be closed
,ok 198 The mux stream should be closed
(lldb) ,2017-06-22 07:07:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# teardown
,2017-06-22 07:07:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-22 07:07:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:07:51 - DEBUG createNativeListener: 'listening 52984'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
(lldb) ,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-06-22 07:07:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
(lldb) ,2017-06-22 07:07:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
(lldb) ,ok 199 native server is nulled out
,ok 200 native server should be closed
(lldb) ,ok 201 incoming has been removed
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
(lldb) ,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-06-22 07:07:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# teardown
,2017-06-22 07:07:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
(lldb) ,2017-06-22 07:08:13 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:08:13 - DEBUG createNativeListener: 'listening 53036'
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:08:13 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 202 we should not have gotten an error
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 203 Buffers are identical
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:08:13 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-22 07:08:13 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 204 server should be fine
(lldb) ,ok 205 server should be open
,ok 206 incoming has been removed
(lldb) ,ok 207 The mux object should be closed
,ok 208 The mux stream should be closed
(lldb) ,2017-06-22 07:08:13 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# teardown
,2017-06-22 07:08:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:08:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:08:14 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# native server - timing out the incoming connection cleans everything up
(lldb) ,2017-06-22 07:08:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:08:29 - DEBUG createNativeListener: 'listening 53040'
(lldb) ,2017-06-22 07:08:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:08:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 209 we should not have gotten an error
,2017-06-22 07:08:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 210 Buffers are identical
,2017-06-22 07:08:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
(lldb) ,2017-06-22 07:08:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-22 07:08:29 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-22 07:08:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 211 server should be fine
,ok 212 server should be open
,ok 213 incoming has been removed
(lldb) ,ok 214 The mux object should be closed
,ok 215 The mux stream should be closed
(lldb) ,# teardown
,2017-06-22 07:08:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-22 07:08:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:08:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:08:30 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# can create servers manager
(lldb) ,ok 216 serversManager must not be null
,ok 217 serversManager must be an object
(lldb) ,# teardown
,# setup
(lldb) ,# calling stop without start causes error
,ok 218 We need to call start first
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# can start/stop servers manager
(lldb) ,2017-06-22 07:08:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:08:57 - DEBUG createNativeListener: 'listening 53043'
ok 219 port must be in range
,# teardown
(lldb) ,2017-06-22 07:09:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-22 07:09:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# starting twice resolves with listening port
(lldb) ,2017-06-22 07:09:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:09:08 - DEBUG createNativeListener: 'listening 53044'
(lldb) ,ok 220 second start should return same port
,# teardown
(lldb) ,2017-06-22 07:09:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-22 07:09:08 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# terminateIncomingConnection will terminate a connection
(lldb) ,2017-06-22 07:09:22 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-22 07:09:22 - DEBUG createNativeListener: 'listening 53046'
,2017-06-22 07:09:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-22 07:09:22 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 221 we should be connected
,2017-06-22 07:09:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 222 now we are disconnected
,2017-06-22 07:09:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# teardown
,2017-06-22 07:09:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-22 07:09:47 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# terminate an Outgoing connection
(lldb) ,2017-06-22 07:10:19 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
(lldb) ,ok 223 Passed bogus id
,2017-06-22 07:10:19 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
(lldb) ,ok 224 Passed good id but bogus port
,2017-06-22 07:10:19 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
(lldb) ,ok 225 Passed right context
,ok 226 Right server
(lldb) ,ok 227 No error should be set
,ok 228 Retry should be false
,ok 229 We called close server
(lldb) ,# teardown
,# setup
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:21 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:10:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# #startListeningForAdvertisements should fail if start not called
,ok 230 specific error should be returned
(lldb) ,# teardown
,ok 231 must be stopped
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
(lldb) ,ok 232 specific error should be returned
,# teardown
(lldb) ,ok 233 must be stopped
(lldb) ,2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:10:33 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #stopListeningForAdvertisements many times
,2017-06-22 07:10:45 - DEBUG thaliMobileNativeWrapper: 'listening 53048'
(lldb) ,2017-06-22 07:10:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:10:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 234 no errors
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
(lldb) ,# teardown
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-06-22 07:10:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 236 must be stopped
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'listening 53049'
,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 no errors
(lldb) ,2017-06-22 07:10:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-22 07:10:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-22 07:10:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 238 still no errors
,# teardown
(lldb) ,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-22 07:10:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
2017-06-22 07:10:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
2017-06-22 07:10:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:10:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 239 must be stopped
20(lldb) ,17-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:10:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:10:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:04 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:11:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
(lldb) ,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'listening 53050'
,2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:11:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:11:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 240 no errors
2017-06-22 07:11:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-22 07:11:04 - INFO thaliMobile: 'Received state(lldb) , ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-22 07:11:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 241 still no errors
,# teardown
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped st(lldb) ,ate).'
2017-06-22 07:11:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 242 must be stopped
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:08 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:11:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:11:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #stopAdvertisingAndListening many times
,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'listening 53053'
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 243 no errors
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 244 still no errors
(lldb) ,# teardown
,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false,}'
2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:11:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 245 must be stopped
2017-06-22 07:11:10 - DEBUG thaliMo(lldb) ,bileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:11:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:11:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:11:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:11:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:11:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:11:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:11:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
(lldb) ,ok 246 network status should have certain non-empty properties
,# teardown
(lldb) ,ok 247 must be stopped
(lldb) ,2017-06-22 07:11:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:11:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:11:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:11:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:11:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:11:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:11:47 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:11:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# error returned with bad router
,2017-06-22 07:12:13 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 248 specific error expected
(lldb) ,# teardown
,ok 249 must be stopped
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
(lldb) ,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# all services are started when we call start
,2017-06-22 07:12:15 - DEBUG thaliMobileNativeWrapper: 'listening 53054'
2017-06-22 07:12:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:15 - INFO thaliMobi(lldb) ,le: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
201,7-06-22 07:12:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-22 07:12:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-22 07:12:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di(lldb) ,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
(lldb) ,ok 250 all connection succeed
,# teardown
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F270D393-BD32-4F1E-80C8-FA3E26652B4A","generation":0}]'
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F270D393-BD32-4F1E-80C8-FA3E26652B4A","generation":0}'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F270D393-BD32-4F1E-80C8-FA3E26652B4A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-06-22 07:12:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F270D393-BD32-4F1E-80C8-FA3E26652B4A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisi,ngStateUpdate (was in stopped state).'
2017-06-22 07:12:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 251 must be stopped
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:12:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
(lldb) ,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'listening 53057'
2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-22 07:12:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive(lldb) ,":true,"advertisingActive":true}'
2017-06-22 07:12:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArgu,ments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 TCP Servers Manager doesn't exists
(lldb) ,# teardown
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,2017-06-22 07:12:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 253 must be stopped
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:12:19 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# all services are stopped when we call stop
,2017-06-22 07:12:20 - DEBUG thaliMobileNativeWrapper: 'listening 53059'
(lldb) ,2017-06-22 07:12:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
,2017-06-22 07:12:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-06-22 07:12:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-06-22 07:12:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-22 07:12:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-22 07:12:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-22 07:12:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
,(lldb) ,2017-06-22 07:12:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-22 07:12:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-22 07:12:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 254 is stopped after calling stop
(lldb) ,ok 255 connection should fail after stopping
,# teardown
(lldb) ,ok 256 must be stopped
(lldb) ,2017-06-22 07:12:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:12:26 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# make sure terminateConnection is properly hooked up
,2017-06-22 07:12:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
(lldb) ,# teardown
(lldb) ,ok 257 must be stopped
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
(lldb) ,ok 258 error description matches
(lldb) ,# teardown
,ok 259 must be stopped
(lldb) ,2017-06-22 07:12:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:12:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:12:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:12:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:12:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:12:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:12:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:12:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
(lldb) ,2017-06-22 07:12:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
(lldb) ,ok 260 must be stopped
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
(lldb) ,ok 261 error description matches
(lldb) ,# teardown
,ok 262 must be stopped
(lldb) ,2017-06-22 07:13:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:25 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
(lldb) ,ok 263 IMPLEMENT ME!!!!!!
(lldb) ,# teardown
(lldb) ,ok 264 must be stopped
,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:39 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:39 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,(lldb) ,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
(lldb) ,2017-06-22 07:13:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
(lldb) ,ok 265 must be stopped
2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:42 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-06-22 07:13:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
(lldb) ,# teardown
,ok 266 must be stopped
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:43 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-06-22 07:13:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
(lldb) ,# teardown
(lldb) ,ok 267 must be stopped
2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:13:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:13:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
(lldb) ,2017-06-22 07:13:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
(lldb) ,ok 268 must be stopped
2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:13:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:13:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:13:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 269 NOT IMPLEMENTED # SKIP
(lldb) ,# teardown
(lldb) ,ok 270 must be stopped
,2017-06-22 07:14:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:12 - DE,(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:14:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:14:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# make sure bad PSK connections fail
,2017-06-22 07:14:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
(lldb) ,# teardown
,ok 271 must be stopped
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:14:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:14:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:14:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# peer changes handled from a queue
,2017-06-22 07:14:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
(lldb) ,# teardown
(lldb) ,ok 272 must be stopped
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:14:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-22 07:14:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-22 07:14:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
(lldb) ,2017-06-22 07:14:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
(lldb) ,ok 273 must be stopped
(lldb) ,2017-06-22 07:14:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:14:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:14:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-22 07:14:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-22 07:14:58 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
2017-06-22 07:14:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:14:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:14:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-22 07:15:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-22 07:15:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-22 07:15:10 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-22 07:15:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-22 07:15:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-22 07:15:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-22 07:15:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-22 07:15:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-06-22 07:15:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
(lldb) ,# teardown

```
