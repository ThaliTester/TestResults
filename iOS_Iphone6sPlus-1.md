#### Test 11335185130e646f_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/08C06B78-2BE0-40DD-BA3E-C1C4C5049EC1/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/08C06B78-2BE0-40DD-BA3E-C1C4C5049EC1/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51232"
,(lldb)     command script import "/tmp/08C06B78-2BE0-40DD-BA3E-C1C4C5049EC1/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:36:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B75C2BD9-5103-4AF3-AA,36-0697ECCB9DED", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B75C2BD9-5103-4AF3-AA36-0697ECCB9DED
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:29C6ABF1-6594-4FAF-A1C6-F0934B05DAF4
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1DB1FBC9-,5DED-47A7-9F5B-540A4C7356D3
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "10B67CC0-4D99-4341-BBA0-3F3553F146B0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:10B67CC0-4D99-4341-BBA0-3F3553F146B0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10B67CC0-4D99-4341-BBA0-3F3553F146B0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10B67CC0-4D99-4341-BBA0-3F3553F146B0", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-27 09:36:30 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.584873974323273
,2017-07-27 09:36:30 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-27 09:36:30 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:10B67CC0-4D99-4341-BBA0-3F3553F146B0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "10B67CC0-4D99-4341-BBA0-3F3553F146B0", generation: 0)
,2017-07-27 09:36:31 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-27 09:36:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-27 09:36:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-27 09:36:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-27 09:36:33 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-27 09:36:33 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-27 09:36:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:36:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:36:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:36:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:36:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:36:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:36:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:36:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:36:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:37:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:37:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:37:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:37:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:37:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:37:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:37:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:37:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:37:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:37:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:37:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:37:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:38:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:38:47 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-27 09:38:47 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-27 09:38:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-27 09:38:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-27 09:38:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-27 09:38:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-27 09:38:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-27 09:38:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-27 09:39:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-27 09:39:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
ok 6 should be equal
# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
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
# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
,ok 26 secondPromise - second to run
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
,ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
,# setup
,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
ok 42 executors is called
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
,2017-07-27 09:39:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-27 09:39:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-27 09:39:12 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
,ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-27 09:39:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:39:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:39:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-27 09:39:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:048841BC-5A14-4A7B-B9D6-352713F877FC
[ThaliCore] Browser.startListening
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F7AC225-F0A7-483F-9168-1949004CD275
[ThaliCore] Browser.startListening
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8F2CA96-99FA-499A-9B4D-FA59B78BAF2F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A8F2CA96-99FA-499A-9B4D-FA59B78BAF2F
2017-07-27 0,9:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:A8F2CA96-99FA-499A-9B4D-FA59B78BAF2F
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C723FC50-EB28-45B3-A290-67D10344943C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C723FC50-EB28-45B3-A290-67D10344943C
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C723FC50-EB28-45B3-A290-67D10344943C", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:C723FC50-EB28-45B3-A290-67D10344943C
2017-07-27 0,9:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:3,9:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C723FC50-EB28-45B3-A290-67D10344943C
[ThaliCore] Advertiser.s,topAdvertising() peerID:C723FC50-EB28-45B3-A290-67D10344943C
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:39:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E915080D-D526-4FB8-80FE-E5B6C7288468", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E915080D-D526-4FB8-80FE-E5B6C7288468
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:39:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7F4819C6-12BF-4529-BB43-9A86C64FFE0B
[ThaliCore] Browser.startListening
2017-07-27 09:39:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-27 09:39:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:980AB9B2-4046-43E4-8FB8-434566707B01:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "980AB9B2-4046-43E4-8FB8-434566707B01", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31037A71-18FB-4EDC-9425-AE037F466BC6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31037A71-18FB-4EDC-9425-AE037F466BC6", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E915080D-D526-4FB8-80FE-E5B6C7288468:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E915080D-D526-4FB8-80FE-E5B6C7288468", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E915080D-D526-4FB8-80FE-E5B6C7288468
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6
2017-07-27 0,9:39:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:94AA360F-CFB6-4D1F-9587-9D47B8A1E928
[Thal,i,Core] Browser.startListening
2017-07-27 09:39:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:39:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"760B269A-1CC6-4302-B7BF-56CA6A0C4EC0","generation":0}'
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 760B269A-1CC6-4302-B7BF-56CA6A0C4EC0 (syncValue: ZaKpgzYcOi0wh7N3PfWQWk0RPuat5KUh)'
,2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D7B1B88-0F,B5-4D2B-B0F3-0C19B3221DD6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B
[ThaliCore] Advertiser: session connected Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
2017-07-27 09:39:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"73A09F1E-56FB-45EF-99A3-14DCD6DE2211","generation":0}'
2017-07-27 09:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:37 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62131
2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZaKpgzYcOi0wh7N3PfWQWk0RPuat5KUh","error":null,"portN,umber":62131}'
2017-07-27 09:39:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZaKpgzYcOi0wh7N3PfWQWk0RPuat5KUh', error: 'null', listeningPort: '62131''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B
,2017-07-27 09:39:40 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
[ThaliCore] Session.session(_:peer:didChange:) peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B state: connecting -> connected
,2017-07-27 09:39:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62131
[ThaliCore] Session.disconnect,() peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4D7B1B88-0FB5-4D2B-B0F3-0C19B3221DD6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B
[ThaliCore] AdvertiserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9
,2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6CA8AEF2-D177-43A2-9821-A81F72AC,4C06
[ThaliCore] Browser.startListening
2017-07-27 09:39:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:39:41 - INFO thaliMobile: 'Received state ({"discovery,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:DDEF01BA-3E50-43A9-B6BB-4FE7CF7F0C7B
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
2017-07-27 09:39:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"73A09F1E-56FB-45EF-99A3-14DCD6DE2211","generation":0}'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 73A09F1E-56FB-45EF-99A3-14DCD6DE2211, (syncValue: 1Nyc5m65ASdjIwTcZWkg8qFq4yIDH6ZU)'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6D,E2211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"760B269A-1CC6-4302-B7BF-56CA6A0C4EC0","generation":0}'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE78BB24-6874-4581-AD57-0DC8832424B4","generation":0}'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8", generation: 0)
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8","generation":0}'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,3A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73A09F1E-56FB-45EF-99A3-14DCD6DE2211", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:39:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1Nyc5m65ASdjIwTcZWkg8qFq4yIDH6ZU","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:39:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1Nyc5m65ASdjIwTcZWkg8qFq4yIDH6ZU', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:39:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:39:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 760B269A-1CC6-4302-B7BF-56CA6A0C4EC0 (syncValue: sIrXg1uHALRaiBPMUMqeqZDMyPSY1TyE)'
2017-07-27 09:39:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:760B269A-1CC6-4302-B7BF-56CA6,A0C4EC0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:39:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 ,0,9:39:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:73A09F1E-56FB-45EF-99A3-14DCD6DE2211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,60B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "760B269A-1CC6-4302-B7BF-56CA6A0C4EC0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:39:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sIrXg1uHALRaiBPMUMqeqZDMyPSY1TyE","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:39:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sIrXg1uHALRaiBPMUMqeqZDMyPSY1TyE', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:39:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:39:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FE78BB24-6874-4581-AD57-0DC8832424B4 (syncValue: BCI1tlKENGDq29ap3iLaMlx,qb42XU0ps)'
2017-07-27 09:39:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC88,32424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:760B269A-1CC6-4302-B7BF-56CA6A0C4EC0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62138
2017-07-27 09:39:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BCI1tlKENGDq29ap3iLaMlxqb42XU0ps",,"error":null,"portNumber":62138}'
2017-07-27 09:39:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BCI1tlKENGDq29ap3iLaMlxqb42XU0ps', error: 'null', listeningPort: '62138''
,Connecting to the localhost:62138
,Connected to the localhost:62138
2017-07-27 09:39:49 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-27 09:39:49 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C
[ThaliCore] Advertiser: session connected Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
[ThaliCore] Advertiser: session connected Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C
,[ThaliCore] Session.startOutputStream(with:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-27 09:39:56 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
[ThaliCore] Session.startOutputStream(with:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [1, 2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:39:57 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-27 09:39:57 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-27 09:39:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-27 09:39:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3,
[ThaliCore] VirtualSocket.deinit vsID:3 [1, 2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocke,tDisconnectHandler disconnecting:false
,2017-07-27 09:39:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:FE78BB24-6874-4581-AD57-0DC8832424B4
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62138
[ThaliCore] Session.disconnect,() peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AEE928C1-5243-4F40-A3FD-C638BC70252B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC135E3A-28E7-492E-AE28-98B676DE705C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "64B3EA7D-E3EE-4014-B73C-A9EA8C2A7CD9", generation: 0)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:39:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:39:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5D887890-529C-4AA4-8B6E-27EF41303DBD
2017-07-27 09:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-27 09:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D7212EAC-DF58-4E39-8270-0D299AD0220B
[ThaliCore] Browser.startListening
2017-07-27 09:39:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-27 09:39:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:39:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:AEE928C1-5243-4F40-A3FD-C638BC70252B
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8:0
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE78BB24-6874-4581-AD57-0DC8832424B4","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8", generation: 0)
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FE78BB24-6874-4581-AD57-0DC8832424B4 (syncValue: hm0fbRIQZgNkablV2OFXZ8ZGhv4bwReP)'
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8","generation":0}'
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:39:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
2017-07-27 09:40:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A7A20DB4-FB47-4900-98BA-D663B3798342","generation":0}'
2017-07-27 09:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5284E402-404F-461B-A0AD-E6A5CA3CD24A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5284E402-404F-461B-A0AD-E6A5CA3CD24A", generation: 0)
2017-07-27 09:40:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5284E402-404F-461B-A0AD-E6A5CA3CD24A","generation":0}'
2017-07-27 09:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:5D887890-529C-4AA4-8B6E-27EF41303DBD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D887890-529C-4AA4-8B6E-27EF41303DBD", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BA3A1057-C9FB-4282-BB03-C01A7F0FE0E8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FE78BB24,-6874-4581-AD57-0DC8832424B4 error: max retries exceeded
2017-07-27 09:40:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hm0fbRIQZgNkablV2OFXZ8ZGhv4bwReP","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:40:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hm0fbRIQZgNkablV2OFXZ8ZGhv4bwReP', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:40:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:40:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A7A20DB4-FB47-4900-98BA-D663B3798342 (syncValue: ONijzno,gokWQ3vFSApdeFWzXidazaxr4)'
2017-07-27 09:40:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7A20DB4-FB47,-4900-98BA-D663B3798342:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:40:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62156
2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ONijznogokWQ3vFSApdeFWzXidazaxr4",,"error":null,"portNumber":62156}'
2017-07-27 09:40:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ONijznogokWQ3vFSApdeFWzXidazaxr4', error: 'null', listeningPort: '62156''
,Connecting to the localhost:62156
Connecting to the localhost:62156
Connecting to the localhost:62156
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,Connected to the localhost:62156
Connected to the localhost:62156
Connected to the localhost:62156
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 2, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 2, 4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-27 09:40:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 94 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 2, 5, 6]
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:5
[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 2, 6]
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 2]
,# teardown
,2017-07-27 09:40:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5D887890-529C-4AA4-8B6E-27EF41303DBD
2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09,:,40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:A7A20DB4-FB47-4900-98BA-D663B3798342
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62156
[ThaliCore] Session.disconnect() p,eer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E27FBB5D-EE77-449F-841C-C5B2D7938662
,2017-07-27 09:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B0AE0244-121A-44D7-981A-7E0E70E76DA2
[ThaliCore] Browser.startListening
,2017-07-27 09:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:40:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
2017-07-27 09:40:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE78BB24-6874-4581-AD57-0DC8832424B4","generation":0}'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FE78BB24-6874-4581-AD57-0DC8832424B4, (syncValue: dTQzV257TIFga2TNehYWGBORCP5Qz8N0)'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832,424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"A7A20DB4-FB47-4900-98BA-D663B3798342","generation":0}'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
2017-07-27 09:40:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"90F04B47-253B-44D4-BB34-B5C287986AB0","generation":0}'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F597521-BA0A-4144-A2E4-1D226FF5B49F","generation":0}'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:40:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E27FBB5D-EE77-449F-841C-C5B2D7938662:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E78BB24-6874-4581-AD57-0DC8832424B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FE78BB24-6874-4581-AD57-0DC8832424B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FE78BB24,-6874-4581-AD57-0DC8832424B4 error: max retries exceeded
2017-07-27 09:40:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dTQzV257TIFga2TNehYWGBORCP5Qz8N0","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dTQzV257TIFga2TNehYWGBORCP5Qz8N0', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:40:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A7A20DB4-FB47-4900-98BA-D663B3798342 (syncValue: dpvlxg0ZIOuTC4bi7NPpH3Oi05Q5GpzD)'
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7A20DB4-FB47,-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FE78BB24-6874-4581-AD57-0DC8832424B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FABC8F34-5629-46DF-90BC-859367EC0792
[ThaliCore] Advertiser: session connected Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FABC8F34-5629-46DF-90BC-859367EC0792 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
[ThaliCore] Advertiser: session connected Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A7,A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FABC8F34-5629-46DF-90BC-859367EC0792
,[ThaliCore] Session.session(_:peer:didChange:) peer:FABC8F34-5629-46DF-90BC-859367EC0792 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FABC8F34-5629-46DF-90BC-859367EC0792
[ThaliCore] Session.startOutputStream(with:) peer:FABC8F34-5629-46DF-90BC-859367EC0792
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 2, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-27 09:40:30 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-27 09:40:30 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-27 09:40:30 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-27 09:40:30 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-27 09:40:30 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 2]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
[ThaliCore] Session.startOutputStream(with:) peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 2, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-27 09:40:31 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeSt,reams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 2]
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A7,A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7A20DB4-FB47-4900-98BA-D663B3798342", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:40:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dpvlxg0ZIOuTC4bi7NPpH3Oi05Q5GpzD","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:40:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dpvlxg0ZIOuTC4bi7NPpH3Oi05Q5GpzD', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:40:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:40:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 90F04B47-253B-44D4-BB34-B5C287986AB0 (syncValue: q7hc6pLerHKNPIGzsmtUfStouaToHO0o)'
2017-07-27 09:40:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90F04B47-253B-44D4-BB34-B5C28,7986AB0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:40:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 ,0,9:40:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A7A20DB4-FB47-4900-98BA-D663B3798342:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "90F04B47-253B-44D4-BB34-B5C287986AB0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62180
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"q7hc6pLerHKNPIGzsmtUfStouaToHO0o",,"error":null,"portNumber":62180}'
2017-07-27 09:40:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'q7hc6pLerHKNPIGzsmtUfStouaToHO0o', error: 'null', listeningPort: '62180''
,Connecting to the localhost:62180
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 2, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:62180
2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-27 09:40:37 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 2]
,# teardown
,2017-07-27 09:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:40:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E27FBB5D-EE77-449F-841C-C5B2D7938662
2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:90F04B47-253B-44D4-BB34-B5C287986AB0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62180
[ThaliCore] Session.disconnect() peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FABC8F34-5629-46DF-90BC-859367EC0792 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E27FBB5D-EE77-449F-841C-C5B2D7938662", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
,[ThaliCore] Session.deinit peer:90F04B47-253B-44D4-BB34-B5C287986AB0:0
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:40:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:9FB87A3C-114D-4621-9A00-25A3A52DF757
[ThaliCore] AdvertiserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D028B2EF-4493-4F02-B3B2-E9956CFE8164
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A15260A5-8C04-447A-AE83-D766D3C971EB
[ThaliCore] Browser.startListening
,2017-07-27 09:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F597521-BA0A-4144-A2E4-1D226FF5B49F","generation":0}'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F597521-BA0A-4144-A2E4-1D226FF5B49F (syncValue: jhKsq22kWNA0QFzcsacmOPkdtNO6KgaE)'
,2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F,597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D028B2EF-4493-4F02-B3B2-E9956CFE8164:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61237622-BEF2-4351-A24C-AE880E588319:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
2017-07-27 09:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}'
2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D", generation: 0)
2017-07-27 09:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1BDA067-0FC6-423A-BEBF-8AA6CBEF794D","generation":0}'
2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:40:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F597521-BA0A-4144-A2E4-1D226FF5B49F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:40:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jhKsq22kWNA0QFzcsacmOPkdtNO6KgaE","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:40:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jhKsq22kWNA0QFzcsacmOPkdtNO6KgaE', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:40:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:40:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61237622-BEF2-4351-A24C-AE880E588319 (syncValue: cJqzhxQoIGk35Y8bwUiNcHz,cnSuydJhY)'
2017-07-27 09:40:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61237622-BEF2-4351-A24C-AE880,E588319:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:40:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4F597521-BA0A-4144-A2E4-1D226FF5B49F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F
[ThaliCore] Advertiser: session connected Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:61237622-BEF2-4351-A24C-AE880E588319:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
[ThaliCore] Advertiser: session connected Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:61237622-BEF2-4351-A24C-AE880E588319:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:61237622-BEF2-4351-A24C-AE880E588319:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62192
2017-07-27 09:40:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cJqzhxQoIGk35Y8bwUiNcHzcnSuydJhY",,"error":null,"portNumber":62192}'
2017-07-27 09:40:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cJqzhxQoIGk35Y8bwUiNcHzcnSuydJhY', error: 'null', listeningPort: '62192''
,Connecting to the localhost:62192
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:61237622-BEF2-4351-A24C-AE880E588319:0
,Connected to the localhost:62192
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:61237622-BEF2-4351-A24C-AE880E588319:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 2, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-27 09:40:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
ok 102 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 2]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F
,[ThaliCore] Session.session(_:peer:didChange:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F
[ThaliCore] Session.startOutputStream(with:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 2, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (5617 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (7594 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (7523 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (1308 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received (191 bytes):'
,2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-27 09:40:48 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
[ThaliCore] Session.startOutputStream(with:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 2, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017,-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (4238 bytes):'
,2017-07-27 09:40:49 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server received (25185 bytes):'
,2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
,2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server received (4216 bytes):'
,2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-27 09:40:50 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 2, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:40:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D028B2EF-4493-4F02-B3B2-E9956CFE8164
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:61237622-BEF2-4351-A24C-AE880E588319
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62192
[ThaliCore] Session.disconnect() p,eer:61237622-BEF2-4351-A24C-AE880E588319:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:61237622-BEF2-4351-A24C-AE880E588319:0
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:6BC3BD79-DB14-472E-B488-45998FA9E58F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D028B2EF-4493-4F02-B3B2-E9956CFE8164", generation: 0)
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C794DC84-1CDA-484F-A944-F44DECAE8A12
[ThaliCore] Browser.startListening
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-27 09:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdv,ertisingAndListening(onPort:errorHandler:) Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:043B6E7B-5BF1-4D4E-A18A-4039818E34E6
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: ',d,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":fa,lse,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start, updating fine
,# teardown
,[ThaliCore] Session.deinit peer:B1E49570-D25C-4E1C-B54E-3EDDB2FD7150
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61237622-BEF2-4351-A24C-AE880E588319:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61237622-BEF2-4351-A24C-AE880E588319", generation: 0)
2017-07-27 09:40:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}]'
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"61237622-BEF2-4351-A24C-AE880E588319","generation":0}'
2017-07-27 09:40:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
2017-07-27 09:40:52 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8450063C-E352-4DE2-8028-790BEAC33A89","generation":0}]'
2017-07-27 09:40:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8450063C-E352-4DE2-8028-790BEAC33A89","generation":0}'
2017-07-27 09:40:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:043B6E7B-5BF1-4D4E-A18A-4039818E34E6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "043B6E7B-5BF1-4D4E-A18A-4039818E34E6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4EC8ABF-9651-4E51-A4EB-1008683F3A0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4EC8ABF-9651-4E51-A4EB-1008683F3A0E", generation: 0)
2017-07-27 09:40:53 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4EC8ABF-9651-4E51-A4EB-1008683F3A0E","generation":0}]'
2017-07-27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F4EC8ABF-9651-4E51-A4EB-1008683F3A0E","generation":0}'
2017-07-27 09:40:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:043B6E7B-5BF1-4D4E-A18A-4,039818E34E6
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:40:57 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-27 09:40:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:40:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:40:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3ABC9BE3-3174-4B3F-9002-2C87CA259C5D
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "44714BB6-1053-47A6-A560-148F79378506", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:44714BB6-1053-47A6-A560-148F79378506
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:44714BB6-1053-47A6-A560-148F79378506
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:40:58 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-27 09:40:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:40:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:40:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-27 09:41:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-27 09:41:00 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-27 09:41:01 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-27 09:41:02 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-27 09:41:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ebb74a4a-bce9-49d2-ad7b-363479cce303 error: startListeningNotActive
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iWotQYF2gnkyol,8wvZV4Ve89ysvIgvf9","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:06 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AEC90F45-8819-4A62-B280-B0EC649A677F
[ThaliCore] Browser.startListening
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:41:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jYDxa7n2sm3pcoc39wzfc8tTfv0ageuE","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect ,r,eturned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-27 09:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2893E9E8-8DAA-463E-A758-6767AFA6E188
[ThaliCore] Browser.startListening
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27, 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:2f1b7d3f-2b9e-4960-a21a-0c3ea44f2e5c
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:11 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8205ADF4-3323-4842-8B88-4588EAF9E8A1
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:11, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:03646242-A0E1-44F0-91FC-87940E6C4419
[ThaliCore] Browser.startListening
2017-07-27 09:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-27 09:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E4673876-CD79-4B66-A02B-FE40C77AED43:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "E4673876-CD79-4B66-A02B-FE40C77AED43", generation: 0)
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8450063C-E352-4DE2-8028-790BEAC33A89","generation":0}'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8450063C-E352-4DE2-8028-790BEAC33A89 (syncValue: V08BsQJo66om6xufp4lpb2tv4oiubd44)'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68","generation":0}'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E4673876-CD79-4B66-A02B-FE40C77AED43","generation":0}'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8205ADF4-3323-4842-8B88-4588EAF9E8A1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8205ADF4-3323-4842-8B88-4588EAF9E8A1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8450063C-E352-4DE2-8028-790BEAC33A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,50063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,450063C-E352-4DE2-8028-790BEAC33A89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8450063C-E352-4DE2-8028-790BEAC33A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,50063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,450063C-E352-4DE2-8028-790BEAC33A89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"V08BsQJo66om6xufp4lpb2tv4oiubd44","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'V08BsQJo66om6xufp4lpb2tv4oiubd44', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:41:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68 (syncValue: VGwZswgCcNHG2sv1kkYOXD4,R6aNc0XAZ)'
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A,6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:41:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
2017-07-27 09:41:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8450063C-E352-4DE2-8028-790BEAC33A89","generation":0}'
2017-07-27 09:41:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:18 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:41:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8450063C-E352-4DE2-8028-790BEAC33A89:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8450063C-E352-4DE2-8028-790BEAC33A89", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62210
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VGwZswgCcNHG2sv1kkYOXD4R6aNc0XAZ",,"error":null,"portNumber":62210}'
2017-07-27 09:41:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VGwZswgCcNHG2sv1kkYOXD4R6aNc0XAZ', error: 'null', listeningPort: '62210''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) found active relay
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BlEsGnt0mRr7oVI0b99HKJgqz7KVgTB,5","error":null,"portNumber":62210}'
ok 144 No error
ok 145 Ports equal
ok 146 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) found act,ive relay
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EJka4O84GyVgvXZpHygNpf2T7UDt9Wfi","error":null,"portNumber":62210}'
ok 147 No error
,ok 148 Ports equal
# teardown
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 2, 11, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:41:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8205ADF4-3323-4842-8B88-4588EAF9E8A1
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62210
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCP,Listener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStr,e,amsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] Session.disconnect() peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocket,StreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 2, 11]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
2017-07-27 09:41:26 - DEBUG th,aliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-27 09:41:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-27 09:41:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-27 09:41:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:41:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:41:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-27 09:41:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:29 - DEBUG createNativeListener: 'listening 62213'
ok 149 Should throw
,# teardown
,2017-07-27 09:41:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:29 - DEBUG createNativeListener: 'listening 62215'
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-27 09:41:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'listening 62218'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - close'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'listening 62222'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - close'
2017-07-27 09:41:31, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'listening 62227'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - close'
2017-07-27 09:41:31, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'listening 62231'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-27 09:41:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-27 09:41:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 62235'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
2017-07-27 09:41:32, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 62239'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'listening 62243'
,2017-07-27 09:41:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-27 09:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-27 09:41:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-27 09:41:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'listening 62295'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-27 09:41:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'listening 62299'
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-27 09:41:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:35 - DEBUG createNativeListener: 'listening 62302'
ok 196 port must be in range
,# teardown
,2017-07-27 09:41:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-27 09:41:35 - DEBUG createNativeListener: 'listening 62303'
ok 197 second start should return same port
,# teardown
,2017-07-27 09:41:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:35 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-27 09:41:36 - DEBUG createNativeListener: 'listening 62305'
,2017-07-27 09:41:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-27 09:41:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-27 09:41:36 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-27 09:41:36 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 62307
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:41:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:41:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:41:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:41:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:41:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:878DACE9-3741-43AD-9FBE-AB693BD154B7
[ThaliCore] Browser.startListening
2017-07-27 09:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:41:37 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68","generation":0}'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68 (syncValue: hLaJ3jUbKQ9M5CJkdWtNBbkvO2r576FV)'
,2017-07-27 09:41:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2620B9A-00C1-4B34-8AA8-6CE552013511","generation":0}'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
2017-07-27 09:41:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EA0C969-35BA-462D-8165-A0BABFC74371","generation":0}'
2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:41:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-27 09:41:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C
[ThaliCore] Advertiser: session connected Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC9BDDF8-215E-43EF-9BEA-8B22BA7ACE4C state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,2ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:41:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hLaJ3jUbKQ9M5CJkdWtNBbkvO2r576FV","error":"Peer is unavailable","portNumber":null}'
2017-07-27 09:41:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hLaJ3jUbKQ9M5CJkdWtNBbkvO2r576FV', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:41:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:41:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2620B9A-00C1-4B34-8AA8-6CE552013511 (syncValue: 5R97qxNPAkvpXgsdAIudqmzB59vYLJBh)'
2017-07-27 09:41:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE55,2013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:41:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F42ADCBF-AC92-476A-BCC8-C1E6A6D73C68:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62319
2017-07-27 09:41:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5R97qxNPAkvpXgsdAIudqmzB59vYLJBh",,"error":null,"portNumber":62319}'
2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5R97qxNPAkvpXgsdAIudqmzB59vYLJBh', error: 'null', listeningPort: '62319''
,ok 210 should be equal
2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6EA0C969-35BA-462D-8165-A0BABFC74371 (syncValue: F2lLrYWf2GtMPcAQNwiIqgCvoXxx9MuH)'
2017-07-27 09:41:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62322
2017-07-27 09:41:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"F2lLrYWf2GtMPcAQNwiIqgCvoXxx9MuH",,"error":null,"portNumber":62322}'
2017-07-27 09:41:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'F2lLrYWf2GtMPcAQNwiIqgCvoXxx9MuH', error: 'null', listeningPort: '62322''
,ok 211 should be equal
# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
[ThaliCore] Advertiser: session connected Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:043B36AE-A7EF-45C0-AEC3-D1596533F824 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62319
[ThaliCo,re] Session.disconnect() peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:BC9BDDF8-215E-43,EF-9BEA-8B22BA7ACE4C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5R97qxNPAkvpXgsdAIudqmzB59vYLJBh","error":"Session disconnected","portNumber":null}'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:42:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A0FCD6E9-33DE-4B08-AA31-5AA00E3CBC3D
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F2620B9A-00C1-4B34-8AA8-6CE552013511
,[ThaliCore] BrowserManager.disconnect peer:6EA0C969-35BA-462D-8165-A0BABFC74371
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62322
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,2017-07-27 09:42:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"F2lLrYWf2GtMPcAQNwiIqgCvoXxx9MuH","error":"Session disconnected","portNumber":null}'
,# Multiple local http requests
,[ThaliCore] Session.deinit peer:043B36AE-A7EF-45C0-AEC3-D1596533F824
[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCor,e] BrowserRelay.deinit
,listening on 62324
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0
2017-07-27 0,9:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30896872-3DD6-400A-99B0-91CCF3BF0BBD
[Tha,l,iCore] Browser.startListening
2017-07-27 09:42:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:42:02 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
2017-07-27 09:42:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EA0C969-35BA-462D-8165-A0BABFC74371","generation":0}'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6EA0C969-35BA-462D-8165-A0BABFC74371, (syncValue: SsFwwm9fJGi3wri3ka7rYXxGJLz0q3rr)'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC,74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo,:) found peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2620B9A-00C1-4B34-8AA8-6CE552013511","generation":0}'
,2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 09:42:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-27 09:42:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7703811-CCCA-4D64-BE3F-2CE0B9423AE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,A0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,A0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,A0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EA0C969-35BA-462D-8165-A0BABFC74371", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:42:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SsFwwm9fJGi3wri3ka7rYXxGJLz0q3rr","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:42:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SsFwwm9fJGi3wri3ka7rYXxGJLz0q3rr', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:42:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:42:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2620B9A-00C1-4B34-8AA8-6CE552013511 (syncValue: moKKxCbjBvLtvwBOl6YUL4c,jmAASnNoU)'
2017-07-27 09:42:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE55,2013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:42:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-27 ,0,9:42:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6EA0C969-35BA-462D-8165-A0BABFC74371:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FBE91978-6593-4C2C-80BD-6B5270525409
[ThaliCore] Advertiser: session connected Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FBE91978-6593-4C2C-80BD-6B5270525409 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1
[ThaliCore] Advertiser: session connected Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FBE91978-6593-4C2C-80BD-6B5270525409
,[ThaliCore] Session.session(_:peer:didChange:) peer:FBE91978-6593-4C2C-80BD-6B5270525409 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2,620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F2,620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F2620B9A-00C1-4B34-8AA8-6CE552013511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F2620B9A,-00C1-4B34-8AA8-6CE552013511 error: max retries exceeded
2017-07-27 09:42:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"moKKxCbjBvLtvwBOl6YUL4cjmAASnNoU","error":"Connection could not be established","portNumber":null}'
2017-0,7-27 09:42:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'moKKxCbjBvLtvwBOl6YUL4cjmAASnNoU', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-27 09:42:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-27 09:42:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0ECECFD-99D4-4837-84C7-C4E68676530E (syncValue: uXgqAHL,mpaSci2bhvlMupw1jpNrl3VKQ)'
2017-07-27 09:42:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0ECECFD-99D4,-4837-84C7-C4E68676530E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:42:21 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-27 09:42:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F2620B9A-00C1-4B34-8AA8-6CE552013511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62348
2017-07-27 09:42:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uXgqAHLmpaSci2bhvlMupw1jpNrl3VKQ",,"error":null,"portNumber":62348}'
2017-07-27 09:42:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uXgqAHLmpaSci2bhvlMupw1jpNrl3VKQ', error: 'null', listeningPort: '62348''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-27 09:42:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F26BEBDA-8461-458A-80B4-5C81D72A6F32 (syncValue: Z7rVkPzpslWCu8m5XReuyUHmrKaneFww)'
2017-07-27 09:42:,24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-27 09:42:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62354
2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z7rVkPzpslWCu8m5XReuyUHmrKaneFww","error":null,"portNumber":62354}'
2017-07-27 09:42:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z7rVkPzpslWCu8m5XReuyUHmrKaneFww', error: 'null', listeningPort: '62354''
,ok 220 should be equal
ok 221 should be equal
ok 222 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-27 ,09:42:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E7703811-CCCA-4D64-BE3F-2,CE0B9423AE0
2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:E0ECECFD-99D4-4837-84C7-C4E68676530E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62348
[ThaliCore] Sessi,on.disconnect() peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[Thal,iCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62354
[Thali,Core] Session.disconnect() peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
,2017-07-27 09:42:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:42:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z7rVkPzpslWCu8m5XReuyUHmrKaneFww","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B262399-1BC1-4506-9E08-61EB06510EB1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2B262399-1BC1-4506-9E08-61EB06510EB1
,[ThaliCore] Session.session(_:peer:didChange:) peer:FBE91978-6593-4C2C-80BD-6B5270525409 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E7703811-CCCA-4D64-BE3F-2CE0B9423AE0", generation: 0)
,[ThaliCore] Session.deinit peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:2B262399-1BC1-4506-9E08-61EB06510EB1
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-27 09:42:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'listening 62358'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:33C37C07-3344-4008-B1AF-70253B47B05F
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,# teardown
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}]'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}]'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'listening 62359'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "01131FA0-E7B7-4757-B2E2-DC19F0F4E194", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:01131FA0-E7B7-4757-B2E2-DC19F0F4E194
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "01131FA0-E7B7-4757-B2E2-DC19F0F4E194", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:01131FA0-E7B7-4757-B2E2-DC19F0F4E194
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:01131FA0-E7B7-4757-B2E2-DC19F0F4E194
,[ThaliCore] Advertiser.stopAdvertising() peerID:01131FA0-E7B7-4757-B2E2-DC19F0F4E194
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'listening 62362'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 236 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:31 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-27 09:42:31 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'listening 62363'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CBFEF892-ADA8-4097-80EB-77586B9A88D4
[ThaliCore] Browser.st,artListening
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9CE7BA5A-7BAA-4433-9A1E-9B0CB4C8E456", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,9CE7BA5A-7BAA-4433-9A1E-9B0CB4C8E456
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9CE7BA5A-7BAA-4433-9A1E-9B0CB4C8E456
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-27 09:42:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:32 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:32 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper:, 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'listening 62366'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:35E4F6E9-4B10-432E-A4FD-B6DBC06084CD
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "32AD0066-5494-4A63-B267-16E6775B1CE1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:32AD0066-5494-4A63-B267-16E6775B1CE1
,2017-07-27 09:42:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-27 09:42:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:32AD0066-5494-4A63-B267-16E6775B1CE1
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-27 09:42:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:33 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:33 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'listening 62368'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9E4B4098-6D33-43F5-8609-6525D2D374CB
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "55ADB9E7-3E2C-408B-8099-F4999C06FAFB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:55ADB9E7-3E2C-408B-8099-F4999C06FAFB
2017-07-27 0,9:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:55ADB9E7-3E2C-408B-8099-F4999C06FAFB
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-27 09:42:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:34 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-27 09:42:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:35 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-27 09:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-27 09:42:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-27 09:42:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-27 09:42:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-27 09:42:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-27 09:42:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-27 09:42:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-27 09:42:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 62371'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:39B59F38-B86F-4B38-A992-8D59C9D7B36F
[ThaliCore] Browser.st,artListening
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 266 discoveryActive matches
ok 267 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
2017-07-27 09:42:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 62372'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2F6ABA5F-156E-448D-B743-D3AE1D1CCDE8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2F6ABA5F-156E-448D-B743-D3AE1D1CCDE8
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2F6ABA5F-156E-448D-B743-D3AE1D1CCDE8
2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:42:38 - DEBUG thaliMobileNativeWrapper: 'listening 62374'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'listening 62375'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D75F277-ADCE-4E1F-83EE-0EE720500681
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96", generation: 0)
[ThaliCore] Adverti,ser.startAdvertising with peerID:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96
2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-27 09:42:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[,ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerI,dentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}]'
2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","genera,t,ion":0}'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}]'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-07-27 09:42:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:51E3490C-3571-426B-910E-CC3E35165F7B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "51E3490C-3571-426B-910E-CC3E35165F7B", generation: 0)
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}]'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
2017-07-27 09:42:40 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}]'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:42:40 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:97FE6EC2-0DDE-484B-ACE5-65BE1FA4CA96
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-27 09:42:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:40 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-27 09:42:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-27 09:42:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-27 09:42:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-27 09:42:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:42 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'listening 62377'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:273CA323-F42B-40C3-89D9-73B6D8E9BE06
,[ThaliCore] Browser.startListening
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:327545E6-9804-4ADB-A8DA-5253B0B8EB0E
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-27 09:42:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:51E3490C-3571-426B-910E-CC3E35165F7B:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "51E3490C-3571-426B-910E-CC3E35165F7B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", gene,ration: 0)
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}]'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}]'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}]'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1AD4E328-1AC8-42F2-840E-E312222887D5 (syncValue: u8rbyyQTgrFgZmS55Ya98hlBDW2crfKs)'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A,D4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:42:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}]'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:42:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:42:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:327545E6-9804-4ADB-A8DA-5253B0B8EB0E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
2017-07-27 09:42:43 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}]'
2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}'
,2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:42:44 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-27 09:42:44 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F26BEBDA-8461-458A-80B4-5C81D72A6F32:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F26BEBDA-8461-458A-80B4-5C81D72A6F32", generation: 0)
2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}]'
2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","generation":0}'
,2017-07-27 09:42:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-27 09:42:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F26BEBDA-8461-458A-80B4-5C81D72A6F32","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,D4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:51E3490C-3571-426B-910E-CC3E35165F7B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "51E3490C-3571-426B-910E-CC3E35165F7B", generation: 0)
2017-07-27 09:42:46 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}]'
2017-07-27 09:42:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","generation":0}'
,2017-07-27 09:42:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-27 09:42:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51E3490C-3571-426B-910E-CC3E35165F7B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1AD4E328-1AC8-42F2,-840E-E312222887D5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
2017-07-27 09:42:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peer,Available":false,"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","generation":0}]'
2017-07-27 09:42:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"1AD4E328-1AC8-42F2-84,0,E-E312222887D5","generation":0}'
,2017-07-27 09:42:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-27 09:42:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1AD4E328-1AC8-42F2-840E-E312222887D5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1A,D4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1AD4E328-1AC8-42F2-840E-E312222887D5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:42:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u8rbyyQTgrFgZmS55Ya98hlBDW2crfKs","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:42:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'u8rbyyQTgrFgZmS55Ya98hlBDW2crfKs', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:42:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:42:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0ECECFD-99D4-4837-84C7-C4E68676530E (syncValue: H6S9Q5EmYxmUUYlasBgDUqUHR0HkP9iK)'
2017-07-27 09:42:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0ECECFD-99D4-4837-84C7-C4E68,676530E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1AD4E328-1AC8-42F2-840E-E312222887D5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
[ThaliCore] Advertiser: session connected Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,2017-07-27 09:42:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}]'
,2017-07-27 09:42:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","generation":0}'
,2017-07-27 09:42:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:42:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E0ECECFD-99D4-4837-84C7-C4E68676530E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
,[ThaliCore] Session.session(_:peer:didChange:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0ECECFD-99D4-4837-84C7-C4E68676530E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:42:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H6S9Q5EmYxmUUYlasBgDUqUHR0HkP9iK","error":"Peer is unavailable",,"portNumber":null}'
2017-07-27 09:42:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'H6S9Q5EmYxmUUYlasBgDUqUHR0HkP9iK', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-27 09:42:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-27 09:42:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6ECF630A-A1AB-4826-8FC0-E527CADCE577 (syncValue: R1fjJmnMmHYY0EZMqyD2ukz,wqlHYqkyW)'
2017-07-27 09:42:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6ECF630A-A1AB-4826-8FC0-E527C,ADCE577:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0ECECFD-99D4-4837-84C7-C4E68676530E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
[ThaliCore] Session.startOutputStream(with:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 2, 11, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0 state: notConnected -> connecting
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62386
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R1fjJmnMmHYY0EZMqyD2ukzwqlHYqkyW","error":null,"portNumber":62386}'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'R1fjJmnMmHYY0EZMqyD2ukzwqlHYqkyW', error: 'null', listeningPort: '62386''
,2017-07-27 09:42:54 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 2, 11, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:42:54 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:42:54 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:327545E6-9804-4ADB-A8DA-5253B0B8EB0E
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] Virt,ualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [1, 2, 11, 15]
,ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62386
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [1, 2, 11]
,[ThaliCore] Session.disconnect() peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-27 09:42:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R1fjJmnMmHYY0EZMqyD2ukzwqlHYqkyW","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:73929F52-4D39-4C39-A307-4B21AE2B67D2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "327545E6-9804-4ADB-A8DA-5253B0B8EB0E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:73929F52-4D39-4C39-A307-4B21AE2B67D2
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-27 09:42:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-27 09:42:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-27 09:42:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-27 09:42:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-27 09:42:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-27 09:42:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-27 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:42:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 62388'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 62389'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:57F3F7CB-36E4-44D2-A5ED-52BB5BA1F1C2
[ThaliCore] Browser.st,artListening
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 304 error should be null
ok 305 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateU,pdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advert,isingActive":false}'
2017-07-27 09:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'listening 62390'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8FAB9757-414E-4321-8342-A236457115B5", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:8FAB9757-414E-4321-8342-A236457115B5
2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8FAB9757-414E-4321-8342-A236457115B5", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:8FAB9757-414E-4321-8342-A236457115B5
,2017-07-27 09:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8FAB9757-414E-4321-8342-A236457115B5
[ThaliCore] Advertiser.stopAdvertising() peerID:8FAB9757-414E-4321-8342-A236457115B5
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
,ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'listening 62393'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 318 error should be null
ok 319 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
ok 320 error should be null
ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:42:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:42:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-27 09:42:58 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'listening 62394'
,ok 330 first call should succeed
,ok 331 first call should succeed
,ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:42:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:42:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:42:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-27 09:42:59 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-27 09:42:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-27 09:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07a3569a-f366-4165-b4b3-2c8539944db2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 342 should be calle,d once
ok 343 should not have been called more than once
,# teardown
,2017-07-27 09:42:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"07a3569a-f366-4165-b4b3-2c8539944db2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
2017-07-27 09:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b659cee6-2dd0-4023-9aee-76056c916cb2","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 352 peer should be available
ok 353 cache contains native peer
2017-07-27 09:43:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b659cee6-2dd0-4023-9aee-76056c916cb2","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 354 peer should be unavailable
ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"db969bd8-2ba5-40f0-995b-d93143ab255b","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"db969bd8-2ba5-40f0-995b-d93143ab255b","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 362 peer should be unavailable
ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c1a2191d-8125-4a0a-8a57-c52bb933a794","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 367 first peer is a,vailable
2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3b8860bf-8e7c-43dd-b1d1-3a575bed4ac0","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 second, peer is available
ok 369 first and second peers are different
,# teardown
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c1a2191d-8125-4a0a-8a57-c52bb933a794","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3b8860bf-8e7c-43dd-b1d1-3a575bed4ac0","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97329103-8891-4f67-843d-a8ac4c230e61","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-07-27 09:43:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"97329103-8891-4f67-843d-a8ac4c230e61","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-27 09:43:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
,ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-27 09:43:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22d3b03f-87f5-4a39-a2e3-94400b3c3ce0","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 384 peer should be available
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22d3b03f-87f5-4a39-a2e3-94400b3c3ce0","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be ,available
ok 386 should store correct generation
,# teardown
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"22d3b03f-87f5-4a39-a2e3-94400b3c3ce0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-27 09:43:02 - DEBUG thaliMobileNativeWrapper: 'listening 62395'
2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d04d3f01-d228-42f9-8f09-ae9b397d1508","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-07-27 09:43:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d04d3f01-d228-42f9-8f09-ae9b397d1508","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 392 discovered corr,ect peer
ok 393 got correct generation
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d04d3f01-d228-42f9-8f09-ae9b397d1508","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:03 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'listening 62396'
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1cc23a9c-f381-42fe-b35b-15815cb1f6a4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 397 discovered available peer
ok 398 peer is available
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1cc23a9c-f381-42fe-b35b-15815cb1f6a4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b6677409-0730-4035-a8f4-445387fb16c0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b6677409-0730-4035-a8f4-445387fb16c0","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 403 peer should be unavailable
ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'listening 62397'
2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"335ba1c4-3273-4db9-b888-e901f4924b42","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 408 first peer is expected to be available
2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6be8b91-b525-44f7-a4c2-3350f97c21ac","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 second peer is expected to be available
2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a6be8b91-b525-,44f7-a4c2-3350f97c21ac","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 410 peer became unavailable
,ok 411 it was wifi peer
2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6be8b91-b525-44f7-a4c2-3350f97c21ac","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 412 we found peer again
ok 413 it was wifi peer
2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a6be8b91-b525-44f7-a4c2-3350f97c21ac","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
ok 414 peer became unavailable
ok 415 it was wifi peer
,# teardown
,2017-07-27 09:43:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"335ba1c4-3273-4db9-b888-e901f4924b42","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:43:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-27 09:43:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'listening 62398'
2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93622f43-c51c-44f8-909e-28fcd30aa022","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 422 first peer is expected to be available
2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0191bdfb-dbab-4307-a278-50f9ddd6ae9e","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 423 second peer is expected to be available
,2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"93622f43-c51c-44f8-909e-28fcd30aa022","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 424 pee,r became unavailable
2017-07-27 09:43:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0191bdfb-dbab-4307-a278-50f9ddd6ae9e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:04 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-27 09:43:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-27 09:43:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b83100c-adae-471d-b0c8-e5cf06f3e431","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 435 peer discovered first time does not have new address
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b83100c-adae-471d-b0c8-e5cf06f3e431","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
ok 436 address has not been changed
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b83100c-adae-471d-b0c8-e5cf06f3e431","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 437 new port handled correctly
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b83100c-adae-471d-b0c8-e5cf06f3e431","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 438 new host handled correctly
2017-07-27 09:43:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b83100c-adae-471d-b0c8-e5cf06f3e431","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-27 09:43:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-27 09:43:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-27 09:43:06 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 460 contains expected properties
ok 461 the same ho,stAddress
ok 462 the same portNumber
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-27 09:43:07 - DEBUG thaliMobileNativeWrapper: 'listening 62400'
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0683bf2b-5903-4f26-9ad6-875445ef98d5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-07-27 09:43:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0683bf2b-5903-4f26-9ad6-875445ef98d5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'listening 62401'
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5186b670-eafc-4193-b1ab-a066f1c12b79","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:5186b670-eafc-4193-b1ab-a066f1c12b79
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-27 09:43:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5186b670-eafc-4193-b1ab-a066f1c12b79","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-27 09:43:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-27 09:43:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
,ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-27 09:43:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-27 09:43:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'listening 62402'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DE9963C-F7BD-42DD-9BB2-3ED51DE21723
,[ThaliCore] Browser.startListening
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"40e7f26b-c8eb-4891-816a-6ea67b4b5f6b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bd1f89f9-9539-46f7-b44a-10d013f12c02","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"40e7f26b-c8eb-4891-816a-6ea67b4b5f6b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-27 09:43:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bd1f89f9-9539-46f7-b44a-10d013f12c02","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-27 09:43:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-27 09:43:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:43:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'listening 62403'
2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a459239f-bf7c-4a58-818d-00134b32fc07","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1948efdb-807a-48af-b3c3-24005c341abd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-27 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a459239f-bf7c-4a58-818d-00134b32fc07","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:43:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1948efdb-807a-48af-b3c3-24005c341abd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:11 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-27 09:43:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-27 09:43:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-27 09:43:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'listening 62404'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7,A5D25F38D1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1
2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D1E5492-0160-40AE-945C-BAF01CA6A32C
[ThaliCore] Browser.startLi,stening
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"97AC027D-E887-4A31-,AA7D-B254708661C6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 97AC027D-E887-4A31-AA7D-B254708661C6 (syncValue: 0)'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}]'
2017-07-27 09:43:12 - DEBUG thaliMob,ileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}]'
2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","generation":0}'
,2017-07-27 09:43:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-27 09:43:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"97AC027D-E887-4A31-AA7D-B254708661C6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","generation":0}]'
2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}]'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","generation":0}'
,2017-07-27 09:43:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:43:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:97AC027D-E887-4A31-AA7D-B254708661C6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,7AC027D-E887-4A31-AA7D-B254708661C6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "97AC027D-E887-4A31-AA7D-B254708661C6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6ECF630A-A1AB-4826-8FC0-E527CADCE577 (syncValue: 1)'
2017-07-27 09:43:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:97AC027D-E887-4A31-AA7D-B254708661C6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
[ThaliCore] Advertiser: session connected Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,2017-07-27 09:43:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}]'
,2017-07-27 09:43:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","generation":0}'
,2017-07-27 09:43:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-27 09:43:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6ECF630A-A1AB-4826-8FC0-E527CADCE577","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,CF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6ECF630A-A1AB-4826-8FC0-E527CADCE577", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-27 09:43:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
,2017-07-27 09:43:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7855F8AD-79AD-4F93-83C6-37C069A6A92D (syncValue: 2)'
2017-07-27 09:43:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78,55F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6ECF630A-A1AB-4826-8FC0-E527CADCE577:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
[ThaliCore] Advertiser: session connected Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] Session.startOutputStream(with:) peer:1F3359D3-43B0-42AE-8758-97201BCDFBF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 2, 11, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7855F8AD-79AD-4F93-83C6-37C069A6A92D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62413
2017-07-27 09:43:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":62413,}'
,2017-07-27 09:43:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 3630E379-CFFE-462E-BB68-4CD97BA5BD0F (syncValue: 3)'
2017-07-27 09:43:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7855F8AD-79AD-4F93-83C6-37C069A6A92D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 2, 11, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:43:21 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:21 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
,[ThaliCore] Session.session(_:peer:didChange:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
[ThaliCore] Session.startOutputStream(with:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 2, 11, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62418
2017-07-27 09:43:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":62418,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 2, 11, 16, 17, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:43:23 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:24 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,2017-07-27 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7855F8AD-79AD-4F93-83C6-37C069A6A92D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-27, 09:43:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3630E379-CFFE-462E-BB68-4CD97BA5BD0F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F1A16AEB-67F5-4902-8B82-F7A5D25F38D1
,2017-07-27 09:43:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-27 09:43:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-27 09:43:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-27 09:43:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-27 09:43:24 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-27 09:43:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:,O,ptional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 525 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false s,ocket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
ok 526 error should be null
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Ad,vertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:,18
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 2, 11, 17, 18, 19]
# setup
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [1, 2, 11, 17, 19]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [1, 2, 11, 19]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSoc,ketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F1A16AEB-67F5-4902-8B82-F7A5D25F38D1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:9248DDDB-0E5D-42E6-BB2F-BC9180CF3396
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-27 09:43:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
ok 531 getConnectionType
ok 532 getActionType
,ok 533 getActionState
ok 534 getPskIdentity
ok 535 getPskKey
,# teardown
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[Th,aliCore] VirtualSocket.deinit vsID:19 [1, 2, 11]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
,# #testThaliPeerAction - start and kill
,ok 536 initial state
,ok 537 after start
,2017-07-27 09:43:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-27 09:43:34 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 clean kill
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
,ok 544 agent's destroy should be called
,ok 545 agent's destroy should not be called again
,ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
,ok 548 Entry exists
,ok 549 Size must be 1
,ok 550 Entry counter must be 2
,ok 551 Entry exists
,ok 552 Size must be 2
,ok 553 Entry counter must be 1
,ok 554 Entry exists
,ok 555 Size must be 3
,ok 556 Entry counter must be 2
,ok 557 Entry exists
,ok 558 Size must be 4
,ok 559 Entry 1_1 should not be found
,ok 560 Entry 1_1 does not exist
,ok 561 Size must be 3
,ok 562 Entry 1_2 should not be found
,ok 563 Entry 1_2 does not exist
,ok 564 Size must be 2
,ok 565 should be equal
,ok 566 Entry 2_1 should not be found
,ok 567 Entry 2_2 should not be found
,ok 568 Entry 2_1 does not exist
,ok 569 Entry 2_2 does not exist
,ok 570 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 571 Size must be100
,ok 572 Entries between 20 and MAXSIZE + 20 should exist
,ok 573 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 574 Entries between 6 and MAXSIZE + 4 should exist
,ok 575 Size should be MAXSIZE
ok 576 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 577 WAITING state entry should not be removed
,ok 578 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 581 Kill should be called once
,ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
ok 584 enqueue is fine
ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
,ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
ok 593 good enqueue
,ok 594 Identity should match
,2017-07-27 09:43:38 - DEBUG testUtils: 'Got response data'
,2017-07-27 09:43:38 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-27 09:43:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
ok 598 enqueue worked
,ok 599 is an agent
ok 600 enqueue 2 worked
ok 601 enqueue is not available when stopped
ok 602 start action is killed
ok 603 killed action is still killed
ok 604 enqueued action when stopped is killed
ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
,ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
ok 610 wrong arg type
ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
,ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
,ok 615 2nd good enqueue
ok 616 we are in the pool
ok 617 We are out of the pool
ok 618 Action was killed
ok 619 The original kill was called too
ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
ok 625 2nd good enqueue
ok 626 1st action is in the pool
ok 627 2nd action is in the pool
ok 628 1st action is out of the pool
ok 629 2st action is out of the pool
ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-27 09:43:42 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
,ok 632 Start should not be called
,ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:43 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 637 Got null
2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 638 is an agent
2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 640 Got Null
ok 641 Got another null
2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 642 is an agent
2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
,2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 643 is an agent
2017-07-27 09:43:43 - DEBUG thaliPeerPoolOneAtATime: 'acti,on returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
ok 647 should have gotten null
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activit,y time out - noActivityTimeOut'
ok 648 Should have stopped nicely
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startErr,or: eeeek! - failureButNotAvailable'
ok 649 Still looking for null
,2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-07-27 09:43:44 - DEBUG thaliPee,rPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone,!'
2017-07-27 09:43:44 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 650 Yup, another null
ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 652 Null 1
ok 653 (unnamed assert)
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 654 is an agent
ok 655 Null 3
ok 656 Replication not yet called
ok 657 Notification 2 not yet called
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 658 is an agent
ok 659 Notification went first
ok 660 Notification 2 not called yet
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action, ,Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action ,Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 664 is an agent
ok 665 First does not throw
2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'Action ,Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 666 is an agent
,ok 667 Second does not throw
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-27 09:43:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 668 is an agent
ok ,669 first ok
2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 670 is an agent
ok 671 second ok
ok 672 third ok
,2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-27 09:43:46 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-27 09:43:46 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-27 09:43:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-27 09:43:46 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-07-27 09:43:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-27 09:43:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-27 09:43:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-27 09:43:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
,ok 684 correct error message
,# teardown
,2017-07-27 09:43:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-27 09:43:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
ok 689 Start after killed
,# teardown
,2017-07-27 09:43:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-07-27 09:43:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-27 09:43:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-07-27 09:43:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-27 09:43:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-27 09:43:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
ok 701 ecdh for local device cannot be null
ok 702 milliseconds cannot be less than 0
ok 703 milliseconds cannot be 0
,ok 704 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 705 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 706 should be equal
,ok 707 should be equal
ok 708 (unnamed assert)
,ok 709 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 710 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 711 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 712 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 713 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 714 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 715 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-27 09:44:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
,ok 720 good preAmble
ok 721 good unencryptedKeyId
,ok 722 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 723 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 724 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 725 Matching numbers
,ok 726 We have an entry!
,ok 727 keys match
,ok 728 secrets match
,ok 729 We have an entry!
ok 730 keys match
,ok 731 secrets match
,ok 732 We have an entry!
,ok 733 keys match
,ok 734 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 735 Streams have same length
,ok 736 matching size
ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 739 should be equal
,ok 740 peerDictionalty contains 2 peers
,ok 741 bluetooth peer's notification has correct connection type
,ok 742 tcp peer's notification has correct connection type
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-27 09:44:08 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-27 09:44:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
2017-07-27 09:44:09 - WARN thaliNotificationClient: 'peer is not available'
ok 744 notification peer dictionary does not contain any peers
2017-07-27 09:44:09 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-27 09:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-07-27 09:44:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-27 09:44:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-27 09:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-27 09:44:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-27 09:44:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-27 09:44:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
ok 764 correct number of requests
ok 765 correct number of failures
ok 766 correct final peer state
,# teardown
,2017-07-27 09:44:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-27 09:44:16 - WARN thaliNotificationClient: 'peer is not available'
2017-07-27 09:44:16 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-07-27 09:44:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-27 09:44:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
,ok 769 peer state should be RESOLVED
,# teardown
,2017-07-27 09:44:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-27 09:44:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
,# teardown
,2017-07-27 09:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
ok 774 hostAddress must match
ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
ok 777 connectionType must match
,# teardown
,2017-07-27 09:44:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-27 09:44:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-27 09:44:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-27 09:44:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-27 09:44:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-27 09:44:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-27 09:44:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-27 09:44:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
,ok 796 should be 200
,ok 797 should be equal
ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-07-27 09:44:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-07-27 09:44:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
# teardown
,2017-07-27 09:44:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-27 09:44:27 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
2017-07-27 09:44:28 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
ok 812 first action kill called
,ok 813 second action kill called
ok 814 first cleared dictionary
ok 815 first cleared pool
ok 816 second cleared dictionary
ok 817 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 818 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-27 09:44:29 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 819 listener has been set
,ok 820 peer dictionary has expected number of entries
,ok 821 Dictionary and pool have same action
,ok 822 ads match
,ok 823 PouchDB matches
,ok 824 DB Names match
,ok 825 public keys match
,ok 826 peer dictionary has expected number of entries
,ok 827 Dictionary and pool have same action
,ok 828 ads match
,ok 829 PouchDB matches
,ok 830 DB Names match
,ok 831 public keys match
,2017-07-27 09:44:29 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
,ok 837 no entries left
,ok 838 Third action is dead
,ok 839 peer dictionary has expected number of entries
,ok 840 Dictionary and pool have same action
,ok 841 ads match
,ok 842 PouchDB matches
,ok 843 DB Names match
,ok 844 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-27 09:44:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-27 09:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-27 09:44:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-27 09:44:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-27 09:44:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-27 09:44:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-27 09:44:32 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-27 09:44:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-27 09:44:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-27 09:44:33 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:33 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
ok 851 All tests passed!
,# teardown
,2017-07-27 09:44:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-27 09:44:39 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:39 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-27 09:44:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-27 09:44:43 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-27 09:44:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-27 09:44:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-27 09:44:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-27 09:44:47 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:44:47 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-27 09:44:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-27 09:44:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 858 action should be killed
ok 859 Error should be timed out
,# teardown
,2017-07-27 09:44:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-27 09:44:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
ok 862 Same pouchdB
ok 863 same localDbName
ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-27 09:44:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'listening 62545'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A199F954-C675-4B5C-AE40-A799E390F491
,[ThaliCore] Browser.startListening
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3
,2017-07-27 09:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
2017-07-27 09:44:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","generation":0}]'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31FA610D-63B5-4DE0-AB0D-AEAF0401113A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 31FA610D-63B5-4DE0-AB0D-AEAF0401113A (syncValue: 4)'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Advertiser: session connected Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C07858DB-C444-45BD-90AB-9D83702F7366 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
2017-07-27 09:44:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","generation":0}]'
2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","generation":0}'
,2017-07-27 09:44:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-27 09:44:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4B93F383-00C0-458F-9A5F-89AA952BC1DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] Session.session(_:peer:didChange:) peer:C07858DB-C444-45BD-90AB-9D83702F7366 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "31FA610D-63B5-4DE0-AB0D-AEAF0401113A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62548
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":62548}'
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4B93F383-00C0-458F-9A5F-89AA952BC1DA (syncValue: 5)'
,2017-07-27 09:44:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 2, 11, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 2, 11, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 2, 11, 21]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [1, 2, 11, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [1, 2, 11, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-27 09:44:57 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [1, 2, 11, 21, 22, 23, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHand,ler
[ThaliCore] Session.session(_:peer:didChange:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [1, 2, 11, 21, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Advertiser: session connected Peer(uuid: "D0CC6B78-EA3C-4577-8A18-99D1E5BAC0A3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [1, 2, 11, 21, 22, 23, 24, 25, 26]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
,[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] Session.startOutputStream(with:) peer:C07858DB-C444-45BD-90AB-9D83702F7366
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,1 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 31]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31FA610D-63B5-4DE0-AB0D-AEAF0401113A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 32]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-27 09:44:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={N,SLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed,, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [1, 2, 11, 21, 22, 23, 24,, 25, 26, 27, 28, 30]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4B93F383-00C0-458F-9A5F-89AA952BC1DA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62564
2017-07-27 09:45:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":62564,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,4 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 34]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 34, 35]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 35]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [1, 2, 11, 21, 22, 23, 24, 25, 26, 27, 28, 30, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [1, 2, 11, 21, 22, 24, 25, 26, 27, 28, 30, 35, 36]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
,[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [1, 2, 11, 21, 22, 24, 26, 27, 28, 30, 35, 36]
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:27 [1, 2, 11, 21, 22, 24, 26, 28, 30, 35, 36]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [1, 2, 11, 21, 22, 24, 26, 30, 35, 36]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDid,Disconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-27 09:45:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain C,ode=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [1, 2, 11, 21, 24, 26, 30, 35, 36]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [1, 2, 11, 21, 26, 30, 35, 36]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [1, 2, 11, 21, 30, 35, 36]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [1, 2, 11, 21, 35, 36]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [1, 2, 11, 21, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [1, 2, 11, 21, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [1, 2, 11, 21, 35, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [1, 2, 11, 21, 35, 36, 37, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
[ThaliCore] Session.startOutputStream(with:) peer:52FA95C9-D5FD-4F7B-A51F-778176181EF1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [1, 2, 11, 21, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [1, 2, 11, 21, 35, 36, 37, 38, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B93F383-00C0-458F-9A5F-89AA952BC1DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [1, 2, 11, 21, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [1, 2, 11, 21, 35, 36, 37, 38, 39, 40, 41, 43]
,2017-07-27 09:45:02 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] TCPClient.socketDidDisconnect(_:withErro,r:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore], VirtualSocket.deinit vsID:36 [1, 2, 11, 21, 35, 37, 38, 39, 40, 41, 43]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore], VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:38 [1, 2, 11, 21, 35, 37, 39, 40, 41, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[,ThaliCore] VirtualSocket.deinit vsID:39 [1, 2, 11, 21, 35, 37, 40, 41, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,41
[ThaliCore] VirtualSocket.deinit vsID:41 [1, 2, 11, 21, 35, 37, 40, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCo,re] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-27 09:45:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-27 09:45:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] Virtua,lSocket.closeStreams() vsID:43
[ThaliCore] VirtualSocket.deinit vsID:35 [1, 2, 11, 21, 37, 40, 43]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.deinit vsID:37 [1, 2, 11, 21, 40, 43]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [1, 2, 11, 21, 43]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [1, 2, 11, 21]
,[ThaliCore] Session.session(_:peer:didChange:) peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:62418
[ThaliCore] Session.disconnect() peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3630E379-CFFE-462E-BB68-4CD97BA5BD0F", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,2017-07-27 09:45:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:3630E379-CFFE-462E-BB68-4CD97BA5BD0F:0
[ThaliCore] BrowserRelay.deinit
,2017-07-27 09:47:55 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-27 09:47:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:47:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:48:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:48:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:49:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:49:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:50:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:50:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:51:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:51:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:52:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:52:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:53:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:53:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:54:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-27 09:54:53 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-27 09:,54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-27 09:54:53 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-27 ,0,9:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBe,acons'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-27 09:54:53 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-27 09:54:53 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 865 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-27 09:55:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:55:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:55:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:56:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:56:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:57:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:57:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-27 09:58:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FE,C-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-27 09:58:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4,FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/65FA73EB-9C13-4FEC-A634-3D0FCAB11C26/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
