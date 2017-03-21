#### Test 11172753914f1591_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11172753914f1591/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/B6247040-FE2B-4FA5-8728-738CBB29AE8C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B6247040-FE2B-4FA5-8728-738CBB29AE8C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11172753914f1591/build_ios/ThaliTest.app"
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Current executable set to '/Users/thali/Github/CI/builder/builds/11172753914f1591/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62034"
,(lldb)     command script import "/tmp/B6247040-FE2B-4FA5-8728-738CBB29AE8C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-21 09:19:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
(lldb) ,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-21 09:19:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
(lldb) ,Total duration:  1.609156966209412
,2017-03-21 09:19:42 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-03-21 09:19:42 - WARN testUtils: 'myNameCallback not set!'
,2017-03-21 09:19:45 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-21 09:19:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-21 09:19:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-21 09:19:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-21 09:19:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-21 09:19:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-21 09:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-21 09:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-21 09:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-21 09:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-21 09:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-21 09:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-21 09:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-21 09:19:50 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
(lldb) ,appEnteredForeground wasn't registered
(lldb) ,2017-03-21 09:19:50 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-21 09:19:51 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,2017-03-21 09:22:32 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-03-21 09:22:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:22:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:22:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:22:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:23:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:23:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:23:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:23:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:23:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:23:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap(lldb) ,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:23:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:23:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:24:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:24:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:24:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:24:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:24:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:24:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:25:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:25:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:25:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:25:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:25:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:25:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:25:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:25:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:26:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:26:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:26:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:26:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap(lldb) ,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:26:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:26:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap(lldb) ,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:26:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:26:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:27:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:27:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:27:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:27:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:27:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:27:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:28:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:28:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:28:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:28:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:28:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:28:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:28:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:28:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap(lldb) ,plication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:29:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE(lldb) ,-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:29:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:29:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:29:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:29:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:29:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:29:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:29:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:29:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:29:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:30:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:30:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:30:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:30:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:30:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:30:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:30:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:30:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:30:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:30:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:30:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:30:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:31:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:31:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:31:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:31:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:31:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:31:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:31:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:31:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:31:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:31:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:31:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:31:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:32:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:32:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:32:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:32:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:32:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:32:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:32:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:32:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:32:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:32:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:32:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:32:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:33:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:33:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:33:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:33:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:33:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:33:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:33:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:33:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:33:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:33:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:34:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:34:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:34:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:34:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:34:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:34:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:34:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:34:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:34:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:34:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:34:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:34:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:35:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:35:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:35:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:35:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:35:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:35:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:35:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:35:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:35:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:35:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:35:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:35:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:36:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:36:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:36:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:36:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:36:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:36:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:36:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:36:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:36:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:36:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:36:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:36:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:37:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:37:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:37:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:37:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:37:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:37:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:37:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:37:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:37:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:37:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:37:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:37:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:38:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:38:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:38:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:38:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-21 09:38:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:38:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:38:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:38:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:38:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:38:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-21 09:38:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47F(lldb) ,E-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-21 09:38:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B8A87648-79AB-47FE-B181-45D0166BC98B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
