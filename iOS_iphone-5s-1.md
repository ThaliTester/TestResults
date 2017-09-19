#### Test 14182954130f6dc3_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/0A1F0163-19CB-4A32-A49F-CDE708294764/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0A1F0163-19CB-4A32-A49F-CDE708294764/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62708"
,(lldb)     command script import "/tmp/0A1F0163-19CB-4A32-A49F-CDE708294764/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
Process ARCH arm64
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:err,orHandler:) Peer(uuid: "27257B0D-BC77-4C60-B8CA-8AEF12919804", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:27257B0D-BC77-4C60-B8CA-8AEF12919804
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4E9F3971-508B-4313-8AE0-62F8FA16DF50
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:59CEE67D-,1FBA-4A70-9BED-02CE6352348B
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F5152AEE-DB32-4D33-95EF-F40C613505D0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F5152AEE-DB32-4D33-95EF-F40C613505D0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5152AEE-DB32-4D33-95EF-F40C613505D0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5152AEE-DB32-4D33-95EF-F40C613505D0", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-09-19 12:46:24 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.509710013866425
201,7-09-19 12:46:24 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-09-19 12:46:24 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F5152AEE-DB32-4D33-95EF-F40C613505D0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F5152AEE-DB32-4D33-95EF-F40C613505D0", generation: 0)
,2017-09-19 12:46:28 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-09-19 12:46:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-09-19 12:46:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-09-19 12:46:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-09-19 12:46:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-09-19 12:46:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-09-19 12:46:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-09-19 12:46:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-09-19 12:46:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-09-19 12:46:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-09-19 12:46:32 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-09-19 12:46:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:47:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:47:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:27 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-09-19 12:47:27 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-09-19 12:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-09-19 12:47:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-09-19 12:47:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-09-19 12:47:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-09-19 12:47:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-09-19 12:47:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-09-19 12:47:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-09-19 12:47:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
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
,2017-09-19 12:48:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-09-19 12:48:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-09-19 12:48:14 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
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
,ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-09-19 12:48:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-09-19 12:48:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:55DF5446-8713-4E96-83A8-2171259B058C
[ThaliCore] Browser.startListening
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B796945-73C7-4909-BBBA-4B8F8FB0A47E
[ThaliCore] Browser.startListening
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:23 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:48:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:27 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C07D91A-4BE5-4970-9270-06A318EE22B5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9C07D91A-4BE5-4970-9270-06A318EE22B5
2017-09-19 1,2:48:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9C07D91A-4BE5-4970-9270-06A318EE22B5
2017-09-19 12:48:27 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1C60D2F1-1F2E-49D6-8BB1-3EE8760EA939", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1C60D2F1-1F2E-49D6-8BB1-3EE8760EA939
2017-09-19 1,2:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1C60D2F1-1F2E-49D6-8BB1-3EE8760EA939", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:1C60D2F1-1F2E-49D6-8BB1-3EE8760EA939
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1C60D2F1-1F2E-49D6-8BB1-3EE8760EA939
,[ThaliCore] Advertiser.stopAdvertising() peerID:1C60D2F1-1F2E-49D6-8BB1-3EE8760EA939
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:90D276E0-9265-451E-B424-F09E6598D6BE
2017-09-19 1,2:48:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:99A28371-E117-4217-900B-5ED31F97A28B
[Thali,C,ore] Browser.startListening
2017-09-19 12:48:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:48:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:90D276E0-9265-451E-B424-F09E6598D6BE
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9FE7713F-E1CA-49E3-8F90-9C5C97270C09
2017-09-19 1,2:48:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC
[ThaliCore] Browser.startListening
2017-09-19 12:48:33 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:48:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
2017-09-19 12:48:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8C630424-8DA2-471A-94E5-D7030EA7C764","generation":0}'
2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8C630424-8DA2-471A-94E5-D7030EA7C764, (syncValue: 9hcAeswpEydhFapsAf2iKU1L5wuZn3EO)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD91,8", generation: 0)
2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F99EF8B7-1AD6-4A8B-9090-EC705C6AD918","generation":0}'
2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-,19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
2017-09-19 12:48:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF13A8A5-46A4-4EA6-9302-580CEBBE797A","generation":0}'
2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
2017-09-19 12:48:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"396621D0-FC75-4B94-8457-AEC9F0E309BF","generation":0}'
2017-09-19 12:48:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8C,630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9hcAeswpEydhFapsAf2iKU1L5wuZn3EO","error":"Peer is unavailable","portNumber":null}'
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9hcAeswpEydhFapsAf2iKU1L5wuZn3EO', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:48:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DF13A8A5-46A4-4EA6-9302-580CEBBE797A (syncValue: RrbIcNjDWrX8fI8iHmjTFohxiRMfUW7p)'
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:29346E8E-E1A2-49B6-896F-074F68A5135A
[ThaliCore] Advertiser: session connected Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:29346E8E-E1A2-49B6-896F-074F68A5135A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61423
2017-09-19 12:48:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RrbIcNjDWrX8fI8iHmjTFohxiRMfUW7p","error":null,"portNumber":61423}'
,2017-09-19 12:48:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RrbIcNjDWrX8fI8iHmjTFohxiRMfUW7p', error: 'null', listeningPort: '61423''
,2017-09-19 12:48:39 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:29346E8E-E1A2-49B6-896F-074F68A5135A
,[ThaliCore] Session.session(_:peer:didChange:) peer:29346E8E-E1A2-49B6-896F-074F68A5135A state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:29346E8E-E1A2-49B6-896F-074F68A5135A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:29346E8E-E1A2-49B6-896F-074F68A5135A
[ThaliCore] Advert,iserRelay.deinit
,2017-09-19 12:48:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:48:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9FE7713F-E1CA-49E3-8F90-9,C5C97270C09
2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61423
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RrbIcNjDWrX8fI8iHmjTFohxiRMfUW7p","error":"Session disconnected","portNumber":null}'
,# Can shift data
,[ThaliCore] Session.deinit peer:29346E8E-E1A2-49B6-896F-074F68A5135A
[ThaliCore] Session.deinit peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE
2017-09-19 1,2:48:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C70C581A-6F96-4146-A741-09B345570AC6
[Thal,i,Core] Browser.startListening
2017-09-19 12:48:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:48:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-09-19 12:48:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
2017-09-19 12:48:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"396621D0-FC75-4B94-8457-AEC9F0E309BF","generation":0}'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 396621D0-FC75-4B94-8457-AEC9F0E309BF, (syncValue: nk4bp8ElUfSJcnNfHvULhspNNH4y0VhF)'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E,309BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
2017-09-19 12:48:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF13A8A5-46A4-4EA6-9302-580CEBBE797A","generation":0}'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
2017-09-19 12:48:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDB7528A-6D5A-476F-989F-0B13DC545963","generation":0}'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C","generation":0}'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,6621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,96621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,6621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,96621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,6621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,96621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
[ThaliCore] Advertiser: session connected Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4,B94-8457-AEC9F0E309BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] Browser: session ,notConnected retry count #3 for Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF error: max retries exceeded
2017-09-1,9 12:48:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nk4bp8ElUfSJcnNfHvULhspNNH4y0VhF","error":"Connection could not be established","portNumber":null}'
2017-09-19 12:48:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nk4bp8ElUfSJcnNfHvULhspNNH4y0VhF', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:48:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-09-19 12:48:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DF13A8A5-46A4-4EA6-9302-580CEBBE797A (syncValue: SzYX8o7mDMXAECd1ieQe5ognIJVSOW5C)'
2017-09-19 12:48:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DF13,A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:48:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
,[ThaliCore] Session.startOutputStream(with:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:48:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-09-19 12:48:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-09-19 12:48:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-09-19 12:48:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DF,13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,F13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:48:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SzYX8o7mDMXAECd1ieQe5ognIJVSOW5C","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:48:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SzYX8o7mDMXAECd1ieQe5ognIJVSOW5C', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:48:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:48:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDB7528A-6D5A-476F-989F-0B13DC545963 (syncValue: owDACH3jHJGdCOBiwCXuw7x,2hjTVj7Rv)'
2017-09-19 12:48:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDB7528A-6D5A-476F-989F-0B13D,C545963:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:48:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61431
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"owDACH3jHJGdCOBiwCXuw7x2hjTVj7Rv","error":null,"portNumber":61431}'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'owDACH3jHJGdCOBiwCXuw7x2hjTVj7Rv', error: 'null', listeningPort: '61431''
,Connecting to the localhost:61431
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,Connected to the localhost:61431
,2017-09-19 12:48:59 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-09-19 12:48:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-09-19 12:48:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
2017-09-19 12:4,8:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:FDB7528A-6D5A-476F-989F-0B13DC545963
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61431
[ThaliCore] Session.disconnect() p,eer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
,[ThaliCore] Session.deinit peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C9FA9FBD-592F-44A9-BCC8-99C3A66B2463
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FA542401-F573-4621-9DBD-9F1F61CD325C
2017-09-19 1,2:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[Thal,iCore] Browser.startListening
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDB7528A-6D5A-476F-989F-0B13DC545963","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9788CAA8-E98E-4E3D,-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDB7528A-6D5A-476F-989F-0B13DC545963, (syncValue: V6eUtU4b75olCtoN2iZWAotqBT8WLfvn)'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C","generation":0}'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4FF4D8AD-7583-4E46-A0AE-07975F33B677","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09FDF337-6845-4807-9835-1630B55E626D","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,B7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,B7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"V6eUtU4b75olCtoN2iZWAotqBT8WLfvn","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'V6eUtU4b75olCtoN2iZWAotqBT8WLfvn', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C (syncValue: tzCzLOIkETrEp6xtl44GmnC,hpi8fjKfi)'
2017-09-19 12:49:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9788CAA8-E98E-4E3D-8BF2-43BDD,1B37C3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
[ThaliCore] Advertiser: session connected Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,88CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
,[ThaliCore] Session.session(_:peer:didChange:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
[ThaliCore] Session.startOutputStream(with:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [1, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
[ThaliCore] Session.startOutputStream(with:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
,[ThaliCore] Session.startOutputStream(with:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received all data: Kv7qglzMPrBQiNo9sQsNIa3vKg9ZVqvppNMPCICV9TXHteYy4OT8FnKMcB2CRwUi6ZQiOub7J2nvrUSGjBBrSagvzeUj8eCWtjLUCil277gun9ZO4g7L3im45tYTSWtG8SZ7qtKO1BNWGwtmNSpfXuX2iCkzRjgpFH0NxTE2K8VwB669hw,ZsmPFUFIIkYhoY43u6fBE6nM4OjAVPfsgfOxpZ3yfkDUli4ZZyNWXYHC3pghyzZgUC6eiUBmqpeoQl6vgV93Egc63pDeJ2cuv4KtdLBKJXbN2l8DP1s1RBC5EbfrjijiIaGY7LeULwfi4E2ZHVMnGxUBmwaZ3TsSHnn6f3Z2feWEhghtdy1tlm4cO0sZjALzbJbJeX1HBeNBKYZIwZBf2eWt0NzvcqXcToaxle1m9xu4TS8RHpm25Ez8IEUHMbIy,Jiq218UkqiPrHFA45rfwiBIn1vp44xVT3TDLe35NmF1rTcTWDrIReGHphFbiMM6S97ZKxZBkMToK9OTLdOGzgmc5JA8e96Ygu0l7F5DLzuHnWXiNm7NsA0opLJJSytE0GanpovuSluSBc3SdRI5r0nOeoayIYkPJlJJf4GAlR6Bfrc4DOrrvuOpZzALzNPrR1OAc2RMHjuNz7n7HGhL8WQyZP40TV14F5T39T1ia7nkwu1bQyg7nsn58ecGe9pHS,fdmqK7OE7VlPCWmtr1YkLBkglDYjvjtxsPAPfbQj1on0Na8i5eLMSGysduK9OzIaETMKjcWsxesCwhSkBuGegwDak34zN19oSiNGOBAZBsXEHKLGU44SLNmUVMMmy7SzbCI0FWqZPQni8okV6apnCfazRlwIbHf9YvPP5jMCwrbaHZYUGtOoErlNjkkXzqJXZ4vRHUnAbLZUeWjdZ0tLQjNsGatjXAIsmgG1o1Q6PQCIfPlAXXQrkQ7C18UsVgmr,hb88Th981AH8Osk4RYDX5OifvElv1mi1MrUaYpxIGKwDuJhJptQxKbjWs8YclfJmUT4raZa3eQVxu8M11BnBqvM5pYWW6xdfgaaqC6cCnIqG3CN8fElhd7PCZk9FkqV90E9H9OpEeAjkydWU3T7h4BLZVIfptBsJ2c1kjvuSPHEglNzlhUzRFSIH45md6FKc48eD2vwY8XaDJERfKOP8vVd19jgB61Uhl6UtCSJzv0wivfE9gH8LpxsNORkrVbCg,u8xSiy9Pc43slesfMtPJ9d0HMZyJapIJr4YbDyfNZa1cu9V3i1YBOBIq6dT5oYeKeoW6DskgHLPyy7jkLiAoGNjeouNbnKA6W7gLKBUUcFySoRnCoeEFE9T63kvO3udiNSoHGQZVid2CDogSCtkvJpbBGdEYV0yEeZ1eXcpP7WCm60Ng9VjjxuKnbOEV5xptooakobrtjeBPOX1kuaOQkfvzniLJFLmHd25UpDmxnkGukvNUVB6iaBDYrjQ0cVXJ,PAIFJSpxP8WHIJELyLjbSuw8TdBuzp2B3CEFWdt6whJ9gzQ2KH0YAAjVAnPEedPZzmyEaEUjLax8km6SlJC6iKLsx0W8BduNsxlAabUesiH0Lfy6er1dOvEuVNP1Zv4jczVwkND9XIgMoihI61hWznObna9BOK6GnmS4TnVVUNhtHzEsrEa84Yt8svcLZ1IJY4z5H2L3c8Zm5qWDZD2bbDS6gXExvtkvfCAi8ABFgE8glGc60au9QM0RNrWyl4QR,er1ykHockvRzshNWpHaZJr2GceWkWHoLr1ZeKo4f5sPZDGC5Qlq0pSKlONeJ9nTAiuaXn2BGmbbbRGCqZt8Qxfecd6xXrtXDM4WldI0jVwG0kjFpZvg7DwOfNPqv4pJ8c26BGiNHljrYdYj7E1qMuzh52QbNfOZCHsT7DC3ZW8FiP7oZZTfCvI0n3JZoBMtHVqq326l1QVluBbcfiyt98u71mjB40gCFFMjr3vFBGhnp18uwHQHj2NKWcdutl0Fy,cN0uuGnlib6ls3oPEFDgqQWCmOrSSY2adGocuSd31whvNjYnwT7JjA8BXgH9qzqB2S775cUa0AuVrYtBavpYctuvgOG2LqJZHBZZnRgbogzCKIHRD1zhl99rDGnP40ZHTbvcVrQOkN2KyY3zKt6nqLC7FiUsOyIg9p3OB8L2DGqEJyZQwNuufi0Wfo2Os0iZpsYvmKlWyXiuv7o6GF2t3eVYqCCsL0CQpKNhXt4RanEUwRL8u3h4ci6yie62MWgn,l6LwQBokxl3SMpBI1TVNsgyQoXtKPXv4ZjNkCgpI0w81M9WbtI1csLOqRc2jsedosSIOT2y7Q6Osd62wY4J0Df16Kpx50TkCDNHW0y2oo2Vc6Vb3gZ1pjMX8ZbRHc29DxedC9SqJ9LBxwjM6TZ27yuwgjSzDcOAHJgppNkAgMvxSNgRLzjp423H5UX5kcXCq5bWdXqKMbZ4n12suZmr5RNt4hSlqX5FzGKcBsUicSKIAyWt4UhLdLRcXjOLwKwF0,gzs3mAnZYZs6iZFIYoi8sbqjESMp0sbhdMSHcHQfYAlUkrxdyDZpu4f0BmkAfqk8zU9ifrXBtkuwAd3DOZ0EVHETBES8EXR8dHfiMlhofjEWEueUGLI86YwN0QdOipCsbIvYjg2KWZtHmRtoWV3Mvdf4fNUcrPKnb7FBnIdBviYDiiIVOdmJ60wvSqgoY7EsnrgdTy3eGQjvD5iYgSFldo3QnJTxZDh4PLQZhaE9CzkcOlOtDgwOInWE42RbqWai,bbXVX6oQvXh1Sxq4S2YHrgeI8bdpJ2dVrAmDTXtLJwoldOZ4Der01fYXAsK7B8rXlXB7xhWcKVWMywKuS8ySf7EruIvKBF15MW60xyOgl0wUBjO3vkXH8C1TZATc3ZiOmzMwmvEAWSGuHMLNk2uP9sDhrO5ESKouLHkMrYkpsxD3YEzjB8NJqz70Vpv6Dnckg4pU4a1h67ueOqT5bR5iyRMi8w7QtECGY6oSVkgjngu0zqsdySARu0HPAhdaHhZI,0KCLR0sFflZPLPaFfzLQA2XrY7CH67FN3mk4ky2dOXRiz9gFUiPedJ4K0osfnqsuOXTlbD0obCHnPn0DQW8RNEBstvL9AugGQob4fCUKegplnrM8au3XJvlVMe4alVkHdzFTJmUcnkTdzhnn05mxVqlkcKbzxIy481NefRdrK6p7UEmJAxZHL9NM2rZiXO7SwzD4LcBgexBJh8txJmhWhGZVMYHbYdzXiAkhQow5ha89QwXzx6c1cnVlVNwY3Jck,g8vqwn0lVEqSCjgU2qp8zga3EA3lDagSgQ0TLHDxmimCOOIEb6twg3GCUJ9WmchHQrSEdcgoSekgaqcvZynHvqd9iiZnkDwgltCjwe03ucss2ykSRgnkWwJsFhZ9HkX9QGMLxIusAUL1r8N7zCBKSAdTAEQJu7Vq0DCnD8pKKQNMJNOiXRik5xLVU6rffcM0RcOlcSbczd3WmjJaZs0ITb3SiXgkaw1c8H6WifK1lE7LOa4IMLJOZm7ehOzktcbG,6xa74Wk3DJJPF6hHp9JVsHsdVmFozbFG4E02Zglbbi9ULiEdXY2gyAsnVnCbI88vRlBihGicEeh1fguLho2ch5W4zWVH7sB9ymYL9BRDMIQfdYjLGwTmJpPx8V5VggFRymj0U74n0W0V5wrc2ZHkepPXALMJSy4p3bZzLLGqUF8KXpycCZymwCknjf5sdI7uEDcEy4IhyoF3slbjFKqtrzVoAy8vrBhTjmS5DrWz3DZSSgKKUXCJh22Ax3zYoShH,x91iHAbFDWsZ9QfnWlxXjT5O2N4SeuOgbhCVUsPMVjRo011nZAz2lB3Mzqf20d8CQVS6WxubE1MdLGKuxt7Lz2JJ8GdoYmjABH9ItLHbOPftmAJfJCIeX49wX2IGyt3b5DxKiv1KIpIfz9plp65ULfyYHfIrvpeZZMVBOvzILBuKvJrDROxA2cj0THqNozGKZoYmUDqg1BBZklTxPeIGeyoMP8DM7odEpcPuXwoEZOi3AJQg0jrxFHKEd7cLScbN,k8euifdNzKoA53hTCBBrX4BTiCPTrlQHjE7S3YpS3v2X8Ip8k8hIKUL3T7cbtxxNT0Xh0b8XMZ509xPrBZs7A973KpWOTa1JFfSXbzIxvcTEfCa2LAu21BeoQu5mOgRYqqrw2vvOKIQxoQZTmBcFvNKgRciHEjdr6XXG3mfOHoVX63MC0H3SNt0xiSmxxfm9LwLJ6EQ4lQLsdS2pWQidhxy1Iwe0oso6HBjN9y7Hf9V8u2wNlmoWKvtm5H0Ebfwq,BOG9n9LlYJ9V8qAaJtI3EPxegNJDLeCYiKkPd7P9Zd48NtYGKa5Rp4plrVb3o94OXmOcs3LWs1qj5zysSDoj7siJ4XY8nPHP24NJousV9qxKf4h0Ih1F437SAAK94EzOjFwv289RbhFTW3HdAcL7PuEny3h2iUYwxRyhwKlQJ3dN1ck2CVkCIVaMctABWJmpuylK1itwlVaBcWi1ko0UMhMRRAGT9TpGW2oB245lJok4UqWCFOVp99ST6tPCADmW,ZiHkusgIL0StEtjh0s9FTOJtGVLHQyXX1DflItRhZkVOnDJbcRDzRA4pQahPymYlz0mh8zMd8ly2ks6Ttgr6e7jkJQhj5TDAxKNNEh2fy3L1xxIin1LVkqIC8rJMinUPKG1pmHW91U7SzlA2DnsDE2ZwAfTJiHZw2eqK747f22Gv3TtSfkWb1YLLMcOBeqDSKldA2gtdqlw3KiDeOV6zYzpWbFqGd80vouWM4aCkcaRqaQZ2XIQ8G2qCmm6sm3ha,nG74hacOXEMDhDsKJgsjCEVJVqsuvFyxIHscqUHfR99CepiSMiXP4f0SXgVPdfxZv7XbfdWavRFopCPuBYUUcPl2NAN3vZMDrUcxs5PLUD2LVveP9J70phTMVLKRbLq9Cwxg7e6YWpiMe4qNFhT2JrRKbveo50ndyROHWywH0TAGSktvFDRPTeZPvSBKfDoUKyRb4uH358eH0A3XKq6NkeIAkc1pJmGRLquL9l52aaQa3czjDcd98qAVz22Sa0SY,l1ZAzSvXZOJ92iS7tr9w28t3QhM8vKZek0vp6GSX7KqAl9YfxUUX8DbfusGKfkOko4qTuqsxR3JSpe8WZEDogYpdbDwLjJWRTXXzK2DVpuuOtprWyyfhfLM9nqqRUtbjoKRzfWh8qULCHTaLqB5ZPGbO6ZglZm7TT2BDtcLL5uzqKna7xot9d52VseTROhyLySsyIbyCOj9Qrcvgh0Mzpfzp5ecumXYvjtkAgygw6i8bDMQsebSR74z4I4DmivOV,QGw6fvy77Oft6jE8dzYDMPmhiK317CQjbuwBI3iIGnWU6ZESc7l2kugxKWCSuZOdtU0eA3hLOBD0N82Ny9duX5MUXHdJve1FzYHbfTFM8STNhSijx7wvoWNUX9FgmysnIu6wbFtkSLH05J762gyGVgfesTFCFlpECg0kBSdaFrhXuK2byocyRZKmawxlvx2moK2c8IaNNHVqhnDFR6R4jCDmIrhtBkXDNuqsHwz3CYgqz7z9QXw1VCouhuensDsd,VbDlDgFjHLq0NtC5zZmdm2QcrOU65PDlWqiBXkoHGhvOEpbmi2Mp76ZhMo3iGMiQ05B4n7ng9hwBFiXuc8Qc1mL7uPQ0od7LH7nQo3Z00qP2kpLM6gjqaZ7NTeBqE1T47PorQ0idGTbOv7INcIRBclKZ66Zd1PviQ7nkLBzYNnEUmSub1bxxUqaHuO7BD5R4ELTRVw0vzNRi4oqUnk8Gr8kmSxD7trnL913KcIKm3jK7DnqBiADdJOGsu6rmsLSj,Dc9nCxgAR1APAwE95S21yi8XCBIAEOUq1ntf2dBMkSUYIwrHOLvCJec6bPgXHYOjsaKyO5BaC0kwUFkASObcjZgm6xi2GOTPl5qbG50FuGFvFB83qrrbA6rJMWXKttdsBs4Tu3pvm3UUIXlL3F9lVLYiegG2zcL3QMO2Xlp1MatDTz3iaFRSklf7k5KexI0yiK3KpHr2wNQBe7oJUUYZz4TyrupLRi7VeYBtTayyGZp9KZFayH5cP3OEKUi3cskf,C2K5Jshog8MBi40AZJvrn5i6ZY0l4vJ17YXDRu62J66A2hfHBX0a9Td8pSZywjfbUa120MrmBxwqBb1r2NAlylH7m0fGpTYR2Q5qbg2otbAWwJhHim2y4WTX9jDl29lVhg9uaIcSohlGDZVcAcugbAFiPh6LaFzGGsfyjHGkbDxnBe126UNLrssfBqAm1gG3ktbIgAz7pk5hTHkt9a66g7tlRyWD6S0lNEqzsno5Z3LJ6sYtHyGytWmqRrqazd5p,pvQdunyNHigvPACb215ov6dtGBntoPN6BtPgZU3AkcAHhTtB4Dkbsvkj1IGOYKjMDgX3wZEFmzW8zqA6ysLK5zWeJLkD65GJqXEHsHeu7pOCEH3l0Qfo3N1LguRx4esoEhFjljHD54g9iMVbcqgFUZnBPjLthSbbqukCsZ7g1WY4ellgBPzIys74WDJWA0XVtMmXA9YYp1Yn3DOOqUTvnqGuCpnLoFW7s5TI1jAmdzRqrceUjBX6tlLpJib1I82C,fYnTaMzmYnx7n15HyAiPIukpdYGEScnTv2BjG7eAxNkH84lCy1gQPq9sJxqwF700tBGEWvk8ZHBXS7hdtKyKxwEjw2btWFxM1AcfndjKWgEdx1aFOoW5gJf91cgjghVGPDmiF6UluPmyjQFzeT25vYbgPz8qfkOK6BCqCYHughptSYIU7MobH3yJsjsoMZ2crIedAVXW4kvUP6PrGwlBkETMMgWLcVhuceYgTtXcKlmspPNc5aHfVq1FKZ4caLka,PxG6yMAxvhzDTXXRGA94P4T4qwi7REb8kQrZISYsI7gsq4bgexAQg28eAB4nvmmpZX8Ip5FEK4QJysAqu1QwRj9xO7LZ0Gpxf5UZOCXStOFLdu9ty1RSZsha4JfxOTHpGEJfTSvcMpnXEHaNmbDBsv95HKPMlmidxC8bLOFzdWRVH2ksPeE7jkj9ZsJUsHHkYmyJUkW2GNHSkVaXbbLHrDe2GqZ2sRgdPIsaubk0ucaIvnaeTHfjg4I8AOjWp9IZ,Vj2anIT9GB0maFfL0i6DNieX1MywvitRDykKAaZxIVxN9B7w3IUQJVVgwvcdeEAtQ46q7QAgmGK5thrzLOSLv5V3LSTuCKVubYrmIcI7A8oLWpzu6la40BFYGMlfrettnhs6xVJERUqOTyDN3c13ZPtcXX3bP2iX2FEoeQ87ppLEDuojkCWVWMbfIvBODTctomQc0buOj73W2Mp51DUa8PCG2WmKXPliUrLHX7oCxaGF75AQ7sJFh4hkZtIKA17r,RNJD2Gt2NcBQ3m0FpiupmxuaiBy5CiqmjM7KUH5wbQCLp6pKMI7qSOpe9hiAJG9ixScwddokhIEVqv9cmDlGneLPRvkbJLBbpBt0WamwIl0HZAwuWjwBEASf5B4sohbH2XkBkSmKTvVNMxncHDgmGPN9bXX1mt9TzS6LOeY2JmAOEC8JtjvJLkHPXf3274cBtmyNtsC3JlOaqkJdCSMsQGOGuwszmpcS79AIUQEnA2pEmegoFNHZn9LFrhIfLPKs,sDaW3Zhfkaf4nt98RC9guWscBBgiVIAK96wVKUFuV6QSRUGq06FaG0JbUjrRt7HVDXth9LPEWJB9NSdCdgMi3yzJC7ilHkXLgFgDJ4R9lK4KrMA6bR0JquGK4UKyWTWbV0VkRvV7yNMIpXGF8f8OXdDS0kjL6WS1OoQN4ILGeKjIYqXqW2X6joFRfukhJGmzLu02g44PrgERLV9Gdm96hn8edXAB5rJEXacAxIG1gQwrIdJ8GEs9n2FualGBcxy5,LEHTOp1doHIXWe2SibbilB8nysFzkjNTHaNB63KcvSKr67jwtmh9M4JCRpC4sZBHZFTZra0up925WKtggJVZBsZmqcNvEr8qaqTGvBKJvW9cwWe7yUntQaohCEJ4NfcakTTnXMtjSTeSIpl9Bhqr32TLzYzkrDg4TLNJiURGnPmtPx6P41K9RxVm5y47fXPMCKrI9V9ZcMDnecOiINHwOjCiXREg3NpPSdcuNqM0wGWaP0XV4gCoVybqF7Lwb4kl,luB8grYxHX9E6Glzle3hmX5OulVu1L4zqIicLRT0owrSeOx6Ve4lJeKiGnSzCz0Omb20jFySqSchWBTli0DrPUt8iJ59A97Kq8Cv3KNA1kjTy0hf0hu7SFJ6CNP2oHhjAUGDT6z9rJewolao6BiQc69eGc5xKdFsKgK75TG9mSg7PlzvIYzvknUx9g6KyPNAeUeXhNc08h1A2X4pkJZFhmuZWujI0o8hOUqmLaDeDGbjXM2397N3MJ69HKN8MHOE,begHaTtJz1sz4xg31UWwe1qy459M24l6XlVQXdYV6qP2BKn3LTuNt88PDXJ2rTuyarhDWJar1yNI1xr6XW7sR0UQqHvJiEJZEJU47uIpKXvnV7ckCLSSVRZWYgDj5DVbq0YOeXpXAJUBMqEvsisncPKih7CBNfxHhXh2sTE0GkxKx2GYU6y5SZRyAV19jxUcUbUdGqDvB2jvsMYmuS4cDWEutowysAM3q34dmVA0MGM2ZDqDNB0aDXjHZ7cRKntj,M2lGn1R3DiTAD8bBFfBbN7bHg4M0ChFGjZ5XlWXP3FSDdFJ2II5camJbGNHuJOu3IhAWIFMBLf55ZgocjFcNhbjjtKQIWWV00ElEfPXIX8Q14L3UzfyHiQeuQeKqNvPpTH8FFsqhJQgCsm0x8OxARtot1eIZfR7MKNGZ19S8AL73sJ3daUcgF99QEWuuipLNpB5g58D5sskmSuB3YLvnDE9cmVXXMxvgDu7HX6tsBqSYtJmkgTKRUuUOqmNuepdt,8J3YUmkvHdvU7jcWC4xTrDwxqc2IKAUyPbn7i4F768cxyUDdtLBgr5YVCXteXvKc1W0Ur12fd89VN9theQew31pyavQVCbk562GJfuSlYhlDb6JfJagqzHqrm7q8G8aIDgGTmNprRMjQy1eNCNdJGiz4Xsc4Tq2dE0ZG3MP8wjvVMg3YRMUBfiu4JEIjfKGz51hAoF2krdIYzaqY3nRzElIasGjgHJSpIso8kHh2sYZUp8ypF3v8kTTbUKTnmKpD,NgxfzBub2HG7wMGD8HxfPDiEGfkO8oWcp58paUujJLkt4OIjy0Rn73peA8DhEF4Rz9CJu2bUpW73XKfOpptX1uaEw3N3bAF2XlHglGOdFksLqPC4mNY2ggtKgLK9VvfT60OInznW9BT8a9MPXoNUR2s5uSEtw0gCYhWMETATq1TzK56dvER1NPhKeDhxSdJ4tzrYbYjJuT38uwn0Z5YNmg0hYH2Yjbj17CuciipJS8hVuBak6kf4UoLhftfWVSo6,oGecTzVslS9FtcpEpZxAhCBSAtjIIbFXeSvwdSMtVCtv0vfjSMpSOTj6bSQxQ2OZSnRNnQfOfVN0A73ckHNmSjqrjr91OI9uPwDnBj4NlFxB5cRMnoNFBSH4sysgDYFQwDdBVv0k1O5tci9qiNzE8JH2tizVltfuzHBlXB8rMCZOlTRtA2hqcDwjFlq4pmu97kclOVRoOh84pL8Y2BFB5d1GwlylWuQ83fxbhxRhAV47JwBQtlvd7IOej2cHXPQu,s4iz4oVnm852OyuRjnyYKIhhZ3VrPQs1T3BMlDu4pL8y2VJf5Xcml7N7EkCL2AOB5BcnoAg7XXe39Wz7LbLMR76tiDvAOsFrJf7rDJt2XKR9zZEWeF1IOtOsQSMzgYbZLDm7eSekELgBlHH1ImzGyUc79ZBxuf1F83jO3Lrbo2xf4xo64AbOr64dqXGdJJP2youhmBqiUx3sxzTKZYJs5npWjzv0phozUCeB202MrdFUt1cJONAS0MjmDh8Dl8jD,vk0xuqY3PWguhxPmHwbaSpgaDemPAzpukUCa1NmV5R4GA0phF3jJgobxLOITy6eDeSsjg7IcbkQ11FFqrnKP7f7lDwUtSfWIKD3tp7n0CoEQ2LZNHLBhNNuLQ2QEwSdBLLD1T27mVyu18MyP7Fjjs2tbhj5dThsxg023s5KB2Cnj8IVhOeoS4hN7ndBeemiTTBDCmSeAE0BiTW34qEmlqluRHPnVwmeid2dxwKwFfJxCgM0NB2NoMWSdgkHusbXJ,NDDM66SXfbyJIJhQYMhHn1ahxJW8oeux8M6646TxYyvkJYOey1rm0PqLbLs7HlU8Vs6PcvuELi8Ge5K6Pg57JBF76lFj3trhcUW4UIL8Z7pdofeogpJGm85lEBCH2MxXBr9Nf2E8NI4gqYCJR0rBnut8aklDXHs5mpwZGjKUqVBwgnqoCL68J5QX3Zq9yFH6Tx2wyaRbYmut1f15bEqiTsYWt5AsrJLOm2CMPO98sIpU7hK8zNMCMSi2fNvzNE0V,G2ob6FT16qQjBLvunfe3WLspwRtDSbev6EsJwhOWgBtpkPMxRasRwC6pJh3bPqfR47IGPMRgyIFxuRwanN2n1DiBgtTLwaJLVOCKsiUICH6lkK73Pw0okgVDzy8rqZou6SoojEWJ7Lz2TpTYS0z27noIKvpyjm7E5iBfqfomCE45z7xAJJrVcK6unOUxsSIJNuTffk0K6XG2sCBKkg517fdiiEi6tUAM7QRg5WaH46vMx7OlRFhwoi6YRIlkZoOk,Tj9KlhZTm1N3MmTVIQY9xJrTj18rY0MMfJoV5AjIEjcY3h4TZ6TjTkihZvp16Ojrxkppxcpxh7fn7kJPwWOBHZf0v9FoXxBMC9xyeYlhb66wd9pMZ0uJk2CBTx2unxHfMEgLfkqh8GNVScF8gPv5ouVWHhzvMmSQoQCbKHe5SA038A6PbD3vx8vFMxGnZlxad85gBHQOsIfpAAC8f8kwP7Nv4aQmIyh3UTl32CYiN4uAzoAzZB5I7EIDhnRC1ox7,K3XfW2CFDx8fNeHR6PRnie5dyOwXtN8Lqb90I5IY8J61cGl3XtNwOJPocwmjpUHf4y0NFmfT8KV4R4PB9MfuAze6s386KGTxKzSIIBvr22jvP77IyoGj7gR8ArUxyyzGSrzcCjdqxq8Xq8iAjsaP3wXRrUwraU3SGFu0VwZc2QLcy6D2ZnEQ0pNb8Wg9vigiujYeRAFN5WSvujzIn8ft4EHmLoRcd6zo8eexJqX4mxLZXgKk6SGYUaWH1twKnLzs,a7FHMwMbcutWi8ilbBPLiycRDrWvP0lM81MFZhZe8xKEC8kTnqqjHQr08tNd9LtnVsEu7QpMzXiovG4uKnKzQN1GL1BGk043h8vrZR1Jo5i3e2x5rGdrPTtCVMG7zQe3CdC6Mwk3LpXxonWTAIuyFcAwWPePPLUVdUGoUOYK2YeZ3zkH3O89Ejx2aCm8jpFnbVEkgZ0B1zeKFgKFqTesP3WPfQtY9b5KgOFRK1n2GhfCZ4HqwiMzroZTbiogC5HB,9NS014fyxsT4qDIeQdscRwMkU4spCoRSfI64uw2YR8V5l753HdxyrZ2pYV1rCvnqO4OgCAGyJM69W4bOCr02m715bx9C9MKYuKF9TbAU5xvQZMKGE9z6YIFR5TigLoFiaVTbev6sBFzJDvwIEEsEIwy9w3h1Ct6J6oecW9eAAIlT4VoDB6haTKR2f9EZ8Ul15NatSzrRzdm6d1YIhk0AZo0Gg2sDsSzshcAYg7Uem0izNBTKW3GktnVXby5xq9PO,ps3PBbbXvNOn7i7MQa6JGTe12hLfaHAS5FGqTYKjAe2TiJkRbXp4Mlp08r02T53oTtCF69pDpnpkMtF4aLq4v2Qb4bQY2Y3nToH5HB8vKNR1OotHqClHDtG9srH93RfwygLnVRUCUT3bf9BqzxQKFxUzeVRt8MSQzt7ZfCKxrUbUzrNAWbvD74mjevn51SGJoMVBNsuYCXHI7oWojNtgARnFfLEG5xCfKHk4F6dcj1kXhz2Bq14znZylReic3oDX,89IiKajo2UbjLGkuDpKEQbsnSMDSM1dyDEwwxKEwtVnl7tHDByjY0GFtsWTp22zMucsMTZqrG6s7CzJCVFOLB1EcmlLUgijShiaSsCZHLs0ginFCmjq5RTE9db0aXUFZy2Jbv7ENwoH6PixOGaMQQHMA9D9OWWOvHwziXCzg3FKgB1bNgDRulZUbTuhOgXEAfg6whpacOtL38nxrw1MbNwqF6tyN4wNR8K1gzrVBUOxU7aFa5BJnfgBqjH8XRFIX,Y6BBZtXPDvcdE7olxPd9HB4qjNov0nKfQVx4VZaAE5096ECsOCkmADQiWaLlTPMqrrvBURv68JjLpMuunuSt0dgwL4n299HQ2G0qv5uW5rH8tJn4SMSXUiSwqNG0QXbm7goYCAgOpJmmK8qD0ChWx3YQA290ig0rCVAqe0TTM8aSSoAs1rAMADcX6NZOcuqFJqS6gSY9niOuVsDxMOvsZb0YljnLipDkYo5YMZ5YDNbBE06P084xF4oM5K4m39z3,BaLE1wZsjNb5J7HNXOdGECzgkKNYordwTLASeq9awPA1vmMQtPsAJNYos8CtnMkt8VymTgZzEjzg1PZWLlq966moEQaU4lDEKtz8kO4jzvnuqLfvQGwSweM4N6Pw64WIBKfG7VhluwK8q4rBZC2bRNH5ZeGNBYoMTo2WG086spcNWbsuJ2UL1RwGwYu5g8zx8H0EpukFtN3yTWsj5Lzrmqn3ydzJ10jtkRQYOXhJvozTuFH0AXkqPVAsXPHWp6Kb,m9FBiLOZrIGc9Qa1D0UuaRgIoQjAH9QhK5sDiYilmfVLzeKHkfqFFinMQ4gQkIqiEDpd343dypJtI9CymouZqmkHOrkqd8kl636m4iSvVS2xInyU0UoVAz6ro1mJrYCNQSiTL2u7ELmlcRR1jLBCzFxYt9w1BEuuaHgxjhlqjARWbRBs1NDwC7CVpZcXnNp0p4d58QRTIEPVWQKoqj4iHx2jmbrYeNLAIg43fa5mezVTFOALglh7lTNlaAawsDcF,4fNTu6h1JCT3ERXf7h9MfsXjUTpPFN2NL4Fv6KxxxtHJr1TnFUCUyGwwnxEciufSDJutt4C5CPkRWMr5i2Z5rOVo9j1vrYUnmev38goNwZhIoL8Leg6zte4RCYATu0MKBcbDPrVw06Td1PGsvtM6H52bPsh2v2rjVsmeXiSw1r4sSs3gQRamVCK3jDgRy5D2i0if1xKtT7kpig8iGaUa2WWUBA9Dm9NSlBTet1enuVme0iB815UA7z4miqVtiuFQ,cwJwzHFDFZTIOJQ79VdmeCyoC8UhJSunktAhB49mWcXHUK9YQfL58lRAELQHnP3luFJBg6CLSFILz7MTK5JuC1MYntiqjmlJRZMOZoZjHgYpxLnQ2UySJ81tAPuhsalhrcrOm9KTzAgoEnvAK4o4WjOQnlmS0BMLteHLEVcfA6dXqMfNLHMs3gfROp1731GTEhWo0scaGxBhRRQ2Mz8bAYM259LU6OMLY7ZKjADWdVtfj9v7Lny7MWoiN085pQWE,aVKvjkXwD96WTf9w8dkSxHh2WaO03BAddFi72pswCBaYWPZdWls7ZR5KGdNlqjDWCd1DWRatNeH4fN2Uz5K1NkzgABJ42e8cHuAH5OR6ZAsh0lxd6D54q2Y4soJbsEMAe761pSjQ1OdotZ47LrubSgeMvL2zAxx6EhLql2dRwNHql8uD8sgF7EVPllC4AFeTacLhdgIat52BpTfJY30TPWkBpOoLPeGmghUJhHidQNBWo4efPk0Y2MJd5Q6UaLjU,MLPdDOmI2NfSz8o3RhTLEtSWXuIWEhkuqCvIuqpPPAJ9DupVBn611JlpizWUWgFftmzZ6n8A7ELJy7suT1D0ZFJSEp8rTs8WO2jaKEN1XmX728zUXH7qNydya6eBx2nfoRaU6zf6gAgPospH7tZGgLCFRYsv1mpe0AKDoP2Wmhiwye0lfaadhvXYJWlnOPng23Nh85lSHgHLmkFobW92ewvvgcbcIKx5X78yOPdV73KzaMOOYx5E6oPB3YD10dz5,yWitLtEVFBS97rBDgt9pHK246pQrFV9CBf5fVwRnMQbTh0HPud4HdAH4qRiGNuId5wWWsG13z5cMUhhShUzL1qKrmuq6OiDpede2RNvjJrxETtOSaeJSvdHe99pJnDQVnmpyBpOJOYDj0579R4QNrJ0gGXiSGtcvQYt85eKTdtDs6ZGMe6SWK76ninHyq2bkqj8rH5bKMPyEkv0XrYeVyP4v2a7ZFOiWvC8SjLENjLbqcE70Hx3W4S8CTzxWI0zx,Sv6kXYLsTWaHkdDbMmoBtbQHdxPxHP6hpPzZtqvaaPEthWTNWXlzl5f6SwLfIyLWF9fSKFiF1u27H9U7XSM6iigpXYx7faUFwwpj8kY9jnXPUlV6aRZiQNnoZl43Pysb6HONFqKPXW4TXECyJNgxMTul5cAmVrJWlukOpdLA8XBQY9SnMd4fOwDs47Uz5KAqhaOwJvFReLlDyurxekx2QEpZ2o8GajiDlsv3GKql3juVke12w7XwbwhPkLeivRtu,0eSW0uJoFPfV0yBtny3huNQvmq8CYyEKNkqFJ0kZZUsUeB6Cuz72yjm2YXfJDyZSlaGqWaMh1ivJSMIYEaDf0dG8wDZjuFUPpjZgELZw5qacRE9YKqrQ9R3D4M6ggsSy51pJHzHM2wUsR87kjicT6ACA1kby5TEAEwQv7s67ygFdgx7zAs0LQhrjuWEQGtGJZ3AgR3qjpOWnINlOg5iCHtqBvpzSAokvSZhFyy7GzGjJDPZslMbxv082uG5MwgEK,lEiFSwpcV6y61Z4WRjbqlk7x6darwUxwuchxvtoxeZpvaICu6dQ1BBObXf4A6AYWNgQkA7fw53w37bsm0m8r8cSQ9nf2GHPVC4oHK1pCh2keVr1SLunj4MLtJW4LkKq4Ekp7YKLDeJOlgRbu5ZSOpYGfpV1T28Y1AkfAzoLpW67H2SxQlrcWG2e3CsF2gb64xbXcBzCpneHArH1WLo1cRyz55dl03Q4U5JYDf9k8AEbAazy3uUoYutNFiMDEECSM,PkDS6d0CpRkEKHo1u7opydUs7gljy0mW8n1ibzDjgVQd33mYnqBrGHTPDBaKPZstzSFr2mcQR1fVYTTGL8NLQ7bbYFUO9LuUgD0iOGcwjKGPurFSjndRb68TuuaeBVDN66wZCkW5pQwQ4qMvF9So17kDcZh6KLPT2KK6WpYRjKhLsRbALawPQI1BDyV6eFRzoP4WSbNxijeFlaGcdTnxVx987PRrLrScPiB3CbXKfN9AIE3mD0YDqgZYwV7MpDNJ,eSlqFo0gTZpcXMkjRUxGI7EqyE81jQ5WNLoSh36KO58iGFEw9fNHTPqcCmNuOoqJGsiGHrYguab1WB5uFbs8Zni9ph9LNpmpvq6Sdvb2RatWoRKVxo33d9YS6RtQwtuc0g3eNiEGB3m8BRhiSfjlVjxGSjkENkfjvLrAeBbUs19pAaaObG6nLkbTdqO0FOWarb52IbJ7iJ2JYyHkMhhuUhvyGIgou4povyc83ZryvCVk3CELFNA1ft460eZwWLcL,AfT91BF3dDVQJ1iRex54quB0Gedpzmz5IXc6L5tUVr5DNWOvaKTZYeYQcC1ttKbUwgOS89rZ51b0sVx9tfyn8xuNWFI45rUSjaBFwW0wnbv6EcUI9QAjMoiTDv6rS8EkkZ0AVSu9qAWJA4XsYyVqt2uXO4tqW9KfMVSxi2VSstts8RYHul7dsicWobx68YsilktJ1PbPTkDVz79rABQMnZtA3GstsmyQy2tcZSwjV9GHjLsVGEjSsLaQkQ1niPtT,38Py7AFPjEgIjzWM1MTPQ2za3Dj9APShpE9daJB3wFTqQ9vkOgMC5dWqBfYYJJlReG8m6ctutv2Q1N2G8Sbe6QPgRomYFFx7MGSGN5ZS4EJYr2WtOmwysOeQ7mDSRSepF4RPZL6P0Mj2eD0q9BO61gKy6gbVH1LchO8v8DXbyBK9DAArXa0FTcICMsy00tuZ10y7iv2zWHg0qQNz0WaLqAlIJEopoDwlzgdgkrVOa4nvPNDQFpZ6KxljlEHJtWsi,5n1fcqiOy54SfA4WWdKcyasMnfC4HrJM4Q54W6It3N2BTdulwDnKH84fhZ9FPyblBUypHSQm9zimjqUu0HGOqPh82ifSAbWR5zFJjJALMat2itvtwKN0iTnnuTnT0WfoD4Z4VMkGqwt1ujOBoKxxp3Dh4sjKRCWiMjhXNJXBIkWp3ulap6779XhMqmEypzhKfEu38YQ6EJgdiQk3pRfSn9arElY704WmdvcZ3qeAueIpYqLbjJgzgmiswGh3YTzk,PcGGwb2mZph9gtBzIzNKOhRCK0MJ70QXt7V4t33MKgyoQc4LmEw2ol92k7DZzrCpe83wqjULNY3AcI'
2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:97,88CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
,[ThaliCore] Session.deinit peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] Advertiser: session connected Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F338BE61-6F8A-4688-B675-EE08105E092D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", ,generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-09-19 12:49:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tzCzLOIkETrEp6xtl44GmnChpi8fjKfi","error":"Peer is unavailable","portNumber":null}'
,2017-09-19 12:49:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tzCzLOIkETrEp6xtl44GmnChpi8fjKfi', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:49:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4FF4D8AD-7583-4E46-A0AE-07975F33B677 (syncValue: kMACxtw0A0o0UfMHeGhOR7vb6IraQZ3i)'
,2017-09-19 12:49:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-09-19 12:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
,[ThaliCore] Session.session(_:peer:didChange:) peer:F338BE61-6F8A-4688-B675-EE08105E092D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] Session.startOutputStream(with:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [1, 3, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] Session.startOutputStream(with:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[,ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] Session.startOutputStream(with:) peer:F338BE61-6F8A-4688-B675-EE08105E092D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 3, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (3315 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (7624 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 6, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 8]
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received (9814 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-09-19 12:49:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61448
2017-09-19 12:49:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kMACxtw0A0o0UfMHeGhOR7vb6IraQZ3i","error":null,"portNumber":61448}'
,2017-09-19 12:49:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kMACxtw0A0o0UfMHeGhOR7vb6IraQZ3i', error: 'null', listeningPort: '61448''
,Connecting to the localhost:61448
,Connecting to the localhost:61448
,Connecting to the localhost:61448
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
,[ThaliCore] Session.startOutputStream(with:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
,Connected to the localhost:61448
,Connected to the localhost:61448
,Connected to the localhost:61448
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 9, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 9, 10, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 9, 11]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 11]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3]
,ok 96 got the same data back
,# teardown
,2017-09-19 12:49:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:49:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FA542401-F573-4621-9DBD-9F1F61CD325C
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61448
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F338BE61-6F8A-4688-B675-EE08105E092D
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kMACxtw0A0o0UfMHeGhOR7vb6IraQZ3i","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:F338BE61-6F8A-4688-B675-EE08105E092D
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B224C079-0793-4C1D-8FF3-899E71D44BAD
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039
,[ThaliCore] Browser.startListening
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09FDF337-6845-4807-9835-1630B55E626D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09FDF337-6845-4807-9835-1630B55E626D","generation":0}'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09FDF337-6845-4807-9835-1630B55E626D (syncValue: KczKvdS4QiE6IWJzMPnZrN0E6vIXjBMG)'
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4FF4D8AD-7583-4E46-A0AE-07975F33B677","generation":0}'
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C58D711-31E1-42BB-A9B7-C41E6294A0FD","generation":0}'
2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62C3A3CE-D25E-4073-8C66-B8F9673DB39F","generation":0}'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09FDF337-6845-4807-9835-1630B55E626D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9FDF337-6845-4807-9835-1630B55E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09FDF337-6845-4807-9835-1630B55E626D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9FDF337-6845-4807-9835-1630B55E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09FDF337-6845-4807-9835-1630B55E626D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9FDF337-6845-4807-9835-1630B55E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09FDF337-6845-4807-9835-1630B55E626D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:09FDF337,-6845-4807-9835-1630B55E626D error: max retries exceeded
2017-09-19 12:49:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KczKvdS4QiE6IWJzMPnZrN0E6vIXjBMG","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KczKvdS4QiE6IWJzMPnZrN0E6vIXjBMG', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:49:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C58D711-31E1-42BB-A9B7-C41E6294A0FD (syncValue: CBBNwui,9spzAQS6nRXInLNtFcXirmKbg)'
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C58D711-31E1,-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281
[ThaliCore] Advertiser: session connected Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:09FDF337-6845-4807-9835-1630B55E626D:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61466
,2017-09-19 12:49:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CBBNwui9spzAQS6nRXInLNtFcXirmKbg","error":null,"portNumber":61466}'
,2017-09-19 12:49:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CBBNwui9spzAQS6nRXInLNtFcXirmKbg', error: 'null', listeningPort: '61466''
,Connecting to the localhost:61466
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281
,[ThaliCore] Session.startOutputStream(with:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 3, 12, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Server received psk id: psk-id
,Connected to the localhost:61466
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" Use,rInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconne,ct(_:withError:) accepted socket error:nil
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() v,sID:12
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 13]
,ok 99 got the same data back
,# teardown
,2017-09-19 12:49:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:49:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B224C079-0793-4C1D-8FF3-899E71D44BAD
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3D63136F-81D8-413D-91AA-28D9BAC9F28,1
,[ThaliCore] AdvertiserRelay.deinit
,2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61466
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CBBNwui9spzAQS6nRXInLNtFcXirmKbg","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:3D63136F-81D8-413D-91AA-28D9BAC9F281
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:865FCB1B-7BD8-4406-B2FB-599546BA3E60
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:49:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
,[ThaliCore] Browser.startListening
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:49:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62C3A3CE-D25E-4073-8C66-B8F9673DB39F","generation":0}'
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62C3A3CE-D25E-4073-8C66-B8F9673DB39F (syncValue: tTRE1hLHMt0I2LDr4LqG9r74GWJpPWDB)'
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C58D711-31E1-42BB-A9B7-C41E6294A0FD","generation":0}'
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
2017-09-19 12:49:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
2017-09-19 12:49:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:62C3A3CE,-D25E-4073-8C66-B8F9673DB39F error: max retries exceeded
2017-09-19 12:49:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tTRE1hLHMt0I2LDr4LqG9r74GWJpPWDB","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:49:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tTRE1hLHMt0I2LDr4LqG9r74GWJpPWDB', error: 'Connection could not be established', listeningPort: '%s''
2017-09-19 12:49:45 - ERROR thaliMobileNativeTestUtils: 'Fatal ,c,onnect error: 'Connection could not be established''
2017-09-19 12:49:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C58D711-31E1-42BB-A9B7-C41E6294A0FD (syncValue: tbbs8AIK2oQGws4eRuhov9zlh0Z9Mum6)'
2017-09-19 12:49:45 - DEBUG thaliMo,bileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:s,essionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.init(session,:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:45 - DEBUG thaliMobileNativeTestUtils: 'Al,r,eady running test!'
,2017-09-19 12:49:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5C58D711,-31E1-42BB-A9B7-C41E6294A0FD error: max retries exceeded
2017-09-19 12:49:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tbbs8AIK2oQGws4eRuhov9zlh0Z9Mum6","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:49:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tbbs8AIK2oQGws4eRuhov9zlh0Z9Mum6', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:49:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-09-19 12:49:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5B0178B6-A741-4E00-AC62-1F9897244011 (syncValue: cxXC6hD2Er3e2dIwn7HoMuT8KMeMkXtc)'
,2017-09-19 12:49:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:49:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserRelay.deinit
2017-09-19 12:49:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61491
,2017-09-19 12:49:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cxXC6hD2Er3e2dIwn7HoMuT8KMeMkXtc","error":null,"portNumber":61491}'
,2017-09-19 12:49:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cxXC6hD2Er3e2dIwn7HoMuT8KMeMkXtc', error: 'null', listeningPort: '61491''
,Connecting to the localhost:61491
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,Connected to the localhost:61491
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 3, 13, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-09-19 12:50:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:865FCB1B-7BD8-4406-B2FB-599546BA3E60
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:5B0178B6-A741-4E00-AC62-1F9897244011
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61491
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] Session.deinit peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A8E37BF6-9675-43D6-B915-B437853F674D
,[ThaliCore] Browser.startListening
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
2017-09-19 12:50:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}]'
2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}'
2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}]'
,2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5B0178B6-A741-4E00-AC62-1F9897244011","generation":0}'
2017-09-19 12:50:01 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06803A25-E8DE-4A6B-8E67-EF7F618CC7F4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06803A25-E8DE-4A6B-8E67-EF7F618CC7F4", generation: 0)
,2017-09-19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"06803A25-E8DE-4A6B-8E67-EF7F618CC7F4","generation":0}]'
,2017-09-19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"06803A25-E8DE-4A6B-8E67-EF7F618CC7F4","generation":0}'
,2017-09-19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:50:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5ECB47BE-74E6-45B9-ABDF-F,0FFE6321A0B
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-0,9-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-09-19 12:50:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4D4EFF6C-7249-4551-9A55-448072DF6755
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "16C189C0-8160-43B5-96F2-F2C30A946695", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:16C189C0-8160-43B5-96F2-F2C30A946695
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:16C189C0-8160-43B5-96F2-F2C30A946695
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-09-19 12:50:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-09-19 12:50:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-09-19 12:50:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:baeb7b12-4802-41e5-9fc8-b9ec793e50ba error: startListeningNotActive
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"Axu1Yu1ke8S7gmR9xA5jlfhCFDnhh90k","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:429BC1E5-0F9D-43BC-A2C8-3BDA0E69C4EE
,[ThaliCore] Browser.startListening
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
ok 132 Got null as expected
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k7Bjzjo9wWJhYNpOYns31JCfJPRVo9dG","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-09-19 12:50:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:051AA5A8-9B92-4656-910B-D07884C878DB
[ThaliCore] Browser.startListening
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged regis,tered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:519e9263-cc1b-4000-a60c-840a8524f034
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E205BA54-258E-4F38-8E64-D5B41A94C652
2017-09-19 1,2:50:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:50:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C9A9E26D-98D4-40A7-9875-ED34C32DF968
,[ThaliCore] Browser.startListening
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,2017-09-19 12:50:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-09-19 12:50:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}'
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49A00F14-0EB2-468A-A004-75D2B5F0AF5F (syncValue: wJPAmJODyV2ixakzHq5mTRGiHAATy4De)'
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
2017-09-19 12:50:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CE085BEC-A868-440D-8066-CAEC5CC0BC19","generation":0}'
2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5","generation":0}'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:50:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wJPAmJODyV2ixakzHq5mTRGiHAATy4De","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:50:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wJPAmJODyV2ixakzHq5mTRGiHAATy4De', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:50:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:50:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CE085BEC-A868-440D-8066-CAEC5CC0BC19 (syncValue: VgYtHaIrGnc5WwE9doy3Cel,uecllVFeW)'
2017-09-19 12:50:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE085BEC-A868-440D-8066-CAEC5,CC0BC19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:50:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
2017-09-19 12:50:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}'
2017-09-19 12:50:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61505
,2017-09-19 12:50:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VgYtHaIrGnc5WwE9doy3CeluecllVFeW","error":null,"portNumber":61505}'
,2017-09-19 12:50:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VgYtHaIrGnc5WwE9doy3CeluecllVFeW', error: 'null', listeningPort: '61505''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) found active relay
,2017-09-19 12:50:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bTw8YRYH8ivedEpe2XYIwOzPmKapnvyT","error":null,"portNumber":61505}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 13, 14, 15]
,ok 144 No error
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) found active relay
,2017-09-19 12:50:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SQAmdbDMfB2dkwD317KWvzI3BugZb3Xq","error":null,"portNumber":61505}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[Th,aliCore] VirtualSocket.deinit vsID:15 [1, 3, 13, 14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocket,DisconnectHandler
,2017-09-19 12:50:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:50:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E205BA54-258E-4F38-8E64-D,5B41A94C652
2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61505
[ThaliCore] Session.disconnect() p,eer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
2017-09-19 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-09-19 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-09-19 12:50:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'listening 61508'
,ok 149 Should throw
,# teardown
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'listening 61510'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 61513'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 61517'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 61522'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'listening 61526'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'listening 61530'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'listening 61534'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'listening 61538'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-09-19 12:50:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'listening 61590'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'listening 61594'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
,ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 61597'
ok 196 port must be in range
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 61598'
,ok 197 second start should return same port
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 61600'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61602
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
[ThaliCore] Browser.startListening
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5 (syncValue: mSz4JXxCO0TA14T7tQuMRS3LKiviYhCH)'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CE085BEC-A868-440D-8066-CAEC5CC0BC19","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39C6DE90-E027-43EA-AFED-DFDEEFC4A256","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AB,A4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,BA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AB,A4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,BA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:50:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mSz4JXxCO0TA14T7tQuMRS3LKiviYhCH","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:50:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mSz4JXxCO0TA14T7tQuMRS3LKiviYhCH', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:50:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:50:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CE085BEC-A868-440D-8066-CAEC5CC0BC19 (syncValue: ZstcxmxZcuUgpT6Q3y67Zx013Y2Wzje1)'
,2017-09-19 12:50:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:50:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CE,085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,E085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:50:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZstcxmxZcuUgpT6Q3y67Zx013Y2Wzje1","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:50:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZstcxmxZcuUgpT6Q3y67Zx013Y2Wzje1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:50:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:50:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D (syncValue: SVEKYzMcmESgosTK42msvj5,Wq0ww2ifU)'
2017-09-19 12:50:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D77D6C02-7E8C-45AB-8EFC-0709A,D5F2D8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:50:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
[ThaliCore] Advertiser: session connected Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61614
,2017-09-19 12:51:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SVEKYzMcmESgosTK42msvj5Wq0ww2ifU","error":null,"portNumber":61614}'
,2017-09-19 12:51:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SVEKYzMcmESgosTK42msvj5Wq0ww2ifU', error: 'null', listeningPort: '61614''
,ok 210 should be equal
,2017-09-19 12:51:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39C6DE90-E027-43EA-AFED-DFDEEFC4A256 (syncValue: ftYNheLg2Fqw95myAp9B1ZjqyPszzXYG)'
,2017-09-19 12:51:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
,[ThaliCore] Session.session(_:peer:didChange:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61618
,2017-09-19 12:51:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ftYNheLg2Fqw95myAp9B1ZjqyPszzXYG","error":null,"portNumber":61618}'
,2017-09-19 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ftYNheLg2Fqw95myAp9B1ZjqyPszzXYG', error: 'null', listeningPort: '61618''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BAF145EB-1C51-4367-A988-16E703F33D45
[ThaliCore] Advertiser: session connected Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BAF145EB-1C51-4367-A988-16E703F33D45 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BAF145EB-1C51-4367-A988-16E703F33D45
,[ThaliCore] Session.session(_:peer:didChange:) peer:BAF145EB-1C51-4367-A988-16E703F33D45 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:51:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61614
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61618
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BAF145EB-1C51-4367-A988-16E703F33D45 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BAF145EB-1C51-4367-A988-16E703F33D45
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:BAF145EB-1C51-4367-A988-16E703F33D45
,[ThaliCore] Session.session(_:peer:didChange:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Session.deinit peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:51:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SVEKYzMcmESgosTK42msvj5Wq0ww2ifU","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 61620
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:446E2367-C254-4409-9086-F5ED433913DB
2017-09-19 1,2:51:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:51:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-09-19 12:51:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForA,dvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
[ThaliCore] Browser.startListening
2017-09-19 12:51:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discover,yActive":true,"advertisingActive":true}'
2017-09-19 12:51:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","st,artArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D","generation":0}'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D (syncValue: w1udSjuOTDsuBuoIBXgC4rbN1dKez8lS)'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39C6DE90-E027-43EA-AFED-DFDEEFC4A256","generation":0}'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:446E2367-C254-4409-9086-F5ED433913DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,7D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,7D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,7D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,7D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D77D6C02,-7E8C-45AB-8EFC-0709AD5F2D8D error: max retries exceeded
2017-09-19 12:51:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"w1udSjuOTDsuBuoIBXgC4rbN1dKez8lS","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'w1udSjuOTDsuBuoIBXgC4rbN1dKez8lS', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:51:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39C6DE90-E027-43EA-AFED-DFDEEFC4A256 (syncValue: uoEqvoZ,b3ryQ20Ol8tzgOrqjFGm8OUoy)'
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39C6DE90-E027,-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:51:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uoEqvoZb3ryQ20Ol8tzgOrqjFGm8OUoy","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uoEqvoZb3ryQ20Ol8tzgOrqjFGm8OUoy', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 37F90D9D-C502-4429-B6AC-531362636BBF (syncValue: 0qOqwIt43KcUsfQ18jkwXq9,0sbTLCJk6)'
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:37F90D9D-C502-4429-B6AC-53136,2636BBF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1
[ThaliCore] Advertiser: session connected Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:37F90D9D-C502-4429-B6AC-531362636BBF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61641
2017-09-19 12:51:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0qOqwIt43KcUsfQ18jkwXq90sbTLCJk6",,"error":null,"portNumber":61641}'
2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0qOqwIt43KcUsfQ18jkwXq90sbTLCJk6', error: 'null', listeningPort: '61641''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9
[ThaliCore] Advertiser: session connected Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9 state: notConnected -> connecting
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 73CFC2FD-1259-4083-9C92-2E89F1043EE6 (syncValue: 3Nl1Ujxoso7PvwefCGRb3YGRPa3aiHtT)'
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73,CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1
,[ThaliCore] Session.session(_:peer:didChange:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61647
,2017-09-19 12:51:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3Nl1Ujxoso7PvwefCGRb3YGRPa3aiHtT","error":null,"portNumber":61647}'
,2017-09-19 12:51:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3Nl1Ujxoso7PvwefCGRb3YGRPa3aiHtT', error: 'null', listeningPort: '61647''
,ok 220 should be equal
ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:446E2367-C254-4409-9086-F5ED433913DB
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:37F90D9D-C502-4429-B6AC-531362636BBF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61641
[ThaliCore] Session.disconnect() peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:61647
[ThaliCore] Session.disconnect() peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,[ThaliCore] Session.deinit peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6
,2017-09-19 12:51:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3Nl1Ujxoso7PvwefCGRb3YGRPa3aiHtT","error":"Session disconnected","portNumber":null}'
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 61651'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] Session.deinit peer:2C6B04F4-9640-46F5-8BD2-F0B52C819BA9
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.deinit
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 61652'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A479E312-F64D-498E-860F-7B613E8E9FD7
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 61653'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "36569429-13D9-4937-9EAB-286FB36EF91B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:36569429-13D9-4937-9EAB-286FB36EF91B
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "36569429-13D9-4937-9EAB-286FB36EF91B", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:36569429-13D9-4937-9EAB-286FB36EF91B
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:36569429-13D9-4937-9EAB-286FB36EF91B
[ThaliCore] Advertiser.stopAdvertising() peerID:36569429-13D9-4937-9EAB-286FB36EF91B
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'listening 61656'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-09-19 12:51:34 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'listening 61657'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:494107F1-C8E6-4CF5-B094-C022795036F0
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E3839301-A16A-43FF-9EF2-7DDD0BDE0366", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E3839301-A16A-43FF-9EF2-7DDD0BDE0366
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,ok 243 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}]'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","generation":0}'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"37F90D9D-C502-4429-B6AC-531362636BBF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E3839301-A16A-43FF-9EF2-7DDD0BDE0366
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'listening 61660'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9037D23D-DD33-4D2A-8EC1-49BCF870FC17
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "58B6444D-7C37-442A-8DA2-42E5BAEBA734", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:58B6444D-7C37-442A-8DA2-42E5BAEBA734
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:58B6444D-7C37-442A-8DA2-42E5BAEBA734
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:35 - I,NFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":,null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:35 - DEBUG thaliMob,ileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:35 - DEBUG mak,eIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'listening 61662'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:98E73481-CDC5-4AF4-8297-24F60E4F6D22
[ThaliCore] Browser.startListening
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CB8BF1D4-FFDD-4F9E-A817-461A2FD41484", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CB8BF1D4-FFDD-4F9E-A817-461A2FD41484
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CB8BF1D4-FFDD-4F9E-A817-461A2FD41484
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-09-19 12:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-09-19 12:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-09-19 12:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-09-19 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-09-19 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-09-19 12:51:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-09-19 12:51:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'listening 61665'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:030E8D07-0846-4F12-AEFB-2E06BE141E4A
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-09-19 12:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'listening 61666'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DA35F0EE-0CEA-4023-920B-1EB9272AF261", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DA35F0EE-0CEA-4023-920B-1EB9272AF261
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DA35F0EE-0CEA-4023-920B-1EB9272AF261
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'listening 61668'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'listening 61669'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2E3DA6D8-A454-4C08-8A90-1714A21908D1
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1EB74B74-2182-4EF8-AB06-C62817FE919E
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:BAD17115-B3D7-4616-834B-02D88C9985D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}]'
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3",",generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1EB74B74-2182-4EF8-AB06-C62817FE919E
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'listening 61671'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:11F98CCD-AF7B-421E-ACC2-2EBC279ED663
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BAD17115-B3D7-4616-834B-02D88C9985D3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 73CFC2FD-1259-4083-9C92-2E89F1043EE6 (syncValue: wX7VbDyHjAi6DIPGlOZC3QskWWvBUIEN)'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73,CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BAD17115-B3D7-4616-834B-02D88C9985D3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BAD17115-B3D7-4616-834B-02D88C9985D3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":false,"generation":n,u[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0
ll,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
,2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Browser,.browser(_:foundPeer:withDiscoveryInfo:) found peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"573C5C14-23,ED-405D-B676-0A82D053A509","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed even,t with {"peerAvailable":true,"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","generation":0}]'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1D0148D-6FD3-48E7-B035-B4E113A88E98","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-09-19 12:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,3CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:47 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91937F6F-BD98-4E96-8699-1C9D51983889
[ThaliCore] Advertiser: session connected Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:91937F6F-BD98-4E96-8699-1C9D51983889 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,3CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,2017-09-19 12:51:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
,2017-09-19 12:51:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-09-19 12:51:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:91937F6F-BD98-4E96-8699-1C9D51983889
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-09-19 12:51:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wX7VbDyHjAi6DIPGlOZC3QskWWvBUIEN","error":"Peer is unavailable","portNumber":null}'
,2017-09-19 12:51:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wX7VbDyHjAi6DIPGlOZC3QskWWvBUIEN', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:52 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:51:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 573C5C14-23ED-405D-B676-0A82D053A509 (syncValue: tE23EUseUttttCGOVqqVeXHHfNXUXgaH)'
,2017-09-19 12:51:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:91937F6F-BD98-4E96-8699-1C9D51983889 state: connecting -> connected
,[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91937F6F-BD98-4E96-8699-1C9D51983889
,[ThaliCore] Session.startOutputStream(with:) peer:91937F6F-BD98-4E96-8699-1C9D51983889
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 13, 14, 16]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,3C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,73C5C14-23ED-405D-B676-0A82D053A509", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,3C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,73C5C14-23ED-405D-B676-0A82D053A509", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,3C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,73C5C14-23ED-405D-B676-0A82D053A509", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:573C5C14-23ED-405D-B676-0A82D053A509:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:57,3C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:573C5C14,-23ED-405D-B676-0A82D053A509 error: max retries exceeded
2017-09-19 12:52:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tE23EUseUttttCGOVqqVeXHHfNXUXgaH","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:52:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tE23EUseUttttCGOVqqVeXHHfNXUXgaH', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:52:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:52:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C1D0148D-6FD3-48E7-B035-B4E113A88E98 (syncValue: hV5XVXI,RcCIXwy58MtPiupG6fveDROGh)'
2017-09-19 12:52:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1D0148D-6FD3,-48E7-B035-B4E113A88E98:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61691
,2017-09-19 12:52:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hV5XVXIRcCIXwy58MtPiupG6fveDROGh","error":null,"portNumber":61691}'
,2017-09-19 12:52:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hV5XVXIRcCIXwy58MtPiupG6fveDROGh', error: 'null', listeningPort: '61691''
,2017-09-19 12:52:06 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 13, 14, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-09-19 12:52:06 - DEBUG testUtils: 'Got response data'
,2017-09-19 12:52:06 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-09-19 12:53:06 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-09,-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-09-19 12:53:06 - INFO Coordinated,Client: '***TEST_LOGGER result: passed - another'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-09-19 12:53:06 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can do HTTP requests between peers, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151,D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers,.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-09-19 12:53:06 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-09-19 12:56:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-09-19 12:56:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-4,96E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-4,96E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-4,96E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-4,96E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496,E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8AC0B61B-9A2E-496E-8F3F-FA2BCFE7151D/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
