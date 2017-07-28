#### Test 11335185130e646f_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/74AAE3DF-2240-4014-946C-76AD79E17BB6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/74AAE3DF-2240-4014-946C-76AD79E17BB6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53128"
,(lldb)     command script import "/tmp/74AAE3DF-2240-4014-946C-76AD79E17BB6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:22:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18CEAF2F-3927-4AD0-B7,B3-45C1D23AB8FB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:18CEAF2F-3927-4AD0-B7B3-45C1D23AB8FB
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisement,s
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0FA2C0F9-A95D-442B-8FE8-173325773276
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3EFD6E81-74C5-4F17-BFA3-A972C5BC74C9
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onP,ort:errorHandler:) Peer(uuid: "DF8C868A-0F41-4DDB-B81F-CB5D8C25633D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DF8C868A-0F41-4DDB-B81F-CB5D8C25633D
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF8C868A-0F41-4DDB-B81F-CB5D8C25633D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF8C868A-0F41-4DDB-B81F-CB5D8C25633D", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-28 10:23:02 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.67637711763382
,2017-07-28 10:23:02 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-28 10:23:02 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF8C868A-0F41-4DDB-B81F-CB5D8C25633D:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF8C868A-0F41-4DDB-B81F-CB5D8C25633D", generation: 0)
,2017-07-28 10:23:05 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-28 10:23:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-28 10:23:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-28 10:23:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-28 10:23:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-28 10:23:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-28 10:23:09 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-28 10:23:09 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-28 10:23:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:43 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-28 10:23:43 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-28 10:23:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-28 10:23:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-28 10:23:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-28 10:23:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-28 10:23:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-28 10:23:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-28 10:23:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-28 10:23:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
,# teardown
,# setup
,# enqueue and run in order
,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
,# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
,ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
,# setup
,# mix enqueue and enqueueAtTop
,ok 31 fourth
ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
,# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
,# setup
,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
,ok 42 executors is called
,# teardown
,# setup
,# exceptions in the executor are properly handled
,ok 43 got expected error
,# teardown
,# setup
,# basic
,ok 44 sane
,# teardown
,# setup
,# another
,ok 45 sane
,# teardown
,# setup
,# skip
,2017-07-28 10:24:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-28 10:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-28 10:24:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
ok 46 test sandbox spy works correctly
,# teardown
,# setup
,# test sinon sansbox stub
,ok 47 test sandbox stub works correctly
,# teardown
,# setup
,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
,# teardown
,# setup
,# test sinon sansbox mock
,# teardown
,# setup
,# test sinon sansbox restore after test end
,ok 49 test restore
,# teardown
,# setup
,# can pass data in setup
,ok 50 test participant has uuid
ok 51 participant data matches
ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-28 10:24:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-28 10:24:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4D3379F4-16E8-400D-87E5-A0A46C99192D
[ThaliCore] Browser.startListening
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:29 - INFO tha,l,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8FB6C14F-3335-4F03-985C-C950FC7847C1
[ThaliCore] Browser.startListening
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4B876C26-04AF-4979-94BF-37D49CF7F6CC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4B876C26-04AF-4979-94BF-37D49CF7F6CC
2017-07-28 1,0:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4B876C26-04AF-4979-94BF-37D49CF7F6CC
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E848B7EB-1969-4C35-A4F3-DAF2BB28D1AB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E848B7EB-1969-4C35-A4F3-DAF2BB28D1AB
2017-07-28 1,0:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E848B7EB-1969-4C35-A4F3-DAF2BB28D1AB", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:E848B7EB-1969-4C35-A4F3-DAF2BB28D1AB
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E848B7EB-1969-4C35-A4F3-DAF2BB28D1AB
[ThaliCore] Advertiser.stopAdvertising() peerID:E848B7EB-1969-4C35-A4F3-DAF2BB28D1AB
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:35 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24
2017-07-28 1,0:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8DDF0592-930F-4432-BD13-2C91061ED88A
[Thali,Core] Browser.startListening
2017-07-28 10:24:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:24:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,anged registered to native'
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FDF967AF-AC1F-48BB-BDA5-DC0E81797566
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8120360A-B668-4F82-9C62-C4287F089F29
[ThaliCore] Browser.startListening
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C90D592-5A1A-4AB3-9831-94152F0137BD","generation":0}'
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C90D592-5A1A-4AB3-9831-94152F0137BD (syncValue: mDC2Y8y4Xl1yrYxZ2AUihovRWCSaw83J)'
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DF6EC92-4C39-48D4-90E9-D0752BF3BD64","generation":0}'
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
2017-07-28 10:24:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A","generation":0}'
2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:8B8E5E40-BA6B-4AFA-A8E7-23B642839774:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B8E5E40-BA6B-4AFA-A8E7-23B642839774", generation: 0)
2017-07-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"8B8E5E40-BA6B-4AFA-A8E7-23B642839774","generation":0}'
2017-07-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2C,90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-28 10:24:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mDC2Y8y4Xl1yrYxZ2AUihovRWCSaw83J","error":"Peer is unavailable","portNumber":null}'
,2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mDC2Y8y4Xl1yrYxZ2AUihovRWCSaw83J', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:24:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A (syncValue: g7tZGpTPy8Qz61ODpt1ZAC8CGS7tUCrI)'
,2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:643EA949-813F-4976-9EB7-0C17CF196E13
[ThaliCore] Advertiser: session connected Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:643EA949-813F-4976-9EB7-0C17CF196E13 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:643EA949-813F-4976-9EB7-0C17CF196E13
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63637
,2017-07-28 10:24:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"g7tZGpTPy8Qz61ODpt1ZAC8CGS7tUCrI","error":null,"portNumber":63637}'
,2017-07-28 10:24:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'g7tZGpTPy8Qz61ODpt1ZAC8CGS7tUCrI', error: 'null', listeningPort: '63637''
,[ThaliCore] Session.session(_:peer:didChange:) peer:643EA949-813F-4976-9EB7-0C17CF196E13 state: connecting -> connected
,2017-07-28 10:24:47 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-28 10:24:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:24:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FDF967AF-AC1F-48BB-BDA5-D,C0E81797566
2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63637
[ThaliCore] Session.disconnect() peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:643EA949-813F-4976-9EB7-0C17CF196E13 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:643EA949-813F-4976-9EB7-0C17CF196E13
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:643EA949-813F-4976-9EB7-0C17CF196E13
[ThaliCore] Session.deinit peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.deinit
2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F84CD8E8-8996-4FBF-892D-97FE4B025995
2017-07-28 1,0:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4A04F713-3F43-4524-81DB-048DA457F037
[Thal,i,Core] Browser.startListening
2017-07-28 10:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:50 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,2017-07-28 10:24:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A","generation":0}'
,2017-07-28 10:24:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A (syncValue: avetbcLQ1LIZueezOHp1ViTld6gZJxRK)'
,2017-07-28 10:24:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7","generation":0}'
,2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
,2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA","generation":0}'
,2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BF44BF5E,-C20B-44D2-BDD7-247D52CA9B5A error: max retries exceeded
2017-07-28 10:25:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"avetbcLQ1LIZueezOHp1ViTld6gZJxRK","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:25:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'avetbcLQ1LIZueezOHp1ViTld6gZJxRK', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:25:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-28 10:25:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7 (syncValue: aCCnZ5YQytuB0XCRwWmHtXRFniGKkN5r)'
,2017-07-28 10:25:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83352589-F114-40FD-A8E8-A577BA592395
[ThaliCore] Advertiser: session connected Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:83352589-F114-40FD-A8E8-A577BA592395 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63650
2017-07-28 10:25:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aCCnZ5YQytuB0XCRwWmHtXRFniGKkN5r",,"error":null,"portNumber":63650}'
2017-07-28 10:25:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aCCnZ5YQytuB0XCRwWmHtXRFniGKkN5r', error: 'null', listeningPort: '63650''
,Connecting to the localhost:63650
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
Connected to the localhost:63650
,2017-07-28 10:25:03 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-28 10:25:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83352589-F114-40FD-A8E8-A577BA592395
,[ThaliCore] Session.session(_:peer:didChange:) peer:83352589-F114-40FD-A8E8-A577BA592395 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83352589-F114-40FD-A8E8-A577BA592395
[ThaliCore] Session.startOutputStream(with:) peer:83352589-F114-40FD-A8E8-A577BA592395
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:25:04 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-28 10:25:04 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-28 10:25:04 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-28 10:25:04 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-28 10:25:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:F84CD8E8-8996-4FBF-892D-97FE4B025995
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10,:,25:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed, by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserManager.disconnect peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63650
[ThaliCore] Session.disconnect() p,eer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCor,e] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] Session.deinit peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:83352589-F114-40FD-A8E8-A577BA592395 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:83352589-F114-40FD-A8E8-A577BA592395
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:83352589-F114-40FD-A8E8-A577BA592395
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4C4A28E9-2035-47E8-A153-BA2B2523267F
2017-07-28 1,0:25:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9F04B825-1E9B-4FB7-A1B5-E04D9D3A95F9
[ThaliCore] Browser.startListening
2017-07-28 10:25:06 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:25:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA","generation":0}'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA (syncValue: Q0FLGeha52AWn4yhLyN3DD1QvbD1zPiR)'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A","generation":0}'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39056CDE-F8B9-4D96-B071-8452DE2C822B","generation":0}'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DE573A-0E5A-4BD7-B7BC-01111EFB454A","generation":0}'
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AE,58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,E58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AE,58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,E58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:25:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q0FLGeha52AWn4yhLyN3DD1QvbD1zPiR","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:25:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Q0FLGeha52AWn4yhLyN3DD1QvbD1zPiR', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-28 10:25:11 - ERROR thaliMobileNativeTestUti,ls: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:25:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39056CDE-F8B9-4D96-B071-8452DE2C822B (syncValue: wannxRZE6yflLkeWp0m6L8SNYXQBEdFE)'
2017-07-28 10:25:11 - DEBUG thaliMobile,NativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sess,i,onConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:gen,eration:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63659
2017-07-28 10:25:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wannxRZE6yflLkeWp0m6L8SNYXQBEdFE",,"error":null,"portNumber":63659}'
2017-07-28 10:25:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wannxRZE6yflLkeWp0m6L8SNYXQBEdFE', error: 'null', listeningPort: '63659''
,Connecting to the localhost:63659
Connecting to the localhost:63659
Connecting to the localhost:63659
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
Connected to the localhost:63659
Connected to the localhost:63659
C,onnected to the localhost:63659
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 93 correct string length
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-28 10:25:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:5
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:5 []
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliCore] Advertiser: session connected Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
,[ThaliCore] Session.session(_:peer:didChange:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliCore] Session.startOutputStream(with:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliCore] Session.startOutputStream(with:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliC,ore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliCore] Session.startOutputStream(with:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (3386 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [7, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server received all data: jVAuwoavocnWdUi4hlloPdUs1y23YJSA8fmou5FYhc6jTPWi4ygq441MdXiXIRc76ypT2amKHGa0yceO9alSSxzAphvIxlmHF7umoMuXpOsmaRykH6ONmKRtxyJ9fWkJgXscMRPFWOWAhZnA6RMJuSwEukIjNPm50e5alPhN2BNBhjDbLu,jQJPVQBWldkKFbAMqUHtsvo0VYaOLO6nGClE9AugHBppxbjrX9diV0LcoVjkt2FI5BgHj5mMWeR8Ugc5pO3NadykIvXqz8X2o2VVY9MH5BY7gDKiNETLVlRXUK8FUVfjo6uQIsQu9D4juBKwtebECDiX3WUpwfCNpHhe7FRs2VI87Pk0OVM6E85iYAEy2J25SPkhB83zkq603Nly8xFwA4HCTeWZX5LRrCstQ4Tb416Vj0rkQeVZPf5s7ZbxCyIE,t993jEWtwcXzBNyP3og0jlPCMwyLCJKv3BXS0Czw8JGG9MTRZ2QYdvvYHTujiSCGEC20K2AlHV7Yiryntvn3Xtr090TkcgleN3AK8PNLUI4rcmpBOXMotGdeVosVAS9kFxiWdZqFrS1bdsKYsSu8TUlgPDgFrH5eaK2qBP4y2Trvu4QODmGqkaYPqoGCADTyCxf567ghB31Gc63EoMPqHAaQg2N5yxtZ6qdCfa4yHqpTknwrSCE5SNfdlH6Hs8bi,oM7Jpdg43fhblA5U432ICXb6VEqmZfy72f5oFOAHe6gr9KI1No6ZmaRne9lv3pGXH2OuOHsdO3aPWbTp9nOlLY2v4jRh4MqvOobPlDXCNNL1zWQCFIA7qCS8Ngztkvn7jcGD4UVfUqgclAreytj87bBiaudQ3iXTB65wB8LkxmeDHFuskgV5yZn3Jmh2zbg7Aopj1MMTcPEu0qYVmlDAnSuBnhAchaVPydNO9zhqZvVPvcaeuA9JbG7JQmENfyDK,ezbtzugwgv17byAuBpbzFYEjnzewDNIL7ttzyNWJG1MB7SxK0q93akkH61hCrH3R08OOkwfBMDZCAHoWSV6JR7WpennJPqwYBzKqrAkdxDbWnJjvSzHAZvGbVuRMvIsU6aMH3iebYU6BspztIMr1kpWWEAygIfc3u4uzOUh7Ky0D7ceez4NwyV1kDZ5BlY8oUlMcFaLpQtZjlUqSus21hLAEvwbtiiZ2b8xZDJTJEtkdXYAggII4XnuR50sPbCVl,IDbeCe2zXMIKDkAeePmzpbu08SnNLqLdJualfVBSiynxwPikU2zTVcHkUGMjqbjMHLlGFMXTvrq48zCzROu0R9CCnN9Q04ljDGyTOdgMaS9GV8Yf2XzHZ0GbMmj0BFwh07yXaehiXJjaIv9t5ucoXuLIzzIIbBumKzTQws7leJN6wogyKIpOAm0rO3KT8sM6i0zVIMy5ygx2J7S1omqEooEuoahpA0A60UE2WcYb005mm3fk2nkB5I2IVnELdy8Y,vj4MSla8VMIf0ULlQDxCjHY43CbU8k1lR33Jz6mYE3PMFxiGUfUZCOfnC0PAHCHvLTvnYqP32gvsfsl6VboE72ytfuCaWZjoWZOkEFxC3mR3AdSZklkXa379AJwhMxWqC03ET0rkPz8MQVGOaglOXsg3CCMgx6eFNbcbRDswBz1VuuEiWtGSp7gOUJ0W6FbQiG8dOBYmODmsX1Op4vGVAoZ53UFbV7Ch6jVYJjsOgrw0D0PXFBrBlJDECrH0CVkz,KqBrMpjjysCbC8ieNEhzYBWA2avXy4cWHO86IFALJ7VG2we7ErT3ZxABOkJiyH4H4QrD4RaeaNa1iLrkXiyIkTWctxiqTHV3enGJg0QJJ3N9F8Sern7wnhbzJgFL0PmncEGhYfooaNcwBsGsT4ga9d9pnmQdQkNR4Qq3fnSiFnBiQFAsCWfrURRSfFMKEmPQ6zfI3uUjHKokqH9P58e3wTbE6ATcH5DG6ihST2ofhJAuOKULW3Vi0bpSvVEFt52t,qM6mgvxktqK4uSh53aoYJ29hVR7YEqjPKjsJnQUpMAd94GsXtuW9YgMO5JewX1y2ZyCYlm87ZJeoT9dZ8s92g7SK0KrMpvJAt9pspuKEnGsZoTwrAiSUptPNu2QIxnLSweR0cSDI1753oAIqibhi7dqAPilxYE7AUdwGrix2kweprTAGvKfqRigJSevDOilxSRLMIptjjoz69GbYkfmujWRB8C3p4aRzaGICtsKpCQ352CzZ7bryF20bcYjfVr5l,u9c7KohzHcqZSaSpqVVQ0qjMtaKZn6pLUkJ8QD1yEsVn1VI5U8fpfNyHW5mtuT1xzj8vMGPKQRpgSFaw4S3CPCu6HonF6LuFt1dURmBTwMLgnq0aGbjxsPOLqeiur0FEKqVbtaE7aOu2bRRQmhWfnQuteedZ2dEtVyTLRZHDbSLZ3uOuBWLlEYfxckfLA5Y7JNNAducUEDrEOZhbttjLiLkPIVNgozvNlSfavNw8WKrD0gKHcc4rmBbIl8K61OrU,5tW7agpFb5WbccEFD4Al6wQfOj9bSkaAqDfisp0vRzwV5z07bkIk8y0MyoFUlFJBME8ZcjOOZ2UYKipN1Pviezg3vLlducpljBcH4f1SZORrYpYsaWWyRzDUM3GXLgTv8m7px0alXCqfVAJ0XfORTNRjo1HeiWFnrctLnZtQNlW5HO5Czb2yBN3PBmQ5QJidgDokaFoIeYd1cZuAhaz7NRheaU7oGicSetBWoeGJgmJLJFMgRtip1xzXceZL3P0c,mYmwLNEATOZmRIklMv3Pfh46zZveqVC5fFkbEsDi0nffrgJ3Fq90IirOm18ccISU00C1QuKgBuEYrCZRxOw88wGA9rKnz3maZ86GfCfrtDrXNGZWrnysgBbrJhChpKknRuNEmO7qQk0qc0ZUSr1adM23oEzqfjFGIKOxsNyyqK4qGvGzrf6GXiiH3TKDWEr6SQj2bWWzUTPP9qmb3CTD4VwYUOG3Nng5H1sKm0Lfl5dlGez79waTLlBQJUAovVXc,4tFjdzUPc2onr55ir28Op2t1meayF1SWgXsnUx2czGsIwvTCpRpJLhla6RAztTf91Wh36UGgq2wmqHHp240stJ3h2xfPBwU2rOlci7DRDCNBBaJmPfIakXnzcQ5lti9znwadnup2VDc7oedCGNJwEPiappG59BPRZopK35oux860LvSPxmD9X6AHRBvf7yCSWAhedIJvqsqXlvLiuecKjbItR6hWrdFdplaTFH74shN2TkbmAxaCDjokojxGvCoX,Q71Ba6z55dg3S0NMjOg6mNL2sKhXuVD8T3CkrTuXcARpQp4VKRSkbZQ41U9weLnpGphDThJkULVvNngZQ96dQTl6p2JQZTtBCYd27QQPikhU5EMASag4M841sUSDB9vEqnuoTUdBrcOyWAYaHTL3KEVJe7xiTzspbek2cMkUtObIVFYz1Z7Qb02hnCgEgpt6nuERGWAKvXL1zPtOYrmLEpdZsVqY5bFfGIePRJozfNmvODAqLEPEu9dgn7OPxcmi,gSXMqubsgOHBlXpBehlOi1DI9jd6K8ZFutkCLwXKOw5m1xdJ8Byn2lEPt10BbYrU7E2apWIHZI3uNRanXQkKJvMgiXszAmS7mDm1VX83LyLza4erYTjCJNt1ztLPdEyzMNoQcV9gevtZrex3YYFpJ2zPqQp5TgdvZ9R0oeJ0RNKjFoxsTy3V29w3UB5UhiDHjv7JqZYvaxJekrKEgOhDGNJd4iNEaxTjlZjpATGVPgGYkHqaCCz7Az7EcLTCpRCM,Rsu83HUK4tfT7UukxOurOdC5BR64NmJ7xmtrOYkMC9l2HabB9wisnVmbvGblm7RV2DowYItnrnMMIQUwJYHmfujUijJ0IEYwe4IXfTqpZhGMn4vbVeWS7fcgrQmfo9KJsuMkdS87W2pS8pY1x6npA2qqJcqnkOZ2kBl1i2QUpx1ofl5cuwLfGTPDIc2g3aiaeEyj1i0vx5S9M4JSJqiHVzCHW4wI59sAu9EyvW6K1yDP0x91sGwlxjedjZffwIsH,a3JfMomSbA2F2I4CYHruvmQCJ923rfnR4buCKV9oCbsbip6UrTV9YvsYDoXvGc2HEMhRi9XGwem6nuzsdSURKXfs5I5B015CRj8KO7usIi8Jfw9C8EAoKGmJM7RmktSlnlLuvpOE5FkTXKZfowihM2xBdg77EX6sfQ3DGxwbcxKD8zHeFKkwDulW9Zjcf6s8Rt8bads7WXe0ewoPTiknQHKMbYTewzSbdG3vDcisjIjnNTJLKf21McFfTlxOxeve,tyJAxYYdM6kvFR8XxoG2w6U8r5ivbQtmLztIKJxOr1CMyTvdvmkEmPB0D61teIpSyazQlL9lJeNtfqjejzxSo3XnhsJMGBzJaN1p7BTonW4fjZJ58ySQQKhEjWAnbyTzzNxqCg1kdp5R6N7nE2QsRZrGC5MHu9DZoh2qY4rPkedDB6Hv1rpasbcpVmPxwX4NXAsxftQiRjbVKAxsPpmPXbBj46h4efiEc3xaDLGhp33Y9IlQiCDV285Pj8dBZgaf,f4MedbNrFRIPqCafTmFWSqYFoDTh41qqNdSv8Ti7FKJLkHHQAHZX8uj5s8hN1HgCeGwOouNxLPXeOO9d8vK2hOTnrXiS3qe6haRWZywgOKRq9Bxp0RceLkrswvYaqmYgmAaC9q3yieJwcOTzVRr3VIwp14CTZXHMitN6MVVSZFqFKgetTVBK1TYaJwNo056gzvxjXfBTWCJcpP6p9MOWJlXnfTUOkFNotXudMqbKD9jgSmqR6uOSBUblfI7W0rDx,StoP7e8KwaXNPwoM0jFhWiy5mmCC3I42K2cRn3z66s318xCIh7unDJYi4TOBQ8Bu0rOjPQp6GAZMUw0LwSXDlbQ1UOuLTmwv3jfV0YHRaza8U8KcEtrVnQGzQG1S3oYcSV4nPBGSKdpTNJ43VJtLAQfJfW24cgjT7rfu8Xnc3gByXPmJTcjHliKFPTSanh0R0P4vOkqHkDNmfyAMie65lQYNOm91cnodK5MufS5E4ENEKWvnw0INjegbRmqxplmZ,nrSIzynI3yMtLLyJ164Ktl5W37X7879M0xOMJkyIG6vplsZTRJjkVOdupcFXcygO1D5C2FzdOIestpD7ZoB6BLrxtSkC3g2vA3YZ2EWUuMt21Xl13j7p18xpoucQPt3wIt2AWOrpTGvT3NZucMHS0cpDFfxU6PqPTWTpbtVBn7weQ3oirlTgd2vC9Sc3IWk3ELczgUnUYAlT7hin8orTOpFFm3AQzzGY1m8mRYjZLbrr0r0NSezIXfwVoYv9Vou0,oWx1PGh92ZurivnyYYOYVjRXL38Vpn8aUhjP8wq1uBpO7yHASh5dDwzwenzATaw2CNjiyMfHFgeXUqIInLrMKxeUgeVqsLyt26sjal4yv407NTpZVrw2EdtguKpMEGJ7ST2LLg4DGnOI4Qyd7y5afj9rVbELwYHqVJ54tjSpJOKaj5shkk3Nxd3AISRqnnQZVdZypqmg4UXgWQJqQZHOiN4u7LQBVx4x6BwYQ9vYjBRDJr8RFMMcLCjBRSUTx7BZ,BHRTt5vn746XhLBmp7EOHCZzjerBQUD7Dfl29wOogcgkn6Cr2khQq4JeMQxtFk9eiS2qfhhX2n0BiHTwetAzbKNzcjGqaU1n6vOoROR9kIWLB6Aafpcx4TwPKGCKEIkbkURDBAR1HZDuEK6xSObkLRKUshty7obxnGMJ8c53q9VFoBinapgnH7hh6kYyqIGrFHGuqpOIbpG0kQvyH2sox6K7z8J6dBymP0BfxzZyc1nHbA4eGL9nVu62EzGqBfh9,hI9KCOqERqTll5qhMKbRMLIMMwSNLZh8dq0oJMfLIk06Xy38havts3irdwPXBbEiioL5BVFFYJTLPh33NkhwE08Ssonhqnl471a75L4wc7bB17lmtQ84hLC0d03dl6vymx28gNVfg9XnWoEFv7jeMoebYJKwdKCPo4YGxhamhyOWx1JwxinVksa6HAjpzgd2kWwYWXo1jCsWDojEK1txJ8EDilDYfL1fZ10zMYgOssRay7QNdA7gdOc5b9cNYlcv,KDoCOcoJracMTM6oXtWRSf2oscjSKqbBhk2geq4Gk3yjL76vCFW4rnmnFW5q7sX3dR1nkRK2H9ccrTIgm0LwgnlDT5MmY5KfRwo3LjaTfydvAJN7z3kr5Gc0rSoWpi5LfULrQuYweCD1qZAF9qFMzy2QC0Zfzu7odqujFl7n0sT2LHQDCRvYhIpdJnCCGesBE1UTMTk4x3lq0TePzhKdF7zL3qh6hMSxS9RekEQ8Jca4CrZ67wQ3f3a7VEYssxVM,Nq2RomrEsEu9i5U3OdqdoSkldgPWGZKkg7fuWo65Zlu1Gaydkh5Sxc7T3MctVXWLOv8MyLWU2ktj92XPJ2zcsUkPniRHDvsmVhRVPZ6MMA8cdY99moQiFa5tygqyk3S2gCJqC0bPtSmjPCLyyLXI2CUdR3iodkbYmxQL0zYPfj9GY4oTUmlQWhBt1Vo9ixRBDOQaAAVEJN07i7vgZME148lY8zJWYeQnPsG5Mg8ChYWphR25uvpZgrWkmQ9irHAe,FA8rXyeWCsCDUqEZUlNxMBGVQVf4bPPrXy5kxmJJGq99YuWKpJVtYVyqBOEplfdzop0It83kd2M4AkYdNPRJESsgOxZ2Irh2I4aGg467JeNld8cDIKvJRXkLALR52wiQVuspTPFFBONKS142yHguRK2csGmcum6KvtCK2TMkBGlgndedRrPJYW5ZXdYxaSgylaiX73WVtckx42CP2HrocxhVCKDlwvnzds32vOJmecXQ9itzVibMzcbWRyM0ypGz,4nF2TuvRZtOJiImQrOi08AMO0Kactt7Eo084kKN9btcxJo7ogJ0JX9AGihAD7bF1xJJkzyh5QqPJSUs62rjAYzqm92P6oZ2Cg4iXHKwnEBOEuT2GjqqGFcjjFOQa7mdHGHoDRmjwBakhmmU0fhPqReuEqO19njRw5exknm8aWpIDBT7bPDWtE02o9G4OaSV8NIOG7RzsU5UzQ0fKxIn1szHLPFC8Ahu4BPSqWJ5L29LGMuRwLwWs9lnhrzNumsIr,7DEwkvzxGoP3W0mjeFlNJbozWRv3m1DuMtj5bvOrSSkiN21NEoXX80UNB5NkWiuF9pm5wJRDlF7gfcIlIXnC2ZJjKPLCbexqfYLlcDdV5Q0dT5HNHo9yyGKX6oUa6MdnooK67CvOGh2qVdhZ30wBFcuPcMM3nDBIQpyFAIXw8Tr8ui7TvLjVqgxHh7rp4OKUzrnJLJS8j1txDed84nW3UolBcsmtrgGOkjkjYWRhtoOyjzQuxc3prUaP7bCjFWn1,2nW4rGFPKaO1DIg9QxQwCsoqYVkM1tns2TaFj6Uyaoh4QypwbREUi83l1nyiJlFrc2ekBCB1eFLsuMG2URHaUDFqqfxHorjCYEfZX2fZD3ElfrZ4WtSUp9ieAKHb0PeGKCOy3gnSDYaLxCuyJdc1Eibg8nxLUPKzrePmp76L1m6BwFQ3pgDdqaXGPTIW0XxDeLRkpvpXcGhCok4QakojAU6qWmyUXez2UfsG3WkV8iRLFig3GQfsAzUkWuD6prAG,RwDXbTLN4c8guy29rVEh50x1BdqkezelYyDj4Iw6LjApwxywK2Gp7KE6lhfPwTxdwf8PN51y1azIkwD9gFzb106JsPuoboZH9poAIfkEakMYEFET613DfYaLRXk7PSS18cTcAGCUVue4DNaEt18LVahGcJg7h6Gw3EL6hiopM2KkDOFvDR6ldIMQdrArhsvqxXi1pZyitir66gneJ4NZd4ZcsE7gRDj7hZJLHnYPR1le15nME0F3xFUWkXu1HxXi,nd3MGcv82GeX25k426a9gLKAjperCx1V5uvM90R67GAU4zJuJccrBNDGXhj5YUhYx8Hvl8P3qKeUvATFM8Dk6LNKx1JOLMBtRqVsGy0WNh35wbvt7rCettWjSqHYXjIjzpJUgqjvFnrKiKtH3lN8ma2kdelb0wOWy5VhZXxIaHJD9CQOnwNsynVv0V18s3lYUZSDVGrrJIxWfqv9Y6hKJzmdAhyFVsX26SZBocVV544aJEkiqdNLNJwjRdkfs785,ao4eo7eEZ5wGAWg4s669swq61JvGheASsEy3jnFW9vBQP3NYGbp3wv5A6Kk87tjNYNxFSX3oRCFcxJrEqC5TcfsYviTW0RoKisHdYPKLGXVX6xPodc95xA06loxfUcJN1rgFHhy8jHlnO22sM3Stnn9XhOq3BrwCw82lbV2e3q2joU7TBPwfwmAGDV1lnARKKhwS6dZIlWhWklwLxgoclJGKDjt2LOhDo3kJ0Upc65c42JS6Ba7GGCXqhDLGfqJT,beAkUOTM6eO3tuVWfJI16RNvVm8jVLNLlThE2HRdB85bwmhhsfuDhGYD3Z4MqL748G68yzLyhyHIbCjEo7r0GgZFiqvF0AGzzp3qHsEUX2FbwMaHyIOsgaEowL1RHYc7ZS9k4blndopF2dDU3vFBgK8isVeV6iEDKelTT0W0Z4t1jmGZe0pw2FyqnuWgq0SiFri36ETMRgdMrkW0rQGIEwih5KNckkjYjN1iNauypuEygJ7lGx0l5NjOqPH5rh7B,4tXlgqncgfxRjIACeFuKb4XCeIyr2DXMa503qBrIMXGYJtpkKloNsuiUJufP215uqkR5f5uYEGJFQGKS2uwFsdIM8j4EQW8dQzdqviCB8ym0rukB765NgRpK9ScTEX4zz1KvhVlLetQo4L1qIooEclfgTsOuWSun0f6rCc1ov3u15oUMGoPSjE7YrCT9gBTJBW3sSClOUd8QqHsEuDpVVKrkhJAzxW0xd6xi2a0ggwrmbJSaHxDgJ2QXgVOsm6P2,HpytC2QTRgFs8VIp3qAdbKQdSTO0Un7efc65pMUmWvorSAocfZjZVsEg0N5pexvCB6SegEXiVHOIDuJAvAo3gtXSySmsVdQbIkkHtTOJQkuERX2ea1O5yXflZQWz5viativ8ZHE4FMdA3qw8SW9BCrzKzAefTah13Ag03UGiXE6108PoWC3CCTqLgm9OWC8R1EQ2yqnWlFoKx9gmWmVi9fPazFo1BBjSDLNzkbr58MgHa3rWZ6IHMeaBZJDuZEvI,IJwYNu2KsfRing1ZWNhfI4Fp1FnaSal8Sc9vLgNLobkaKX5GuOB3tlXp7ui8LylgcvZbun0vc5EwhnuLvg5qF6WVRf0BA2W0BIsRqDiXHZRRZiovpToCepTIxUBmjOLjfzk1d9vWAEsnBNcLqBMeElDjojqSDjFpffVr7Lbov5ri1zW2NZ8KYowvlHnWTzroc1BKFmTzc2FfXj7056Bvu8YhVTXRtWfcB7gs6XlLh8jZ1XX5phxvd59Qk4fR5LPP,cHlEvaq6vJFw44kEY1zOKJPvKXLmWz9LZ0SCUD4oNLjWQUUjnMsVwZk1HdQaeHV4ri230KPSeFjSArfhhMYRykhIW2GniGQlmGuqMbsCw8jqCsdS09weJzQQy7IniHmpdUsjYPM7H7c9SmCfNY3sP8LOBioFA10m8eT8RFfzkTd2J2ttXfWorHiQR8wD1dvor0LDWZkbeQpniWWSu0ajcVh2FS4hkVAUqIFIawLyFLwS1O3dZtVJ4kCOk5UMCYQy,zplIAdGvW8CtwgFAuDMxcQvKwQBvzPvfD21PfDtxM7SgP6v8MSfukDW1VveHre8aEcWPgP6Aw2prI2lSg63Tdo88A30q3BV2tzfCCpYS0yCXMLPEgaY5V9WU3qsMNZqJmmdiLrXTktAopwpxpaCv4DMDjR9EbXCU3w8EMx7l8vgflOY5YTG1U3dIyBOL5a2pfzJDR0trtiLxncISUd9akcRHFRYlprpYJCbjSYmJ0USExeqqPAyuPyFshoqc0Dc5,S6tUngsP0eVR4ar8I6LGpM1DirowhLSsevXNuUUL96RZw5LtJqzzRHhJAu0Ej6v1MDXFnX5KjhiyeS9IB9Mx8Mzyjj7J46Qi613ghQk4TCF7K9tnf3U97ei3RGJh736eWlu6rAXEqKHgw3AOgULvGumUggT4IwUGWaUwqAHzULkEj3yB5qD0Js3mVMmIXBXmfcvI7oXv8pIF6qcMpYpR6DIfzpt1QTcyy1o3wb8LXznFIW5MUlJE111u9cg1KoWk,dfE0sLHrYeS9VTpvTdkruRrAPEYZPwIS0gQga2AH8WU4tKVCrRZJ9mev07v8NELm2bCfsBi30JmIfmg21OE40Khec3Z8QC8WVd7QzxszAFGpzHwpjIdQtgpLPQWlyUB8cHU5aDiZtEQi1KTHMEEfIfiAxbNLRYqm5e0l4omYTc8YuJX06RwNs6RUbd2X4aE804goS3CoPL5H1wj1biunHgPjkudMfyCxRXltF4FnTNlYpxhbhIQQknW9sooVYQ6O,298pIRZhjFMAhjiPZdHmR9HNT53ySeUbJYxlAKOkIeSMzGcTOLWMO4yt8rfgXJmN7h1d4TzvWMWQKtaTNVqhRdicCgmZVbSBwgJZrf4ebwawZqdXHkiuNuhnS5OwdyIRnbAbGzRpIP246MWESUwuw3nMBHjCxe5yB2Gl5w5jLaT4RHs7MYX6x65k4jAmvmHtljV6ZglSSZF1jGYepiFooSRCqNQUIf0D3xGcTiOlj6Mz1x9JdhcFmXXAITFG3hdB,rBghvRiVTIK9t80gVtpxxvndBsUJkEcUs3l9KzAF85XYgFqoF4gqga6RRMXqgZtZtk6Xt1qe7CT1FMrqx5YCRCUWYSPJmYdBQT3JtEm5hWHGpZmt7BFjzNbsrMxV40FdQHCpRxV8YyglPiPKOP86VZDXHYumhW82C1szYHs3tma4oEppCK3M4wn3fDRhPqnqg7kdn6VMr3qOyt4WkUocoL7eH0VDcz6C7dW3eMeRz1zoXmdLVQ9e8skGtVlF5lG0,cAGkxfO6lO6f0I5zA8AYV2Uff6ZOLfafmNPUOj962cCnjcnl7xwvcUaKPHCNRumOBjqWtIR6uwNvaJRZhSUUrF0WCL2h5MPXfjFQvmETV9U6NAQYUIQ4Tsbk4FkUIY3atFM9Rj2VfZhhC27kOg2xEeAUDotN7oYvQostZIctsoMGD33kq7t3ZyGJd5SOoWO98yVc6zc0pZnBdoCHcHSeOXEV428iGgCjk1rVpts3AcCAxRDfeYicBRuEQykSwWnQ,r3QE71OY8bwmW0ztJayeFWjQ4rRBt4Nt3CVJcIrDCFxZAZsSTTyAlUfuey8y9t1YPJE1EMMUTSI70Ns3WMFxAXAO7js6yQLmQadEaTG5uNTo3pEIRbCaVnJJe1ZTQBtUx8xnGk3mthF58njFjMqDt5qe9g5th1DR3IwCnKGVJh12CmBt0bx6xlgwdkPxvUTkpdeDWkk24gBNy2l5avvUALpd6Y1BxKBeQPadoh2vuznLtOcgmo5DO2YJY5IW0P54,8ACEtvBJCS9UDaP9hvXDpyfWC1xsKHPWA4wh9OEMp9AgefnuAxrE80TPa49Gh1BTuIWzwKJJBJh3fZaYdCUx7QwXxJmY2AIXChAspQqqusQNhP7zHTpwpSMtbiyP2yvRWCnKwhxqS5oxWNQf0BCmXl1aSh1JVRSxIzFUxrQVbRlhM5uOrBxwvED2PWKvNKSWoL9Kqh562hB2A2NkITTJcioMYs3wkLRuidHLUFQ4UhrHvYbIsuDEyYsAEkzKmuE8,6txn1rpgEAdX8JNyhFzeVqhQhZNssAtIdI81Pa9yK1krarJg2SiRbs4szZTgOtGIOHWT81KSqtm48VU1V5Muxe44ghcJRTV4unDhR5K9EcuZdCd60xuOWrbvetDFvuQ8E8Ba93tJc9Ij6youxRDCOB9l7JUfKlHDV814Xqv25uHLQRmNBOqS1H6SMnVwe1j56n1gzeKojbHYELtVpvZjt61malaRMWdWHr9GbTmNluEgoBGzMoqd8ZApMUE7Zexh,CqVCAGhyqzlitTpK8JHCDKrM46LJoFytfjjPLkqcP7ajhk5GB2qjOprjhUF5SjApbCGJNBMfg2EzG0TtUV4gMu5l5AxDNK8oXZgC6a4KWivrLhVwPMGsDfL0eoBFHg7bQHrYSdrI1WbWx5OsFgLkAOy7N83gojme7HZcAjqz5vKJOnIzMrZQHv5a0bwOhKQknkmxfJJjRhj4vAajfaSlGt6BHyuQU9geAIZ26X4AHbhbTajGD80Dy6PlFbaGwv7[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
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'
2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-28 10:25:20 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
[ThaliCore] Advertiser: session connected Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,[ThaliCore] Session.startOutputStream(with:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [9]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
[ThaliCore] Session.startOutputStream(with:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,[ThaliCore] Session.startOutputStream(with:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (15360 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (6712 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received (1125 bytes):'
,2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-28 10:25:29 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [9, 11]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [11]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:25:30 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:25:30 - DEBUG testThaliMobileNative: 'Server received (15289 bytes):'
,2017-07-28 10:25:30 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:25:30 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-28 10:25:30 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:25:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:4C4A28E9-2035-47E8-A153-BA2B2523267F
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:39056CDE-F8B9-4D96-B071-8452DE2C822B
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63659
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,[ThaliCore] Session.disconnect() peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wannxRZE6yflLkeWp0m6L8SNYXQBEdFE","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC62E1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:5B2EB23A-E969-4097-ACDC-38E6B6A0C19B
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2923606D-3F00-4705-8BE9-987546819CD0
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:25:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:25:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EA691BFE-D9C4-433B-A70E-C9ECD613FE4D
[ThaliCore] Browser.startListening
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:25:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39056CDE-F8B9-4D96-B071-8452DE2C822B","generation":0}'
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39056CDE-F8B9-4D96-B071-8452DE2C822B (syncValue: MLM8ThXE2EKsK9QhvGOvu006q9clBrlp)'
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3905,6CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DE573A-0E5A-4BD7-B7BC-01111EFB454A","generation":0}'
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8817D8DE-3A96-471E-BCE8-28B15E159AEF","generation":0}'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EB6E114-08CB-40BC-BC8E-AF9C5927C203","generation":0}'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:25:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MLM8ThXE2EKsK9QhvGOvu006q9clBrlp","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:25:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MLM8ThXE2EKsK9QhvGOvu006q9clBrlp', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:25:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:25:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8817D8DE-3A96-471E-BCE8-28B15E159AEF (syncValue: Fv8VAbZoHgVeRq9J7y3ma92,vaU31n3Ek)'
2017-07-28 10:25:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8817D8DE-3A96-471E-BCE8-28B15,E159AEF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93
[ThaliCore] Advertiser: session connected Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93
,[ThaliCore] Session.startOutputStream(with:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-28 10:25:43 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeS,treams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 []
,[ThaliCore] Session.session(_:peer:didChange:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63683
2017-07-28 10:25:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Fv8VAbZoHgVeRq9J7y3ma92vaU31n3Ek",,"error":null,"portNumber":63683}'
2017-07-28 10:25:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Fv8VAbZoHgVeRq9J7y3ma92vaU31n3Ek', error: 'null', listeningPort: '63683''
,Connecting to the localhost:63683
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:63683
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-28 10:25:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
[ThaliCore] Advertiser: session connected Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
[ThaliCore] Session.startOutputStream(with:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeS,treams() vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [13]
,2017-07-28 10:25:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2923606D-3F00-4705-8BE9-987546819CD0
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63683
[ThaliCore] Session.disconnect() peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E10EA18-052F-4852-871C-DB44FA9E3D93 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,# Can shift large amounts of data
,[ThaliCore] Session.deinit peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A
,[ThaliCore] Browser.startListening
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8817D8DE-3A96-471E-BCE8-28B15E159AEF","generation":0}'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8817D8DE-3A96-471E-BCE8-28B15E159AEF (syncValue: AOPUybxG9hAqg8afcXcoZuLlzvYfRw9e)'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EB6E114-08CB-40BC-BC8E-AF9C5927C203","generation":0}'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DEF4005-6540-42F4-B0CD-F8B75F1A30AB","generation":0}'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
2017-07-28 10:25:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}'
2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:53 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,17D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,17D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,17D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,17D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8817D8DE,-3A96-471E-BCE8-28B15E159AEF error: max retries exceeded
2017-07-28 10:26:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AOPUybxG9hAqg8afcXcoZuLlzvYfRw9e","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:26:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AOPUybxG9hAqg8afcXcoZuLlzvYfRw9e', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:26:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:26:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7EB6E114-08CB-40BC-BC8E-AF9C5927C203 (syncValue: KU6U9cd,VEYdizgnBIy3OGgaE0OTviWTg)'
2017-07-28 10:26:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7EB6E114-08CB,-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,B6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,B6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,B6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,B6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7EB6E114,-08CB-40BC-BC8E-AF9C5927C203 error: max retries exceeded
2017-07-28 10:26:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KU6U9cdVEYdizgnBIy3OGgaE0OTviWTg","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:26:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KU6U9cdVEYdizgnBIy3OGgaE0OTviWTg', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:26:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:26:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DEF4005-6540-42F4-B0CD-F8B75F1A30AB (syncValue: YzVgM2h,E2KCeZI5pCQQOctilutbetr1e)'
2017-07-28 10:26:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DEF4005-6540,-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63708
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YzVgM2hE2KCeZI5pCQQOctilutbetr1e","error":null,"portNumber":63708}'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YzVgM2hE2KCeZI5pCQQOctilutbetr1e', error: 'null', listeningPort: '63708''
,Connecting to the localhost:63708
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,Connected to the localhost:63708
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [13, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
ok 102 got the same data back
,[ThaliCore] VirtualSocket.deinit vsID:15 [13]
,# teardown
,2017-07-28 10:26:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63708
,[ThaliCore] Session.disconnect() peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "366FB7A7-D8EB-4F14-8D46-78B25FD8D289", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:366FB7A7-D8EB-4F14-8D46-78B25FD8D289
2017-07-28 1,0:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90FD00D1-764D-4287-AA8F-1901272586C8
[ThaliCore] Browser.startListening
2017-07,-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:26:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC20BFCE-89C5-4087-9DBF-512405597B19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC20BFCE-89C5-4087-9DBF-512405597B19", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:366FB7A7-D8EB-4F14-8D46-78B25FD8D289
2017-07-28 10:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
201,7-07-28 10:26:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret",:null,"networkType":null}})'
2017-07-28 10:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopList,ening()
,2017-07-28 10:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-28 10:26:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:01BD18F3-A24C-4AD8-88B1-C64045DAE4AC
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6436BCF7-6221-4BB2-8E09-EA3C924B1620", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6436BCF7-6221-4BB2-8E09-EA3C924B1620
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6436BCF7-6221-4BB2-8E09-EA3C924B1620
,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-28 10:26:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:c67cc0e2-39c9-4ec8-b870-9f5146a2be36 error: startListeningNotActive
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"yIWJxAfWPDtm4nXsND8jS6AD5ipHkP6e","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort ,is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:522A66A7-3939-4318-94AF-2228EBCB74E9
[ThaliCore] Browser.startListening
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
,ok 134 Got null as expected
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MLcpwrckOJFRtd9bi4pwhphR7cDJ79sh","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
,ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-28 10:26:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE259EB6-2E2F-4736-9D2F-AE71B4DD066F
,[ThaliCore] Browser.startListening
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:4fa6adad-a551-4c3f-b8b4-dcb06139bce4
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5A32A711-3AC9-4795-86B0-CC719851C109
2017-07-28 1,0:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
[ThaliCore] Browser.startListening
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6230A678-BDFC-47EE-97B5-B204F76EEA87","generation":0}'
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6230A678-BDFC-47EE-97B5-B204F76EEA87 (syncValue: 3aXJPgfMsfJ0h99JJg0biti6YXxGLzSW)'
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FC4C696C-75CA-4D68-9DED-BD4676EDB25B","generation":0}'
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE8EAE0C-6391-48F3-99B5-6FCC3C505E23","generation":0}'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,30A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:081E4B09-42B8-4868-95BD-2078A3159137
[ThaliCore] Advertiser: session connected Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:081E4B09-42B8-4868-95BD-2078A3159137 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:081E4B09-42B8-4868-95BD-2078A3159137
,[ThaliCore] Session.session(_:peer:didChange:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,30A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:081E4B09-42B8-4868-95BD-2078A3159137 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:081E4B09-42B8-4868-95BD-2078A3159137
,[ThaliCore] Session.startOutputStream(with:) peer:081E4B09-42B8-4868-95BD-2078A3159137
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [13, 16]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,30A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:6230A678,-BDFC-47EE-97B5-B204F76EEA87 error: max retries exceeded
2017-07-28 10:26:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3aXJPgfMsfJ0h99JJg0biti6YXxGLzSW","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:26:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3aXJPgfMsfJ0h99JJg0biti6YXxGLzSW', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:26:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:26:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FC4C696C-75CA-4D68-9DED-BD4676EDB25B (syncValue: e7pZuaE5iC15RzxoJXA3Zlshe0grs56j)'
2017-07-28 10:26:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FC,4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:26:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63725
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"e7pZuaE5iC15RzxoJXA3Zlshe0grs56j",,"error":null,"portNumber":63725}'
2017-07-28 10:26:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'e7pZuaE5iC15RzxoJXA3Zlshe0grs56j', error: 'null', listeningPort: '63725''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) found active relay
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P4zJHxcSUPcFWWREt2pRbcqNciwT45ts","error":null,"portNumber":63725}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) found active relay
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DbyEkr8GfjVkO6YstkDMIFPbIFYPHziC","error":null,"portNumber":63725}'
,ok 149 No error
,ok 150 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [13, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
# teardow,n
,2017-07-28 10:26:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5A32A711-3AC9-4795-86B0-CC719851C109
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10,:,26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeS,treams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [13, 17]
,[ThaliCore] BrowserManager.disconnect peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63725
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:17 [13]
,[ThaliCore] Session.disconnect() peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:081E4B09-42B8-4868-95BD-2078A3159137 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:081E4B09-42B8-4868-95BD-2078A3159137
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"e7pZuaE5iC15RzxoJXA3Zlshe0grs56j","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-07-28 10:26:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:081E4B09-42B8-4868-95BD-2078A3159137
,# update peer discovery 1
,2017-07-28 10:26:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-28 10:26:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-28 10:26:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-28 10:26:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-28 10:26:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'listening 63728'
,ok 151 Should throw
,# teardown
,2017-07-28 10:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'listening 63730'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'listening 63733'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'listening 63737'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'listening 63742'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63746'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63750'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63754'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63758'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - ,0 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'listening 63810'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'listening 63814'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 63817'
ok 198 port must be in range
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 63818'
ok 199 second start should return same port
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 63820'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 203 Passed good id but bogus port
2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing co,nnection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 63822
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28, 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:93BE8C3D-4DB1-49AB-B941-42D47D125E6C
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
,[ThaliCore] Browser.startListening
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FC4C696C-75CA-4D68-9DED-BD4676EDB25B","generation":0}'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FC4C696C-75CA-4D68-9DED-BD4676EDB25B (syncValue: XKvFkQfgh2De8kqgsiF7Yvcfb8GhzDWk)'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
2017-07-28 10:26:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF8648D-CF32-4B35-8271-410FDEA09399","generation":0}'
2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
2017-07-28 10:26:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D","generation":0}'
2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FC,4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,C4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FC,4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,C4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XKvFkQfgh2De8kqgsiF7Yvcfb8GhzDWk","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XKvFkQfgh2De8kqgsiF7Yvcfb8GhzDWk', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BBF8648D-CF32-4B35-8271-410FDEA09399 (syncValue: U0V3b8FpPtAUsPpIaSoQe0R,1D2a8x8YU)'
2017-07-28 10:27:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBF8648D-CF32-4B35-8271-410FD,EA09399:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:27:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB174017-018E-4451-84F9-48C81BD7147D
[ThaliCore] Advertiser: session connected Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DB174017-018E-4451-84F9-48C81BD7147D state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:511BFC48-3654-43A0-B9A7-334003382552
[ThaliCore] Advertiser: session connected Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:511BFC48-3654-43A0-B9A7-334003382552 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63832
,2017-07-28 10:27:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U0V3b8FpPtAUsPpIaSoQe0R1D2a8x8YU","error":null,"portNumber":63832}'
2017-07-28 10:27:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U0V3b8FpPtAUsPpIaSoQe0R1D2a8x8YU', error: 'null', listeningPort: '63832''
,ok 212 should be equal
,2017-07-28 10:27:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D (syncValue: DTvHJVge6tcJ2LiLZQokqmK5wJJ7gpVx)'
,2017-07-28 10:27:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB174017-018E-4451-84F9-48C81BD7147D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:511BFC48-3654-43A0-B9A7-334003382552
,[ThaliCore] Session.session(_:peer:didChange:) peer:511BFC48-3654-43A0-B9A7-334003382552 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB174017-018E-4451-84F9-48C81BD7147D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63836
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DTvHJVge6tcJ2LiLZQokqmK5wJJ7gpVx","error":null,"portNumber":63836}'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DTvHJVge6tcJ2LiLZQokqmK5wJJ7gpVx', error: 'null', listeningPort: '63836''
,ok 213 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:27:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:93BE8C3D-4DB1-49AB-B941-4,2D47D125E6C
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BBF8648D-CF32-4B35-8271-410FDEA09399
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63832
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63836
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB174017-018E-4451-84F9-48C81BD7147D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:511BFC48-3654-43A0-B9A7-334003382552
,[ThaliCore] Session.deinit peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] BrowserRelay.deinit
2017-07-28 10:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered ,to native'
,[ThaliCore] Session.deinit peer:511BFC48-3654-43A0-B9A7-334003382552
[ThaliCore] AdvertiserRelay.deinit
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U0V3b8FpPtAUsPpIaSoQe0R1D2a8x8YU","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 63838
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7CEF816A-6CE4-449C-8991-54BCD7BAA133
2017-07-28 1,0:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF
[ThaliCore] Browser.startListening
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF8648D-CF32-4B35-8271-410FDEA09399","generation":0}'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BBF8648D-CF32-4B35-8271-410FDEA09399 (syncValue: VPeVhdkITshv7c8UXJo10N3WOC1YEOh3)'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D","generation":0}'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,F8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,F8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VPeVhdkITshv7c8UXJo10N3WOC1YEOh3","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VPeVhdkITshv7c8UXJo10N3WOC1YEOh3', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95F44C45-7F4B-4ED1-94A3-C1753634B03C (syncValue: 0JkNhcAGdxXRv6qwQAwLQ1Q,WaQy0cuPP)'
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95F44C45-7F4B-4ED1-94A3-C1753,634B03C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
[ThaliCore] Advertiser: session connected Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63851
,2017-07-28 10:27:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0JkNhcAGdxXRv6qwQAwLQ1QWaQy0cuPP","error":null,"portNumber":63851}'
,2017-07-28 10:27:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0JkNhcAGdxXRv6qwQAwLQ1QWaQy0cuPP', error: 'null', listeningPort: '63851''
,ok 219 should be equal
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
,ok 220 should be equal
,ok 221 should be equal
,2017-07-28 10:27:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95F29FF2-0D10-45FD-BF02-EBCF261CB31F (syncValue: nhySRLtlQgCDJibFYoQzW2DNi6WkC1s0)'
,2017-07-28 10:27:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
[ThaliCore] Advertiser: session connected Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63857
,2017-07-28 10:27:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nhySRLtlQgCDJibFYoQzW2DNi6WkC1s0","error":null,"portNumber":63857}'
,2017-07-28 10:27:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nhySRLtlQgCDJibFYoQzW2DNi6WkC1s0', error: 'null', listeningPort: '63857''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7CEF816A-6CE4-449C-8991-54BCD7BAA133
2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63851
[ThaliCore] Session.disconnect() p,eer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63857
,[ThaliCore] Session.disconnect() peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:27:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,[ThaliCore] Session.deinit peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-28 10:27:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'listening 63861'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FCFC6DAD-7FBA-49A6-9086-B5D23F16BBE6
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}]'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'listening 63862'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA7FEFB4-1B10-4BEA-BED5-EA8612B90CA2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CA7FEFB4-1B10-4BEA-BED5-EA8612B90CA2
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA7FEFB4-1B10-4BEA-BED5-EA8612B90CA2", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:CA7FEFB4-1B10-4BEA-BED5-EA8612B90CA2
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CA7FEFB4-1B10-4BEA-BED5-EA8612B90CA2
[ThaliCore] Advertiser.stopAdvertising() peerID:CA7FEFB4-1B10-4BEA-BED5-EA8612B90CA2
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'listening 63865'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:35 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-28 10:27:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'listening 63866'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30396D6C-6370-4681-9C80-A3C24B5F3321
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF945E04-3FF7-42A7-8924-3AA6519B26E8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,DF945E04-3FF7-42A7-8924-3AA6519B26E8
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DF945E04-3FF7-42A7-8924-3AA6519B26E8
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'listening 63869'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BD57EC86-119C-426A-899C-6D36BE3F5351
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CADE5A97-6E9E-4F02-95B7-A8C7B88188AB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CADE5A97-6E9E-4F02-95B7-A8C7B88188AB
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
2017-07-28 10:27:36 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}]'
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"pe,erAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CADE5A97-6E9E-4F02-95B7-A8C7B88188AB
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
2017-07-28 10:27:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'listening 63871'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:364E51BC-692B-4B51-A517-3381FB88335A
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00B54BB2-B971-4EB4-812A-4420AD350D22", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:00B54BB2-B971-4EB4-812A-4420AD350D22
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00B54BB2-B971-4EB4-812A-4420AD350D22
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-28 10:27:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-28 10:27:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-28 10:27:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-28 10:27:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63874'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:552390B6-BC20-4F91-A603-7C9BE37BB90D
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63875'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ED2D2A33-4474-4178-99F2-E0ACFF348ED9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ED2D2A33-4474-4178-99F2-E0ACFF348ED9
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:ED2D2A33-4474-4178-99F2-E0ACFF348ED9
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63877'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63878'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32A70C6A-C9E5-4820-8708-BCC1925636C9
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
2017-07-28 10:27:42 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-,45FD-BF02-EBCF261CB31F", generation: 0)
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}]'
2017-07-28 10:27:42 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","generation":0}'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC", generation: 0)
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","generation":0}]'
2017-07-28 10:27:43 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","generation":0}'
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7FB3F7D-6098-45DE-996C-3806B0585C2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7FB3F7D-6098-45DE-996C-3806B0585C2A", generation: 0)
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","generation":0}]'
2017-07-28 10:27:44 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","generation":0}'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:45 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'listening 63880'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0323044D-1913-4454-B736-375476473E4A
2017-07-28 1,0:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
2017-07-28 10:27:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95F44C45-7F4B-4ED1-94A3-C1753634B03,C (syncValue: OUi4NKiQyjnlhAJvQqCz8vD1LOVDiyJF)'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C17536,34B03C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnecte,d,:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}]'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}]'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,5F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
2017-07-28 10:27:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
,2017-07-28 10:27:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-28 10:27:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,5F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OUi4NKiQyjnlhAJvQqCz8vD1LOVDiyJF","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:27:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OUi4NKiQyjnlhAJvQqCz8vD1LOVDiyJF', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66D1520A-8B85-4C7C-98D7-E64579619E08 (syncValue: 1cWh3mAkmj1MWBe5gdhAvTI,V4HtObspQ)'
2017-07-28 10:27:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66D1520A-8B85-4C7C-98D7-E6457,9619E08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63888
2017-07-28 10:27:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1cWh3mAkmj1MWBe5gdhAvTIV4HtObspQ",,"error":null,"portNumber":63888}'
2017-07-28 10:27:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1cWh3mAkmj1MWBe5gdhAvTIV4HtObspQ', error: 'null', listeningPort: '63888''
,2017-07-28 10:27:53 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [13, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:27:54 - DEBUG testUtils: 'Got response data'
2017-07-28 10:27:54 - DEBUG testUtils: 'Got end'
ok 283 response body should match testData
ok 284 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
[ThaliCore] Advertiser: session connected Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
,[ThaliCore] Session.session(_:peer:didChange:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
[ThaliCore] Session.startOutputStream(with:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [13, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0323044D-1913-4454-B736-375476473E4A
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:57 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserManager.disconnect peer:66D1520A-8B85-4C7C-98D7-E64579619E08
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63888
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocke,tErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconne,cting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] Session.session(_:peer:didChange:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
[ThaliCore] BrowserRelay.didCloseVirtualSocketSt,reamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [13, 19]
[ThaliCore] Session.disconnect() peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.deinit
[ThaliCore,] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [13]
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1cWh3mAkmj1MWBe5gdhAvTIV4HtObspQ","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
,[ThaliCore] Session.deinit peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserRelay.deinit
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-28 10:27:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-28 10:27:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"95F29FF2-0D10-45FD-BF02-EBCF261CB31F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F7FB3F7D-6098-45DE-996C-3806B0585C2A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'listening 63891'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'listening 63892'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:81F6F51B-7C2F-4779-8211-6F497D6AC83B
[ThaliCore] Browser.st,artListening
2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}]'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}]'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","generation":0}'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:28:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"66D1520A-8B85-4C7C-98D7-E64579619E08","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'listening 63893'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "476B1C4A-E08D-4773-8628-CD3AE284C769", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:476B1C4A-E08D-4773-8628-CD3AE284C769
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "476B1C4A-E08D-4773-8628-CD3AE284C769", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:476B1C4A-E08D-4773-8628-CD3AE284C769
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:476B1C4A-E08D-4773-8628-CD3AE284C769
,[ThaliCore] Advertiser.stopAdvertising() peerID:476B1C4A-E08D-4773-8628-CD3AE284C769
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'listening 63896'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-28 10:28:02 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'listening 63897'
,ok 332 first call should succeed
,ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-28 10:28:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-28 10:28:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-28 10:28:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5631be3c-44a3-414a-807d-dbc0616c1240","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 should be calle,d once
ok 345 should not have been called more than once
,# teardown
,2017-07-28 10:28:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5631be3c-44a3-414a-807d-dbc0616c1240","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
,ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# can get the network status
,ok 349 network status should have certain non-empty properties
,# teardown
,ok 350 error should be null
ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 353 we have not added peer to the cache yet
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a394f694-a1e4-479e-acd3-9630186ce80d","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a394f694-a1e4-479e-acd3-9630186ce80d","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b8cfff5-ea35-4dc3-91da-6ffed54cc9ac","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b8cfff5-ea35-4dc3-91da-6ffed54cc9ac","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5ae708f-e9f8-4ed1-9bb5-56980efcc656","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c42e2c6c-0090-4922-b65a-f4414b376c77","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c5ae708f-e9f8-4ed1-9bb5-56980efcc656","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c42e2c6c-0090-4922-b65a-f4414b376c77","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a00274cf-b3bd-4797-8473-6fe813e83e16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 376 peer is available
,# teardown
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a00274cf-b3bd-4797-8473-6fe813e83e16","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-28 10:28:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-28 10:28:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76ed6d11-f80c-4604-bbd3-4548125a9a29","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76ed6d11-f80c-4604-bbd3-4548125a9a29","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be available
,ok 388 should store correct generation
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"76ed6d11-f80c-4604-bbd3-4548125a9a29","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'listening 63898'
2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ca8ca35-d59d-4a65-ace0-119193bb75ae","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ca8ca35-d59d-4a65-ace0-119193bb75ae","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ca8ca35-d59d-4a65-ace0-119193bb75ae","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'listening 63899'
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"448b139e-854d-412a-bc38-d2468c79d582","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"448b139e-854d-412a-bc38-d2468c79d582","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0c85a56b-790e-4440-a55a-636e7bf4909b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 404 peer should be ,available
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0c85a56b-790e-4440-a55a-636e7bf4909b","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer, should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'listening 63900'
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6670261e-f23e-4bdb-a5aa-bf7af675d8b2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 first peer is expected to be available
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b2923f2-ddb9-4521-9787-4e32687351c5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 411 second peer is expected to be available
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2b2923f2-ddb9-4521-9787-4e32687351c5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b2923f2-ddb9-4521-9787-4e32687351c5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2b2923f2-ddb9-4521-9787-4e32687351c5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6670261e-f23e-4bdb-a5aa-bf7af675d8b2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'listening 63901'
2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bb081e7f-2c2f-4b2a-950b-8a7d8af4c78a","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"319fc073-7558-420f-9359-e781d986caf5","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bb081e7f-2c2f-4b2a-950b-8a7d8af4c78a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"319fc073-7558-420f-9359-e781d986caf5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-28 10:28:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d6fd6c20-86cc-4676-abcd-3b8069587a94","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d6fd6c20-86cc-4676-abcd-3b8069587a94","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 438 address has not been changed
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d6fd6c20-86cc-4676-abcd-3b8069587a94","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 439 new port handled correctly
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d6fd6c20-86cc-4676-abcd-3b8069587a94","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 440 new host handled correctly
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d6fd6c20-86cc-4676-abcd-3b8069587a94","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-28 10:28:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-28 10:28:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
ok 453 error should be null
,# setup
,ok 454 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 455 should be equal
,# teardown
,ok 456 error should be null
ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-28 10:28:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
,ok 463 the same hostAddress
,ok 464 the same portNumber
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 468 contains expected properties
ok 469 the same hos,tAddress
ok 470 the same portNumber
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'listening 63902'
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d913f154-1941-4c15-9a26-bd56e7b075d2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d913f154-1941-4c15-9a26-bd56e7b075d2","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'listening 63903'
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c542bbc9-3145-42ab-a21a-6080cd929c2d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:c542bbc9-3145-42ab-a21a-6080cd929c2d
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-28 10:28:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c542bbc9-3145-42ab-a21a-6080cd929c2d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-28 10:28:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'listening 63904'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FCE3D568-230D-4854-973B-A8579F0411FD
,[ThaliCore] Browser.startListening
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1bc95042-d9ac-49c4-93c4-1057976e6275","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dbb5ec51-5e92-41db-9a9f-6ef8a0e62c59","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1bc95042-d9ac-49c4-93c4-1057976e6275","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"dbb5ec51-5e92-41db-9a9f-6ef8a0e62c59","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'listening 63905'
2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b8219b04-7532-4ca7-a9ea-45c5d2b6b454","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"24694854-d644-47b1-a4bb-0eaac23605dc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b8219b04-7532-4ca7-a9ea-45c5d2b6b454","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"24694854-d644-47b1-a4bb-0eaac23605dc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-28 10:28:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'listening 63906'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0ED2C542-CB86-45A5-99D9-C349BC60F395
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Browser.startListening
2,017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}]'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 0)'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","generation":0}]'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63910
,2017-07-28 10:28:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":63910}'
,2017-07-28 10:28:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD0D4E6E-B98D-47EB-BD63-5DD28772CB37 (syncValue: 1)'
,2017-07-28 10:28:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [13, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0 state: notConnected -> connecting
,2017-07-28 10:28:21 - DEBUG testUtils: 'Got response data'
2017-07-28 10:28:21 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63914
2017-07-28 10:28:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":63914}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [13, 20, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:28:23 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:23 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Advertiser: session connected Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:701D18EE-61FC-4884-9394-6931A9342548 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] Session.session(_:peer:didChange:) peer:701D18EE-61FC-4884-9394-6931A9342548 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [13, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.session(_:peer:didChange:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
,[ThaliCore] Session.session(_:peer:didChange:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [13, 20, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28, 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0ED2C542-CB86-45A5-99D9-C349BC60F395
2017-07-28 10:28:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-28 10:28:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-28 10,:28:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:28:35 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:35 - DEBUG makeIntoCloseAllServer: 'cl,oseAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeS,treams() vsID:22
ok 527 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=S,ocket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual s,ocket vsID:23
ok 528 error should be null
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
# setup
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] VirtualSocket.deinit vsID:22 [13, 20, 21, 23]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [13, 20, 21]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [13, 20]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[Th,aliCore] VirtualSocket.deinit vsID:20 [13]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnect,Handler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-28 10:28:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
,ok 533 getConnectionType
,ok 534 getActionType
,ok 535 getActionState
,ok 536 getPskIdentity
ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
,2017-07-28 10:28:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-28 10:28:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 clean kill
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 544 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 545 forever agent should have it's own destroy method
,ok 546 agent's destroy should be called
,ok 547 agent's destroy should not be called again
,ok 548 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 549 Entry counter must be 1
,ok 550 Entry exists
,ok 551 Size must be 1
,ok 552 Entry counter must be 2
,ok 553 Entry exists
,ok 554 Size must be 2
,ok 555 Entry counter must be 1
,ok 556 Entry exists
,ok 557 Size must be 3
,ok 558 Entry counter must be 2
,ok 559 Entry exists
,ok 560 Size must be 4
,ok 561 Entry 1_1 should not be found
,ok 562 Entry 1_1 does not exist
,ok 563 Size must be 3
,ok 564 Entry 1_2 should not be found
,ok 565 Entry 1_2 does not exist
,ok 566 Size must be 2
,ok 567 should be equal
,ok 568 Entry 2_1 should not be found
,ok 569 Entry 2_2 should not be found
,ok 570 Entry 2_1 does not exist
,ok 571 Entry 2_2 does not exist
,ok 572 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 573 Size must be100
,ok 574 Entries between 20 and MAXSIZE + 20 should exist
,ok 575 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 576 Entries between 6 and MAXSIZE + 4 should exist
,ok 577 Size should be MAXSIZE
,ok 578 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 579 WAITING state entry should not be removed
,ok 580 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 581 Size should be MAXSIZE
,ok 582 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 583 Kill should be called once
,ok 584 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 585 is an agent
,ok 586 enqueue is fine
,ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
,ok 589 first enqueue is fine
,ok 590 is an agent
,ok 591 second enqueue is fine
,ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-28 10:28:43 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:43 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-28 10:28:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
,ok 600 enqueue worked
,ok 601 is an agent
,ok 602 enqueue 2 worked
,ok 603 enqueue is not available when stopped
,ok 604 start action is killed
,ok 605 killed action is still killed
,ok 606 enqueued action when stopped is killed
,ok 607 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 608 good start
ok 609 good enqueue
ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
ok 612 wrong arg type
ok 613 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 614 good enqueue
ok 615 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
,ok 617 2nd good enqueue
,ok 618 we are in the pool
,ok 619 We are out of the pool
,ok 620 Action was killed
,ok 621 The original kill was called too
,ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
ok 624 first kill
ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
ok 627 2nd good enqueue
ok 628 1st action is in the pool
ok 629 2nd action is in the pool
ok 630 1st action is out of the pool
ok 631 2st action is out of the pool
,ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-28 10:28:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-28 10:28:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-28 10:28:48 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got null
,2017-07-28 10:28:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 640 is an agent
,2017-07-28 10:28:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
,ok 643 Got another null
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 644 is an agent
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 654 Null 1
ok 655 (unnamed assert)
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 663 is an agent
,ok 664 Notification finished
ok 665 Replication finished
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-28 10:28:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-28 10:28:52 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 675 peerIdentifier should match
,ok 676 generation should match
,ok 677 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 678 good beacon
,ok 679 good preAmble
,ok 680 public keys match!
,ok 681 must return null after successful call
,ok 682 Once start returns the action should be in KILLED state
,# teardown
,2017-07-28 10:28:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-28 10:28:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-28 10:28:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-28 10:28:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
ok 686 correct error message
,# teardown
,2017-07-28 10:28:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-28 10:28:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-28 10:28:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-28 10:28:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-28 10:29:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-28 10:29:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-28 10:29:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-28 10:29:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
ok 703 ecdh for local device cannot be null
ok 704 milliseconds cannot be less than 0
ok 705 milliseconds cannot be 0
,ok 706 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 707 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 708 should be equal
,ok 709 should be equal
,ok 710 (unnamed assert)
,ok 711 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 712 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 713 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 714 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 715 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 717 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-28 10:29:14 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 721 right number of calls to address book
ok 722 good preAmble
,ok 723 good unencryptedKeyId
,ok 724 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 725 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 726 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 727 Matching numbers
,ok 728 We have an entry!
,ok 729 keys match
,ok 730 secrets match
,ok 731 We have an entry!
,ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
,ok 735 keys match
,ok 736 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 737 Streams have same length
,ok 738 matching size
,ok 739 keys match
,ok 740 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 741 should be equal
,ok 742 peerDictionalty contains 2 peers
ok 743 bluetooth peer's notification has correct connection type
ok 744 tcp peer's notification has correct connection type
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-28 10:29:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-28 10:29:19 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-28 10:29:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-28 10:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-28 10:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-28 10:29:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-28 10:29:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-28 10:29:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-28 10:29:23 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 765 action should be resolved with NETWORK_PROBLEM error
,ok 766 correct number of requests
,ok 767 correct number of failures
,ok 768 correct final peer state
,# teardown
,2017-07-28 10:29:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-28 10:29:27 - WARN thaliNotificationClient: 'peer is not available'
2017-07-28 10:29:27 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-28 10:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-28 10:29:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-28 10:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-28 10:29:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-28 10:29:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-28 10:29:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-28 10:29:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-28 10:29:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-28 10:29:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-28 10:29:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-28 10:29:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-28 10:29:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-28 10:29:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-28 10:29:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-07-28 10:29:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-28 10:29:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-28 10:29:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-28 10:29:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
,ok 814 first action kill called
,ok 815 second action kill called
,ok 816 first cleared dictionary
,ok 817 first cleared pool
,ok 818 second cleared dictionary
,ok 819 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 820 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-28 10:29:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 821 listener has been set
,ok 822 peer dictionary has expected number of entries
,ok 823 Dictionary and pool have same action
,ok 824 ads match
,ok 825 PouchDB matches
,ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-28 10:29:44 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 834 start called once
,ok 835 One entry left
,ok 836 Dictionary and pool have same action
,ok 837 Start never called
,ok 838 Kill called once
,ok 839 no entries left
,ok 840 Third action is dead
,ok 841 peer dictionary has expected number of entries
,ok 842 Dictionary and pool have same action
,ok 843 ads match
,ok 844 PouchDB matches
,ok 845 DB Names match
,ok 846 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-28 10:29:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-28 10:29:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:29:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-28 10:29:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-28 10:29:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-28 10:29:47 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-28 10:29:47 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-28 10:29:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-28 10:29:48 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-28 10:29:48 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-28 10:29:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-28 10:29:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-28 10:29:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-28 10:29:52 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:29:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:29:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-28 10:29:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-28 10:29:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:29:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-28 10:30:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-28 10:30:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-28 10:30:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-28 10:30:07 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:30:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-28 10:30:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-28 10:30:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
,ok 861 Error should be timed out
,# teardown
,2017-07-28 10:30:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-28 10:30:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-28 10:30:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'listening 64043'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] Browser.startListening
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}]'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 2)'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":63910}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:746F6ED9-D195-4EAC-8676-23249C3D2C78
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [13, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:30:13 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 3)'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":63910}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [13, 24, 25]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [13, 24]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:13 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 4)'
2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":63910}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [13, 24, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [13, 24]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:13 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [13, 24, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [13, 24]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","generation":0}]'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","generation":0}'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"538E926E-B201-4924-A207-2E81E539D7B5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 538E926E-B201-4924-A207-2E81E539D7B5 (syncValue: 5)'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [13, 24, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [13, 24]
,[ThaliCore] Session.session(_:peer:didChange:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Advert,iser: session connected Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FED41591-EF39,-4DE7-A7B3-7F5E7F60CE6C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
2017-07-28 10:30:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","generation":0}]'
2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","generation":0}'
2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:30:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","connectionType":"MPCF","peerAva,ilable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Advertiser: session connected Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64051
2017-07-28 10:30:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":64051}'
,2017-07-28 10:30:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA (syncValue: 6)'
,2017-07-28 10:30:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,9 [13, 24, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [13, 24, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [13, 24, 29]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [13, 24, 29, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:29 [13, 24, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [13, 24, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0 state: notConnected -> connecting
,2017-07-28 10:30:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [13, 24, 31, 32, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[Th,aliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [13, 24, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [13, 24, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [13, 24, 31, 32, 33, 34, 35, 36]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [13, 24, 31, 32, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [13, 24, 31, 32, 33, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
,[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [13, 24, 31, 32, 33, 34, 35, 36, 38]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [13, 24, 31, 32, 33, 34, 35, 36, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [13, 24, 31, 32, 33, 34, 35, 36, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Session.startOutputStream(with:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [13, 24, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [13, 24, 31, 32, 33, 34, 35, 36, 38, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:42 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Session.session(_:peer:didChange:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,3 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
,[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketD,idDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,4 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,7 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46]
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:64073
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":64073}'
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 7)'
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":63910}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46, 48]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:20 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:538E926E-B201-4924-A207-2E81E539D7B5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [13, 24, 31, 32, 33, 34, 35, 36, 38, 40, 44, 45, 46, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [13, 24, 31, 33, 34, 35, 36, 38, 40, 44, 45, 46, 50, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [13, 24, 31, 33, 35, 36, 38, 40, 44, 45,, 46, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:fa,lse
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [13, 24, 31, 33, 36, 38, 40, 44, 45, 46, 50, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.,startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [13, 24, 31, 33, 36, 38, 40, 44, 45, ,46, 50, 51, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [13, 24, 31, 33, 36, 40, 44, 45, 46, 50, 51, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [13, 24, 31, 33, 36, 40, 44, 45, 46, 50, 51]
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:31 [13, 24, 33, 36, 40, 44, 45, 46, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:33 [13, 24, 36, 40, 44, 45, 46, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [13, 24, 40, 44, 45, 46, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [13, 24, 44, 45, 46, 50, 51]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [13, 24, 44, 45, 46, 50]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [13, 24, 44, 45, 46, 50, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [13, 24, 44, 45, 46, 50, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 8)'
,2017-07-28 10:30:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
,2017-07-28 10:30:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":63910}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [13, 24, 44, 45, 46, 50, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [13, 24, 44, 45, 46, 50, 53, 54]
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:21 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [13, 24, 44, 45, 46, 50, 53, 54, 56]
[ThaliCore] BrowserRelay.didOpenVirtualSocketS,treamsHandler
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [13, 24, 44, 45, 46, 50, 53, 54, 56, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,8 [13, 24, 44, 45, 46, 50, 53, 54, 56, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:56 [13, 24, 44, 45, 46, 50, 53, 54, 57, 58]
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,9 [13, 24, 44, 45, 46, 50, 53, 54, 57, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] AdvertiserR,elay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [13, 24, 44, 45, 46, 50, 53, 54, 57, 58]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,44
[ThaliCore] VirtualSocket.deinit vsID:44 [13, 24, 45, 46, 50, 53, 54, 57, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[T,haliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [13, 24, 46, 50, 53, 54, 57, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [13, 24, 46, 50, 53, 54, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect,(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [13, 24, 50, 53, 54, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [13, 24, 50, 53, 54, 57, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={,NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socke,t vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [13, 24, 50, 53, 5,4, 57]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [13, 24, 50, 53, 54, 57, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [13, 24, 50, 53, 54, 57]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [13, 24, 50, 53, 54, 57, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [13, 24, 50, 53, 54, 57]
,2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 9)'
2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":63910}'
[Th,aliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [13, 24, 50, 53, 54, 57, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [13, 24, 50, 53, 54, 57]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-28 10:30:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [13, 24, 53, 54, 57]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler stat,e:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [13, 24, 54, 57]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [13, 24, 57]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [13, 24]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [13, 24, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=22 "Invalid argument" UserInfo={NSLocalizedDescription=Invalid argument, NSLocalizedFailureReason=Error in connect() func,tion})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] AdvertiserRelay.didClos,eVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [13, 24]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Session.startOutputStream(with:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,5 [13, 24, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:65
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [13, 24]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,6 [13, 24, 66]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:66
[ThaliCore] VirtualSocket.closeStreams() vsID:66
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:66
[ThaliCore] VirtualSocket.deinit vsID:66 [13, 24]
,[ThaliCore] Session.session(_:peer:didChange:) peer:701D18EE-61FC-4884-9394-6931A9342548 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Sessio,n.deinit peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] AdvertiserRelay.deinit
,2017-07-28 10:30:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9D650D87-8C6C-4AED-A3AE-5132A5710C9F (syncValue: 10)'
2017-07-28 10:30:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) found active relay
2017-07-28 10:30:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":63910}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [13, 24, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:67
,[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:67
[ThaliCore] VirtualSocket.deinit vsID:67 [13, 24]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remov,ed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:29 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63910
[ThaliCore] Session.disconnect() peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0) relay removed
,2017-07-28 10:30:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}]'
,2017-07-28 10:30:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","generation":0}'
,2017-07-28 10:30:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-28 10:30:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D650D87-8C6C-4AED-A3AE-5132A5710C9F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:30:33 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-28 10:33:14 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-28 10:33:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-28 10:40:12 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-,28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGE,R result: passed - enqueue and run in order'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enq,ueueAtTop'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
2017-07-28 10:40:12 - INFO CoordinatedClient:, '***TEST_LOGGER result: skipped - update peer discovery 2'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set u,p for no peer discovery test'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects',
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error i,f we get called on iOS'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNative,Wrapper is stopped when routerPortConnectionFailed is received'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result,: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-28 10:40:13 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-28 10:40:13 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-28 10:40:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-28 10:40:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-4,17E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417,E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F1E50FE7-EA12-417E-AA72-28EBA51DFF79/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
