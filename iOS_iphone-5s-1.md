#### Test 112016147cd7538d_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/112016147cd7538d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C9CE820C-2148-4500-B899-2D77C5095153/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C9CE820C-2148-4500-B899-2D77C5095153/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/112016147cd7538d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/112016147cd7538d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52771"
,(lldb)     command script import "/tmp/C9CE820C-2148-4500-B899-2D77C5095153/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:85:e6:c2","bluetoothLowEnergy":"on"}'
,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-22 14:33:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-22 14:33:33 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  2.328563988208771
,2017-03-22 14:33:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-03-22 14:33:33 - WARN testUtils: 'myNameCallback not set!'
,2017-03-22 14:33:36 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-22 14:33:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-22 14:33:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-22 14:33:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-22 14:33:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-22 14:33:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-22 14:33:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-22 14:33:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-22 14:33:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-22 14:33:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-22 14:33:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-22 14:33:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-22 14:33:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-22 14:33:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-22 14:33:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-22 14:33:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-22 14:33:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-22 14:33:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-22 14:33:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-22 14:33:41 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-03-22 14:33:41 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-22 14:33:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:33:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:33:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:34:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:34:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap(lldb) ,plication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:34:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:34:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:34:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:34:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:34:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:34:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:35:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:35:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:35:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:35:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:36:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:36:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:36:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:36:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:36:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD(lldb) ,-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:36:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:37:06 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-03-22 14:37:06 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,2017-03-22 14:38:07 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - closeAll can close even when connections open, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-(lldb) ,11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/bluebird/js/rel,ease/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
(lldb) ,2017-03-22 14:38:07 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-03-22 14:38:35 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-03-22 14:38:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:38:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:38:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:38:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:39:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:39:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:39:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:39:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:39:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-4(lldb) ,9AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:39:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:40:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:40:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:40:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:40:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:40:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:40:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:41:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:41:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:41:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:41:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:41:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:41:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:42:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:42:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:42:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:42:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-4,9AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/nod(lldb) ,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:42:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:42:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:42:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:43:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:43:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:43:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:43:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:43:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:43:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:44:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:44:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:44:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:44:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:44:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:44:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:45:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:45:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:45:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:45:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:45:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:45:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:46:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:46:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:46:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:46:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:46:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:46:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:47:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:47:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:47:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:47:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:47:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:48:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:48:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:48:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:48:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:48:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:48:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:49:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:49:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:49:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:49:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:49:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:49:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:50:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:50:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:50:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:50:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:50:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:50:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:51:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:51:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:51:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:52:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:52:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:52:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:52:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:52:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:52:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:53:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:53:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:53:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49A(lldb) ,D-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:53:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B6E5D70C-1B9A-49AD-8611-11A70F7F1B97/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
