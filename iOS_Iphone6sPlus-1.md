#### Test 1133518513e6abb0_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D2497B91-77C4-4251-924C-2A5DD53A61BA/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/D2497B91-77C4-4251-924C-2A5DD53A61BA/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59047"
,(lldb)     command script import "/tmp/D2497B91-77C4-4251-924C-2A5DD53A61BA/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:39:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E50C937F-1017-4013-926A-6CD26669B5FD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E50C937F-1017-4013-926A-6CD26669B5FD
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DF618C37-F4FA-4478-948A-92DFB54300C0
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A17615CC-,E21F-43DD-B898-28E50FDE5467
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E1198C60-361D-4F79-9833-8DC23E134647", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E1198C60-361D-4F79-9833-8DC23E134647
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E1198C60-361D-4F79-9833-8DC23E134647:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E1198C60-361D-4F79-9833-8DC23E134647", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-21 08:39:17 - DEBUG UnitTest_app: 'Running unit te,sts'
,*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.358684003353119
,2017-07-21 08:39:17 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-21 08:39:17 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E1198C60-361D-4F79-9833-8DC23E134647:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E1198C60-361D-4F79-9833-8DC23E134647", generation: 0)
,2017-07-21 08:39:18 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 08:39:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 08:39:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 08:39:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 08:39:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 08:39:20 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 08:39:20 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 08:39:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:39:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:39:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:39:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:39:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:39:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:39:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:39:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:39:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:40:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:40:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:40:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:40:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:40:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:40:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:40:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:40:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:40:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:40:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:40:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:40:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:42:02 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 08:42:02 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 08:42:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 08:42:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 08:42:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 08:42:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 08:42:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 08:42:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 08:42:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 08:42:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
,ok 9 should be equal
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
,ok 33 second
ok 34 secondPromise - in then
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
,2017-07-21 08:42:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 08:42:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 08:42:33 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-21 08:42:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:42:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 08:42:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:42:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ACD20710-15E9-4613-8158-F3550DEE953E
[ThaliCore] Browser.startListening
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D31DDF68-8961-4F80-9315-DECF637ED834
[ThaliCore] Browser.startListening
,2017-07-21 08:42:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:42:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:42:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-21 08:42:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3841BA23-3D2A-427C-875A-954622676700", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3841BA23-3D2A-427C-875A-954622676700
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3841BA23-3D2A-427C-875A-954622676700
2017-07-21 08:42:52 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71055A52-CAE5-4ED2-AFF8-8F11FD388E9A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:71055A52-CAE5-4ED2-AFF8-8F11FD388E9A
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71055A52-CAE5-4ED2-AFF8-8F11FD388E9A", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:71055A52-CAE5-4ED2-AFF8-8F11FD388E9A
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:56, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:4,2:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:71055A52-CAE5-4ED2-AFF8-8F11FD388E9A
[ThaliCore] Advertiser.s,topAdvertising() peerID:71055A52-CAE5-4ED2-AFF8-8F11FD388E9A
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:43:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:43:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:43:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "504F6711-A3CD-47A8-958A-4636FEA06501", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:504F6711-A3CD-47A8-958A-4636FEA06501
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70BD2994-AB1F-443B-86C4-F368D9051,020
[ThaliCore] Browser.startListening
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:06 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
ok 76 peers must be an array,
,ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:504F6711-A3CD-47A8-958A-4,636FEA06501
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9AB7820A-F8F3-453E-834B-995FF5171EC1
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB
,[ThaliCore] Browser.startListening
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
2017-07-21 08:43:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"77BBFECF-121D-4B80-B600-51C99929A3D9","generation":0}'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 77BBFECF-121D-4B80-B600-51C99929A3D9 (syncValue: T4tYwJ5N0L9mx7IPnrMlORPcd6Q6wmDm)'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"06B916F2-4AD1-4258-B3BA-A806E40E233A","generation":0}'
2017-07-21 08:43:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
2017-07-21 08:43:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA866320-E8DD-46F0-82DE-6644335CB228","generation":0}'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:08 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","generation":0}'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:77,BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,7BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"T4tYwJ5N0L9mx7IPnrMlORPcd6Q6wmDm","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'T4tYwJ5N0L9mx7IPnrMlORPcd6Q6wmDm', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:09 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"77BBFECF-121D-4B80-B600-51C99929A3D9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"77BBFECF-121D-4B80-B600-51C99929A3D9","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:43:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:43:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 06B916F2-4AD1-4258-B3BA-A806E40E233A (syncValue: PTOXLnQS6TwLM3rwNTJogh0,1rp1DZRgo)'
2017-07-21 08:43:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06B916F2-4AD1-4258-B3BA-A806E,40E233A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:43:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,8:43:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:10735B8E-6FDD-43B2-931E-5F27971B2749
[ThaliCore] Advertiser: session connected Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:10735B8E-6FDD-43B2-931E-5F27971B2749 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:06,B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,6B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PTOXLnQS6TwLM3rwNTJogh01rp1DZRgo","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PTOXLnQS6TwLM3rwNTJogh01rp1DZRgo', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:11 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"06B916F2-4AD1-4258-B3BA-A806E40E233A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"06B916F2-4AD1-4258-B3BA-A806E40E233A","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 08:43:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:43:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA866320-E8DD-46F0-82DE-6644335CB228 (syncValue: CLXKSim0vScqCAK9627NwF2WIIKBU9k3)'
,2017-07-21 08:43:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:10735B8E-6FDD-43B2-931E-5F27971B2749
,[ThaliCore] Session.session(_:peer:didChange:) peer:10735B8E-6FDD-43B2-931E-5F27971B2749 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56474
2017-07-21 08:43:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CLXKSim0vScqCAK9627NwF2WIIKBU9k3","error":null,"portN,umber":56474}'
2017-07-21 08:43:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CLXKSim0vScqCAK9627NwF2WIIKBU9k3', error: 'null', listeningPort: '56474''
,2017-07-21 08:43:14 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-21 08:43:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:9AB7820A-F8F3-453E-834B-995FF5171EC1
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:EA866320-E8DD-46F0-82DE-6644335CB228
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56474
[ThaliCore] Session.disconnect,() peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:10735B8E-6FDD-43B2-931E-5F27971B2749 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:10735B8E-6FDD-43B2-931E-5F27971B2749
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:10735B8E-6FDD-43B2-931E-5F27971B2749
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B98D732E-24B1-45E1-B5D1-9838E2970C6A
2017-07-21 08:43:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:16, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 08:43:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:96585F97-EA63-4067-89E3-DC97643C6672
[ThaliCore] Browser.startListening
2017-07-21 08:43:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-21 08:43:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1211860E-3540-4274-8371-7D60BFB282B3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","generation":0}'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1211860E-3540-4274-8371-7D60BFB282B3 (syncValue: UKJNSf5pZjGW2CH8FofdLTb35YzZwPYn)'
2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA866320-E8DD-46F0-82DE-6644335CB228","generation":0}'
2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F4AE99C-CB76-483A-8EBC-33C6B96E91C4","generation":0}'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
,2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","generation":0}'
2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1211860E,-3540-4274-8371-7D60BFB282B3 error: max retries exceeded
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UKJNSf5pZjGW2CH8FofdLTb35YzZwPYn","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UKJNSf5pZjGW2CH8FofdLTb35YzZwPYn', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA866320-E8DD-46F0-82DE-6644335CB228 (syncValue: c4zLyz4,EYTUJ3cVhJwXhs3NlDInfh7He)'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA866320-E8DD,-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,A866320-E8DD-46F0-82DE-6644335CB228", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
[ThaliCore] Advertiser: session connected Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
,[ThaliCore] Session.session(_:peer:didChange:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,A866320-E8DD-46F0-82DE-6644335CB228", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
[ThaliCore] Session.startOutputStream(with:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:43:34 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 08:43:34 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 08:43:34 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-21 08:43:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1,
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA866320-E8DD-46F0-82DE-6644335CB228:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,A866320-E8DD-46F0-82DE-6644335CB228", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c4zLyz4EYTUJ3cVhJwXhs3NlDInfh7He","error":"Peer is unavailable","portNumber":null}'
2017-07-21 08:43:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'c4zLyz4EYTUJ3cVhJwXhs3NlDInfh7He', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:35 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"EA866320-E8DD-46F0-82DE-6644335CB228","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EA866320-E8DD-46F0-82DE-6644335CB228","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:43:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:43:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F4AE99C-CB76-483A-8EBC-33C6B96E91C4 (syncValue: RHqyTFUMaYAVDnB08fMQLvx,r3E9oZdLx)'
2017-07-21 08:43:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F4AE99C-CB76-483A-8EBC-33C6B,96E91C4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:43:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,8:43:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56482
2017-07-21 08:43:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RHqyTFUMaYAVDnB08fMQLvxr3E9oZdLx",,"error":null,"portNumber":56482}'
2017-07-21 08:43:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RHqyTFUMaYAVDnB08fMQLvxr3E9oZdLx', error: 'null', listeningPort: '56482''
,Connecting to the localhost:56482
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
Connected to the localh,ost:56482
2017-07-21 08:43:39 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 08:43:39 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
ok 88 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,# teardown
,2017-07-21 08:43:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B98D732E-24B1-45E1-B5D1-9838E2970C6A
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56482
[ThaliCore] Session.disconnect() peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
,[ThaliCore] Session.deinit peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:43:40 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:81DEE32E-D9D8-4C56-83BB-2F7D5C45,E607
[ThaliCore] Browser.startListening
2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
2017-07-21 08:43:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","generation":0}'
2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EDC94BDF-633A-4D81-89CA-4D03B57A38FB, (syncValue: FMHwKRuP3sgL6U4EWR3yVUcdeHKnoQ5I)'
2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57,A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","generation":0}'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","generation":0}'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,C94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,DC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,C94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,DC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,C94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,DC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FMHwKRuP3sgL6U4EWR3yVUcdeHKnoQ5I","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FMHwKRuP3sgL6U4EWR3yVUcdeHKnoQ5I', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:49 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:43:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:43:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B73B52DC-F7A7-4412-9E88-BAB14F24676C (syncValue: L4HQ4K44YKiLfD3q6k0TGSg,WC6WpjriO)'
2017-07-21 08:43:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14,F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:43:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56496
2017-07-21 08:43:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L4HQ4K44YKiLfD3q6k0TGSgWC6WpjriO",,"error":null,"portNumber":56496}'
2017-07-21 08:43:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'L4HQ4K44YKiLfD3q6k0TGSgWC6WpjriO', error: 'null', listeningPort: '56496''
,Connecting to the localhost:56496
Connecting to the localhost:56496
Connecting to the localhost:56496
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
Connected to the localhost:56496
Connected to the localhost:56496
C,onnected to the localhost:56496
,ok 91 correct string length
,2017-07-21 08:43:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 08:43:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 08:43:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 08:43:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 08:43:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 08:43:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-21 08:44:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56496
[ThaliCore] Session.disconnect,() peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:36797C19-C4DE-4D06-8AE0-EA5972815BBE
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser,.init(serviceType:foundPeer:lostPeer:) peer:9D9FAEF4-411C-448B-9D20-057A4E07889E
[ThaliCore] Browser.startListening
2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
2017-07-21 08:44:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","generation":0}'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B73B52DC-F7A7-4412-9E88-BAB14F24676C, (syncValue: 2bkVneJnVnsSAWlSYW1GPMNYtaMILRQk)'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F2,4676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","generation":0}'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
2017-07-21 08:44:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","generation":0}'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A","generatio,n,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
":0}'
2017-07-21 08:44:09 - ,DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMo,bileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,3B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,3B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:44:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2bkVneJnVnsSAWlSYW1GPMNYtaMILRQk","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:44:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2bkVneJnVnsSAWlSYW1GPMNYtaMILRQk', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:44:14 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:44:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:44:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:44:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C91ADCD2-C046-4AA4-A330-A15E9E6C4C01 (syncValue: dkSfYHKQsFbyEM47EHW7mgw,mBUZO0syX)'
2017-07-21 08:44:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9,E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,8:44:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C9,1ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:44:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dkSfYHKQsFbyEM47EHW7mgwmBUZO0syX","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:44:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dkSfYHKQsFbyEM47EHW7mgwmBUZO0syX', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:44:19 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:44:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C91ADCD2-C046-4AA4-A330-A15E9E6C4C01","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 08:44:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:44:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A (syncValue: IYkLf12gSPCR98neQ1i9gkc,exnj3PRAT)'
2017-07-21 08:44:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF,3F5C45A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
[ThaliCore] Advertiser: session connected Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
,[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56514
,2017-07-21 08:44:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IYkLf12gSPCR98neQ1i9gkcexnj3PRAT","error":null,"portNumber":56514}'
,2017-07-21 08:44:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IYkLf12gSPCR98neQ1i9gkcexnj3PRAT', error: 'null', listeningPort: '56514''
,Connecting to the localhost:56514
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
[ThaliCore] Session.startOutputStream(with:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] Virtu,alSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4, 5, 6]
,Connected to the localhost:56514
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.,closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-21 08:44:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:36797C19-C4DE-4D06-8AE0-EA5972815BBE
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56514
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IYkLf12gSPCR98neQ1i9gkcexnj3PRAT","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
,[ThaliCore] Session.deinit peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF
,2017-07-21 08:44:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
[ThaliCore] Browser.startListening
,2017-07-21 08:44:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:09B96C17-6759-44ED-AB0C-84B9366E4D7E
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
2017-07-21 08:44:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","generation":0}'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A, (syncValue: QE4wyqTlgYHgcu6nfCDSrc9h6OzwEBxh)'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F,5C45A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo,:) found peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A","generation":0}'
2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E5BE70F-136E-443D-9F11-E27DA37D9C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
2017-07-21 08:44:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5E5BE70F-136E-443D-9F11-E27DA37D9C01","generation":0}'
2017-07-21 08:44:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:26 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:44:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:60,053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,0053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:44:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QE4wyqTlgYHgcu6nfCDSrc9h6OzwEBxh","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:44:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QE4wyqTlgYHgcu6nfCDSrc9h6OzwEBxh', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:44:28 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:44:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:44:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:44:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A (syncValue: D3QQT93iTyz2q7YcASQ8kt9,QDj45oJns)'
2017-07-21 08:44:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7,E19D22A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,08:44:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0C,7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0C,7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D
[ThaliCore] Advertiser: session connected Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D state: notConnected -> connecting
,[ThaliCore] Session.deinit peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0C,7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27EE564A-9F54-4624-AB03-96C97755C207
[ThaliCore] Advertiser: session connected Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:27EE564A-9F54-4624-AB03-96C97755C207 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D
[ThaliCore] Session.startOutputStream(with:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [4, 5, 6, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017,-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017,-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (5333 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (3498 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received (12976 bytes):'
,2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 08:44:37 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [4, 5, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0C,7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:0C7FFC21,-A2BF-4C15-B36D-7F2D7E19D22A error: max retries exceeded
2017-07-21 08:44:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D3QQT93iTyz2q7YcASQ8kt9QDj45oJns","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:44:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'D3QQT93iTyz2q7YcASQ8kt9QDj45oJns', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:44:38 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 08:44:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:44:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:44:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0B635E3-F14B-483A-B337-CC90A5ACF439 (syncValue: KQ7g4wC,9JTE2SIzoIXUfP7CU6DIaCdl0)'
2017-07-21 08:44:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0B635E3-F14B,-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:44:39 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 08:44:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:27EE564A-9F54-4624-AB03-96C97755C207
,[ThaliCore] Session.session(_:peer:didChange:) peer:27EE564A-9F54-4624-AB03-96C97755C207 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:27EE564A-9F54-4624-AB03-96C97755C207
[ThaliCore] Session.startOutputStream(with:) peer:27EE564A-9F54-4624-AB03-96C97755C207
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [4, 5, 6, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [4, 5, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56534
2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KQ7g4wC9JTE2SIzoIXUfP7CU6DIaCdl0",,"error":null,"portNumber":56534}'
2017-07-21 08:44:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KQ7g4wC9JTE2SIzoIXUfP7CU6DIaCdl0', error: 'null', listeningPort: '56534''
,Connecting to the localhost:56534
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
Connected to the localh,ost:56534
2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0B635E3-F14B-483A,-B337-CC90A5ACF439:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 5, 6, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [4, 5, 6]
,# teardown
,2017-07-21 08:44:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E0B635E3-F14B-483A-B337-CC90A5ACF439
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56534
[ThaliCore] Session.disconnect() p,eer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:27EE564A-9F54-4624-AB03-96C97755C207 state,: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPCl,ient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:27EE564A-9F54-4624-AB03-96C97755C207
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A462663-AE7A-4988-A9E0-172273A06F5D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Session.deinit peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
,[ThaliCore] Session.deinit peer:27EE564A-9F54-4624-AB03-96C97755C207
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CDE27441-97BB-4903-86BB-1AA064E9CAA5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CDE27441-97BB-4903-86BB-1AA064E9CAA5
2017-07-21 0,8:44:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:810E22DB-9E3E-4B94-955B-1646C8273F38
[ThaliCore] Browser.startListening
2017-07,-,21 08:44:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E5BE70F-136E-443D-9F11-E27DA37D9C01:0
[ThaliCore] AdvertiserManager,.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CDE27441-97BB-4903-86BB-1AA064E9CAA5
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
[ThaliCore] Browser.browser(_:foun,dPeer:withDiscoveryInfo:) found peer:9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,2017-07-21 08:44:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:44:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 08:44:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F153CA5D-B04D-4E32-980A-87B5588EAD6A
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "998C4C02-4ADB-4081-8CBC-A3DFD3D78957", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:998C4C02-4ADB-4081-8CBC-A3DFD3D78957
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 d,iscoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:998C4C02-4ADB-4081-8CBC-A3DFD3D78957
ok 113 discoveryActive should be false
ok 114 a,dvertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 08:44:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 08:44:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 08:44:53 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 08:44:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 08:44:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 08:44:55 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:11415d9b-7792-4a9e-83c7-bb9eb2060889 error: startListeningNotActive
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"imXAiMirAenFCovKFgZDLnDEtwupsf7r","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort ,is null
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"11415d9b-7792-4a9e-83c7-bb9eb2060889","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:56 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"11415d9b-7792-4a9e-83c7-b,b,9eb2060889","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:56 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FED1E17B-78AA-4765-9526-9B852A107292
[ThaliCore] Browser.startListening
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eo4mmjjdVF0ptAl3hCfxWqeYZTH0wm4l","error":"Illegal peerID","portNumber",:null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 08:44:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7BBDBC88-CAE2-45B4-9015-C55A14AF3254
[ThaliCore] Browser.startListening
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on starting
ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:44:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:9736f117-db9f-438e-91f5-2193b5747853
,ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:66D54677-E5CE-4872-AF60-920DE29F35DA
2017-07-21 0,8:44:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
[Tha,l,iCore] Browser.startListening
2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:59 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
2017-07-21 08:45:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","generation":0}'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0B635E3-F14B-483A-B337-CC90A5ACF439, (syncValue: xlyesSyZeXjivznb7cWtXYZiPD0kKBQK)'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5A,CF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
2017-07-21 08:45:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","generation":0}'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
2017-07-21 08:45:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","generation":0}'
2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E0,B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xlyesSyZeXjivznb7cWtXYZiPD0kKBQK","error":"Peer is unavailable","portNumber":null}'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xlyesSyZeXjivznb7cWtXYZiPD0kKBQK', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E0B635E3-F14B-483A-B337-CC90A5ACF439","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9F325A6-C7EE-4930-9B90-2AB7F638F9EB (syncValue: zfRPtpJigA8N4MExlHpxTRI,0Hyzxjjt6)'
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9F325A6-C7EE-4930-9B90-2AB7F,638F9EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
[ThaliCore] Advertiser: session connected Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
,[ThaliCore] Session.startOutputStream(with:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 5, 6, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56543
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zfRPtpJigA8N4MExlHpxTRI0Hyzxjjt6","error":null,"portNumber":56543}'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zfRPtpJigA8N4MExlHpxTRI0Hyzxjjt6', error: 'null', listeningPort: '56543''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) found active relay
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FAiwksmP3PUcRV1o1qfnoRXg30yw6thA","error":null,"portNumber":56543}'
,ok 146 No error
,ok 147 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 5, 6, 11, 12]
ok 148 Got null as expected
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) found active relay
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13rX3PiP31rOoSZQR6JY1J449S8Yp88z","error":null,"portNumber":56543}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-07-21 08:45:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeStreams() vs,ID:11
2017-07-21 08:45:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskI,dToSecret":null,"networkType":null}})'
2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:66D54677-E5CE-4872-AF60-920DE29F35DA
2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [4, 5, 6, 12]
2017-07-21 08:45:11 - INFO thaliMobile,: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56543
[ThaliCore] VirtualSocket.closeStr,eams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] Session.disconnect() peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:12 [4, 5,, 6]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017,-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
,# initial peer discovery
,2017-07-21 08:45:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 08:45:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 08:45:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'listening 56546'
,ok 151 Should throw
,# teardown
,2017-07-21 08:45:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 56548'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 56551'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 56555'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:16, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'listening 56560'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
,# teardown
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:16, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'listening 56564'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'listening 56568'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
ok 168 incoming should survive
ok 169 mux should have no streams
,# teardown
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:17, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'listening 56572'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 08:45:17 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 172 native server is nulled out
ok 173 native server should be cl,osed
ok 174 incoming has been removed
ok 175 Incoming should be done
ok 176 The mux object should be closed
ok 177 The mux stream should be closed
2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection ,<-> Mux - 0 - close'
,# teardown
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'listening 56576'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 08:45:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 08:45:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'listening 56628'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-07-21 08:45:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 08:45:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-07-21 08:45:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'listening 56632'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 188 we should not have gotten an error
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-21 08:45:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-21 08:45:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 190 server should be fine
ok 191 server should be open
ok 192 incoming has been removed
ok 193 The mux object should be closed
ok 194 The mux stream should be closed
,# teardown
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
,ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 56635'
ok 198 port must be in range
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 56636'
ok 199 second start should return same port
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 56638'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-07-21 08:45:21 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 203 Passed good id but bogus port
2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
,ok 206 No error should be set
ok 207 Retry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 56640
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:45:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0518CF61-E252-42B9-9611-C4C458B9CB70
2017-07-21 0,8:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
[Tha,l,iCore] Browser.startListening
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","generation":0}'
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 42482938-AF2F-480B-B29A-69D1D0864D42 (syncValue: QSM54WW9zhax54kEauJcShEfjAZCFCbX)'
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42,482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","generation":0}'
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","generation":0}'
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
2017-07-21 08:45:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","generation":0}'
2017-07-21 08:45:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:24 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,2482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,2482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,2482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QSM54WW9zhax54kEauJcShEfjAZCFCbX","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QSM54WW9zhax54kEauJcShEfjAZCFCbX', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9F325A6-C7EE-4930-9B90-2AB7F638F9EB (syncValue: fNfv2HXKYDXNf1PSTr3UXwJ,1KLQSu8Yk)'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9F325A6-C7EE-4930-9B90-2AB7F,638F9EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,0,8:45:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772
[ThaliCore] Advertiser: session connected Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
[ThaliCore] Advertiser: session connected Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772
,[ThaliCore] Session.session(_:peer:didChange:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fNfv2HXKYDXNf1PSTr3UXwJ1KLQSu8Yk","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:45:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fNfv2HXKYDXNf1PSTr3UXwJ1KLQSu8Yk', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:39 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B9F325A6-C7EE-4930-9B90-2AB7F638F9EB","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:45:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:45:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DE913D1C-0249-4CCF-AF63-177E5F6EFB18 (syncValue: 537wj0TYliH9yIM4rm9BEvB,nH2VLEU9N)'
2017-07-21 08:45:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5,F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56658
2017-07-21 08:45:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"537wj0TYliH9yIM4rm9BEvBnH2VLEU9N",,"error":null,"portNumber":56658}'
2017-07-21 08:45:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '537wj0TYliH9yIM4rm9BEvBnH2VLEU9N', error: 'null', listeningPort: '56658''
,ok 212 should be equal
2017-07-21 08:45:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F178AC04-DA74-48EA-963C-5633E8815F6D (syncValue: PCLOicvGlv8Yge7jlimC0woHWoXSSYbF)'
2017-07-21 08:45:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,ected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56662
,2017-07-21 08:45:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PCLOicvGlv8Yge7jlimC0woHWoXSSYbF","error":null,"portNumber":56662}'
,2017-07-21 08:45:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PCLOicvGlv8Yge7jlimC0woHWoXSSYbF', error: 'null', listeningPort: '56662''
,ok 213 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:45:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0518CF61-E252-42B9-9611-C,4C458B9CB70
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56658
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:F178AC04-DA74-48EA-963C-5633E8815F6D
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56662
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
,[ThaliCore] Session.deinit peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
,[ThaliCore] Session.session(_:peer:didChange:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:45:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"537wj0TYliH9yIM4rm9BEvBnH2VLEU9N","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 56664
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:45:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1D07C8CF-1737-4DDE-9F61-B35248B29157
2017-07-21 0,8:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
[Tha,l,iCore] Browser.startListening
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
2017-07-21 08:45:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","generation":0}'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F178AC04-DA74-48EA-963C-5633E8815F6D, (syncValue: f6zuwXmGKBUUndHybezj6IcbMCDWH0dZ)'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E88,15F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","generation":0}'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generatio,n,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
":0}'
2017-07-21 08:45:48 - ,DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMo,bileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86F951D8-EEC1-4408-BE41-8D2039509318
[ThaliCore] Advertiser: session connected Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:86F951D8-EEC1-4408-BE41-8D2039509318 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F178AC04,-DA74-48EA-963C-5633E8815F6D error: max retries exceeded
2017-07-21 08:45:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f6zuwXmGKBUUndHybezj6IcbMCDWH0dZ","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:45:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'f6zuwXmGKBUUndHybezj6IcbMCDWH0dZ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:45:58 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 08:45:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:45:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:45:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DE913D1C-0249-4CCF-AF63-177E5F6EFB18 (syncValue: R2SBIGs,YdbOfQu4a3SObtuS32OYJoOBQ)'
2017-07-21 08:45:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DE913D1C-0249,-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:45:58 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 08:45:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:86F951D8-EEC1-4408-BE41-8D2039509318
,[ThaliCore] Session.session(_:peer:didChange:) peer:86F951D8-EEC1-4408-BE41-8D2039509318 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,E913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,E913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,E913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
[ThaliCore] Advertiser: session connected Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DE,913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DE913D1C,-0249-4CCF-AF63-177E5F6EFB18 error: max retries exceeded
2017-07-21 08:46:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R2SBIGsYdbOfQu4a3SObtuS32OYJoOBQ","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:46:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'R2SBIGsYdbOfQu4a3SObtuS32OYJoOBQ', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:46:09 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:46:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 08:46:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DE913D1C-0249-4CCF-AF63-177E5F6EFB18","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:46:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:46:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:46:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0012F678-84C7-457A-A520-2401E6F33249 (syncValue: d1RG3sB,aHDDOzs7N5lmfUMEhKrQZFUAx)'
2017-07-21 08:46:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0012F678-84C7,-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 08:46:09 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 08:46:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0012F678-84C7-457A-A520-2401E6F33249:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0012F678-84C7-457A-A520-2401E6F33249:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56690
2017-07-21 08:46:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"d1RG3sBaHDDOzs7N5lmfUMEhKrQZFUAx",,"error":null,"portNumber":56690}'
2017-07-21 08:46:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd1RG3sBaHDDOzs7N5lmfUMEhKrQZFUAx', error: 'null', listeningPort: '56690''
,ok 219 should be equal
ok 220 should be equal
ok 221 should be equal
2017-07-21 08:46:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 184ABA8E-200B-45B1-B43C-D18C7DCD96DA (syncValue: g9cNrphOtpU0urn3khe9Jf7sS5yhTtfs)'
2017-07-21 08:46:,12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56696
,2017-07-21 08:46:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"g9cNrphOtpU0urn3khe9Jf7sS5yhTtfs","error":null,"portNumber":56696}'
,2017-07-21 08:46:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'g9cNrphOtpU0urn3khe9Jf7sS5yhTtfs', error: 'null', listeningPort: '56696''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1D07C8CF-1737-,4DDE-9F61-B35248B29157
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0012F678-84C7-457A-A520-2401E6F33249
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56690
[ThaliCore] Session.disconnect() peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:86F951D8-EEC1-4408-BE41-8D2039509318 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
,[ThaliCore] Session.deinit peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56696
,[ThaliCore] Session.disconnect() peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:46:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:16 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'listening 56700'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 56701'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8CBEC326-06E5-4BB8-ACFE-9B09005EE1F3
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 232 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertis,ingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"route,r":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:18 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 234 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:18 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 56702'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B8C3FC68-96DB-4E05-87EE-18B8259F0020", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:B8C3FC68-96DB-4E05-87EE-18B8259F0020
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:4,6:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B8C3FC68-96DB-4E05-87EE-18B8259F0020", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:B8C3FC68-96DB-4E05-87EE-18B8259F0020
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,7-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B8C3FC68-96DB-4E05-87EE-18B8259F0020
[ThaliCore] Advertiser.stopAdvertising() peerID:B8C3FC68-96DB-4E05-87EE-18B8259F0020
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'listening 56705'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:19 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 08:46:19 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 243 specific error expected
,# teardown
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 56706'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CF8C7516-7AB5-45B4-A580-B5D5E126A93B
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE40C7C1-9EA6-47AD-98F9-56D20D12E148", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,AE40C7C1-9EA6-47AD-98F9-56D20D12E148
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AE40C7C1-9EA6-47AD-98F9-56D20D12E148
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 56709'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CF0EE33C-D7F6-451E-998F-6AF80FCC8E31
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A935FF70-2084-42CA-8A28-AAF37AE3145B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,A935FF70-2084-42CA-8A28-AAF37AE3145B
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A935FF70-2084-42CA-8A28-AAF37AE3145B
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'listening 56711'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E691F794-75F5-4037-8169-0493274038CE
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4086310A-AEA0-4BF7-A048-DAB71F45F749", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,4086310A-AEA0-4BF7-A048-DAB71F45F749
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:21 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:21 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4086310A-AEA0-4BF7-A048-DAB71F45F749
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] B,rowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:21 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 08:46:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:21 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 08:46:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 08:46:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 08:46:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 56714'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8E2AAC71-696C-40D3-8CB9-8CBBA46AC361
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 56715'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18C30248-C499-4DAD-BD64-30FBCD7CD57D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:18C30248-C499-4DAD-BD64-30FBCD7CD57D
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:18C30248-C499-4DAD-BD64-30FBCD7CD57D
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 276 discoveryActive matches
ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 56717'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO, thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'listening 56718'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B84DB635-8FC3-4536-B4C2-EA62EB0EE07B
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "982EECC7-3173-4A62-8EB8-BF382A515E60", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:982EECC7-3173-4A62-8EB8-BF382A515E60
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
2017-07-21 08:46:27 - DEBUG thali,MobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A,-A520-2401E6F33249", generation: 0)
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 279 portNumber equal null
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:982EECC7-3173-4A62-8EB8-BF382A515E60
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 08:46:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:27 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:27 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper:, 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 08:46:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 08:46:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 08:46:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'listening 56720'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
[ThaliCore] Browser.startListening
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 184ABA8E-200B-45B1-B43C-D18C7DCD96DA (syncValue: JPkORsEKfRtc7midzWI4bMWbxJi8WF0n)'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
2017-07-21 08:46:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}]'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC9895C0-1863-4433-8EB2-717D7B77F3A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC9895C0-1863-4433-8EB2-717D7B77F3A7", generation: 0)
2017-07-21 08:46:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","generation":0}]'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C36EA720-3E99-469E-993F-ADCEBE140567
[ThaliCore] Advertiser: session connected Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C36EA720-3E99-469E-993F-ADCEBE140567 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,84ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0012F678-84C7-457A-A520-2401E6F33249:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
2017-07-21 08:46:33 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}]'
2017-07-21 08:46:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","generation":0}'
,2017-07-21 08:46:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:46:33 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"0012F678-84C7-457A-A520-2401E6F33249","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C36EA720-3E99-469E-993F-ADCEBE140567
,[ThaliCore] Session.session(_:peer:didChange:) peer:C36EA720-3E99-469E-993F-ADCEBE140567 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C36EA720-3E99-469E-993F-ADCEBE140567
[ThaliCore] Session.startOutputStream(with:) peer:C36EA720-3E99-469E-993F-ADCEBE140567
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [4, 5, 6, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,84ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,84ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
[ThaliCore] Advertiser: session connected Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:184ABA8E,-200B-45B1-B43C-D18C7DCD96DA error: max retries exceeded
2017-07-21 08:46:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JPkORsEKfRtc7midzWI4bMWbxJi8WF0n","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:46:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JPkORsEKfRtc7midzWI4bMWbxJi8WF0n', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:46:40 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:46:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:46:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 08:46:40 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:46:40 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 08:46:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:46:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 08:46:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:46:40 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 31EB686E-9044-4EEE-A274-31621F2214FC (syncValue: yAR3iCCYBRY3uGqKDbzpwuxKFDqvAzSU)'
2017-07-21 08:46:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31EB686E-9044-4EEE-A274-3,1621F2214FC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h,:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
,[ThaliCore] Session.session(_:peer:didChange:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
[ThaliCore] Session.startOutputStream(with:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [4, 5, 6, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56734
2017-07-21 08:46:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yAR3iCCYBRY3uGqKDbzpwuxKFDqvAzSU","error":null,"portNumber":56734}'
,2017-07-21 08:46:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yAR3iCCYBRY3uGqKDbzpwuxKFDqvAzSU', error: 'null', listeningPort: '56734''
,2017-07-21 08:46:42 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [4, 5, 6, 13, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:46:43 - DEBUG testUtils: 'Got response data'
2017-07-21 08:46:43 - DEBUG testUtils: 'Got end'
ok 285 response body should match testData
ok 286 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE
2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:46:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 08:46:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:43 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidD,isconnect(_:withError:) client disconnected
[ThaliCore] BrowserManager.disconnect peer:31EB686E-9044-4EEE-A274-31621F2214FC
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketError,Domain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectH,andler removed virtual socket vsID:13
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56734
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remove,d, count:0
[ThaliCore] VirtualSocket.deinit vsID:13 [4, 5, 6, 14, 15]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [4, 5, 6, 15]
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [4, 5, 6]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:31EB686E-9044-4EEE-A274-31621F2214FC:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yAR3iCCYBRY3uGqKDbzpwuxKFDqvAzSU","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:46:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
,[ThaliCore] Session.deinit peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:9366C858-869E-4C6B-B9C3-2F5DE82E0A93
,[ThaliCore] Session.session(_:peer:didChange:) peer:C36EA720-3E99-469E-993F-ADCEBE140567 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,# will fail bad PSK connection between peers
,ok 288 FIX ME, PLEASE!!!
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 08:46:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 290 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:45 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 08:46:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 292 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 293 specific error should be returned
,# teardown
,2017-07-21 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:46:46 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 297 specific error should be returned
,# teardown
,ok 298 error should be null
ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'listening 56736'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 303 error should be null
ok 304 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 305 error should be null
ok 306 error should be null
,# setup
,ok 307 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'listening 56737'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16CC4C27-5D11-47CA-8B45-C9AA28265C10
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 310 error should be null
ok 311 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC9895C0-1863-4433-8EB2-717D7B77F3A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC9895C0-1863-4433-8EB2-717D7B77F3A7", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","generation":0}]'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","generation":0}'
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 08:46:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 error should be null
,ok 313 error should be null
,# setup
,ok 314 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'listening 56738'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD727BE2-D966-46CC-B487-AC55CFEC66CC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FD727BE2-D966-46CC-B487-AC55CFEC66CC
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
ok 316 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD727BE2-D966-46CC-B487-AC55CFEC66CC", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD727BE2-D966-46CC-B487-AC55CFEC66CC
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 317 error should be null
,ok 318 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD727BE2-D966-46CC-B487-AC55CFEC66CC
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD727BE2-D966-46CC-B487-AC55CFEC66CC
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 319 error should be null
,ok 320 error should be null
,# setup
,ok 321 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'listening 56741'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 326 error should be null
ok 327 error should be null
,# setup
,ok 328 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 08:46:48 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 329 This should not cause wifi to fail
ok 330 native router should be bad
,# teardown
,ok 331 error should be null
ok 332 error should be null
,# setup
,ok 333 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'listening 56742'
ok 334 first call should succeed
ok 335 first call should succeed
ok 336 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:49 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 337 error should be null
ok 338 error should be null
,# setup
,ok 339 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 08:46:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 340 error should be null
ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 08:46:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 343 error should be null
ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 08:46:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"491b620f-6459-4961-b2cf-91c0b8c88bbd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 346 should be calle,d once
ok 347 should not have been called more than once
,# teardown
,2017-07-21 08:46:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"491b620f-6459-4961-b2cf-91c0b8c88bbd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 348 error should be null
ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# can get the network status
,ok 351 network status should have certain non-empty properties
,# teardown
,ok 352 error should be null
ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 355 we have not added peer to the cache yet
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"be8e32ed-a9df-45fe-b1ec-b04352d1e5f5","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 356 peer should be available
ok 357 cache contains native peer
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"be8e32ed-a9df-45fe-b1ec-b04352d1e5f5","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 358 peer should be unavailable
ok 359 peer has been removed from cache
,# teardown
,ok 360 error should be null
ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 363 we have not added peer to the cache yet
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f1683ae6-f302-4d2f-bb56-5027ff9bfc99","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 364 peer should be available
ok 365 cache contains wifi peer
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f1683ae6-f302-4d2f-bb56-5027ff9bfc99","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 366 peer should be unavailable
ok 367 peer has been removed from cache
,# teardown
,ok 368 error should be null
ok 369 error should be null
,# setup
,ok 370 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"421266bc-e0c4-46d3-a6af-6c4222e125ef","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 371 first peer is a,vailable
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e795870f-222a-4d2c-8a88-58be80a1488c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 372 second, peer is available
ok 373 first and second peers are different
,# teardown
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"421266bc-e0c4-46d3-a6af-6c4222e125ef","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e795870f-222a-4d2c-8a88-58be80a1488c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 374 error should be null
ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 377 should not be in cache at start
2017-07-21 08:46:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c060a44-db58-4e55-9f4c-fc9e46bda7e3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 378 peer is available
,# teardown
,2017-07-21 08:46:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3c060a44-db58-4e55-9f4c-fc9e46bda7e3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 379 error should be null
ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 08:46:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 382 error should be null
ok 383 error should be null
,# setup
,ok 384 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 08:46:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 385 error should be null
ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e483e1cf-410b-4840-aa57-af3b57e42616","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 388 peer should be available
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e483e1cf-410b-4840-aa57-af3b57e42616","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 389 peer should be ,available
ok 390 should store correct generation
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e483e1cf-410b-4840-aa57-af3b57e42616","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 391 error should be null
ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'listening 56743'
2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a10026b-d25f-487b-9387-78f770e7a0e3","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 394 discovered correct peer
ok 395 got correct generation
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a10026b-d25f-487b-9387-78f770e7a0e3","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 396 discovered corr,ect peer
ok 397 got correct generation
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4a10026b-d25f-487b-9387-78f770e7a0e3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 398 error should be null
ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'listening 56744'
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b02b3e05-6a74-49f7-9598-aa65a7cee27c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 401 discovered avai,lable peer
ok 402 peer is available
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b02b3e05-6a74-49f7-9598-aa65a7cee27c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 403 error should be null
ok 404 error should be null
,# setup
,ok 405 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7bef25a4-c77e-428c-817d-9c1c8917ca9f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 406 peer should be available
2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7bef25a4-c77e-428c-817d-9c1c8917ca9f","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 407 peer should be unavailable
ok 408 should be removed from cache
,# teardown
,ok 409 error should be null
ok 410 error should be null
,# setup
,ok 411 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'listening 56745'
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6613c362-b0bc-44b4-a521-f0a03fb7649d","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 412 first peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"573bce92-2a21-4a2a-a9f8-79a09391af21","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 413 second peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"573bce92-2a21-,4a2a-a9f8-79a09391af21","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 414 peer became unavailable
ok 415 it was wifi peer
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handle,P,eer {"peerIdentifier":"573bce92-2a21-4a2a-a9f8-79a09391af21","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 416 we found peer again
ok 417 it was wifi peer
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAv,ailabilityChanged from emitPeerUnavailable {"peerIdentifier":"573bce92-2a21-4a2a-a9f8-79a09391af21","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 418 peer became unavailable
ok 419 it was wifi peer
,# teardown
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6613c362-b0bc-44b4-a521-f0a03fb7649d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 08:46:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 423 error should be null
ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'listening 56746'
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05d95093-d26d-426d-bab8-cfb6acba6aef","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 426 first peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"72b87dec-35dc-4a7e-b6ef-2a5425c8f3d5","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 427 second peer is expected to be available
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"05d95093-d26d-426d-bab8-cfb6acba6aef","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 428 pee,r became unavailable
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"72b87dec-35dc-4a7e-b6ef-2a5425c8f3d5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 429 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 430 error should be null
,ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 08:46:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 433 error should be null
ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 08:46:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 436 error should be null
,ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d3d003-73e5-4c7d-84b9-2c476503901b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 439 peer discovered first time does not have new address
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d3d003-73e5-4c7d-84b9-2c476503901b","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 440 address has not been changed
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d3d003-73e5-4c7d-84b9-2c476503901b","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 441 new port handled correctly
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d3d003-73e5-4c7d-84b9-2c476503901b","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 442 new host handled correctly
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"25d3d003-73e5-4c7d-84b9-2c476503901b","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 443 newAddressPort is null for unavailable peers
,# teardown
,ok 444 error should be null
ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 08:46:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 450 NOT IMPLEMENTED # SKIP
,# teardown
,ok 451 error should be null
ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 08:46:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 457 should be equal
,# teardown
,ok 458 error should be null
ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 08:46:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 461 error should be null
ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 464 contains expected properties
ok 465 the same ho,stAddress
ok 466 the same portNumber
,# teardown
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 error should be null
ok 468 error should be null
,# setup
,ok 469 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 470 contains expected properties
ok 471 the same hostAddress
ok 472 the same portNumber
,# teardown
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'listening 56747'
2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8e29292b-20af-4003-8df9-ead31b0451ef","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 476 Got specific error message
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8e29292b-20af-4003-8df9-ead31b0451ef","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 477 error should be null
ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'listening 56748'
2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c487a956-04f1-4f24-a8da-42626de17e38","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:c487a956-04f1-4f24-a8da-42626de17e38
ok 480 native wrapper `disconnect` called once
ok 481 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c487a956-04f1-4f24-a8da-42626de17e38","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 482 error should be null
ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 08:46:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 485 error should be null
ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 08:46:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 488 error should be null
,ok 489 error should be null
,# setup
,ok 490 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 491 error should be null
,ok 492 error should be null
,# setup
,ok 493 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 494 error should be null
ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 497 error should be null
ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 08:47:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 500 error should be null
ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 08:47:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'listening 56749'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:28026663-59C5-4E05-932A-4B2E1FECD4BE
[ThaliCore] Browser.startListening
2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d80b474-3926-493c-8265-5c8466e68f61","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 Peer availabilities has one entry for our connection type
2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9943fb6b-9a9a-4b4b-b2e4-d9d99fddc936","connectionType":"tcp","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
,ok 507 Peer availabilities has one entry for our connection type
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1d80b474-3926-493c-8265-5c8466e68f61","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9943fb6b-9a9a-4b4b-b2e4-d9d99fddc936","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:47:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 508 No peers
,ok 509 No peers
,ok 510 No peers
,# teardown
,ok 511 error should be null
,ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'listening 56750'
2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fd13d9bf-fd6d-49f4-b24a-c07aeff895ac","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 514 1
ok 515 2
2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b9b9c78b-7e9e-4257-b848-6b2c3059f16f","connectionType":"MPCF","peerAvailabl,e":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 08:47:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fd13d9bf-fd6d-49f4-b24a-c07aeff895ac","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:47:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b9b9c78b-7e9e-4257-b848-6b2c3059f16f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:47:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:47:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:47:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:47:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:47:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 516 error should be null
ok 517 error should be null
,# setup
,ok 518 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 08:47:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 519 error should be null
ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'listening 56751'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
,[ThaliCore] Browser.startListening
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0,
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,ok 526 error should be null
,ok 527 error should be null
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:47:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 184ABA8E-200B-45B1-B43C-D18C7DCD96DA (syncValue: 0)'
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
2017-07-21 08:47:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","generation":0}]'
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","generation":0}'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:47:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
2017-07-21 08:47:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","generation":0}]'
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","generation":0}'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:47:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
[ThaliCore] Advertiser: session connected Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,84ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
[ThaliCore] Advertiser: session connected Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
[ThaliCore] Session.startOutputStream(with:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [4, 5, 6, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,84ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
2017-07-21 08:47:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}]'
2017-07-21 08:47:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}'
2017-07-21 08:47:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"31EB686E-9044-4EEE-,A274-31621F2214FC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:47:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","connectionType":"MPCF","peerAv,a,ilable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,84ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
[ThaliCore] Session.startOutputStream(with:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [4, 5, 6, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,4ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:184ABA8E,-200B-45B1-B43C-D18C7DCD96DA error: max retries exceeded
[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0",,"error":"Connection could not be established","portNumber":null}'
2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"portNu,m,ber":null,"recreated":true}'
2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":tr,ue}'
2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:47:14 - DEBUG thal,iMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8459AAD8-241C-4AD7-BE87-B4FA7347D935 (syncValue: 1)'
2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:47:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:47:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:47:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:47:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 08:47:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
2017-07-21 08:47:16 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}]'
2017-07-21 08:47:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","generation":0}'
,2017-07-21 08:47:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:47:16 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
2017-07-21 08:47:17 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
2017-07-21 08:47:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:47:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 08:47:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56765
2017-07-21 08:47:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":56765,}'
,2017-07-21 08:47:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E271E485-9892-4779-A404-B48D6F6DDB5A (syncValue: 2)'
2017-07-21 08:47:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [4, 5, 6, 16, 17, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:47:17 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:17 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56769
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":56769,}'
,2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 31EB686E-9044-4EEE-A274-31621F2214FC (syncValue: 3)'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", ge,neration: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 184ABA,8E-200B-45B1-B43C-D18C7DCD96DA (syncValue: 4)'
,2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 184ABA,8E-200B-45B1-B43C-D18C7DCD96DA (syncValue: 5)'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96D,A,", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 08:47:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emittin,g {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"31EB686E-9044-4EEE-A274-31621F2214FC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativ,eWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailability,Changed - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"184ABA8E-200B-,45B1-B43C-D18C7DCD96DA","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 08:47:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA",,",peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserManager.disconnect peer:31EB686E-9044-4EEE-A274-31621F2214FC
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCor,e] BrowserManager.disconnect peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA
[ThaliCore] Session.startOutputStream(with:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] BrowserManager.disconnect peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [4, 5, 6, 16, 17, 18, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandl,er
,2017-07-21 08:47:22 - DEBUG testUtils: 'Got response data'
2017-07-21 08:47:22 - DEBUG testUtils: 'Got end'
ok 528 received all uuids
,# teardown
,2017-07-21 08:47:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:47:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E271E485-9892-4779-A404-B48D6F6DDB5A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11
,2017-07-21 08:47:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:47:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:47:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:47:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:47:22 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:47:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:,O,ptional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 529 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false s,ocket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 530 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] Adver,tiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:17
# setup
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [4, 5, 6, 17, 18, 19]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliC,ore] VirtualSocket.deinit vsID:17 [4, 5, 6, 18, 19]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [4, 5, 6, 19]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [4, 5, 6]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 531 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 08:47:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 532 error should be null
ok 533 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 534 getPeerIdentifier
ok 535 getConnectionType
ok 536 getActionType
ok 537 getActionState
ok 538 getPskIdentity
,ok 539 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 540 initial state
ok 541 after start
,2017-07-21 08:47:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 08:47:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 544 clean kill
ok 545 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 546 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 547 forever agent should have it's own destroy method
,ok 548 agent's destroy should be called
ok 549 agent's destroy should not be called again
,ok 550 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 551 Entry counter must be 1
ok 552 Entry exists
ok 553 Size must be 1
ok 554 Entry counter must be 2
ok 555 Entry exists
ok 556 Size must be 2
ok 557 Entry counter must be 1
ok 558 Entry exists
ok 559 Size must be 3
ok 560 Entry counter must be 2
ok 561 Entry exists
ok 562 Size must be 4
,ok 563 Entry 1_1 should not be found
,ok 564 Entry 1_1 does not exist
,ok 565 Size must be 3
,ok 566 Entry 1_2 should not be found
,ok 567 Entry 1_2 does not exist
,ok 568 Size must be 2
,ok 569 should be equal
,ok 570 Entry 2_1 should not be found
,ok 571 Entry 2_2 should not be found
,ok 572 Entry 2_1 does not exist
,ok 573 Entry 2_2 does not exist
,ok 574 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 575 Size must be100
,ok 576 Entries between 20 and MAXSIZE + 20 should exist
,ok 577 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 578 Entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
ok 580 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 581 WAITING state entry should not be removed
,ok 582 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 583 Size should be MAXSIZE
,ok 584 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 585 Kill should be called once
,ok 586 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 587 is an agent
,ok 588 enqueue is fine
ok 589 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 590 is an agent
ok 591 first enqueue is fine
ok 592 is an agent
ok 593 second enqueue is fine
ok 594 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 595 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 596 is an agent
ok 597 good enqueue
,ok 598 Identity should match
,2017-07-21 08:47:31 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:31 - DEBUG testUtils: 'Got end'
,ok 599 Got expected response
,ok 600 Got psk call back
,# teardown
,2017-07-21 08:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 601 is an agent
ok 602 enqueue worked
,ok 603 is an agent
ok 604 enqueue 2 worked
ok 605 enqueue is not available when stopped
ok 606 start action is killed
ok 607 killed action is still killed
ok 608 enqueued action when stopped is killed
ok 609 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 610 good start
ok 611 good enqueue
,ok 612 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 613 null arg
ok 614 wrong arg type
ok 615 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 616 good enqueue
ok 617 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 618 good enqueue
ok 619 2nd good enqueue
ok 620 we are in the pool
ok 621 We are out of the pool
ok 622 Action was killed
ok 623 The original kill was called too
ok 624 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 625 good enqueue
,ok 626 first kill
,ok 627 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 628 1st good enqueue
ok 629 2nd good enqueue
,ok 630 1st action is in the pool
ok 631 2nd action is in the pool
ok 632 1st action is out of the pool
ok 633 2st action is out of the pool
ok 634 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 08:47:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 635 Got right error
,ok 636 Start should not be called
,ok 637 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:34 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 638 Got right error
,ok 639 Start should not be called
,ok 640 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 641 Got null
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 642 is an agent
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 643 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 644 Got Null
ok 645 Got another null
2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 646 is an agent
2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 647 is an agent
2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 648 Action 1 killed at least once
,ok 649 Action 1 went first
ok 650 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
ok 651 should have gotten null
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activit,y time out - noActivityTimeOut'
ok 652 Should have stopped nicely
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startErr,or: eeeek! - failureButNotAvailable'
ok 653 Still looking for null
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-07-21 08:47:36 - DEBUG thaliPee,rPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone,!'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 654 Yup, another null
ok 655 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 656 Null 1
ok 657 (unnamed assert)
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 658 is an agent
ok 659 Null 3
ok 660 Replication not yet called
ok 661 Notification 2 not yet called
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 662 is an agent
ok 663 Notification went first
ok 664 Notification 2 not called yet
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 665 is, an agent
ok 666 Notification finished
ok 667 Replication finished
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Ide,ntifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 668 is an agent
ok 669 First does not throw
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Action ,Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 670 is an agent
ok 671 Second does not throw
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Ty,pe: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 first ok
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 second ok
,ok 676 third ok
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 08:47:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 08:47:38 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 677 peerIdentifier should match
,ok 678 generation should match
,ok 679 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 680 good beacon
,ok 681 good preAmble
,ok 682 public keys match!
,ok 683 must return null after successful call
ok 684 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 08:47:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 08:47:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 08:47:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 685 Response should be NETWORK_PROBLEM
ok 686 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 08:47:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 687 Resolution should be BAD_PEER
,ok 688 correct error message
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 689 Call start once
,ok 690 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 691 must return null after successful call.
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 692 Should be Killed
,ok 693 Start after killed
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 694 Should be KILLED
,ok 695 must return null after successful kill
,# teardown
,2017-07-21 08:47:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 696 Should be KILLED
ok 697 must return null after successful kill
,# teardown
,2017-07-21 08:47:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 698 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 699 must return null after successful call
,# teardown
,2017-07-21 08:47:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 08:47:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 700 Should be NETWORK_PROBLEM caused closing server socket
ok 701 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 702 Should be NETWORK_PROBLEM caused closing client socket
,ok 703 Should be Could not establish TCP connection
,# teardown
,2017-07-21 08:47:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 704 publicKeysToNotify cannot be null
ok 705 ecdh for local device cannot be null
ok 706 milliseconds cannot be less than 0
ok 707 milliseconds cannot be 0
ok 708 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 709 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 710 should be equal
,ok 711 should be equal
,ok 712 (unnamed assert)
,ok 713 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 714 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 715 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 716 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 717 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 719 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-21 08:47:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 721 should be equal
ok 722 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 723 right number of calls to address book
,ok 724 good preAmble
ok 725 good unencryptedKeyId
,ok 726 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 727 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 728 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 729 Matching numbers
,ok 730 We have an entry!
,ok 731 keys match
,ok 732 secrets match
,ok 733 We have an entry!
,ok 734 keys match
ok 735 secrets match
,ok 736 We have an entry!
ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 739 Streams have same length
,ok 740 matching size
,ok 741 keys match
,ok 742 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 743 should be equal
,ok 744 peerDictionalty contains 2 peers
,ok 745 bluetooth peer's notification has correct connection type
,ok 746 tcp peer's notification has correct connection type
,2017-07-21 08:47:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 08:47:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:47:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 747 notification peer dictionary contains exactly 1 peer
2017-07-21 08:48:01 - WARN thaliNotificationClient: 'peer is not available'
ok 748 notification peer dictionary does not contain any peers
2017-07-21 08:48:01 - DEBUG thaliPeerPoolDefault: 'Got, err   peer not available'
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 749 entry exists
,ok 750 entry is resolved
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 751 Action should be KILLED
,ok 752 Peer state should be RESOLVED
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 753 hostAddress must match
,ok 754 portNumber must match
,ok 755 suggestedTCPTimeout must match
,ok 756 connectionType must match
,ok 757 peerIDs must match
,# teardown
,2017-07-21 08:48:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 758 Correct error
,# teardown
,2017-07-21 08:48:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 759 hostAddress must match
,ok 760 portNumber must match
,ok 761 suggestedTCPTimeout must match
,ok 762 connectionType must match
,ok 763 peerIds must match
,# teardown
,2017-07-21 08:48:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 766 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 action should be resolved with NETWORK_PROBLEM error
ok 768 correct number of requests
ok 769 correct number of failures
ok 770 correct final peer state
,# teardown
,2017-07-21 08:48:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 08:48:08 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 08:48:08 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 771 peerDictionary should become empty
# teardown
,2017-07-21 08:48:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 08:48:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 failed with expected error
ok 773 peer state should be RESOLVED
,# teardown
,2017-07-21 08:48:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 08:48:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 774 First action failed
,ok 775 second action killed
# teardown
,2017-07-21 08:48:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 776 secrets are equal
,ok 777 Public key matches with the server key
,ok 778 hostAddress must match
,ok 779 portNumber must match
,ok 780 suggestedTCPTimeout must match
,ok 781 connectionType must match
,# teardown
,2017-07-21 08:48:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 782 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 783 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 08:48:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 785 All keys need to be available in the cache
,ok 786 All entries should be expired after 1 second
# teardown
,2017-07-21 08:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 787 Size of the cache should be 2
ok 788 Cache doesn't contain dictionary1
,ok 789 Size of the cache should be 1
ok 790 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 08:48:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 791 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 792 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 08:48:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,ok 794 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 795 no error
,ok 796 should be 204
,# teardown
,2017-07-21 08:48:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 797 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:48:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 798 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:48:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 799 no error
,ok 800 should be 200
,ok 801 should be equal
,ok 802 should be equal
,ok 803 (unnamed assert)
,ok 804 no error
,ok 805 should be 204
,# teardown
,2017-07-21 08:48:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 806 error should be null
ok 807 should be 204
# teardown
,2017-07-21 08:48:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 808 should be 404
# teardown
,2017-07-21 08:48:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 809 equal keys
ok 810 not equal connection type
ok 811 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 08:48:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 813 second cleared dictionary
,2017-07-21 08:48:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 814 First start and on called correctly
,ok 815 First stop and removeListener called correctly
ok 816 first action kill called
ok 817 second action kill called
ok 818 first cleared dictionary
ok 819 first cleared pool
ok 820 second cleared dictionary
ok 821 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 822 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-21 08:48:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 823 listener has been set
,ok 824 peer dictionary has expected number of entries
,ok 825 Dictionary and pool have same action
,ok 826 ads match
,ok 827 PouchDB matches
,ok 828 DB Names match
,ok 829 public keys match
,ok 830 peer dictionary has expected number of entries
,ok 831 Dictionary and pool have same action
,ok 832 ads match
,ok 833 PouchDB matches
,ok 834 DB Names match
,ok 835 public keys match
,2017-07-21 08:48:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 836 start called once
,ok 837 One entry left
,ok 838 Dictionary and pool have same action
,ok 839 Start never called
,ok 840 Kill called once
,ok 841 no entries left
,ok 842 Third action is dead
,ok 843 peer dictionary has expected number of entries
,ok 844 Dictionary and pool have same action
,ok 845 ads match
,ok 846 PouchDB matches
,ok 847 DB Names match
,ok 848 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-21 08:48:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 08:48:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:48:22 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 08:48:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 849 right error
,# teardown
,2017-07-21 08:48:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 850 right error
,# teardown
,2017-07-21 08:48:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 08:48:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 852 Got error as expected
,# teardown
,2017-07-21 08:48:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 08:48:25 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 08:48:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 853 Got error as expected
,# teardown
,2017-07-21 08:48:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 08:48:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:29 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-07-21 08:48:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 08:48:32 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:32 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:35 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 856 should be equal
ok 857 All tests passed!
,# teardown
,2017-07-21 08:48:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 08:48:36 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 858 action should be killed
ok 859 Error should be timed out
,ok 860 No doc found
,# teardown
,2017-07-21 08:48:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 08:48:39 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:39 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 861 should be equal
,2017-07-21 08:48:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 862 action should be killed
ok 863 Error should be timed out
,# teardown
,2017-07-21 08:48:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 864 socket hung up
,# teardown
,2017-07-21 08:48:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 865 same getPeerAdvertisesDataForUs
ok 866 Same pouchdB
ok 867 same localDbName
ok 868 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 08:48:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'listening 56896'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Browser.startListening
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Advertiser: session connected Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Advertiser: session connected Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","generation":0}]'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:48:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"71D9EF6F-6E7A-4A39-8A89-C097EA09540E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 71D9EF6F-6E7A-4A39-8A89-C097EA09540E (syncValue: 6)'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71,D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","generation":0}]'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","generation":0}'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:48:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.session(_:peer:didChange:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [4, 5, 6, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOu,tputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [4, 5, 6, 20, 21]
[ThaliCore] TCPClient.con,nectToLocalhost(onPort:)
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [4, 5, 6, 21]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] Session.session(_:peer:didChange:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56901
2017-07-21 08:48:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":56901}'
,2017-07-21 08:48:49 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 52D46020-2085-46B8-B61C-0464BC17069B (syncValue: 7)'
,2017-07-21 08:48:49 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [4, 5, 6, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [4, 5, 6, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:22 [4, 5, 6, 21, 23]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [4, 5, 6, 21]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [4, 5, 6, 21, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [4, 5, 6, 21, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:48:50 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [4, 5, 6, 21, 24, 25, 26]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [4, 5, 6, 21, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [4, 5, 6, 21, 24, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [4, 5, 6, 21, 24, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [4, 5, 6, 21, 24, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [4, 5, 6, 21, 24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [4, 5, 6, 21, 24, 25, 26, 27, 28, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [4, 5, 6, 21, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 32, 33]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] Virtu,alSocket.init(inputStream:outputStream:) vsID:34 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket.deinit vsID:37 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 38, 39]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 38, 40]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 38, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,2 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 38, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 41, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] ,TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56925
,2017-07-21 08:48:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":56925}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42, 43]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42, 44, 45, 46]
[ThaliCore] B,rowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Session.startOutputStream(with:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,7 [4, 5, 6, 21, 24, 25, 26, 27, 28, 30, 31, 33, 34, 35, 42, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:25 [4, 5, 6, 21, 24, 26, 27, 28, 30, 31, 33, 34, 35, 42, 44, 45, 46, 47]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [4, 5, 6, 21, 24, 26, 28, 30, 31, 33, 34, 35, 42, 44, 45, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Tha,liCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [4, 5, 6, 21, 24, 26, 28, 30, 31, 34, 35, 42, 44, 45, 46, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cl,ient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [4, 5, 6, 21, 24, 26, 28, 30, 31, 34, 35, 42, 44, 45, 46]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [4, 5, 6, 21, 24, 26, 28, 30, 31, 34, 35, 42, 44, 45, 46, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [4, 5, 6, 21, 26, 28, 30, 31, 34, 35, 42, 44, 45, 46, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:26 [4, 5, 6, 21, 28, 30, 31, 34, 35, 42, 44, 45, 46, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [4, 5, 6, 21, 28, 30, 34, 35, 42, 44, 45, 46, 48]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:34 [4, 5, 6, 21, 28, 30, 35, 42, 44, 45, 46, 48]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [4, 5, 6, 21, 28, 30, 35, 42, 44, 45, 46, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [4, 5, 6, 21, 28, 30, 35, 42, 44, 45, 46, 48, 49, 50]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [4, 5, 6, 21, 28, 30, 35, 42, 44, 45, 46, 48, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandle,r disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [4, 5, 6, 21, 28, 30, 35, 42, 44, 45, 46, 50]
,2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,21
[ThaliCore] VirtualSocket.deinit vsID:21 [4, 5, 6, 28, 30, 35, 42, 44, 45, 46, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnecte,d
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,30
[ThaliCore] VirtualSocket.deinit vsID:30 [4, 5, 6, 28, 35, 42, 44, 45, 46, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[,ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreams,Handler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [4, 5, 6, ,2,8, 42, 44, 45, 46, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [4, 5, 6, 28, 44, 45, 46, 50]
[ThaliCore] TCPClient.socketDidDis,connect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:48:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.,s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription,=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnec,t(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:1
[ThaliCore] VirtualSocket.deinit vsID:44 [4, 5, 6, 28, 45, 46, 50]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconne,c,t(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStre,ams() vsID:46
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited Run,Loop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [4, 5, 6, 28, 46, 50]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [4, 5, 6,, 28, 50]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [4, 5, 6, 28]
,2017-07-21 08:51:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 08:51:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:51:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:51:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:51:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-4,88B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:51:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:51:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-4,88B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-4,88B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-4,88B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-4,88B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-21 08:58:45 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-21 08:58:45 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-21 08:,58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-21 08:58:45 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-21 ,0,8:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call ,start/stopListeningForAdvertisements'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - Calling stopListeningForAdvertisements without calling start is NOT an error'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
2017-07-21 08:58:45 - INFO CoordinatedCli,ent: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-21 08:58:45 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 08:58:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 869 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 08:59:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-4,88B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488,B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/225D4889-55AD-488B-A3B4-FA939517DC0A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
